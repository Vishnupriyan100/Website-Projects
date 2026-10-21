# Security and privacy

This is a public **portfolio/documentation** repository.

## Never commit
- Hospital patient records, clinical details, phone numbers, dates of visits, billing data or identifying screenshots.
- Marketplace customer details, delivery addresses, contact numbers or order histories.
- API keys, tokens, account credentials, database URLs, session cookies, production environment files or database backups.
- Backend endpoints that expose private records or rely on client-side-only access controls.

## Publication checklist
1. Review every proposed source file for secrets, private data and internal URLs.
2. Confirm server-side authentication and role-based authorization for every patient/order endpoint.
3. Use synthetic test records only.
4. Verify public README and screenshots contain no sensitive information.
5. If secrets were previously committed, revoke/rotate them; adding a rule to `.gitignore` cannot erase Git history.

## Reporting
Please do not post patient or customer data in public issues. Contact the project owner privately through an established secure channel.
