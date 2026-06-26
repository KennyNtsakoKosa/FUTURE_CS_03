# API Security Risk Analysis Report - FUTURE_CS_03

## Task Overview
This repository contains the deliverables for **Task 3** of the Future Interns Cyber Security Internship.

## Target API
- **URL**: `https://jsonplaceholder.typicode.com`
- **Scope**: Read-Only Analysis of Public Endpoints

## Tools Used
- **Hoppscotch (Postman alternative)** – API request testing and response inspection
- Browser DevTools – Header and response inspection
- Canva – Report Design

## Key Findings

| Risk | Severity |
| :--- | :--- |
| Unauthenticated Access to User Data | 🔴 High |
| Broken Authorization (IDOR) | 🔴 High |
| Excessive Data Exposure | 🟡 Medium |
| Server Information Disclosure | 🟢 Low |

## Remediation Summary
- Implement authentication (API keys / OAuth2)
- Enforce user-specific access controls (prevent IDOR)
- Add pagination to limit data exposure
- Obfuscate server headers (`X-Powered-By`, `Server`)

## Deliverables
- [API_Security_Risk_Analysis_Report_Kenny_Kosa.pdf](API_Security_Risk_Analysis_Report_Kenny_Kosa.pdf)
- Evidence: Screenshots of API requests and responses

## Author
**Kenny Kosa** - Cyber Security Intern, Future Interns  
Date: June 26, 2026
