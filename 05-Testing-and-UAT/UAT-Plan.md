# UAT Plan — Finance & Procurement

## Objective
Demonstrate that approved business requirements can be executed successfully by representative business users before production deployment.

## Entry criteria
- [ ] Critical configuration/build complete
- [ ] System/integration testing exit approved
- [ ] UAT environment stable
- [ ] Test data available
- [ ] Business testers trained on UAT process
- [ ] Requirements and expected outcomes traceable
- [ ] Access provisioned

## Sample scenarios
| UAT ID | Requirement | Scenario | Expected Outcome | Priority | Result |
|---|---|---|---|---|---|
| UAT-01 | P2P-001 | Create approved-category requisition | Requisition created successfully | Critical | |
| UAT-02 | P2P-002 | Submit PO above approval threshold | Routes to correct approver | Critical | |
| UAT-03 | AP-001 | Enter potential duplicate invoice | Expected control is triggered | Critical | |
| UAT-04 | FIN-002 | Produce monthly P&L by unit | Report reconciles to approved test data | High | |
| UAT-05 | SUP-001 | Submit incomplete supplier | Workflow prevents approval | High | |

## Defect severity
**S1 Critical:** prevents critical business process / no acceptable workaround  
**S2 High:** major impact with limited workaround  
**S3 Medium:** partial impact / workable alternative  
**S4 Low:** minor issue

## Exit criteria
- All critical scenarios executed.
- No unresolved S1 defects.
- S2 defects resolved or formally accepted with owned plan.
- Business owners approve UAT outcome.
- Residual risks are visible in go-live decision.
