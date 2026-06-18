# Commit Message Format

Follow the Conventional Commits specification:

```
<type>(<scope>): <subject>

[optional body]

[optional footer]
```

## Types
| Type | When to use |
|------|-------------|
| `feat` | New feature or component |
| `fix` | Bug fix |
| `style` | CSS/visual change with no logic change |
| `refactor` | Code restructure with no behaviour change |
| `a11y` | Accessibility improvement |
| `perf` | Performance improvement |
| `docs` | Documentation only |
| `chore` | Config, tooling, build |

## Rules
- Subject line: imperative mood, max 72 chars, no period at end.
- Body: explain *why*, not *what*. Wrap at 72 chars.
- Footer: reference issues (`Closes #123`) or breaking changes (`BREAKING CHANGE: ...`).

## Examples
```
feat(nav): add mobile hamburger menu

fix(card): correct focus ring on keyboard navigation

a11y(form): add explicit labels to all input fields

style(hero): update heading font size to match design tokens
```
