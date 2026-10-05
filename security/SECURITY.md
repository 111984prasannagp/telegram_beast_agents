# 🔐 Security

Never commit:
- Telegram bot tokens
- AI/API keys
- passwords
- cookies
- private customer information
- production databases

Recommended controls:
- Telegram allowlist and roles
- rate limiting
- input validation
- audit logging
- secret redaction
- least-privilege credentials
- confirmation for sensitive operations
- local-only control endpoints where possible

If a credential is exposed, revoke it immediately and create a replacement.
