# css

Shared CSS design system. Plain CSS, `fb-` namespace, tokens as custom properties.

```html
<link rel="stylesheet" href="https://forbaska.github.io/css/v1/fb.css">
```

- Live examples: https://forbaska.github.io/css/
- For LLMs: https://forbaska.github.io/css/llms.txt (index) and https://forbaska.github.io/css/llms-full.txt (full reference)

## Using it in an app's CLAUDE.md / AGENTS.md

```
UI: use the shared stylesheet https://forbaska.github.io/css/v1/fb.css.
Before writing any UI, read https://forbaska.github.io/css/llms-full.txt and follow it.
Use fb- classes and var(--fb-*) tokens only. No Tailwind, no other CSS frameworks.
```

## Versioning

Small fixes go in `v1/`. Breaking changes go in a new folder (`v2/`) so existing apps keep working.
