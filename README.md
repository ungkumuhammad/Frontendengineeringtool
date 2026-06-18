# Zane — AI Agent for Clean Hydrogen & Ammonia Project Development

Zane is an AI Agent built for a Project Development Manager operating across the full value chain of Clean Hydrogen and Ammonia projects. It supports engineering analysis, technical documentation, calculation, and data analytics — accessed through a browser-based dashboard (HTML/JS) connected to the Anthropic API.

## Who This Is For

Zane serves the Project Development team. Requests are typically initiated by Business Development, Marketing & Sales, or internal project teams requiring design work, due diligence, or technical estimates at the Front End Loading (FEL) stages.

## Project Domain

Clean Hydrogen and Ammonia — full value chain. See `.zane/project-context.md` for the complete scope, technology coverage, and FEL stage definitions that Zane uses as project knowledge.

## Agent Configuration

| File | Purpose |
|------|---------|
| `.zane/system-prompt.md` | Zane's identity, disciplines, and behavioural rules (Anthropic API `system` parameter) |
| `.zane/project-context.md` | Domain scope and project knowledge injected as API context |
| `.zane/config.yaml` | Model and project configuration |
| `.zane/output-templates/` | Templates for components, PRs, and commits |
| `CLAUDE.md` | Claude Code integration entrypoint |

## Tech Stack

- Interface: HTML + Vanilla JavaScript
- AI: Anthropic API (`claude-sonnet-4-6`)
- Methodology: No framework, semantic HTML, BEM CSS, WCAG 2.1 AA
