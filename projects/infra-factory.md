# Infra Software Factory

**Purpose:** carry a human-defined software brief through planning, approval, bounded implementation, testing, review, and an evidence-based debrief.

[Portfolio](../README.md) · [Status and evidence](../docs/status-and-evidence.md) · [AI assistance](../docs/ai-assistance.md)

## The problem

AI-assisted development can produce a convincing completion report without establishing that the right work was authorized, the intended workspace was changed, or the result passed its acceptance criteria. Interruptions can also separate a conversation from the state of the work.

The software factory develops a practical local workflow around those problems. Its value is coordination and inspectable evidence: a brief becomes an explicit plan, implementation follows human approval, and completion must account for tests, review, remaining gaps, and the original request.

## Roles and workflow

The human owner sets goals, approves scope and resources, decides material changes, and retains authority for acceptance, publication, merge, and deployment. An accountable AI lead owns planning, delivery, integration, and the return of evidence within that authority.

Current documented policy requires separate test-engineer and read-only final-reviewer roles for software-development runs. The test engineer independently evaluates acceptance and regression coverage; the reviewer examines the final change and evidence. Other specialists are conditional on the task. Multiple AI roles provide separated duties, but do not by themselves establish independent corroboration or security assurance.

The intended workflow is to inspect the target, record the brief, propose a bounded plan, check prerequisites, and obtain explicit approval before implementation. After approval, the lead implements within the recorded limits, coordinates applicable specialists, tests and repairs, records checkpoints, and returns a debrief. Material changes and unresolved blockers return to the human decision boundary. Failure, blocked work, and exhausted limits remain visible outcomes.

These are operating requirements. They do not establish that every historical task followed the current policy.

## Implemented capabilities

The reviewed local implementation supports structured plans, prerequisite checks, approval tied to recorded inputs, durable task state, progress checkpoints, and recovery inspection. Its primary interface uses a native coding-agent terminal session rather than requiring the owner to relay instructions between applications.

Completion handling validates the submitted result and reruns the plan's acceptance commands before accepting a successful result. Recorded limits constrain progression, and changed approval inputs can require renewed approval. Regression evidence covers selected invalid inputs, stale results, failed acceptance, interruption, and recovery paths.

These are local implementation and test observations. A workflow check cannot establish that the acceptance criteria were sufficient or that an AI review was correct.

## Demonstrated progress

Retained records distinguish three bounded demonstrations:

- **Planning:** a real AI planning session produced a structured proposal and passing prerequisite checks, then stopped before implementation approval.
- **Recovery:** an earlier task deliberately blocked, reconstructed its objective from durable records in a fresh process, resumed after human authorization, and completed its recorded acceptance checks.
- **Interactive delivery:** a trivial synthetic software task proceeded through approval, implementation, checkpoints, passing contract tests, and a completed debrief. The harness independently reran the recorded acceptance commands.

The interactive demonstration predates the stronger requirement for separate test-engineer and final-reviewer children. Those records establish the bounded task flow; execution of the current specialist policy requires separate evidence. The demonstrations were not repeated for this portfolio, and the reviewed current working tree is not presented as an accepted release.

## Limitations and relationship to the portfolio

The evidence does not establish general autonomous-delivery reliability, production readiness, a verified host-security boundary, or effectiveness across arbitrary projects. Blocker reporting remains local. Interactive elapsed limits are checked at workflow boundaries; an already open session is not forcibly terminated at the exact limit. A broader security-review procedure is documented, but its existence is not evidence that a product passed that review.

The factory is a supporting engineering capability alongside the four research projects. It is distinct from [Infra Agent Operations](infra-agent-ops.md), whose architecture, operational-runtime proof, and security obligations retain their own scope and acceptance gates. Factory demonstrations do not close those obligations or establish an integrated portfolio product.

The work and this brief use AI assistance as described in the [portfolio disclosure](../docs/ai-assistance.md). Human responsibility for scope, consequential decisions, acceptance, and publication remains explicit.
