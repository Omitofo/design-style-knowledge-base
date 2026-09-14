# Type Hierarchy & Scale

## Purpose of Hierarchy
Readers scan before they read. A clear type hierarchy guides the eye to the most important information first and creates a predictable rhythm across a system.

## Building a Scale
Common approaches:
- **Modular scale** (e.g., major third 1.25, perfect fourth 1.333, golden ratio 1.618) applied to a base size.
- **Practical UI scales**: a small set of named sizes (display, h1–h3, body, small, caption) with consistent ratios.
- Optical adjustment: sizes at the extremes often need manual tracking or weight tweaks.

## Hierarchy Levers (in approximate order of strength)
1. Size
2. Weight
3. Color / contrast
4. Position and space (proximity, isolation)
5. Case, style (italic, small caps), or width
6. Decorative treatment (use sparingly)

## Practical Rules
- Limit the number of distinct sizes and weights in a single system (often 4–7 sizes and 2–3 weights is enough).
- Maintain consistent alignment (baseline grid where possible).
- Body text measure: roughly 45–75 characters for comfortable continuous reading.
- Leading: typically 1.2–1.5× the type size for body text; tighter for large display type.
- Test hierarchy by squinting or viewing at small size — the structure should still be visible.

## Common Failures
- Too many similar sizes that create ambiguity
- Relying only on color for hierarchy (fails for color-blind users and in grayscale)
- Inconsistent spacing that weakens the intended relationships
- Display type that is stylish but illegible at the required sizes

## Related
- Lupton’s practical guidance in `lupton-thinking-with-type.md`
- Swiss grid discipline for systematic alignment
- Style-specific type notes in each style folder
