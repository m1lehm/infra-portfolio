# Research Questions and Findings

[Portfolio](../README.md) · [Evidence scope](status-and-evidence.md)

These are selected project observations and questions. **Observed** means recorded in the reviewed internal evidence; **synthetic finding** means a bounded local experiment; **design requirement** means specified but not proven; **hypothesis** means an open research direction. Results have not been rerun for this portfolio, and no external security certification or general safety rate is claimed.

## 1. Can an agent succeed at a task while violating its authorization?

**Evidence type: observed internal failure and synthetic follow-up.**

An internal review handoff recorded a return on a different collaboration surface from the one authorized. Other internal records identified provenance-based attribution problems and work that continued after its higher-order decision relevance had changed. These support distinct failure classes: task correctness, authority attribution, target correctness, and objective relevance.

A later synthetic action-gate experiment challenged exact targets, changed state, competing claims, and ambiguous effects. Initial fixtures passed; expanded tests then reproduced defects, including a simulated dispatch from a permit that should have remained invalid. Repairs were checked without changing the original expected outcomes.

**Result:** the final fixture suite reported zero unauthorized or duplicate dispatches within its stated final opportunities. That final result does not erase the earlier unsafe simulated behavior. Control inputs were synthetic, and durable/provider-backed enforcement was not established.

**Open question:** can independently enforced controls preserve these distinctions across genuine identity, concurrent execution, provider state, and recovery?

## 2. Does valid structure or matching integrity evidence establish valid meaning?

**Evidence type: synthetic finding.**

Structural-admission experiments distinguished valid, invalid, unsupported, and unresolved cases while keeping semantic authority unestablished. Additional tests exposed defects involving derived validation state and incomplete reference checking. Repairs restored the expected classifications, and failed checkpoints remained in the source evidence.

Human-facing-view experiments also found that matching or recomputed hashes could coexist with a material permission or reference-binding defect. Byte integrity answers whether particular bytes match; it does not establish whether those bytes preserve the intended meaning or carry valid authority.

**Result:** the experiments supported separate structural, semantic, presentation, and authorization checks. Their finite cases did not prove general semantic correctness, human understanding, or permission to act.

**Open question:** what independent interpretation and adversarial testing can establish useful agreement beyond a shared implementation and fixed fixtures?

## 3. Can history remain trustworthy when the current state changes?

**Evidence type: synthetic finding and retained negative evidence.**

A conditional semantic-resolution study matched its initial expected classifications, but later integrity checks found two fixture changes that reused the same version identity. This meant matching reports alone did not establish immutable historical continuity.

The correction preserved the older evidence, represented changed state explicitly, and retained exact historical inputs for replay. Final repeated reports agreed within the same implementation. Unsupported and unresolved cases remained visible, with no actual permission or external dispatch produced.

**Result:** expected-output agreement and historical integrity are separate verification obligations. Repeatability with one resolver does not establish independent interpretation agreement.

**Open question:** how should changing context, authority, and evaluation rules affect the future use of retained knowledge without rewriting history?

## 4. Can a synthetic browser workflow demonstrate secure identity?

**Evidence type: implemented prototype boundary and open security requirement.**

Infra OS has documented synthetic backend, API, and browser reference work. Its browser test path uses controlled synthetic identity rather than real-user login. Later design records explicitly retain genuine browser/API identity as a separate trust-boundary problem.

**Result:** a working browser flow provides evidence about its tested workflow. It does not establish authenticated human identity, production access control, or secure deployment.

**Open question:** what is the smallest verifiable route from authenticated human identity to application authorization while keeping role and approval authority outside caller-controlled input?

## 5. What does a working tiny language model actually prove?

**Evidence type: measured experiment.**

The baseline completed training, held-out evaluation, restoration, and generation. Held-out loss improved from approximately 4.389 to 2.105 and beat the registered uniform and unigram comparisons. Text generation still suffered from repetition and inconsistent coherence.

A later fixed-budget unique-data experiment found a practical degradation boundary between 12.5% and 16.796875% of the available training text under its defined method.

**Result:** the pipeline worked and the particular comparisons produced measurable observations. A one-seed, one-corpus result is not a general scaling law, broad language capability, or evidence of commercial utility. See the [model brief](../projects/infra-model-research.md) for the experiment limits.

**Open question:** which findings persist across seeds, corpora, tokenizers, and independently reproduced environments, and which improvements justify additional resources?

## 6. Can a system improve without giving itself authority to change its controls?

**Evidence type: research synthesis and hypothesis.**

The portfolio distinguishes several possible improvement surfaces: knowledge, context, deterministic software, workflow, agent harnesses, data, and model weights. A measured failure may call for a small clarification or control repair rather than retraining or redesign.

The research synthesis also identifies risks from optimizing proxies, learning from corrupted history, overfitting to replay, changing evaluators, and treating internally repeated claims as independent evidence.

**Current result:** a structured research agenda and governance principles exist. An effective recursively improving system, improved safety rate, or general learning policy has not been demonstrated.

**Open question:** can prospective, independently assessed studies show better authorized outcomes while preserving human control over accepted knowledge, policy, and scope?

## What these findings changed

Across the work, passing a local test became a narrower claim: it must identify the exact invariant, implementation, inputs, and environment checked. Negative evidence is retained. Missing proof remains a gap. Research questions generate bounded next studies; they do not create execution or release authority.
