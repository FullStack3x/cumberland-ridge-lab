# Cumberland Ridge Engineering: Company Charter
 
**Status:** Fictional company for a self-directed security lab.
 
## Overview
Cumberland Ridge Engineering, LLC is a 50-person engineering subcontractor
in Huntsville, AL. It provides systems engineering and test support to
defense prime contractors and handles controlled unclassified information (CUI).
 
## Environment
- Microsoft 365 (email, Teams, SharePoint, OneDrive)
- Windows 11 laptops, about 50 users, some remote
- On-premises Active Directory synchronized with Entra ID
- MFA required for all users
- Applications: HR system, finance system, engineering file shares, ticketing
 
## Departments
Executive (3), HR (4), Finance (5), Business Development (7),
Contracts & Compliance (3), Engineering (24), IT (4).
 
## Data classification
| Class    | Examples                          | Handling                              |
|----------|-----------------------------------|---------------------------------------|
| CUI      | Contract technical data, drawings | Restricted groups, MFA, logged access |
| Internal | HR records, financials            | Department-limited access             |
| Public   | Marketing material                | No restriction                        |
 
## Scope of this lab
Networking for identity, Active Directory, Entra ID and SSO, IAM governance
(joiner/mover/leaver, access reviews), and NIST 800-171 mapping.
Out of scope for now: SIEM, vulnerability management, incident response.
 
## Assumptions
- Single office, with remote workers connecting through VPN.
- Security team is the IT department plus one ISSO in Contracts & Compliance.
 
## Goals
1. Every user has least-privilege access based on role.
2. Access is requested, approved, reviewed, and removed on a documented schedule.
3. Controls are mapped to NIST 800-171.
