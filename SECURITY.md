# Security and privacy

The two applications in this repository are independent local implementations. No private Hatchable database was copied.

- All provided initial records are fictional.
- Do not commit real patient records, complaints, phone numbers, orders, addresses, secrets, access tokens or production database exports.
- Both sample backends listen on **127.0.0.1** for local use.
- **Hospital API does not implement authentication/authorization and must not be made public or used for actual patient care without appropriate security controls.**
- The market order tracking uses order ID and phone only; additional security, rate limiting, validation and audit are required before public deployment.
- `.gitignore` does not remove secrets already committed to Git history. Rotate exposed credentials if any are discovered.

Contact the project owner privately to report vulnerabilities; do not disclose actual personal information in public issues.
