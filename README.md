# RANIA MCU 2026 v1.0

Real-time Attendance & MCU Intelligence Analytics.

## Data model
- `employees/{nik}` = immutable master MCU.
- `attendance/{nik}_{tanggal}` = historical MCU transaction per scheduled date.
- Browser IndexedDB is used only as local cache/fallback.
- Firebase Firestore becomes the cloud source of truth after Firebase configuration is supplied.

## Run
Open `index.html` or deploy it to GitHub Pages.

## Firebase
1. Create a Firebase project.
2. Enable Firestore Database.
3. Enable Authentication > Anonymous for this prototype.
4. Copy the Web App config into RANIA > Firebase.
5. For production, replace Anonymous Auth with a dedicated operator login and deploy Firestore Security Rules.

## Important
Do not put service-account private keys in this HTML or a public GitHub repository.
Do not commit the employee Excel file or real employee data to a public repository.
