# Reproducibility Standard

Every meaningful result should be reproducible.

## Minimum standard
- Pinned dependencies (requirements.txt / environment.yml)
- Documented data version + license
- Fixed random seed where applicable
- Commit hash recorded with results
- Clear instructions to rerun

## Experiment logging (required)
Every experiment/run should have:
- date
- dataset + version
- model + version
- parameters
- seed
- metrics
- notes on failure modes and edge cases

Recommended: use the Experiment Log template.
