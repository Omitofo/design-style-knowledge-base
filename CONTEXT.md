# CONTEXT.md — Agent Navigation for Design Style Knowledge Base

## Purpose of this workspace
This is a dense, hierarchical knowledge base of design principles, styles, color systems, typography, layout, UI/UX, and brand inspirations. Use it as Layer 3 (reference / factory) material when advising on visual design decisions.

## How to load context

### For high-level orientation
- Start with `00_principles/` (especially Rams, Norman, Swiss foundations)
- Then `styles/_overview.md` if present, or the specific style folder

### For a specific project brief
1. Identify the desired feeling / constraints (minimal, bold, trustworthy, playful, etc.)
2. Map to 1–3 styles in `styles/`
3. Cross-reference color, typography, and layout folders for supporting rules
4. Pull concrete brand lessons from `inspiration/` that match the desired outcome

### Token discipline
- Never load the entire tree.
- Prefer the most specific files that answer the current question.
- When recommending a style, always cite the dos/don'ts and the underlying principle.

## Output expectations when using this base
- Ground every recommendation in a named principle, style rule, or brand pattern from this repo.
- Distinguish between "this is the rule" vs "this is a common successful application".
- Offer alternatives and trade-offs (e.g., Swiss clarity vs. maximalist energy).
- Flag when a request conflicts with core principles (e.g., "busy" + "high legibility").
