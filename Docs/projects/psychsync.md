# PsychSync

## Purpose
PsychSync is a multi-agent decision support and coordination prototype for **acute mental health / emergency psychiatry workflows**. The goal is not to replace clinicians; it’s to help teams triage, prioritize, and coordinate under uncertainty while maintaining human responsibility.

## Target users
- ED clinicians / nurses (triage + risk framing)
- psychiatry teams (handoff + prioritization)
- unit coordinators (workflow and routing)

## Core capabilities (planned)
- Structured intake (symptoms, risk factors, context)
- Risk framing with uncertainty and escalation logic
- Multi-agent orchestration: evidence gathering, guideline retrieval, plan drafting
- Safety guardrails: “stop and escalate” conditions and conservative defaults

## What success looks like
- Clear, auditable reasoning (not hidden “magic”)
- Calibration: confidence reflects uncertainty
- Human-in-the-loop checkpoints at all high-stakes steps
- Usable workflow integration (doesn’t slow down the clinician)

## Evaluation plan
- Synthetic vignettes + rubric scoring
- Stress tests: ambiguity, missingness, adversarial phrasing
- Bias checks (where feasible)
- Usability feedback loops (non-clinical pilot testing first)

## Deliverables
- Agent architecture diagram
- Evaluation harness + benchmark suite
- Safety Case + Model Card
- Demo video + reproducible run instructions
