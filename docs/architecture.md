# Conceptual Architecture

[Portfolio](../README.md) · [Project maturity](status-and-evidence.md)

This overview describes responsibilities and design directions. It omits schemas, algorithms, implementation interfaces, security-sensitive configurations, and deployment topology. The four projects are not shown as an integrated deployed system.

## Infra OS: governed application flow

| Step | Responsibility | Control boundary |
|---|---|---|
| Mission | Define the objective, scope, and success conditions. | Authorized human context establishes the allowed work. |
| Evidence | Collect permitted context and expose support, freshness, conflict, and missingness. | Source content remains untrusted input. |
| Analysis | Combine deterministic processing with bounded model assistance. | A model suggestion has no approval authority. |
| Review | Present the proposal and its basis for human disposition. | The decision must be attributable and tied to the relevant evidence. |
| Action | Perform only eligible, permitted work. | Policy, durable state, and duplicate prevention constrain execution. |
| Record and measure | Retain the outcome, action evidence, audit, and quality observations. | A reported success and an observed effect remain distinct. |

The selected foundation is a modular monolith with PostgreSQL-backed transactional state and replaceable model, connector, identity, storage, and deployment boundaries. Some synthetic paths are implemented; full identity, provider, persistence, and release proof remains incomplete.

## Infra Agent Operations: controlled engineering work

| Responsibility | Intended role |
|---|---|
| Accountable human | Authorizes scope and makes consequential approval decisions. |
| Coordination agent | Converts the approved objective into bounded work and an evidence obligation. |
| Deterministic enforcement | Constrains permissions, transitions, limits, and stops independently of agent text. |
| Engineering agent | Performs the authorized work within its isolated scope. |
| Independent review | Assesses the implementation and evidence before the human decision. |

This is a documented logical architecture. It does not represent an operational runtime or a verified isolation mechanism.

## Infra Model Research: experiment lifecycle

| Stage | Evidence needed |
|---|---|
| Question and registration | What is being varied, compared, and held fixed? |
| Data preparation | Are source use, provenance, identity, and separation established? |
| Training | Which exact experiment ran and what resources did it consume? |
| Evaluation | What does the defined held-out comparison show? |
| Restoration and review | Can the result be restored, checked, and interpreted within its limits? |
| Next decision | Does the evidence support another bounded experiment or stopping? |

A small training pipeline and selected experiments have been executed. Broader instruments, future studies, and synthetic probes retain their separate maturity labels.

## Infra Knowledge: meaning before execution

| Concern | Design intent |
|---|---|
| Meaning | Preserve the relationships that determine what a statement actually says. |
| Evidence | Distinguish a reference from substantive support and independent corroboration. |
| Context and time | Keep scope, versions, contradictions, and current applicability visible. |
| Authority | Distinguish historical provenance from the operative permission for an action. |
| Presentation | Preserve material meaning when a record becomes a human-readable view. |
| Action boundary | Check the current objective, authority, and exact intended effect before progression. |

The conceptual design and synthetic feasibility experiments provide partial evidence. Physical architecture, integrated interpretation, live enforcement, and qualifying system verification remain open.

## Shared boundary

Knowledge research can inform application design, model research can inform future provider choices, and agent-operations research can inform engineering practice. Each adoption still needs its own project decision. None of these relationships makes a supporting research project a production dependency by implication.
