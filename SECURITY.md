# Security Policy

## Public Repository Rule

This is a public-facing portfolio repository. Do not commit private credentials, personal documents, legal records, private contact details, backend secrets, deployment tokens, or production environment files.

## Sensitive Data That Must Not Be Committed

- API keys and access tokens
- Passwords and recovery codes
- `.env` files or production configuration
- Database URLs and private backend endpoints
- SSH private keys, certificates, or signing keys
- Identity documents, tenancy documents, financial records, or legal correspondence
- Private emails, phone numbers, addresses, or screenshots containing account data

## If a Secret Is Accidentally Committed

1. Revoke or rotate the exposed secret immediately.
2. Remove the secret from the repository history where required.
3. Check recent commits, deploy keys, webhooks, collaborators, and authorized apps.
4. Treat the secret as compromised even if the repository was private at the time.

## Account Protection Checklist

- Use two-factor authentication.
- Add a passkey/security key where available.
- Review authorized OAuth apps and GitHub Apps.
- Review SSH keys and deploy keys.
- Review account security logs.
- Keep recovery codes offline in a safe place.

## Reporting

For security concerns, contact the repository owner through verified GitHub or official organization channels only. Do not post sensitive details in public issues.
