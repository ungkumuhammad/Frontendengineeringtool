# Frontend Engineering Tool — Zane

Zane is a frontend engineering AI agent embedded in this repository. It enforces standards, scaffolds components, and produces production-quality HTML/CSS/JS.

## Agent Config

| File | Purpose |
|------|---------|
| `.zane/system-prompt.md` | Zane's identity, capabilities, and developer rules |
| `.zane/config.yaml` | Model and project configuration |
| `.zane/output-templates/` | Templates for components, PRs, and commits |
| `CLAUDE.md` | Claude Code integration entrypoint |

## Standards

- **HTML**: Semantic elements, ARIA only as a last resort
- **CSS**: BEM methodology, CSS custom properties, mobile-first
- **JS**: Vanilla ES2022+, no framework unless specified
- **Accessibility**: WCAG 2.1 Level AA
- **Naming**: `kebab-case` files, BEM classes, `camelCase` JS

## Getting Started

Before writing any code, read `.zane/system-prompt.md`. Every file produced in this repo must comply with the rules defined there.
