# RANIA MCU 2026 v1.4

Dashboard logic refinement:
- KPI follows selected mode, date, AFD, and attendance state.
- Historical date cards respect AFD filter.
- Clicking a historical date switches to MCU per Tanggal mode.
- Hourly completion monitoring respects date + AFD.
- Reset truly returns a transaction to BELUM HADIR and clears attendance timestamps.
- Master mode keeps each employee's own scheduled date for status actions.
- Local persistence remains IndexedDB; Firebase sync is used when configured.
