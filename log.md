---
title: BPMH Paediatric Scenarios — Change Log
description: Provenance, conversion notes, known assumptions, and maintenance history for the BPMH paediatric scenario bundle.
---

# Change Log

Return to the [scenario index](index.md).

## 2026-07-17 — Initial OKF Conversion

### Added

- Created `index.md` as the bundle entry point.
- Divided the reference library into:
  - `basic.md`
  - `intermediate.md`
  - `advanced.md`
- Added YAML frontmatter to each knowledge file.
- Added relative links between the index, knowledge files, and change log.
- Retained the original scenario numbering, metadata fields, interview flows, decision trees, and Learner Performance Indicators headings.
- Moved the summary table and editing guidance into `index.md`.

### Editorial Changes

- Standardised headings, tables, punctuation, and medication unit spacing.
- Replaced some absolute clinical statements with prompts for appropriate clinical review.
- Clarified the difference between information gathering and independent prescribing decisions.
- Added source verification, confidentiality, safeguarding, and escalation boundaries where relevant.
- Expanded some performance indicators to make scenarios easier to assess consistently.

### Scenario 5 Arithmetic Correction

The source stated:

> Amoxicillin 400 mg/5 mL; parent giving 5 mL = 200 mg per dose.

This is arithmetically inconsistent. A 5 mL dose of a 400 mg/5 mL formulation contains 400 mg. The converted scenario uses 400 mg per dose.

The scenario now treats appropriateness as requiring verification of the indication, prescribed directions, duration, weight, and other clinical factors rather than asserting that the dose is inappropriate from weight alone.

### Clinical Governance Note

These scenarios are educational materials and are not prescribing protocols. Medication continuation, withholding, re-exposure, allergy classification, perioperative management, and dose changes must follow local policy and review by an appropriately authorised clinician.

## Maintenance Guidance

When changing a scenario:

1. Update the relevant difficulty file.
2. Preserve the scenario number unless intentionally versioning the whole collection.
3. Keep the Metadata table and Learner Performance Indicators heading.
4. Record clinically significant or structural changes in this file.
5. Review links from `index.md`.
6. Check calculations involving strengths, concentrations, volumes, and doses.
7. Review clinical assertions against current local guidance before deployment.