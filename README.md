# Data-product marketing skills

25 open-source [Agent Skills](https://agentskills.io/specification) by [Jon Bishop](https://jonbishop.co) for marketing data products. Each skill includes a bounded workflow, domain-specific decisions, an evidence standard, a deliverable, and a linked playbook. There are no required paid services or runtime hooks.

## Built for this product type

Data adoption runs from an approved sample to correct real-data output, reconciliation, recurring workloads, and production approval. These skills account for source/destination semantics, schema changes, freshness, permissions, recovery, governance, and workload economics. A green connector is not proof of value.

This collection has its own skill names, product-specific guidance, and examples. For the other product type, see [Developer-tool marketing skills](https://github.com/jonbishop1/devtool-marketing-skills).

## Install

Clone this repository and copy the desired `.agents/skills/<name>/` folders into the skill location documented by your Agent Skills-compatible host. Keep each folder's references and assets. Each skill is standalone; shared context is optional. Avoid installing duplicate copies through several discovery paths.

For Claude Code:

```text
/plugin marketplace add jonbishop1/data-product-marketing-skills
/plugin install data-product-marketing-skills@jon-bishop-data-product
```

The manifest explicitly discovers `./.agents/skills/`. Format and manifest validation do not establish that every host can load or execute every task. Live research and execution depend on your host's tools and your authorization.

## Skills

| Skill | Task |
| --- | --- |
| [`data-product-evaluation`](.agents/skills/data-product-evaluation/SKILL.md) | Evaluation |
| [`data-product-agent-readiness`](.agents/skills/data-product-agent-readiness/SKILL.md) | Agent readiness |
| [`data-product-community-distribution`](.agents/skills/data-product-community-distribution/SKILL.md) | Community distribution |
| [`data-product-quickstart`](.agents/skills/data-product-quickstart/SKILL.md) | Quickstart |
| [`data-product-audience-research`](.agents/skills/data-product-audience-research/SKILL.md) | Audience research |
| [`data-product-competitive-research`](.agents/skills/data-product-competitive-research/SKILL.md) | Competitive research |
| [`data-product-content-production`](.agents/skills/data-product-content-production/SKILL.md) | Content production |
| [`data-product-content-strategy`](.agents/skills/data-product-content-strategy/SKILL.md) | Content strategy |
| [`data-product-copywriting`](.agents/skills/data-product-copywriting/SKILL.md) | Copywriting |
| [`data-product-customer-psychology`](.agents/skills/data-product-customer-psychology/SKILL.md) | Customer psychology |
| [`data-product-data-analysis`](.agents/skills/data-product-data-analysis/SKILL.md) | Data analysis |
| [`data-product-google-ads`](.agents/skills/data-product-google-ads/SKILL.md) | Google ads |
| [`data-product-landing-pages`](.agents/skills/data-product-landing-pages/SKILL.md) | Landing pages |
| [`data-product-marketing-background`](.agents/skills/data-product-marketing-background/SKILL.md) | Marketing background |
| [`data-product-marketing-plan`](.agents/skills/data-product-marketing-plan/SKILL.md) | Marketing plan |
| [`data-product-meta-ads`](.agents/skills/data-product-meta-ads/SKILL.md) | Meta ads |
| [`data-product-onboarding`](.agents/skills/data-product-onboarding/SKILL.md) | Onboarding |
| [`data-product-product-launches`](.agents/skills/data-product-product-launches/SKILL.md) | Product launches |
| [`data-product-seo-audit`](.agents/skills/data-product-seo-audit/SKILL.md) | Seo audit |
| [`data-product-seo-research`](.agents/skills/data-product-seo-research/SKILL.md) | Seo research |
| [`data-product-conference-pipeline`](.agents/skills/data-product-conference-pipeline/SKILL.md) | Conference pipeline |
| [`data-product-integration-marketing`](.agents/skills/data-product-integration-marketing/SKILL.md) | Integration marketing |
| [`data-product-pricing`](.agents/skills/data-product-pricing/SKILL.md) | Pricing |
| [`data-product-proof`](.agents/skills/data-product-proof/SKILL.md) | Proof |
| [`data-product-sales-enablement`](.agents/skills/data-product-sales-enablement/SKILL.md) | Sales enablement |

## Evidence and actions

Facts, observations, hypotheses, and unknowns stay distinct. Examples are fictional unless explicitly described as measured evidence. Sample success does not establish production readiness. Plans and drafts do not authorize publishing, messaging, spending, or production changes; existing user authorization governs execution.

## Validate and contribute

Use Python 3.9 or later for the repository checks, in an isolated environment:

```sh
python -m pip install -r requirements-dev.txt
python scripts/validate.py
python -m unittest discover -s tests
claude plugin validate .claude-plugin/plugin.json
claude plugin validate .claude-plugin/marketplace.json
```

The final two commands require a compatible Claude Code CLI. The [official reference validator](https://github.com/agentskills/agentskills/tree/main/skills-ref) requires Python 3.11 or later and can validate each skill folder. See [CONTRIBUTING.md](CONTRIBUTING.md) and the [evaluation scenarios](evals/scenarios.json). Authored scenarios are not completed model runs.

## Source and license

This is a standalone distribution generated from [shared authored source](https://github.com/jonbishop1/saas-marketing-skills), with domain overlays maintained there. Prefer contributing shared fixes upstream so both collections receive them. No sibling repo is required at runtime.

MIT — see [LICENSE](LICENSE). External documentation, logos, datasets, and customer material retain their own rights and permissions.
