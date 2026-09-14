# Design Style Knowledge Base

**ICM-style dense knowledge tree for design, style, color, UI/UX, branding, and visual systems.**

This repository is structured as an Interpretable Context Methodology (ICM) workspace. Use it as a reference source for LLMs when designing projects: point the agent at specific folders or files to load only the relevant context layers.

## Purpose

- Macro nodes for quick orientation (principles, major style families)
- Deep trees for rules, dos/don'ts, particularities, historical context
- Brand inspirations broken down for practical application
- Sourced from the highest-acclaimed practitioners and books in design history

## How to Use with an LLM

1. Give the agent this repo (or specific paths) as Layer 3 reference material.
2. Ask for recommendations grounded in these files.
3. For a new project: start at `00_principles/`, then drill into the matching style in `styles/`, then pull relevant brand lessons from `inspiration/`.

## Top-Level Structure

```
design-style-knowledge-base/
├── README.md                          # This file
├── CONTEXT.md                         # Agent routing / how to navigate
├── 00_principles/                     # Macro principles (Rams, Norman, Swiss, etc.)
├── 01_color/                          # Color theory, systems, psychology, palettes
├── 02_typography/                     # Type principles, classification, rules
├── 03_layout-composition/             # Grids, hierarchy, white space, Gestalt
├── 04_ui-ux/                          # Interaction, affordances, usability heuristics
├── styles/                            # Major visual styles & movements (dense)
│   ├── minimalism/
│   ├── swiss-international/
│   ├── brutalism-neubrutalism/
│   ├── maximalism/
│   ├── bauhaus/
│   ├── art-deco/
│   ├── mid-century-modern/
│   ├── skeuomorphism-glassmorphism/
│   └── ... (more to expand)
├── inspiration/                       # Brand breakdowns (Nike, Apple, Amazon...)
├── sources/                           # Canonical books & authors
└── _config/                           # Conventions for using this knowledge base
```

## Guiding Philosophy

Drawn from the best: Dieter Rams ("Less, but better"), Josef Müller-Brockmann (grids & clarity), Don Norman (affordances & human-centered design), Edward Tufte (data integrity & clarity), Ellen Lupton (thinking with type), and the broader Swiss/International tradition.

Every style entry aims to answer:
- What is it (definition + historical context)?
- Core visual rules & particularities
- Dos and Don'ts
- When to use / when to avoid
- How to achieve it (practical levers)
- Connections to other styles and principles

## License

MIT — free to use, adapt, and extend for your own projects.
