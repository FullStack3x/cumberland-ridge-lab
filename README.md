# cumberland-ridge-lab
This is a self-directed lab simulating the identity and access management program of a 50-person defense subcontractor. I'm building it with Windows Server, Active Directory, PowerShell, and Microsoft Entra ID to practice least privilege, role-based access control, MFA and Conditional Access, SSO integration, joiner/mover/leaver processes, and access reviews, and to map each control to NIST 800-171.

 It is not professional experience. AI tools were used for explanation;
> all configurations were built and tested by me.

## Environment
- VirtualBox on a 32 GB laptop
- Windows Server 2022 (domain controller), Windows 11 Enterprise (client)
- Microsoft Entra ID tenant
 
## Architecture
![Network diagram](diagrams/network.png)
 
## Phases
| Phase | Topic                | Status      | Link                       |
|-------|----------------------|-------------|----------------------------|
| 0     | Setup and charter    | Done        | docs/00-company-charter.md |
| 1     | Network for identity | Not started |                            |
| 2     | Active Directory     | Not started |                            |
| 3     | Entra ID and SSO     | Not started |                            |
| 4     | IAM governance       | Not started |                            |
| 5     | NIST 800-171 mapping | Not started |                            |
 
## Key lessons
- [Add one lesson per phase, including something that broke and how you fixed it.]
 
## Repo layout
docs/ write-ups, scripts/ PowerShell, screenshots/ evidence,
diagrams/ network and role diagrams.
