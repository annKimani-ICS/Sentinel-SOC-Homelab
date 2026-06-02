# About This Homelab

This project documents my end-to-end SOC homelab implementation using Microsoft Sentinel in Azure. The goal was to build practical blue-team skills in telemetry onboarding, threat detection, and incident triage while keeping costs controlled and security posture strong.

## Objective

- Build a functional, cloud-based SOC learning environment
- Practice realistic analyst workflows from detection through investigation
- Produce a portfolio artifact for cybersecurity job applications

## Scope

- Azure resource setup for Sentinel-connected services
- Data connector onboarding and telemetry validation
- Basic detection and investigation workflow in Sentinel using KQL
- Cost-conscious operation with planned teardown after completion

## Outcomes

- Implemented a working Sentinel SOC lab environment
- Validated workflow familiarity with incident handling and log analysis
- Produced public-safe documentation and artifacts for employer review

## Implementation snapshot

- Resource groups: `RG-SOC-Lab` and default `NetworkWatcherRG`
- Virtual machine: `CORP-NET-EAST-1`
- Sentinel workspace connected from the new Defender portal
- Three Microsoft data connectors connected
- Activity logs and event query evidence collected
- Watchlist created and used for result enrichment and workbook mapping

## Challenges encountered

- Learning and tuning KQL queries
- Creating a workbook visualization from watchlist data
- Navigating workflow changes in the new Microsoft Defender portal
- Uploading and validating watchlist data

## Key learning

- Writing KQL for security event exploration
- Building and validating workbooks for analyst visibility
- Creating and managing Azure resource groups and virtual machines
- Operating Microsoft Sentinel through the current Defender experience
- Applying watchlists to enrich and contextualize investigation data

## Privacy and security commitments

- All exported/public artifacts are sanitized
- No secrets, tokens, tenant IDs, or credentials are included
- Repository is maintained for learning and portfolio visibility only
