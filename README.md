# harness-engineering

Most repos teach you how to build agent harnesses.
This one optimizes them automatically — using verifiable 
rewards and sandboxed execution.

## What it optimizes
- `AGENTS.md` — agent behavioral constitution
- `skills/*.md` — procedural skill documents
- `tool_config.yaml` — tool enablement & parameters

## How it works
Run N sandboxed rollouts of a candidate harness artifact.
Score each rollout using binary, environment-grounded 
verifiers. Use failure patterns to mutate the artifact.
Repeat until pass rate target is hit.
