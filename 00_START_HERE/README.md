# 00 START HERE

## Research question

This repository examines a practical observation:

> The first turn of a long-running LLM session may need to be treated not merely as the first question, but as part of the session's operational initialization.

In current practice, bootstrap prompts may specify source identity, reading order, retrieval scope, authority boundaries, prohibited search paths, stopping conditions, and Human Owner decision boundaries before substantive work begins.

## Current comparison frame

### CLM
Context Language Models explicitly expose context management to the model during the run.

### Discussion Oogiri / Dragons
Long-horizon dialogue showed persistent generative tendencies emerging from accumulated premises and interaction. The first and second Dragon cases must be kept distinct: the first was substantially emergent; the second used an extracted operating instruction.

### Reader-State Oscilloscope
A01–A04 provide a useful operational example because bootstrap order, open/closed context, and repeated runs were separated rather than treated as one undifferentiated result.

## Important limitation

This repository does **not** assert that the model permanently learned from the conversation. The target is session-level effective behavior under different context conditions.
