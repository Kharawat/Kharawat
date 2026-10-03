# Security

## Scope
This repository is a public GitHub profile README. GitHub controls Markdown sanitization and hosting. There is no executable application, dependency manifest, authentication system, secret, data store or deployment workflow to harden here. Intended public profile/contact and project links are not credentials.

Keep personal credentials and private client data out of profile edits. Security claims for linked projects belong to each project's SECURITY.md; a profile link does not attest to production controls. Fetched Git history was scanned with Gitleaks and no real credential was confirmed. No build/test pipeline is added to a README-only repo. Account MFA, recovery and repository permissions remain owner-controlled and were not modified.

## Reporting and maintenance
Use GitHub private vulnerability reporting if enabled for this repository, or an already established private maintainer contact. If neither is available, open an issue asking for a private contact without publishing exploit details, customer data or credentials. Never paste a secret into an issue or pull request. Potential historical credentials must be treated as compromised, rotated by the owner and audited before any history rewrite; no rotation or rewrite is automatic.

See [pre-change assessment](docs/security/ASSESSMENT.md) and [verification/review](docs/security/VERIFICATION.md). Source review and offline tests are not production certification. Security CI is read-only, pinned by commit, uses no production credentials and never deploys. Keep action pins and scanners current through reviewed maintenance PRs.
