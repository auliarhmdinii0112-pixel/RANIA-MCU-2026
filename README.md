# RANIA MCU 2026 v2.9

Daily Control Tower: default operational date now uses the nearest upcoming scheduled MCU date, so the dashboard does not appear empty when today has no MCU schedule.

- Default mode: MCU per Tanggal
- Nearest upcoming MCU date selected automatically
- Reset Filter returns to the daily control date
- Global filters, AFD/hour monitoring, attendance flow, history and export remain preserved


### v2.9
- Tanggal filter menjadi sumber tanggal dashboard yang konsisten.
- Mode Semua Master tidak lagi tertukar dengan tanggal otomatis.
- Dashboard, AFD, jam, peserta, dan judul mengikuti tanggal aktif yang sama.


### v2.9
- Fixed raw JavaScript text appearing above the dashboard.
- Preserved the active date during normal dashboard rendering.


### v2.9
- Fixed MCU schedule dates shifting one day backward due to timezone conversion.
- Existing legacy local/Firebase schedule records are repaired forward by one day when the known legacy pattern is detected.
