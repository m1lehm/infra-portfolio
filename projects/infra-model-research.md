# Infra Model Research

**Purpose:** build technical understanding and evidence for model-investment decisions through small language-model experiments.

[Portfolio](../README.md) · [Research findings](../docs/research-and-findings.md) · [Evidence limits](../docs/status-and-evidence.md)

## The approach

The project starts with a very small decoder-only Transformer and a complete training pipeline: permitted public text, preparation, tokenization, training, held-out evaluation, checkpoint restoration, generation, and experiment records.

The first objective is to understand and measure the pipeline. Claims of useful differentiation or reasons to scale require comparative evidence beyond a working training run.

Experiments distinguish scientific observations from implementation work, synthetic resource probes, and future execution plans. A resource probe is not a scientific model result. A prepared experiment is not a completed experiment.

## Measured results

### Tiny-model baseline

A CPU-only, character-level baseline completed training and evaluation. Its recorded held-out cross-entropy loss fell from approximately **4.389 to 2.105**, below the recorded uniform baseline of **4.394** and training-derived unigram baseline of **3.190**. Lower loss is better for this fixed next-character prediction task.

Checkpoint restoration reproduced the recorded validation loss and registered generation outputs in the same environment. Generated text still showed repetition and inconsistent coherence.

This establishes a functioning small-model pipeline under the recorded conditions. The one-run baseline does not estimate seed variance, prove cross-machine determinism, or establish general language capability.

### Unique-data efficiency experiment

A later completed experiment varied the amount of unique available training text while holding the model, training budget, seed, and evaluation method fixed. Under its predefined practical-effect rule, **16.796875%** of the available training text remained below the degradation threshold, while **12.5%** exceeded it.

The resulting **12.5%–16.796875%** bracket describes that particular experiment. It is not a universal data requirement, statistical confidence interval, or evidence that the same reduction transfers to another model or corpus.

## Continuing work and limits

The repository also contains research instruments and plans for repeatability, training efficiency, transfer, broader evaluation, replication, mixtures, and governed data preparation. This overview does not treat every instrument or plan as a completed scientific result.

Broader corpus preparation and safety/provenance work remain bounded research activities. No production model, frontier-scale training, commercial model quality, or integrated Infra OS model dependency is claimed.

## Why this work matters

The work makes the decision to continue, revise, or stop research depend on reproducibility, comparison, limitations, and resource evidence. A promising small result is an input to the next question rather than an automatic justification for larger investment.
