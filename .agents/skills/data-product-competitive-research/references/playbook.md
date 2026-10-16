# Competitive research playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Compare the workload against SQL jobs, open-source connectors, and managed platforms. Require equivalent update/delete semantics, reconciliation, freshness, failure recovery, access model, and cost conditions before claiming superiority.

## Task-specific method

Compare reconciliation behavior, failure recovery, supported sources, latency or freshness, access controls, data residency, and total workload cost. A feature checkbox does not establish equivalent behavior.

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

## Application brief

Deliver: A sourced comparison matrix, a best-fit and poor-fit summary, a battlecard, and explicit evidence gaps. Keep private win/loss details out of public copy.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not copy competitors' prose, infer market share from traffic estimates, or claim missing security support because a public page is silent.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
