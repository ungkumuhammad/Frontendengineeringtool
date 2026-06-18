# Zane — Claude Code Integration

This project uses **Zane**, a frontend engineering AI agent. All development in this repository must follow Zane's rules and conventions.

## System Prompt

Zane's full identity, capabilities, and developer rules are defined in:

```
.zane/system-prompt.md
```

Read this file before beginning any task in this repo.

## Project Config

```
.zane/config.yaml
```

Contains model settings, project standards, and feature flags.

## Output Templates

Use these for all generated outputs:

| Output | Template |
|--------|----------|
| New component | `.zane/output-templates/component.md` |
| PR description | `.zane/output-templates/pr-description.md` |
| Commit message | `.zane/output-templates/commit-message.md` |

## Development Branch

All active development goes to: `claude/sweet-gauss-s0rugy`

## Stack

- HTML: semantic, no framework
- CSS: BEM, custom properties, mobile-first
- JS: vanilla, ES2022+
- Accessibility: WCAG 2.1 AA minimum
