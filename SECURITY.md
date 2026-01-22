# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

**Moolaah Finance** deals with financial assets and livestock tokenization. We take security extremely seriously.

If you discover a vulnerability, please **DO NOT** open a public issue.

### 1. Where to Report
Please email our security team directly at **security@moolaah.finance** (or your preferred contact method).

### 2. What to Include
*   A description of the vulnerability.
*   Steps to reproduce the issue (including scripts or transaction hashes on Testnet if applicable).
*   Potential impact (funds at risk, data integrity, etc.).

### 3. Our Response
*   We will acknowledge your report within 24 hours.
*   We will provide a timeline for a fix.
*   We operate a Bug Bounty program for critical contract vulnerabilities (details upon verified report).

### 4. Policy
*   Please test vulnerabilities on the Avalanche Fuji Testnet only.
*   Do not target our production deployment without explicit permission.
*   Do not engage in social engineering or physical attacks against our staff.

---
**Note:** This project involves *synthetic* livestock counting logic and simulated economic flows. Vulnerabilities affecting the simulation logic (e.g., manipulation of animal growth rates via `daily_tick`) are considered high severity.
