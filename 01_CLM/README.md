# 01 CLM

## Scope

This section tracks the Context Language Models (CLM) paper and official implementation relevant to context self-management.

## Current working observation

The official CLM harness gives the model explicit instructions and mechanisms for managing an editable context representation during execution. The harness mirrors editable context to a file, instructs the model to compact stale regions, applies budget nudges, reads accepted edits back into the message list, and keeps the system/task prefix pinned.

Therefore, for the **zero-shot evaluation branch**, describing the reported result as "zero-shot with no instruction" would be misleading.

A more precise shorthand is:

> existing-model zero-shot evaluation with an explicit context-management system prompt and runtime harness.

This wording is intentionally limited to the zero-shot branch. The CLM project separately reports in-context optimization and reinforcement-learning experiments; those should not be collapsed into the zero-shot claim.

## Comparison target

The key comparison is not "same idea" but the different locus of context management:

- **CLM:** model-side / endogenous management of evolving context, enabled by an explicit harness.
- **Our bootstrap practice:** human-designed / exogenous initialization of context before substantive work.
- **Discussion Oogiri:** interaction-driven formation of persistent session tendencies without an explicit editable-context file.

## Primary sources

See [SOURCES.md](SOURCES.md). External claims in this section should be traceable to those official sources before publication.
