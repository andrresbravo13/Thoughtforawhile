# Evaluation Metrics (Healthcare)

Accuracy is not enough.

## Core dimensions
### 1) Clinical usefulness
- Does the output improve decisions, workflows, or coordination?
- Are recommended actions feasible and appropriate?

### 2) Safety
- Does the system behave conservatively under uncertainty?
- Are escalation triggers clear?
- Does it avoid confident hallucination?

### 3) Calibration & uncertainty
- Confidence correlates with correctness
- Low-confidence outputs are clearly marked and safer

### 4) Robustness
- Handles missingness and ambiguity
- Doesn’t collapse on edge cases
- Resistant to prompt/wording artifacts (for language systems)

### 5) Equity & bias (as feasible)
- Performance checks across subgroups when data allows
- Explicit discussion of representativeness and limitations
