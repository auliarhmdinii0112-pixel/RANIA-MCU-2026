# RANIA MCU 2026 v0.9

Prototype RANIA MCU Control Tower.

## v0.9 persistence fix
- Master MCU is persisted synchronously to `localStorage` before the UI reports success.
- IndexedDB is retained as a secondary backup.
- On reload, localStorage is read first to avoid mobile async-storage race conditions.
- Master remains locked; attendance/status is stored separately.
- Reset only changes attendance status back to BELUM HADIR.
- Excel import is awaited through completion before success is shown.

## GitHub Pages
Upload/replace only `index.html` in the repository.
Do not upload the real MCU Excel file to a public repository.

This is still a single-device prototype. Firebase/Firestore should be the production persistence layer before multi-device/multi-operator use.
