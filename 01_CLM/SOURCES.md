# CLM Primary Sources

This page records official sources used for the CLM comparison.

- Official repository: https://github.com/facebookresearch/context-language-models
- CLM harness system prompt: https://github.com/facebookresearch/context-language-models/blob/main/clm/clm_harness/clm_agent/prompts.yaml
- CLM harness documentation: https://github.com/facebookresearch/context-language-models/blob/main/clm/clm_harness/README.md
- Edit gate implementation: https://github.com/facebookresearch/context-language-models/blob/main/clm/clm_harness/context_env/edit_gate.py
- Project README with zero-shot, in-context optimization, and reinforcement-learning result summaries: https://github.com/facebookresearch/context-language-models/blob/main/README.md

## Claim boundary

The zero-shot result should be described as use of existing models with an explicit context-management harness and system prompt. The repository separately reports in-context optimization and reinforcement-learning experiments; those are separate experimental branches.

## Repository snapshot used for this audit

GitHub main-branch commit observed on 2026-10-04:
`18dc11115f50f261233c5bba7937834491e307e8`

Public-facing quotations or implementation claims should preferably be checked against this pinned revision or a later explicitly recorded revision.
