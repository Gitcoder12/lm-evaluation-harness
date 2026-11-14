# LM Evaluation Harness Fork — Feature and Experiment Plan

## Objective

Build a small, reproducible model-evaluation portfolio with transparent configurations and carefully attributed upstream contributions.

## P0 — first reproducible benchmark

- [ ] Run one supported task with a pinned model revision, dataset revision, harness commit, backend version and exact command.
- [ ] Record task configuration, few-shot count, prompt template, batch size, seeds, metric aggregation and hardware.

## P1 — reliability and interpretation

- [ ] Repeat runs where sampling introduces variance and report distribution, not only a single score.
- [ ] Include baseline comparisons and explain metric limitations.
- [ ] Verify task and dataset licences; record contamination caveats.

## P2 — custom tasks and upstream contributions

- [ ] Repeat a run where randomness applies and record variance; check contamination/licence caveats for any custom dataset.
- [ ] Create local benchmark reports in a separate portfolio directory and link exact configs/results.
- [ ] For upstream bugs or task contributions, reproduce on a pinned commit and follow upstream review/licence requirements.

## Definition of done

- [ ] Another researcher can reproduce the result from exact config and model/dataset revisions.
- [ ] Metric definition and aggregation are explicit.
- [ ] Run environment and backend versions are pinned.
- [ ] Local experiments and upstream contributions are clearly separated.
