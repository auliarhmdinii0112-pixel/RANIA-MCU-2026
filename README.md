# RANIA MCU 2026 v0.4

Light green corporate dashboard with functional Excel import based on the actual MCU workbook structure.

Actual source sheets:
- AMR
- SIP

Actual fields mapped:
Company Id, Emp No, Name, Position Title, AFD, Org Name/Divisi, Paket MCU, Konfirmasi data HRGA, Jadwal MCU, plus gender/age.

Logic:
- Only participants with HRGA confirmation YA are imported.
- Initial attendance status = BELUM HADIR.
- Status can be changed to HADIR / PROSES, MCU SELESAI, or TIDAK HADIR.
- Timestamp is automatic for attendance/progress actions.
- KPI, Afdeling, Company, Status, search and hourly chart are calculated from the current data.
- Excel export included.
- localStorage used until Firebase is connected.

Branding is a custom RANIA/Astra Agro Lestari-inspired presentation; official logo assets are not embedded as a replacement for corporate brand files.
