# Integration Register

| ID | Interface | Direction | Business Purpose | Owner | Dependency | Test Evidence | Cutover Action | Status |
|---|---|---|---|---|---|---|---|---|
| INT-01 | Banking interface | Outbound | Approved payment transmission | Integration Lead | Bank specification | End-to-end test | Enable production endpoint | In progress |
| INT-02 | Identity provider | Inbound | User authentication | Security Owner | Role/access design | Authentication/access test | Production access validation | Planned |
| INT-03 | Reporting platform | Outbound | Management analytics | Data/BI Lead | Data model | Reconciliation/report test | Refresh schedule enabled | Planned |

## Integration governance
- Define source/target ownership.
- Document data and security dependencies.
- Confirm error handling and operational monitoring.
- Test business scenarios, not connectivity alone.
- Include every production interface in cutover and support handover.
