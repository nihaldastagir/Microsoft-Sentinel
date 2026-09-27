# Microsoft Sentinel Content Repository

This repository is used to centrally manage, version, maintain, and deploy custom Microsoft Sentinel security content for SOC operations and threat detection.

The repository is intended to serve as a source of truth for Microsoft Sentinel content such as Analytics Rules, Hunting Queries, KQL queries, Parsers, Workbooks, Automation Rules, Playbooks, Watchlists, and deployment templates.

---

## Repository Objectives

The main objectives of this repository are to:

- Centralize Microsoft Sentinel security content.
- Maintain version control for detection and monitoring content.
- Standardize Analytics Rule development and deployment.
- Support GitHub-based CI/CD deployment to Microsoft Sentinel.
- Improve collaboration between SOC analysts and security engineers.
- Maintain change history and rollback capability.
- Reuse detection content across multiple Microsoft Sentinel environments.

---

## Repository Structure

The repository will be organized as follows:

```text
Microsoft-Sentinel/
│
├── AnalyticsRules/
│   ├── Azure/
│   ├── EntraID/
│   ├── Microsoft365/
│   ├── DefenderXDR/
│   ├── Windows/
│   ├── Linux/
│   ├── Network/
│   └── Custom/
│
├── HuntingQueries/
│
├── Parsers/
│
├── AutomationRules/
│
├── Playbooks/
│
├── Workbooks/
│
├── Watchlists/
│
├── Documentation/
│
└── README.md
