# Operational Bootstrap Discipline for GPT-5.6 Sol
## A Reader-State Oscilloscope Case Example

Status: **Draft technical appendix**

### Scope

This note documents a user-side observation: in long-running LLM work, the first turn can function as part of session initialization.

It does **not** claim persistent learning, weight updates, or mechanism equivalence with Context Language Models (CLM).

The narrower question is:

> How much of an LLM session's effective behavior depends on how its initial context, source order, authority boundaries, and retrieval scope are constructed?

### Operational bootstrap practice

A bootstrap may define source identity, reading order, retrieval limits, Human Owner versus AI authority, TARGET / PREDICTED / OBSERVED separation, task role, stop conditions, and handoff boundaries.

This is treated as operational initialization rather than ordinary prompt wording.

### Reader-State Oscilloscope A01-A04

The Reader-State Oscilloscope predicts how reader state may change while a text is read. It is not a scalar quality score or an automatic repair loop.

| Run | Condition summary | Main role |
|---|---|---|
| A01 | Early startup set before later Curriculum/Primer additions | Early baseline |
| A02 | Independent project-only-memory setup with six fixed startup resources | Closed-context baseline |
| A03 | A02 bootstrap pattern reused inside an existing project context | Context-variation specimen |
| A04 | Materially similar launch pattern in an isolated project | Closed-condition re-instantiation |

The strongest safe claim is:

> Different bootstrap and context conditions were associated with visibly different diagnostic and display structures.

This is an observational association, not a one-variable causal estimate.

### Comparability limits

The runs do not share a perfectly normalized design. A02 uses 22 samples, A03 26, and A04 25; channel sets and event granularity also differ. The 0-5 values are run-local ordinal diagnostic representations.

All plotted Reader-State values are **AI PREDICTED**. No human OBSERVED reader-state dataset was supplied.

Therefore, more samples, more channels, or richer display must not be read as higher performance.

### What changed visibly

Representative overview pages show differences in information architecture:

- **A01:** dense multi-channel presentation;
- **A02:** stronger measurement-oriented separation;
- **A03:** more human-facing grouping, event labeling, and commentary;
- **A04:** integrated overview with event and authority boundaries.

A02 and A04 also recover substantial shared qualitative macro-structure in the same target text, while detailed amplitudes and sampling differ.

### Comparison to CLM

The official CLM harness makes context management explicit during runtime: editable context is mirrored to a file, the model is instructed to compact stale regions, budget thresholds trigger nudges, accepted edits are read back into subsequent context, and protected prompt/task material is preserved.

For the zero-shot evaluation branch, a more precise description is:

> existing-model zero-shot evaluation with an explicit context-management system prompt and runtime harness.

The CLM project separately reports in-context optimization and reinforcement-learning experiments.

### Non-equivalence

| Case | Main mechanism | Control locus |
|---|---|---|
| CLM | Editable context during execution | Model + harness |
| Reader-State bootstrap practice | Initial source order, scope, authority, and stop conditions | Human-designed bootstrap |
| First Discussion Oogiri Dragon | Accumulated premises and interaction | Human-model interaction |
| Second Dragon | Extracted operating instruction transferred to an isolated project | Human-designed bootstrap |

No identity or priority claim follows from this comparison.

### Practical lesson

> Context should be treated as part of the experimental apparatus.

For long-horizon work, bootstrap wording, source identity, source order, and environment should be recorded as test conditions rather than discarded as incidental prompt text.

### Evidence boundary

This repository distinguishes **SOURCE**, **OBSERVATION**, and **INTERPRETATION**. The Discussion Oogiri first-dialogue reports are structural reconstructions, not verbatim transcripts. The Reader-State figure compares display/diagnostic structure, not quantitative performance.
