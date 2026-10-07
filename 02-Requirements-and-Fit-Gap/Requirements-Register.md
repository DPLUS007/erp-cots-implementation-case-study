# Requirements Register

| ID | Process | Requirement | Priority | Business Owner | Acceptance Measure | Fit-Gap |
|---|---|---|---|---|---|---|
| FIN-001 | General Ledger | System must enforce approved chart-of-accounts structure | Must | Finance Controller | Invalid combinations cannot be posted | Configure |
| FIN-002 | Reporting | Finance must produce monthly P&L by business unit | Must | Finance Controller | Approved report reconciles to ledger | Standard / Configure |
| AP-001 | Accounts Payable | Duplicate supplier invoices must be identifiable before payment | Must | AP Manager | Duplicate test scenario produces expected control | Configure |
| P2P-001 | Requisition | Users must create requisitions using approved categories | Must | Procurement Lead | UAT scenario passes | Standard |
| P2P-002 | Approval | Purchase approvals must route by value threshold | Must | Procurement Lead | Each threshold routes to correct approver | Configure |
| SUP-001 | Supplier | Supplier creation must require defined mandatory information | Must | Procurement Lead | Incomplete record cannot be approved | Configure |
| INT-001 | Integration | ERP must exchange approved payment data with banking interface | Must | Finance Systems Lead | End-to-end integration test passes | Integrate |
| DATA-001 | Migration | Active suppliers must be migrated and reconciled | Must | Data Lead | Reconciliation meets approved threshold | Migration |
| SEC-001 | Access | Conflicting finance duties must be reviewed before role approval | Must | Security Owner | Access review/sign-off completed | Configure / Process |
| NFR-001 | Operations | Support ownership and escalation path must exist at go-live | Must | IT Operations | Support model approved | Process change |

## Requirements governance
1. Business owners approve requirements and acceptance criteria.
2. Solution specialists classify fit-gap and document implications.
3. Material scope changes follow change control.
4. Requirements trace to design decisions, tests and UAT evidence.
5. Unresolved Must requirements are visible in readiness reporting.
