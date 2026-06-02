# Sentinel SOC Homelab

This repository documents my Microsoft Sentinel SOC homelab implementation in Azure, built as a practical blue-team project and portfolio artifact.

Lab reference: [Microsoft Sentinel SIEM Full Tutorial](https://youtu.be/g5JL2RIbThM?si=9Cf_TeIGksbErDab)

## Project highlights

- Created core Azure resources (`RG-SOC-Lab`, VM, Log Analytics workspace, Sentinel setup)
- Connected data sources in Microsoft Sentinel (3 connectors connected)
- Queried and investigated security events with KQL
- Built watchlist-driven enrichment and a workbook visualization
- Documented learning outcomes and implementation challenges

## Evidence captured

All evidence is in `artifacts/screenshots/`:

1. Resource groups (`NetworkWatcherRG` and `RG-SOC-Lab`)
2. Virtual machine (`CORP-NET-EAST-1`)
3. Microsoft Sentinel overview (Defender portal)
4. Data connectors state
5. Log Analytics activity logs
6. Security events/incidents generated via KQL
7. Watchlist configuration
8. Watchlist query result sample
9. Workbook visualization

## Skills demonstrated

- Azure resource provisioning and management
- Microsoft Sentinel onboarding and operations
- KQL query writing for investigation and enrichment
- Watchlist usage and workbook visualization
- SOC-style thinking: telemetry, triage, and evidence handling

## Repository structure

- `ABOUT.md` - project context, scope, and outcomes
- `SECURITY.md` - vulnerability reporting and secret-handling policy
- `artifacts/screenshots/` - sanitized implementation evidence
- `notes/lab-walkthrough.md` - concise implementation summary
- `notes/lessons-learned.md` - challenges and key learning points

## Security and privacy

- No secrets, credentials, keys, or connection strings are committed
- Artifacts are sanitized for public portfolio visibility
- Sensitive local files are excluded through `.gitignore`
