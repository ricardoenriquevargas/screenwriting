# Screenplay Format Guide

Read this when writing or fixing script pages, or when the user asks about formatting.

## Page setup (US Letter, industry standard)
- Font: Courier or Courier Prime, 12 pt. One page ≈ one minute of screen time.
- Margins: left 1.5", right 1", top 1", bottom 1".
- Dialogue block: starts about 2.5" from the left edge, about 3.5" wide.
- Parentheticals: start about 3.1" from the left edge.
- Character cue: starts about 3.7" from the left edge.
- Transitions: right-aligned, ending at the right margin.
- Page numbers: top right, followed by a period ("12."). The first page is not numbered.
- A4 (common in Spain and much of Latin America) is accepted; keep the same margins and font.

## Elements

**Scene heading (slugline)** — always in caps:
`INT. GIMNASIO DE BOXEO - NOCHE` / `EXT. ROOFTOP - DAY` / `INT./EXT. COCHE - CONTINUOUS`
- INT. = interior, EXT. = exterior, INT./EXT. = moving between both.
- Time: DAY/NIGHT (DÍA/NOCHE) by default; also CONTINUOUS (CONTINUO), LATER (MÁS TARDE), MOMENTS LATER (MOMENTOS DESPUÉS), DAWN/DUSK (AMANECER/ATARDECER).
- Same location, new spot: a secondary heading like `VESTUARIO` or `RING` on its own line.

**Action** — present tense, active voice, 3–4 lines per paragraph max. White space speeds reading. Capitalize a character's name only on their first appearance, plus key sounds or props sparingly.

**Character introduction** — `CAMILA ROJAS (28), wiry, a scar through her eyebrow, wraps her hands like it's a prayer.` Age plus one vivid, playable detail. No long physical inventories.

**Character cue and dialogue** — name in caps above the dialogue. Extensions after the name:
- (V.O.) voice-over — narration or a voice from another place/time.
- (O.S.) / (O.C.) off-screen — present in the scene but not seen.
- (CONT'D) / (CONT.) — same character continues after an action line.
- (PRE-LAP) — dialogue that starts before the cut to the scene.
- In Spanish scripts: (V.O.) / (O.S.) are widely used as is; (CONT.) or (CONT'D) are both accepted.

**Parenthetical** — short, lowercase, only when the line would be misread without it: `(sarcastic)`, `(into phone)`, `(to Diego)`. Never a full action.

**Transitions** — CUT TO:, SMASH CUT TO:, MATCH CUT TO:, DISSOLVE TO:, FADE OUT. Use sparingly; modern specs mostly skip CUT TO:.

**Special sequences**
- MONTAGE / SERIES OF SHOTS — heading `MONTAGE - CAMILA TRAINS`, then short beats with dashes, end with `END MONTAGE`.
- INTERCUT — for phone calls: establish both locations, then `INTERCUT - CAMILA / DIEGO`.
- FLASHBACK — in the heading: `INT. CASA DE LA ABUELA - DÍA (FLASHBACK, 1998)`; close with `BACK TO PRESENT` or a new heading.
- Text on screen: `SUPER: "Lima, 2009"` or `ON SCREEN:`.
- Foreign language: note it in action ("In Quechua, subtitled:") and write the dialogue in the script's language, in italics if helpful.
- Lyrics: italics, only if original or public domain.

## Fountain syntax (for .fountain files)
- Title page at the top: `Title:`, `Credit: Written by`, `Author:`, `Draft date:`, `Contact:` — then a blank line.
- Scene headings: lines starting with INT, EXT, EST, INT./EXT or I/E. Force one with a leading period: `.FLASHBACK`.
- Character: a line in all caps followed by dialogue on the next line. Force with `@`: `@McGREGOR`.
- Parenthetical: a line in (parentheses) under the character.
- Dual dialogue: add `^` after the second character's name.
- Transition: all caps ending in `TO:`, or force with `>`: `> FADE OUT.`
- Centered text: `> THE END <`
- Emphasis: `*italic*`, `**bold**`, `_underline_`.
- Notes (not printed): `[[note]]`. Omitted text: `/* ... */`.
- Sections (outline, not printed): `# ACT ONE`. Synopses: `= Camila loses the fight.`
- Page break: `===`.
- Lyrics: start the line with `~`.

## Title page
Centered: TITLE in caps, "Written by" / "Escrito por", author name. Bottom left or right: email and phone. Optional: "Based on…" credit. For submissions: no draft number, no date, no "Copyright", no WGA number.
