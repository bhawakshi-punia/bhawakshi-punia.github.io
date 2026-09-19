# Portfolio Revamp — Plan Mode Prompt

## Context & Current State

**Who:** Dr. Bhawakshi Punia — AI & Computational Scientist, ~1.5 years employed at Aganitha (post-PhD).

**What exists now:**
- `index.html` — Main page. Has dark/light mode toggle, nav, project cards, experience, publications, and a "Let's Connect" section. Theme uses OKLCH color vars with purple accent (`--accent`). Fonts: Lora, Plus Jakarta Sans, IBM Plex Mono.
- `why-data-analytics.html` — Narrative page about motivations and journey into data science.
- `projects/dopamine-receptor.html`, `projects/sleep-disorder-ml.html`, `projects/sweet-truth-detector.html`, `projects/yoga-youtube.html` — Four project detail pages.
- `aug_2026_CV.pdf` — Recent public CV (primary reference for content).
- `V2 Final - Aganitha_Bhawakshi_Punia_Capability_Profile (1).pdf` — Internal detailed capability profile. Use only for general context; do NOT expose internal project names, client names, or internal tooling details.
- `bhawakshi_portfolio.html` — Old standalone file, can be used as reference.

**Old portfolio (Google Sites):** https://sites.google.com/view/bhawakshi-punia/home-projects — has multiple linked pages. Content from there should be incorporated where not already present.

**LinkedIn:** https://www.linkedin.com/in/dr-bhawakshi-punia-110a81298/ — use for post-employment updates (projects, skills, roles).

---

## Goals (ordered)

### Phase 1 — Content Completion (primary goal for this session)

Ensure all pages are complete with accurate, up-to-date content. This means:

1. **`index.html`** — Verify all sections are present and updated:
   - Hero/landing with current title and tagline
   - About section (brief, professional)
   - Experience (current role at Aganitha + prior academic positions)
   - Projects section with cards linking to project detail pages
   - Publications (with Google Scholar link)
   - Skills (if retained — see pending decision below)
   - "Let's Connect" section with correct links
   - Add project images from `assets/images/main-page/` to project cards

2. **`why-data-analytics.html`** — Pending changes:
   - Resize Twitter/X post placeholders to 3-per-row layout
   - Expand "Where Am I Now" section to cover: type of work, real-world client projects, "AI for science" philosophy, continuous learning

3. **Project pages** — Verify all four are complete and consistent in layout. Check that content matches the old Google Sites versions and CV; fill any gaps.

4. **New pages** — Identify if any pages from the Google Sites are missing from the current repo and need to be created.

### Phase 2 — Design Polish (flag for later, do not implement yet)

After Phase 1 is confirmed complete:
- Layout and spacing tweaks (margins, font sizes, content density)
- Color refinements (accent palette: purple/lilac, beige, brown tones)
- Any structural improvements (section order, card design, etc.)
- This phase will be done via Claude Design / separate planning session

---

## Hard Constraints

- **Do not reveal** internal Aganitha project details, client names, or internal tooling from the capability profile PDF.
- **Confirm before implementing** any non-trivial change. Provide a plan first; wait for user approval.
- **No new pages** without explicit user confirmation.
- All pages must share the same CSS variable theme system already in `index.html` (OKLCH vars, dark default, `.light` class toggle).
- Keep the tone: **scientific, informative, concise** — aimed at industry professionals, not academics.

---

## Design Preferences (for reference throughout)

- Color palette: purple/lilac accents (already in `--accent`), warm neutrals (beige, brown) for secondary tones.
- Light and dark mode with proper contrast in both.
- Clean, minimal layout — no excessive animations, gradients, or decorative elements.
- Typography already set: Lora (serif headings), Plus Jakarta Sans (body), IBM Plex Mono (code/tags).

---

## Pending Decisions (clarify with user before acting)

- Should the Skills & Tools section be kept or removed from `index.html`? (Currently flagged for removal in `changes.md`.)
- What section order is preferred for `index.html`? Suggested: About → Featured Essay → Experience → Projects → Publications → Connect.
- Are there any additional pages from Google Sites not yet represented in the repo?

---

## Workflow Rules

- Read `changes.md` before starting — it tracks specific in-progress change requests.
- Ask/clarify before implementing anything substantial.
- Suggestions are welcome but user confirms what gets implemented.
- Prefer editing existing files over creating new ones.
- No comments in code unless the reason is non-obvious.
