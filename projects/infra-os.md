# Infra OS

**Purpose:** build a reusable platform for carrying a defined mission from authorized context and evidence through review, permitted action, and an inspectable record.

[Portfolio](../README.md) · [Architecture](../docs/architecture.md) · [Status](../docs/status-and-evidence.md)

## The problem

A useful AI answer is only one part of completing consequential work. The surrounding system must establish which sources were allowed, whether evidence is current, who can decide, which actions are permitted, and what happened after interruption or failure.

Infra OS develops that surrounding application foundation. Its intended value is a repeatable way to coordinate intelligence under human control across different business contexts.

## Architectural direction

The approved direction is a modular monolith with explicit domain boundaries and PostgreSQL as authoritative transactional state. Conceptual responsibilities include missions, evidence, deterministic policy, human approval, bounded actions, provider adapters, audit, and measurement.

Models and connectors sit behind replaceable interfaces. Model output remains a proposal or analytical input. Deterministic software owns the controls that decide whether an action is eligible, and consequential decisions require attributable human approval.

Durability, bounded retries, and duplicate prevention are design requirements. Provider neutrality is an architectural objective whose complete substitution evidence remains subject to verification.

## Documented progress

The repository records completed mobilization and founding controls, integrated charter amendment work, and completed Define, Measure, and Analyze gates with conditions carried forward. Several bounded Design slices are accepted and integrated.

Later work includes a synthetic backend reference mission, an in-process API boundary, and a thin browser reference workflow. These connect evidence, non-authoritative model suggestions, human dispositions, permitted local-action handling, and audit views within the stated test environment.

The browser work uses synthetic identities and a controlled test bridge. It does not establish real-user authentication or a deployable authenticated service. The next identity-boundary design work remains separately governed.

## What remains open

Authenticated identity and enterprise-provider proof, complete evidence intake, broader recovery and restore proof, production-like application packaging, complete security evidence, usability validation, provider substitution, and final release acceptance remain open obligations. The acceptance target is a planning target, not a statement of completion.

This portfolio makes no claim of customer deployment or production readiness. The development boundary uses synthetic and specifically approved non-customer material; no customer or personal records are included here.

## Representative design question

Can a system keep a recommendation, its supporting evidence, a human decision, an attempted action, and an independently observed effect distinct throughout the workflow?

The synthetic reference work provides bounded evidence for parts of that separation. Full product verification must show that the same controls survive genuine identity, provider, persistence, failure, and deployment boundaries.
