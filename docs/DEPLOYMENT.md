# Deployment Checklist

Before deployment:

- configure secrets through the deployment environment
- verify Telegram webhook or polling configuration
- verify AI provider connectivity
- verify persistence and backups
- test admin authorization
- test escalation and ticket recovery
- confirm logs do not contain credentials or unnecessary customer content
- verify n8n endpoints and authentication

Run a safe end-to-end test before enabling production traffic.