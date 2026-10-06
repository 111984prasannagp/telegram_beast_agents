# Ticket Lifecycle

Recommended ticket states:

`NEW → OPEN → WAITING_FOR_CUSTOMER → IN_PROGRESS → RESOLVED → CLOSED`

## Rules
- A new customer request creates or updates a ticket according to the configured deduplication policy.
- Human escalation moves the conversation into a support-owned state.
- Resolution should record the reason and timestamp.
- Closed tickets should not silently receive new state transitions.

Implement state transitions centrally so every interface follows the same rules.