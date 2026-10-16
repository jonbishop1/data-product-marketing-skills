# Proof playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Prove equivalent output and semantics before comparing workload speed or cost. Record dataset shape and skew, updates, cache state, concurrency, freshness, failures, resources, repeated runs, and uncertainty. Include unfavorable conditions and limitations.

## Task-specific method

Verify equivalent output and semantics before comparing speed or cost. Include dataset shape, update behavior, freshness, skew, cache state, and operating conditions that affect the conclusion.

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

## Worked application

For this scenario, apply the task-specific method above and deliver: A claim ledger, evidence protocol or results, reproduction instructions, publishable claim language, limitations, and unresolved proof gaps.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not cherry-pick runs, hide failures, manufacture customer results, or label illustrative charts as measured data. A vendor benchmark is evidence with a scope, not independent validation.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
