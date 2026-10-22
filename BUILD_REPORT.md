# Vikkypaedia course build report

Built 21 October 2026 from the supplied 2,156-page PDF. All 103 numbered chapters and both reference appendices are represented. Scope: PDF 21–2156; front matter 1–20 is explicitly excluded from teaching scope. Original source attribution is retained.

| Component | Delivered |
|---|---:|
| Source chapters |103|
| Reference appendices |2|
| Guided modules |105|
| Measurable outcomes and mapped units |525|
| Authored recall cards |630|
| Authored single-best-answer MCQs |525|
| Automated source-association MCQs |0|
| Progressive fictional cases |22|
| Additional staged case decisions |66|
| Image placements/views |1471|
| Raster image placements |1153|
| Recovered vector-diagram renders |318|
| Original figure/table source-page views |1095|
| Additional tight table crops |37|
| Unmatched image-caption placements |134|
| Care principles/narrative excerpts |364|

Every section has six authored cards and five authored MCQs. There are no card/MCQ quota gaps. Cognitive-level coverage varies and is disclosed in the level selector and [curriculum metrics](build/curriculum_metrics.json). Five focused outcomes per module do not exhaust its source chapter.

## Verification

- [Technical/source coverage checks](build/verification.json):passed strict depth requirements, exact supplied-PDF scope, file/link existence, item/options/source validity and script syntax.
- [Browser checks](build/browser_checks.json):28 passed ; 105 local payloads and 105 guided modules rendered; all seven modes tested; narrow 390px layouts checked.
- [Guided browser checks](build/guided_browser_checks.json):25 passed; filtering, answer history, retry, reload persistence, exact source navigation, case stage guards, debrief timing, reflection export, Anki download and mobile focus behavior tested.
- [Extended alignment/media checks](build/extended_checks.json):449 passed; all 2,603 source image pixel streams decoded; all module outcomes and source/case links structurally checked. Case option positions were shuffled with answer indices preserved.
- [Chapter-boundary checks](build/chapter_boundary_audit.json):all 105 first-page titles matched.
- [Original indexing audit](build/source_index_verification.json):working-copy normalization preserved source content streams; independent page count and selected stream hashes compared.

[Desktop preview](build/previews/desktop.png) · [Mobile appendix preview](build/previews/mobile-appendix.png) · [Mobile guided preview](build/previews/mobile-guided.png).

## Review status and limits

Technical checks establish software behavior, structural source traceability and media integrity. Authored teaching was model-checked against selected passages. Chapters 1–8 also received a separate model cross-check. Independent neonatal specialist review, comprehensive sentence/table review, learner testing, measured learning gain and full accessibility conformance audits remain unperformed.

[Source review notes](SOURCE_REVIEW_NOTES.md) document nine selected source concerns avoided in authored teaching, plus 18 printed-page jumps at chapter boundaries. Original text/images have not been silently corrected. Caption pairing and vector bounds remain partly automatic; 134 image placements have unmatched caption metadata. Full original source-page views retain layout for figure/table interpretation, including all nine Appendix A table pages. The tight table crop count is not a count of all textbook tables, and semantic table conversion is not claimed.

The course is a local personal-study package for this source edition. The large original PDF remains in Downloads. [Source credits and rights](SOURCE_CREDITS.md) distinguish the publisher material from Vikkypaedia's teaching interface.
