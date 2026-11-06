# Infra — Governed Intelligence Portfolio

**A human-led, AI-assisted research and engineering portfolio exploring how intelligent systems can remain useful, accountable, and under human control.**

This work asks a practical question: how can software combine AI, evidence, and automation while preserving the authority of the people responsible for the outcome?

Four independently governed projects approach that question from different directions: a reusable application platform, controlled agent operations, small language-model experiments, and knowledge methods that preserve meaning across handoffs.

**Snapshot: November 6, 2026. Publication state: private review draft.** This repository is a sanitized, code-free work sample. It describes documented work and its limits; the underlying repositories and intellectual property remain private.

## Start here

| Project | Goal | Documented maturity |
|---|---|---|
| [Infra OS](projects/infra-os.md) | Coordinate missions, evidence, review, and approved actions in a reusable platform. | Foundations and several design slices integrated; synthetic backend, API, and browser reference work completed within a test boundary. Production acceptance remains open. |
| [Infra Agent Operations](projects/infra-agent-ops.md) | Make AI-assisted engineering bounded, attributable, and independently reviewable. | Architecture and governance baselines completed; implementation-entry and security proof work remain separate gates. An operational agent runtime is not established. |
| [Infra Model Research](projects/infra-model-research.md) | Understand model training and evaluate research choices through small, reproducible experiments. | A tiny language-model pipeline and bounded experiments have produced measured results. Broader research and data preparation continue; no production or frontier-model capability is claimed. |
| [Infra Knowledge](projects/infra-knowledge.md) | Preserve intended meaning, evidence, context, and authority across human and machine handoffs. | Conceptual design and several synthetic feasibility experiments exist. Integrated verification and production assurance remain open. |

The projects share lessons through explicit review. They are separate efforts; this portfolio does not imply that they form a deployed, integrated product.

## Selected work and findings

- **Governed application design:** a synthetic reference workflow separates evidence, model suggestions, human dispositions, local actions, and audit records. Its current browser boundary uses test identities rather than real-user authentication.
- **Model experimentation:** a tiny CPU-trained model improved held-out prediction loss over uniform and unigram baselines. Its generated text remained inconsistent, limiting what the result demonstrates.
- **Security and AI safety:** extended boundary tests exposed defects after initial fixture suites passed. Failed checkpoints were preserved, repairs were tested, and remaining gaps stayed explicit.
- **Meaning and authority:** experiments distinguished structural validity from semantic support and permission to act. A matching hash, valid schema, or successful local task does not establish current authority.

Read the [research questions and findings](docs/research-and-findings.md) for methods, results, negative evidence, and limitations.

## Supporting capabilities

- [Security Assessments](projects/security-assessments.md) — an authorization-gated assessment and reporting framework with tested offline helpers; live integrations and portfolio-wide security assurance are not established.

## Explore the work

| Reading path | What it explains |
|---|---|
| [Foundations](docs/foundations.md) | The problem, development method, and principles behind the work. |
| [Architecture overview](docs/architecture.md) | Conceptual responsibilities and boundaries, with maturity labels. |
| [Research and findings](docs/research-and-findings.md) | What was learned and what remains unproven. |
| [Status and evidence](docs/status-and-evidence.md) | Completed outputs, prototypes, plans, and the source basis for claims. |
| [AI assistance](docs/ai-assistance.md) | How AI supported development and where human responsibility remains. |
| [Publication review](PUBLICATION_REVIEW.md) | The disclosure boundary and review scope for this work sample. |

For an application or interview, this repository illustrates requirements analysis, architecture reasoning, experimental discipline, failure analysis, and responsible use of AI development tools. It is a documentation work sample; it does not independently demonstrate source-code quality, customer adoption, commercial traction, or production security.
