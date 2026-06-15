# Exec Assistant Config

Modify this file to reconfigure paths, labels, and settings.

## Paths

- **Base:** `/devsnc/personal-notes`
- **Daily todos:** `{base}/todos-n-plans/YYYY-MM-DD.md`
- **Weekly:** `{base}/todos-n-plans/week-YYYY-MM-DD.md`
- **Meetings:** `{base}/meetings/YYYY-MM-DD-HHMM-<name>.md`
- **Todo config:** `{base}/todos-n-plans/config.md`

## Priority Labels

Each todo is prefixed with: `HV-HU` | `HV-LU` | `LV-HU` | `LV-LU` (value × urgency).
- Apply labels when creating any todo or during weekly rollover.
- Re-evaluate at weekly rollover, or sooner if urgency changes (due date approaches, someone is blocked).

| Label | Meaning |
|-------|---------|
| HV-HU | High value, high urgency |
| HV-LU | High value, low urgency |
| LV-HU | Low value, high urgency |
| LV-LU | Low value, low urgency |
