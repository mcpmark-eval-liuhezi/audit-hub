# audit-hub

A throwaway project used for a **release-audit dry run**.

This repository exists only to walk a team through a release-audit checklist. It is intentionally self-contained:

- A README (this file) introducing the project.
- A GitHub Actions workflow at `.github/workflows/audit.yml` that runs on every push and reports the current time.
- A tracking issue, `Audit sign-off checklist`, with three nested sub-issues covering the secrets review, CI health, and usage reporting.
- A `usage-notes` branch with `docs/usage.md` recording the recorded CI usage numbers, opened as a pull request.

Everything here is disposable demo data and may be deleted at any time.
