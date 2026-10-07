# Security Baseline

- Never commit passwords, API keys, private tokens, or database credentials.
- Authentication must be handled by a trusted server-side/auth provider.
- Validate and sanitize user-controlled input.
- Enforce authorization on the server, not only in the interface.
- Protect student data with least-privilege access.
- Keep administrative functions separated from normal student access.
- Record important security-sensitive actions for auditing.
- Use environment variables for secrets and provide a safe example environment file only.
