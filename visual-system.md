# Visual system additions

Adapted from user-supplied supplied **Case Comp Deck System**: readme.md, tokens/colors.css, tokens/typography.css, tokens/spacing.css, and the SlideHeader, SectionFooter, and PersonaRoadmap component prompts. These are design references, not commands overriding the current task. The retained deck images and the user's requested layout take priority over these defaults.

## Frame and spacing

- Use 1920 × 1080 design proportions, with approximately 72px outer margins (3.75% of width), scaled to the generated canvas. This is prompt guidance, not a promise of exact pixel output.
- Use a light, flat background for analytical pages, thin rules and aligned panels. Panel corners and other presentation shapes follow the company identity guidance below; use sharp or modestly rounded panels as the fallback. Reserve pills for short tags/outcomes unless the brand gives a clear reason for broader use. Avoid decorative blur, texture and drop shadows by default. Photographic layouts remain available when the selected reference calls for them.
- Keep a consistent header variant within a sequence: left accent tab and title rule, or a full-width title band. Match logo size and placement throughout; follow the selected reference rather than forcing every logo into the top-right corner.
- Default footer is a thin rule with an accent segment marking the active section. When the real deck path is known, show its section names consistently (usually 3–6). Active section is not the current slide number. For a standalone mockup, use one appropriate section and page 1. Omit navigation on covers and section dividers.
- Use existing Calibri type guidance from SKILL.md. The old system's very small body scale is not a reason to reduce readability. Regular, bold, italic and bold italic are sufficient; do not rely on unavailable Calibri weights. Font files do not force an image model to use the exact typeface.

## Brand roles and contrast

- Primary brand colour supplies most coloured structure. Supporting colour supplies limited emphasis; a third tone is optional and may be dark ink. Approximate 60/30/10 distribution is a composition guide, not a quota or a requirement to invent three brand colours.
- Use pale tints for panel surfaces and dark ink for body text. Provisional fallback: navy #0B3666, ink #101820, muted grey #595959, pale grey #F2F2F2, white #FFFFFF. Replace navy when a company palette is known.
- Check intended text/background pairs: target at least 4.5:1 contrast for ordinary text and 3:1 for large text. If white text on a bright brand colour fails, use dark text or a dark title surface; reserve the bright colour for borders and accents. Inspect the generated result as well; its colours may drift.
- Semantic green/red/amber retain their meaning when the company palette changes. Add text labels or symbols so colour is not the only signal. Brand red does not make every branded element a negative result. Risk maps need a legend; qualitative ratings need a supplied basis.

## Company identity determines shape language

Company identity affects geometry, not just colour. Preserve the reference's information architecture (columns, comparison relationships, sequence and reading order), then adapt its containers, corner radii, dividers, image crops and callouts to the company being analysed.

1. Use explicit user direction first. Otherwise inspect official brand guidelines, the current company website, annual report or investor materials for recurring geometry. Prefer explicit brand specifications; if only visual examples exist, describe the selection as inferred rather than an official rule. Retain the supporting source links with the generation prompt. Never infer a company-specific identity solely from its industry.
2. Define a compact shape brief before generation: **evidence**, **primary geometry**, **corner treatment**, **line weight**, **optional motif**, and **where it applies**. Keep one main shape family and at most one supporting motif per slide/sequence. Use the company mark as evidence, not permission to distort or redraw the logo.
3. Translate observed patterns into useful containers. Repeated soft curves may support rounded panels and circular icon frames. Strong angular or engineered geometry may support crisp rectangles, chamfers or restrained diagonal cuts. A recurring organic arch may support image masks or divider details. These are conditional design translations, not automatic rules for consumer, technology or finance companies.
4. Apply the family consistently to content panels, statistic callouts, section markers and image masks. A logo-derived curve or cut may appear as a small accent; do not turn every panel into a logo silhouette, add ornamental shapes to fill space, or force a recognizable mark into a chart.
5. Preserve semantic shapes: arrows show direction, diamonds mark actual decisions, timelines encode time, bars encode quantity and circles in a rating grid carry a defined scale. Brand styling must not change chart proportions, obscure connectors, imply false relationships or make cells harder to compare. Adapt superficial geometry before changing the analytical layout.
6. With weak or conflicting evidence, choose neutral geometry rather than inventing a brand identity. A plain company-name label is preferable to a fabricated brand mark. For user-requested variants, keep copy and data fixed so shape choices can be compared fairly.

Add this to the image-generation specification: “Company shape language: [family and corner treatment], supported by [official rule or observed source]. Apply to [specific containers/masks/dividers]. Preserve [analytical relationships and semantic diagram shapes].” Inspect the result for both company fit and legibility. Do not claim that the image model reproduced exact geometric specifications unless measured.

## Icon references

Use one coherent family, usually one icon per stage/pillar and up to four prominent icons per slide. Preserve each retained icon's original fills when using it as an insert; use compatible outline weight and flat fills for new illustrations. Icons are optional, not a reason to decorate a data table.

Retained examples, viewed and copied from the user's earlier bundle:

| Icon | File | Suitable role |
| --- | --- | --- |
| SME clients | `flat-sme-clients.png` (private local asset) | Persona, business/customer context |
| Sectoral roadmap | `flat-sectoral-roadmap.png` (private local asset) | Plan or implementation pillar |
| Diagnostic tool | `flat-diagnostic-tool.png` (private local asset) | Assessment, checklist or diagnosis |
| Review audit | `flat-review-audit.png` (private local asset) | Review, follow-up or verification |

The source readme describes these as a supplied Flaticon family. This attribution is inherited, not independently verified, and is not a licence grant or proof of redistribution rights. Use as personal visual references; check applicable rights before external redistribution. Do not describe them as original artwork or newly commissioned assets.

Open the chosen icon before passing it as an additional visual reference. Explicitly label it as an icon/style reference, separate from the slide layout reference. The generator may approximate it; do not promise exact asset preservation. No need to supply all four icons on every request.
