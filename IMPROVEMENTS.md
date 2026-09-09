# Improvements — September 9, 2026

Unofficial CP-1 study companion revisions (no ACI/ASTM verbatim text).

## Content depth
- Expanded **C231**, **C173**, and **C31** modules toward C172/C143 depth: JTA angles, equipment limits, invalid-test instincts, aggregate correction (high level), layering/consolidation, curing temperature-band study notes, and edge cases.
- Added interactive **Field workflow checklist** (sampling → temperature → slump → air/density → cylinders → initial cure) with localStorage persistence.
- Softened timing language site-wide to consistent “commonly cited ~X — verify in current ASTM …” phrasing on the numbers sheet and key callouts.

## Quizzes
- Grew the original question bank substantially (timing, invalid-test, equipment, curing, sampling emphasis).
- Kept **overall mix** quiz (now 25 questions drawn from an expanded cross-method pool) + timed mode.
- Added **per-method quiz buttons** in Quiz mode (each ASTM method bank); inline self-checks still mount under each method module.

## Diagrams (original SVGs)
- Thermometer immersion / cover (C1064)
- Equal-volume vs equal-height slump layers (C143)
- Type B meter basics with petcocks/gauge/bowl (C231)
- Volumetric neck / foam sketch (C173)
- C31 cylinder layer counts (6×12 vs 4×8) with rod callouts
- Field workflow sequence diagram (checklist section)
- Existing sampling / density / flow diagrams retained or lightly refined

## UI / interactivity
- Prominent progress **percentage** in sidebar and header; labeled per-section progress list (what each reviewed section is).
- Progress tracks 11 sections (overview, program, timing, workflow, seven methods).
- **Study mode** clarified in UI (focus reading: opens step summaries, de-emphasizes quiz chrome, larger type); state persists; consistent enter/exit labeling.
- Mobile sidebar: wider drawer, touch scrolling, body scroll lock while open, tighter small-phone header.
- Print CSS: hide nav/search/quiz controls/progress chrome; keep content; avoid bad page breaks where practical.
- Quick-search / jump-to hits in the sidebar; jump-grid on the numbers sheet.
- Footer **Last updated: September 9, 2026**.

## Files
- `index.html` — canonical working copy
- `ACI-CP-1-Field-Testing-Study-Guide.html` — identical copy
- `README.md` — last-updated note
- `IMPROVEMENTS.md` — this note

## Validation
- `node --check` on extracted script: pass
- Identical SHA-256 for both HTML copies after sync
