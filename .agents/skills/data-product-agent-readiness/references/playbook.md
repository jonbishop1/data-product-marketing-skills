# Agent readiness playbook

## Fictional product context

FlowLake is a fictional incremental ingestion product. A synthetic source-to-warehouse sample works, but real data needs approved credentials and reconciliation. Sample completion is not production approval. Update, delete, late-arrival, freshness, and recovery behavior must be verified rather than assumed.

## Decision to resolve

Assess a defined data task through documented interfaces, scoped access, schema discovery, query/workload cost, correctness, freshness, and partial-failure recovery. Public-only evidence cannot prove authenticated execution or production data readiness.

## Task-specific method

Also inspect schema discovery, permissions, data boundaries, query or workload cost, correctness checks, freshness, exports, and recovery from partial execution. Public access to sensitive data is not a readiness requirement.

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

For this scenario, apply the task-specific method above and deliver: A task-scoped evidence matrix, a clearly bounded readiness finding, reproducible test notes if performed, and a ranked remediation list.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

A visible MCP endpoint or llms.txt file does not prove execution. A missing one does not prove failure. Do not bypass authentication, incur unapproved charges, or expose private audience results.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
