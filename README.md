# Sentinel SOC Homelab

A concise, employer-facing portfolio repository for my Microsoft Sentinel SOC homelab project based on [this lab walkthrough](https://www.youtube.com/watch?v=g5JL2RIbThM&t=3330s).

## What this project demonstrates

- Azure cloud security operations setup and log onboarding
- Microsoft Sentinel configuration for detection and investigation
- Basic SOC workflow: ingest -> detect -> triage -> investigate
- Security-first documentation with no exposed credentials or tenant secrets

## Repository structure

- `ABOUT.md` - project context, scope, and key outcomes
- `SECURITY.md` - responsible disclosure and secret-handling policy
- `artifacts/` - non-sensitive exported artifacts (rules, workbooks, screenshots)
- `notes/` - investigation notes and implementation decisions

## Quick start for reviewers

1. Read `ABOUT.md` for architecture and outcomes.
2. Review `artifacts/` for anonymized evidence of implementation.
3. Review `notes/` for operational thinking and lessons learned.

## Safe publishing policy

- No credentials, keys, tokens, connection strings, or personal tenant details are committed.
- Public artifacts are sanitized and anonymized before upload.
- Anything that could recreate privileged access is excluded from version control.

## Suggested artifacts to add

- Sanitized screenshots of Sentinel dashboards, incidents, and analytics rules
- Exported rule templates with IDs and tenant-specific values removed
- Workbook screenshots or JSON with sensitive metadata redacted
- A short incident triage walkthrough in markdown

## Status

Core repository scaffolding is ready for public sharing. Add sanitized lab outputs into `artifacts/` and `notes/`, then keep improving this as a living SOC portfolio.
