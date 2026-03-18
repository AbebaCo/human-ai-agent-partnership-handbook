# HEARTBEAT.md

## Schedule: Every 30 minutes
## Model: [CHEAPEST CAPABLE, e.g., gemini-2.5-flash]

## Task List (Priority Order)

| Priority | Task                              | Frequency         |
|----------|-----------------------------------|-------------------|
| 0        | Pre-call briefing check           | Every beat        |
| 1        | Slack and team triage             | Every beat        |
| 2        | Email triage (all accounts)       | If >30 min        |
| 3        | [CUSTOM: e.g., Drive folder scan] | If >60 min        |
| 4        | Pipeline staleness check (CRM)    | If >4h            |
| 5        | Session history and Git sweep     | If >2h            |
| 6        | Security pipeline                 | Every beat        |
| 7        | Interaction ledger maintenance    | Every beat        |
| 8        | Memory Spine Integrity Check      | Every beat        |
| 9        | Event logging                     | Every beat        |
| 10       | Morning self-heal (first >6AM)    | Daily             |
| 11       | Notification digest delivery      | Every beat        |

## State Tracking
- File: memory/heartbeat-state.json
- Stores last-run timestamp per task to prevent redundant execution.
