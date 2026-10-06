# Telegram Beast Observability

## Events worth tracking
- update received
- intent selected
- knowledge lookup succeeded or failed
- ticket created or updated
- escalation requested
- automation started or failed

## Logging rules
Use structured logs with correlation IDs where possible. Do not log bot tokens, API keys, passwords, or unnecessary customer message contents.

## Failure handling
Errors should identify the failed subsystem and provide a safe recovery path without exposing credentials or internal secrets.
