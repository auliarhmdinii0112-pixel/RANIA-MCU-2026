# RANIA MCU 2026 v0.3

Functional prototype with:
- Robust Excel import mapping, including multiple Name/AFD header variants.
- Filter per Afdeling.
- Filter per Company.
- Filter per Status.
- Search NIK/name.
- Afdeling insight: participant count, completed, remaining, progress.
- Status changes with automatic browser timestamp.
- Hourly MCU chart from completion timestamps.
- Data quality checks.
- Excel export.
- localStorage for prototype persistence.

Recommended dashboard logic:
1. Executive KPI stays global.
2. Afdeling filter changes the participant-control view and Afdeling insight.
3. Status filter answers who came / did not come / completed.
4. Firebase will later replace localStorage for real-time multi-user operation.
