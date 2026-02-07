# MedPal

## Purpose
MedPal is an AI-enabled patient navigation prototype designed to reduce friction in care pathways (education, scheduling, adherence, follow-up), with an initial emphasis on chronic care and oncology-style coordination problems.

## Target users
- Patients and caregivers navigating complex pathways
- clinic coordinators
- care teams supporting adherence and follow-up

## Core capabilities (planned)
- Patient-journey state machine (what step are we in, what’s next)
- Retrieval layer for trusted resources (citations required)
- Coordination support: reminders, checklists, preparation steps
- FHIR-aligned integration plan (data inputs/outputs)

## What success looks like
- Clear action steps and “next best actions”
- Explicit boundaries (when to contact a clinician)
- Equity-aware design (language, readability, accessibility)
- Reproducible evaluation: navigation completion rates, error analysis

## Evaluation plan
- Public/synthetic scenarios (no PHI)
- Rubric-based scoring for navigation quality and safety
- User testing with non-clinical volunteers (first)
- Workflow memo: how this could embed into real clinical systems

## Deliverables
- State machine diagram + flows
- Retrieval policy + citations standard
- Safety Case + Model Card
- Demo video + reproducible run
