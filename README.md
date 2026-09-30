# RANIA MCU 2026 v0.8

RANIA — Real-time Attendance & MCU Intelligence Analytics.

v0.8 fixes master persistence after browser refresh:
- Master MCU is stored in IndexedDB on the device.
- localStorage remains as fallback.
- Imported master survives refresh/reopen on the same browser/device.
- Attendance status is stored separately from locked master data.
- Reset only changes attendance status back to BELUM HADIR.
- Excel import, filters, dashboard and export remain available.

Production architecture can later move the master and attendance data to Firebase Firestore.
