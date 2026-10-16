# Evaluation playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Agree on the decision, baseline, representative authorized workload, correctness invariants, updates/deletes/late arrivals, recovery, freshness, cost cap, ownership, and cleanup before results. Keep proposed criteria and measured outcomes distinct.

## Task-specific method

Focus on the actual source-to-consumer workload, not the easiest demo. Separate functionally correct output, operational readiness, and commercial fit.

## Output worksheet

| Field | Record |
| --- | --- |
| Requested decision and task | |
| User, evaluator, buyer, and owner | |
| Supported behavior and environment | |
| Evidence, source, and limits | |
| Proposed action or finished artifact | |
| Meaningful result and verification | |
| Unknowns, failure, and stop condition | |

## Completed example

Already authorized: synthetic data only. Initial 100-row key/value equality observed. Next proposed cases: update key 7 and expect one changed value with count unchanged; delete key 9 and expect exactly that key absent; replay an event to test duplicate multiplicity; deliver an older version after a newer one and compare with the intended documented conflict rule. Recovery experiment: interrupt an isolated test only through a supported mechanism and reconcile after documented resume. None are observed passes yet. No real-data collection is needed for these semantics tests; scale and production fit remain outside their proof.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not invent evaluation results or claim representative scale from a small sample. Never move sensitive records into an unapproved service.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
