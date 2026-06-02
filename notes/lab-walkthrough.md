# Lab Walkthrough Summary

This file summarizes the implementation flow represented by the screenshots in `artifacts/screenshots/`.

## Build flow completed

1. Created and validated resource groups (`RG-SOC-Lab` plus default `NetworkWatcherRG`)
2. Provisioned virtual machine `CORP-NET-EAST-1`
3. Connected and validated Microsoft Sentinel workspace in Defender portal
4. Enabled and verified data connectors
5. Reviewed Log Analytics activity logs for setup operations
6. Queried security events with KQL and reviewed generated results
7. Uploaded and validated a watchlist
8. Ran watchlist-enriched queries and confirmed output fields
9. Built workbook visualization from enriched query data

## Evidence reference

- `01-resource-groups.png`
- `02-virtual-machine.png`
- `03-sentinel-overview.png`
- `04-data-connectors.png`
- `05-log-analytics-activity.png`
- `06-incidents-kql.png`
- `07-watchlist-overview.png`
- `08-watchlist-results-kql.png`
- `09-workbook-visualization.png`
