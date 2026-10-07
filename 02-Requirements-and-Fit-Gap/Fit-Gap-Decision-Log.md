# ERP / COTS Fit-Gap Decision Log

| ID | Requirement | Standard Capability | Decision | Rationale | Delivery Impact | Owner | Status |
|---|---|---|---|---|---|---|---|
| FG-01 | P2P-001 | Standard requisition workflow | Adopt standard | Meets business need with process alignment | Training/process update | Procurement Lead | Approved |
| FG-02 | P2P-002 | Configurable approval rules | Configure | Required value-based approval control | Configuration + UAT | Solution Lead | Approved |
| FG-03 | INT-001 | Integration framework available | Integrate | Banking exchange is external dependency | Interface build/test | Integration Lead | Approved |
| FG-04 | SUP-001 | Supplier fields/workflow configurable | Configure | Mandatory controls required | Configuration + data rules | Procurement Lead | Approved |
| FG-05 | Custom legacy approval | Existing process differs from standard | Process change | Customization adds cost/support risk without sufficient value | Change/training | Sponsor | Approved |
| FG-06 | Specialized operational report | Standard report partially meets need | Further review | Validate whether analytics layer can close gap | Decision dependency | Finance Controller | Open |

## Decision principle
The project uses a **configuration-first / adopt-standard** approach. Extensions or customization require an explicit business case considering value, cost, schedule, testing, upgrade/support impact and operational risk.
