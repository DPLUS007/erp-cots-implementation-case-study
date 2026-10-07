# Data Migration Plan

## Scope
Illustrative migration covers active suppliers, selected finance master data and agreed open transactional data.

## Migration lifecycle
1. Identify source and ownership.
2. Profile and assess quality.
3. Map source to target.
4. Cleanse and enrich.
5. Trial extract/load.
6. Reconcile.
7. Resolve exceptions.
8. Rehearse production migration.
9. Execute cutover load.
10. Obtain business reconciliation/sign-off.

## Data objects
| Object | Source Owner | Target Owner | Quality Concern | Reconciliation | Status |
|---|---|---|---|---|---|
| Active suppliers | Procurement | Procurement | Duplicates/incomplete tax fields | Count + sampled attributes | In progress |
| Chart of accounts | Finance | Finance | Legacy inactive values | Approved mapping | Planned |
| Open AP items | Finance | Finance | Cut-off timing | Value/count reconciliation | Planned |

## Readiness criteria
- [ ] Scope and retention rules approved
- [ ] Mapping signed off
- [ ] Critical cleansing completed
- [ ] Trial loads executed
- [ ] Exceptions owned
- [ ] Reconciliation thresholds agreed
- [ ] Production cut-off communicated
- [ ] Final business sign-off owner identified
