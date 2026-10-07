# Cutover Runbook

| Seq. | Window | Activity | Owner | Dependency | Validation | Decision / Escalation |
|---:|---|---|---|---|---|---|
| 1 | T-5 days | Confirm final readiness / open defects | PM | UAT/readiness | Readiness pack | Steering escalation |
| 2 | T-2 days | Freeze agreed legacy transactions/master changes | Business Owners | Communications | Freeze confirmed | PM |
| 3 | T-1 day | Final extract and reconciliation preparation | Data Lead | Source availability | Control totals | Data escalation |
| 4 | T0 | Production data load | Data/Vendor | Environment ready | Load results | Cutover lead |
| 5 | T0 | Enable/validate production integrations | Integration Lead | Data/load sequence | Interface tests | Cutover lead |
| 6 | T0 | Provision/validate production access | Security Owner | Role approvals | Access validation | Cutover lead |
| 7 | T0 | Business smoke tests | Business Leads | System available | Signed smoke test | Go/no-go |
| 8 | T0 | Go/no-go decision | Sponsor / Governance | Readiness evidence | Decision recorded | Sponsor |
| 9 | T+1 | Business launch communication | Change Lead | Go decision | Communication sent | PM |
| 10 | T+1 onward | Hypercare triage and daily review | Support Lead | Support model | Daily metrics | PM/Operations |

## Rollback / contingency triggers
Examples include unreconciled critical data, inability to execute a critical business process, severe integration failure, or access/control failure that cannot be safely worked around.

A real project would define detailed technical rollback procedures with the responsible solution and infrastructure specialists.
