# Authoring audit: normalized chapters 73–105

Prepared 2026-10-21 by a model author. This is selected-passage source checking, not independent specialist review or a claim that every chapter paragraph was read.

## Delivered data

- Owned modules: batch_073_080.py, batch_081_088.py, batch_089_096.py, batch_097_105.py.
- 33 normalized chapters, including Appendix A (104) and Appendix B (105).
- 198 active-recall cards, 165 distinct authored four-option MCQs, 165 outcome-linked guided units.
- Seven progressive fictional cases, with three stages each: chapters 76, 80, 88, 89, 90, 95, 97. Case stages supplement the 165-item quota.
- Chapters import through the shared authoring helper; no shared save() call or shared JSON overwrite was performed.
- All item pages and case-stage pages checked against their corresponding chapter evidence page sets. Cards and questions preserve source-edition rather than independently updated guidance.

## What was reviewed

Chapter headings and selected paragraphs supporting the authored claims were read in the raw page-marked chapter files. Additional checks resolved question-specific material for coarctation, VSD physiology, atrial septostomy, skin barrier functions, joint aspiration/source control, posterior urethral valves and developmental drug-table interpretation. Original PDF renders were inspected for pages 1615, 2099, 2104, 2106, 2107, 2123, 2125, 2153 and 2156. These include the stool osmotic-gap formula and dense therapeutic/reference tables. No source illustration was re-labeled as manually reviewed when it was not seen.

Appendix A teaching emphasizes age dependence, compatibility, phenytoin-equivalent units, the absence of analgesia/amnesia from neuromuscular blockade, anticoagulant monitoring and elemental-versus-product mass. It deliberately supplies no standalone prescribing regimen. Appendix B teaches reference-population matching, developmental distributions, biomarker ages, bilirubin unit conversion and elementary-equivalent arithmetic. The arithmetic examples are not treatment thresholds or prescriptions.

## Source anomalies retained and avoided in teaching

1. Chapter 73 PDF 1375, Fig. 73.2 caption: bosentan is said to augment smooth-muscle vasoconstriction by blocking endothelin effects. This apparent wording error was not used in authored content.
2. Chapter 83 PDF 1565: WAGR is associated with an 11q13 deletion in the prose. This apparent locus error was not used in authored content.
3. Appendix B PDF 2123, Table B.15: original rendered creatinine unit headers read mmol/L beside values whose scale matches micromoles/L and the adjacent mg/dL values. Appendix B PDF 2153 independently prints the creatinine conversion factor 88.4 micromoles/L per mg/dL. The B.15 unit header was not silently changed and no numeric question relies on it.
4. Appendix B PDF 2125, Table B.18: original rendered hemoglobin mean ± SD is 20.4 ± 11.6 g/dL, alongside a 14.5–23.9 g/dL percentile interval. This internally questionable SD was not used in authored content.
5. Appendix A PDF 2107: original rendered aminophylline/theophylline trough targets use micrograms/L. No teaching item repeats those target values or units.

These are model-identified source concerns, not independently resolved errata. Original source pages remain the authority for what the supplied file actually prints; external authoritative verification has not been performed for this authoring task.

## Limits and review queue

The full reader preserves the substantially greater chapter depth beyond five guided units. The authored subset is an introduction and retrieval scaffold, not an exhaustive clinical protocol. Some modules have no justified Deep Dive unit; that absence is exposed by the helper rather than filled by invented complexity. Case performance assesses written reasoning, not observed clinical competence. Clinical correctness, contemporary guideline reconciliation, rights review, accessibility and rendered frontend behavior require the course-level review performed by the parent task; this audit does not certify those domains.
