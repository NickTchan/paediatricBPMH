---
title: BPMH Paediatric Scenarios
description: A reference library of paediatric Best Possible Medication History scenarios, organised by difficulty.
---

# BPMH Paediatric Scenarios

A reference library of paediatric Best Possible Medication History (BPMH) scenarios for simulated interviews, learner assessment, and clinical communication training.

**For use with:** `BPMH_Copilot_ConsolidatedPrompt.md`

Each scenario is self-contained and human-editable. Copy the patient details into the scenario briefing, then follow the interview flow or decision tree during the simulated interview.

## Scenario Collections

- [Basic Difficulty](basic.md)  
  Parent or caregiver histories, OTC and complementary medicine discovery, and allergy screening.

- [Intermediate Difficulty](intermediate.md)  
  Conflicting informants, formulation verification, adherence barriers, and perioperative medication management.

- [Advanced Difficulty](advanced.md)  
  Adolescent confidentiality, maternal medication exposure, and histories requiring external verification.

## Scenario Summary

| # | Type | Domain | Difficulty | Key Teaching Point |
|---|---|---|---|---|
| 1 | interaction | Caregiver Communication | Basic | Probe for specifics and confirm labels |
| 2 | interaction | OTC/Complementary | Basic | Use a dedicated OTC and complementary medicine prompt |
| 3 | decision | Allergy Screening | Basic | Distinguish allergy from side effect or unclear rash |
| 4 | interaction | Multiple Informants | Intermediate | Reconcile conflicting reports |
| 5 | interaction | Formulation Verification | Intermediate | Confirm the label and calculate the administered dose |
| 6 | exception | Adherence | Intermediate | Probe actual use and explore barriers |
| 7 | decision | Pre-op Context | Intermediate | Include OTC products and supplements; flag concerns for review |
| 8 | interaction | Adolescent Patient | Advanced | Offer an appropriate confidential disclosure opportunity |
| 9 | qna | Neonatal/Breastfeeding | Advanced | Ask about maternal medication history and exposure |
| 10 | exception | External Verification | Advanced | Use secondary sources when the history is incomplete |

## How to Use the Scenarios

1. Select a difficulty level.
2. Choose a scenario appropriate to the learning objective.
3. Give the learner only the scenario briefing or opening information.
4. Use the interview flow, decision tree, and withholding instructions to respond.
5. Assess performance using the Learner Performance Indicators.
6. Record local adaptations in [`log.md`](log.md).

## How to Edit Scenarios

1. **Patient details:** Update Name, Age/Gender, Informant, and Presenting Issue.
2. **Medications:** Add or remove medicines, doses, formulations, and frequencies.
3. **Complexity factors:** Specify what information is withheld and when it should be disclosed.
4. **Interview Flow:** Edit dialogue examples while retaining the intended learner prompts.
5. **Decision Trees:** Modify branches as needed while keeping their structure clear.
6. **Performance Indicators:** Update positive and negative indicators according to local teaching priorities.

**Do not change:** Scenario section headers, Metadata fields, or Learner Performance Indicators headings where downstream agents rely on them.