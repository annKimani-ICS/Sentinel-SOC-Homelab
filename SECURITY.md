# Security Policy

## Supported Versions

This is a portfolio project. Security fixes are applied on the latest `main` branch.

## Reporting a Vulnerability

If you discover a security issue in this repository, open a private report via GitHub Security Advisories (preferred) or create an issue without disclosing exploit details.

## Secret Handling

The repository must never contain:

- Azure credentials, access keys, tokens, SAS links, or connection strings
- Tenant IDs tied to privileged resources
- Private certificates or key material

If sensitive content is identified, it will be removed and rotated immediately.
