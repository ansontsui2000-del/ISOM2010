# Generation recipe and acceptance checks

## Prompt structure

Use the following structure with concrete values, not unresolved placeholders:

```text
Use case: productivity-visual.
Deliverable: one flat, edge-to-edge 16:9 slide image, opaque background.
Reference image 1: layout and visual hierarchy only. Retain [specific geometry,
headers, spacing, arrows, footer]. Replace all old content, names, logos,
numbers, sources, and colours with the specification below.
Company: [name]. Brand palette: [hex values and roles].
Company shape language: [geometry, corner treatment, motif and application areas;
officially specified or inferred from linked company materials]. Preserve the
analytical structure and the meaning of arrows, decisions and chart marks.
Typography: Calibri throughout; bold action title, clear section headers,
regular body text, legible source footer. Keep analytical consulting density.
Composition: [precise position and relationship of each content region].
Text, verbatim by region:
[Exact title, headers, copy, values, labels, units, qualifiers, footer.]
Data encoding: [values and proportional relationships, or no quantitative chart].
Navigation: [section and page, or supplied deck navigation].
Constraints: no invented text, metrics, source citations, logos, or extra panels;
no clipped or overlapping elements; no scene mockup, device around the slide,
3D perspective, decorative gradients, or watermark.
```

The prompt specifies Calibri but does not guarantee that the image model renders that font exactly. Use the tool's supported image-reference mechanism, not an invented argument. View a local reference before supplying it. Do not send an entire PDF or PPTX as though it were an image reference.

## Review every result

- **Meaning:** headline matches the supplied argument, with the same certainty; all evidence and caveats survive.
- **Copy:** inspect spelling, company names, every number, percentages, currency, dates, units, sample sizes, and footnotes. Generated decorative microtext is a defect.
- **Quantitative encoding:** axes and scales agree, bars have proportional lengths, waterfall starts/ends and totals reconcile, arrows express only supported relationships. If accuracy cannot be maintained, use a table/callout while retaining the surrounding reference frame.
- **Layout fidelity:** chosen reference remains recognisable in its geometry and reading order; no generic redesign or unrequested simplification.
- **Branding:** target palette overrides source colours; original company marks and consulting-team names are absent; semantic risk colours have a legend where needed.
- **Shape identity:** container geometry and motifs reflect the target company's supplied or observed identity, not just a colour swap. The shape brief is applied consistently without distorting analytical relationships or inventing an official brand rule.
- **Legibility:** inspect at full size and ordinary slide-view size; no clipping, text collisions, tiny critical labels, or low-contrast text. The slide should fill a 16:9 image without surrounding chrome.
- **Dimensions:** request 16:9 and check the actual saved pixel dimensions. Image generation may return a near-16:9 canvas; do not claim exact dimensions unless verified. If exact sizing is required, correct through the supported image workflow or report the mismatch.
- **Delivery:** save and display the actual image, plus retain the exact prompt. Do not claim editability, exact font fidelity, verified company facts, or interactive navigation.

## Behavioural checks when updating this skill

1. **Analytical comparison:** supplied two-option comparison, fixed criteria, no numerical scores. Expect a reference-based matrix, unchanged conclusions, no fabricated ratings.
2. **Recommendation/process:** supplied stages with owners and durations. Expect correct order and labels, proposed status retained, no invented KPI targets.
3. **Missing evidence:** supplied unsupported superiority claim. Expect uncertainty retained or an evidence-needed flag, not invented statistics.
4. **Different company:** same content structure, different supplied brand palette. Expect the same layout with the new palette, no source company identity.
5. **Dense content:** too much text for one slide. Expect faithful condensation or a justified split rather than tiny text.
6. **Explicit editable request:** explain the image boundary and use the presentation workflow; do not present a raster image as editable PowerPoint.
