# Infra Agent Operations

**Purpose:** design controlled local agent operations for planning, engineering, verification, evidence, and human approval.

[Portfolio](../README.md) · [Architecture](../docs/architecture.md) · [Research](../docs/research-and-findings.md)

## The problem

An agent can produce a useful result while exceeding its authority, modifying the wrong object, consuming excessive resources, or leaving evidence that is difficult to verify. Task completion alone is therefore an incomplete success criterion.

This project studies how work can remain bounded by an explicit human instruction, independently enforced limits, separated duties, and reviewable evidence.

## Architectural direction

The logical MVP design has two agent roles: coordination and engineering. Independent architecture, security, research, and verification functions support review outside that logical runtime.

A deterministic control capability is required to govern permissions, workflow transitions, resource limits, and stops. The probabilistic agents must not enforce or approve their own authority. Approved work should bind to a defined repository, change scope, verification obligation, and human decision boundary.

The intended cycle is authorization, bounded execution, independent verification, evidence return, and a human merge decision. Isolation and trusted confirmation are proof obligations. Technology choices and later security proofs must retain their own approval and verification boundaries.

## Documented progress

The Phase 2 architecture package and governance baselines were completed. Subsequent records address implementation entry, bounded troubleshooting, resource controls, and proof-first investigation of trusted human confirmation.

These are architecture and planning outputs. The reviewed materials do not establish an operational runtime, a completed end-to-end autonomous engineering cycle, or a proven host-security boundary.

## Research questions

- Can authorization be bound to the exact action and target that will be changed?
- Can independent evidence distinguish what an agent reported from what actually occurred?
- Can ordinary mechanical mistakes be repaired within existing authority while material uncertainty stops progression?
- Can resource and permission limits remain effective across failure and recovery?
- Can human confirmation remain trustworthy when the agent and surrounding tools are treated as untrusted?

The architectural requirements are documented. Their implementation and effectiveness require separate proof; they are not presented as measured outcomes.

## Relationship to the portfolio

Infra Agent Operations is an independently stoppable internal-tooling effort. It is not a prerequisite for Infra OS delivery, and its design does not authorize changes to another project.
