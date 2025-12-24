# Incident Response Investigations

## Overview
This repository documents hands-on incident response investigation workflows practiced in a controlled home lab environment. The focus is on structured analysis, log correlation, and investigative decision-making during security incidents rather than tooling or configuration alone.

The investigations documented here are designed to reflect real-world SOC and incident response scenarios, emphasizing how analysts evaluate alerts, pivot across data sources, and determine scope, impact, and next steps.

## Audience
This repository is intended for SOC analysts, incident responders, and security engineers interested in practical investigation methodology and investigative thought processes.

## Scope
The investigations in this repository focus on:
- Endpoint and authentication-based security investigations
- SIEM-driven analysis and timeline reconstruction
- Behavioral analysis of suspicious activity
- Correlation of endpoint, system, and authentication telemetry
- Clear documentation of investigative reasoning and outcomes

## Investigation Methodology
Each investigation follows a consistent structure to mirror real-world incident response workflows:
1. Identification of the initial indicator or alert
2. Review of relevant data sources
3. Investigation pivots and analysis steps
4. Assessment of findings and impact
5. Documentation of outcomes and lessons learned

This approach prioritizes clarity, repeatability, and sound analytical reasoning over assumptions or tool-driven conclusions.

## Data Sources
Investigations may leverage data from:
- Windows Security Event Logs
- PowerShell Operational Logs
- Endpoint process and execution telemetry
- Authentication and logon activity
- Network and syslog data (when applicable)

## Investigations
The following investigations are documented or in progress:
- Suspicious PowerShell Execution
- Authentication Anomalies *(planned)*
- Suspicious Process Execution *(planned)*

Each investigation is documented as a standalone case and focuses on how conclusions were reached rather than simply stating results.

## Purpose
The purpose of this repository is to demonstrate practical incident response thinking, investigative discipline, and the ability to document security investigations clearly and effectively. The content reflects how analysts operate in real SOC and incident response environments, where context, judgment, and communication are as important as technical skill.

## Disclaimer
All investigations documented in this repository are based on lab-generated data or simulated scenarios. No production systems, sensitive information, or proprietary data are included.
