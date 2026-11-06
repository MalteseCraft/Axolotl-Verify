# Security Policy

## Reporting a vulnerability

Please do not disclose security vulnerabilities in public issues. Contact the project maintainer privately at [INSERT SECURITY CONTACT EMAIL]. Do not include real user data, bot tokens, or other secrets in reports.

## Secret handling

- Never commit Discord bot tokens, API keys, passwords, or `.env` files.
- Store secrets in environment variables or a dedicated secret manager.
- If a token is exposed, revoke/reset it immediately in the Discord Developer Portal.
- Restrict bot permissions and enabled intents to the minimum required.
