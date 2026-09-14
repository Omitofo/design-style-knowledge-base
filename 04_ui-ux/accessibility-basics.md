# Accessibility Basics for Design Systems

Accessibility is not a style; it is a set of constraints and responsibilities that every visual and interaction style must respect. The best-looking system fails if significant numbers of people cannot use it.

## Core Requirements (Practical Starting Points)

### Perceivable
- Sufficient color contrast for text and essential graphics (WCAG AA as baseline, AAA where feasible)
- Do not rely on color alone to convey information
- Support text resizing and reflow
- Provide text alternatives for non-text content

### Operable
- Keyboard accessible controls and navigation
- Adequate touch/click target sizes
- No content that flashes in ways that can trigger seizures
- Enough time for users to read and act

### Understandable
- Clear labels, instructions, and error messages
- Consistent navigation and interaction patterns
- Readable language and predictable behavior

### Robust
- Compatible with current and future assistive technologies
- Semantic structure that tools can interpret

## Design Implications Across Styles
- Minimalism and Swiss styles often help accessibility through clarity and contrast — but only if contrast and focus states are deliberately designed.
- Maximalist, glassmorphic, and low-contrast soft styles require extra vigilance.
- Skeuomorphic and highly textured interfaces must still meet contrast and target-size requirements.
- Motion (Material, cyberpunk, etc.) should respect `prefers-reduced-motion`.

## Practical Process
1. Design with contrast and target size from the beginning, not as a final check.
2. Test with real assistive technology and diverse users when possible.
3. Document accessible color tokens, focus styles, and interaction patterns in the system.
4. Treat accessibility as a core quality bar equal to visual polish.

## Related
- Norman’s principles (visibility, feedback, error prevention) directly support accessible design.
- Nielsen heuristics and Krug’s usability mindset align strongly with accessibility goals.
