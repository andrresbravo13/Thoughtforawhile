# Research & Build Agenda (Thought for a while)

## Thesis statement
Healthcare will not be transformed by a single model. It will be transformed by **systems**: human-in-the-loop workflows that coordinate multiple AI components, interoperable data access, careful interfaces, and rigorous evaluation under ambiguity.

My thesis is that the highest-impact path for clinical/applied AI is to build **safety-first, evidence-grounded, interoperable prototypes**—evaluated like real systems, not like isolated models.

## North-star outcomes (12–18 months)
1) A portfolio of **5–8 public, reproducible artifacts** (benchmarks, prototypes, technical reports, tools)
2) **2+ conference-ready submissions** (poster/workshop level or higher)
3) A repeatable build discipline: **reproducibility, evaluation, documentation, governance**

## What I will build (core projects)

### 1) PsychSync — multi-agent acute mental health decision support
**Goal:** a triage + coordination assistant that supports clinician judgment under uncertainty.

**Planned deliverables**
- Agent architecture + guardrails (human-in-the-loop checkpoints)
- Synthetic vignette evaluation harness + scoring rubrics
- Workflow-native UI mockups + integration plan
- Safety case: failure modes, escalation logic, uncertainty reporting
- Documentation: dataset cards, model cards, experiment logs

### 2) MedPal — AI patient navigator for chronic care / oncology
**Goal:** reduce friction in care pathways (education, scheduling, adherence, follow-up).

**Planned deliverables**
- Patient-journey state machine + retrieval layer
- FHIR-aligned integration plan (data inputs + outputs)
- Usability test protocol + equity considerations
- Reproducible demos using public or synthetic data
- Documentation: dataset cards, model cards, experiment logs

### 3) Benchmarks & evaluation tooling (shared infrastructure)
**Goal:** build public evaluation suites for high-stakes, ambiguous clinical tasks.

**Planned deliverables**
- Benchmark tasks + baseline models
- Calibration + uncertainty reporting templates
- Rubrics for “clinically useful outputs” (not just accuracy)
- Reproducibility toolkit (pinned versions, seeds, experiment templates)

## Methods (how I will work)
- Cadence: **1–1.5 hours/day**
- Rule: **ship a weekly artifact**
- Evidence discipline: citations and transparent limitations
- Safety discipline: no PHI, no clinical deployment, governance-first collaborations

## Evaluation (how progress is measured)
- Technical: reproducibility, documented experiments, baseline comparisons, error analysis
- Clinical: workflow fit, usability signals, safe escalation paths, interpretability under ambiguity
- Communication: stakeholder-ready summaries and honest uncertainty reporting

## Collaboration asks (specific)
If you’re open to supporting this journey:
- 15-minute feedback on a prototype or write-up (monthly or one-off)
- Pointers to high-value public datasets and evaluation standards
- Clinical workflow insight (what matters in real practice)
- Governance-approved collaboration pathways (retrospective studies when appropriate)

Contact: **andres@thoughtforawhile.com**
