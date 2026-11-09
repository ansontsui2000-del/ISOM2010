# Reference layout library

All source slide numbers are **one-based presentation order**, not internal XML filenames. Sources are the four decks supplied by the user. Selected PNGs were rendered from full-deck PDF exports and are retained locally. Some original slides use serif fonts or non-Calibri labels: **Calibri always overrides those choices**. Original values, claims, company marks, source citations, and team identities are not reusable content.

## Select by communication task

| Layout | Source deck / slide | Retained image | Reusable geometry and use |
| --- | --- | --- | --- |
| Executive summary | JUCC_Nestle.pptx / 3 | `nestle-03.png` (private local asset) | Four horizontal bands: situation, question, strategy, impact. Narrow left row labels; wider right panels with subcolumns. Use for a complete supplied story. |
| Competitor comparison | JUCC Training 3 PPT_TRYP.pptx / 5 | `maxim-05.png` (private local asset) | Criteria down a coloured left column, alternatives across top, aligned comparison cells, highlighted differentiating row, bottom implication box. Use textual judgments if no rating data is supplied. |
| Option selection | JUCC_Nestle.pptx / 23 | `nestle-23.png` (private local asset) | Compact comparison grid, coloured criteria column, outlined preferred option, takeaway underneath. Harvey balls require supplied ratings and an explicit legend; otherwise use text. |
| Evidence to implication | JUCC Training 3 PPT_TRYP.pptx / 6 | `maxim-06.png` (private local asset) | Capability → problem → impact headers, corresponding light panels, bottom takeaway. Rebuild the central break symbol cleanly; do not copy the empty starburst in the render. Arrows must not invent causation. |
| Problem to response | preface.pptx / 38 | `preface-38.png` (private local asset) | Two stacked problem panels on left mapped to two response panels on right, central gap illustration. Preserve row alignment and the matching problem/response relationship. |
| Strategy overview | preface.pptx / 13 | `preface-13.png` (private local asset) | Two equal photographic halves, dark overlays, thin white inset frames, strategy name and one-sentence audience/value proposition. Useful for two genuinely distinct initiatives. |
| Customer journey | preface.pptx / 22 | `preface-22.png` (private local asset) | Starting context/persona on left, staged circular journey at centre-right, start/end arrow across top, navigation footer. Use only a true cycle; adapt to a line when the supplied journey is linear. |
| Process recommendation | JUCC_Nestle.pptx / 17 | `nestle-17.png` (private local asset) | Compact left context column separated by a vertical rule; three illustrated stage cards on right; numbered horizontal process arrow below; rationale strip above. |
| Campaign sequence | JUCC Training 3 PPT_TRYP.pptx / 30 | `maxim-30.png` (private local asset) | Three visual stage cards along a large horizontal arrow, timing above each, shared duration bracket and outcome below. Use supplied time periods only. |
| Decision and feedback loop | Krungsri Bank Case.pptx / 47 | `krungsri-47.png` (private local asset) | Evaluation splits into pass/benefits and fail/support branches, then review and loop back. Use for conditional journeys, not a generic linear timeline. Simplify connectors to avoid crossings. |
| Annotated interface mockup | preface.pptx / 42 | `preface-42.png` (private local asset) | Large interface/device visual, isolated magnified feature panel, short explanatory callout. The original dim overlay is optional; keep new title and critical labels high contrast. Label proposed UI as a concept. |
| Financial impact bridge | preface.pptx / 52 | `preface-52.png` (private local asset) | Waterfall/bridge on left, stacked driver explanations on right. Preserve supplied values and units, compute totals rather than copy the reference numbers. Use a table if image geometry cannot be made accurate. |
| Monthly impact and KPIs | JUCC Training 3 PPT_TRYP.pptx / 44 | `maxim-44.png` (private local asset) | Period bars left; boxed headline KPIs and caveat/right-side impact notes. The original title/body uses inconsistent revenue/profit wording: copy only layout, never that inconsistency. |
| Implementation timeline | preface.pptx / 53 | `preface-53.png` (private local asset) | Gantt grid with time columns, activity rows, two grouped workstreams in related shades, phase brackets below. Owners and KPIs may be added only when supplied. |
| Risks and mitigation | preface.pptx / 54 | `preface-54.png` (private local asset) | Numbered positions on likelihood/impact plot left, matching numbered risk and mitigation boxes right. Ratings need an explicit supplied basis; otherwise use a risk table. |

## Reference framing

- Maxim's: small section label over the action title; top-left accent tab; thin title separator; source line; logo, section navigation and page at the bottom. Original orange is a replaceable brand token.
- Nestlé: strong full-width title band, coloured table headers and process panels, compact section navigation. Original burgundy and serif typography are replaced by target-company colours and Calibri.
- Krungsri: white background, small section label and left accent tab, company mark at top right, diagram-led body, footer navigation. Original yellow is a replaceable brand token.
- Preface: light analytical pages, dark title and rule, small top-right mark, blue/grey panel hierarchy and bottom navigation. The split-photo strategy page is a deliberate exception to the light body frame.

Choose **one main layout** rather than mixing all four deck styles. Preserve a single frame across a multi-slide request. Use company names as plain labels when an accurate logo is unavailable. For standalone mockups, use the relevant section and page 1 instead of inventing a whole deck's navigation.

## Contact sheets

Use for quick selection, then open the chosen individual image before generation:
`Maxim's` (private local asset), `Nestlé` (private local asset), `Krungsri` (private local asset), `Preface` (private local asset).

No blank pages or repeated animation stages are retained. These are layout references, not polished templates: improve legibility and correct source rendering defects while preserving structural fidelity.
