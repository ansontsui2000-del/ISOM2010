# Component recipes from the earlier deck system

Source: user-supplied **Case Comp Deck System**, specifically DriverTree, Flowchart, ScoringMatrix, JourneyMap, PersonaCard and PersonaRoadmap prompts and their component implementations. Adapt these recipes to image-generation prompts. Do not execute the old SKILL.md's HTML-output instruction or copy its example statistics as research.

Use retained original deck images for the enclosing frame. These recipes extend the analytical vocabulary rather than replacing the reference library. Describe the chosen geometry, then provide exact content by region.

| Recipe | Choose when | Composition and safeguards |
| --- | --- | --- |
| Driver tree | An outcome breaks into drivers | Root left, branches right, leaf explanations aligned. Use supplied formulas and figures for an arithmetic tree; check reconciliation. Qualitative branches are permitted but must preserve their hypothesis status. Use fishbone for several operational cause categories, hub-and-spoke for related non-additive factors. Do not invent figures to satisfy the old instruction to quantify every node. |
| Swimlane | Responsibility or hand-offs matter | Actor rows, chronological stage columns, tasks inside the relevant cells, directional connectors only for supplied dependencies. A useful default is 2–4 actors and 3–4 stages; simplify or split when needed. Label delays only when supplied. Keep arrows clear of text. Use straight process cards when actor distinctions add no meaning. |
| Weighted scoring matrix | A decision has supplied options, criteria, weights and scores | Options across columns, weighted criteria down rows, stated scoring scale, totals below. Show weights summing to 100% and compute weighted totals before generation. Honour cost/risk scale direction. Highlight a winner only when supported. Include supplied exclusion reasons; if missing, flag the gap rather than fabricate them. With no rating data, use a textual comparison instead. |
| Before/after journey | The user supplied both the current experience and proposed changes | Same stage columns in two rows, current friction above and proposed experience below. Clearly label the second row as proposed. Map each intervention to the actual pain point. Emotion/confidence curves require supplied observations or an explicit illustrative label. |
| Persona walkthrough | A recommendation becomes clearer through one person's experience | Compact persona at one side; up to three pillars across the remaining space. Each pillar has a directional chevron, one icon disc, one or two benefit boxes and a short outcome. For a sequence, lock the persona appearance, position, column widths and background while revealing supplied pillars. Reuse the previous slide as a continuity reference. A final persona move is optional, only when requested or needed by the reference. |

## Persona integrity

Use a supplied persona, or an explicitly fictional illustrative persona if authorised by the request. Do not invent a real customer, interview quote, demographic statistic, trait score, testimonial, or observed outcome. A generated stylised illustration is suitable for a labelled fictional persona; use supplied/licensed photography for real people. When no image is needed, use initials.

State the **current problem**, **proposed mechanism**, and **intended outcome** separately. Keep intended outcomes conditional rather than imply that a proposal has been proven. Use the target company's palette for chevrons and framing; reserve semantic green for genuine positive-status meanings, without copying Krungsri's yellow/green as a universal brand scheme.

## Image prompt additions

- Name the recipe and describe its grid, reading order, connectors, and content limits.
- Supply exact copy per node, row, pillar, and footer. Use fixed colours by role, and Calibri throughout.
- For a sequence, repeat invariants explicitly and pass the preceding image as a continuity reference. Do not generate multiple walkthrough slides when only one slide was requested.
- Check all labels and connections after generation. Validate scoring totals independently; a plausible-looking matrix is not evidence of correct arithmetic.

## Deck-length guidance

Only apply when the user requests a sequence. Follow the user's time limit, requested slide count, and presentation requirements; use the older 5-slide and 10-slide templates as optional story patterns, not fixed counts. Prioritise summary, diagnosis, recommendation, feasibility/impact, then risks; use an appendix for supporting detail where appropriate. Do not turn a one-slide request into a deck or assume a universal slide-per-minute rate.
