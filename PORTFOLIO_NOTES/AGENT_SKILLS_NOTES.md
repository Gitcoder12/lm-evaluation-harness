# Agent and Skills Notes — LM Evaluation Harness Fork

## Instruction precedence

Upstream AGENTS.md/CONTRIBUTING.md and repository conventions remain authoritative. These are portfolio-specific additions only.

## Bounded agent workflow

- Inspect task implementation, config schema and existing tests before changes.
- Pin exact harness/model/dataset revisions in experiment plans.
- Do not create benchmark results without executing the full run.
- Keep datasets licensed, privacy-safe and source-attributed.
- Distinguish upstream benchmarks from custom experiments.
- Make task/backend changes small, tested and reviewable.
- Never merge, release or publish benchmark claims autonomously.

## Skill areas

- Benchmark task configuration and metric implementation.
- Dataset provenance, licensing and contamination review.
- Model backend compatibility and reproducibility.
- Statistical treatment of repeated runs and variance.
- Upstream contribution and fork maintenance.
