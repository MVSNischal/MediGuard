# MediGuard AI — Safe Demo Prototype

## What this is
A responsive, standalone browser prototype for demonstrating a medication information intake form and a transparent, non-clinical report. It is designed to open on a computer or Android phone browser. It can also be wrapped in an Android WebView later.

## Open it
1. Extract `MediGuard_AI_Demo.zip`.
2. Open `index.html` in a modern browser.
3. Press **Load sample case**, review the synthetic example, check the demo acknowledgement, then choose **Generate demo report**.
4. Use **Print / Save PDF** to save the report, or **Copy report text**.

No installation, account, API key, server, or internet connection is required after the files are available.

## What the current version does
- Collects synthetic patient context, diet notes, regular medicines, and newly prescribed medicines.
- Looks up selected medicine names against entries in the uploaded *Top Prescribed Pharmaceuticals Guide*.
- Displays the guide's example strengths and stated primary uses for matched entries.
- Flags missing medicine details, repeated entered names, and names not matched to the selected reference entries.
- Produces a report with limitations and questions to discuss with a qualified healthcare professional.
- Keeps form values in page memory only; it does not submit or save them to a server.

## Important limitations
- Demo only; not for clinical decisions or real patient data.
- Does not perform validated drug-drug or drug-food interaction checking.
- Does not calculate whether a dose is right, interpret lab values, diagnose, prescribe, recommend dose changes, or decide whether to change doctors.
- A reference match does not establish safety or appropriateness.
- The uploaded guide is a brief reference with selected medicines, example strengths, and uses. It is not a comprehensive clinical database, and some source entries may be incomplete. Verify all clinical information before any future use.
- The current interface is not a certified medical device and has not undergone clinical validation or security certification.

## Android
The page is responsive and can be opened directly in Android Chrome. For a true installable Android application, wrap this page in a native Android WebView or package it with Capacitor after clinical, privacy, and security requirements are defined. Do not connect real patient records until a qualified clinical team has validated the workflow and a secure backend, authentication, access controls, encryption, audit logging, retention policy, and incident response are implemented.

## Project files
- `index.html` — complete standalone application.
- `README.md` — usage and safety notes.
