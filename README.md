# Math Solver

Static linear-equation solver for demo purposes.

**Live (before):** https://vachanbhogi.github.io/math-solver/

Supports `+ − ×`, powers, and parentheses. Division and dark mode are intentionally missing on `main` — those land via demo PRs / the `demo-after` branch.

## Local

```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## Branches

| Branch | What |
|--------|------|
| `main` | Before — light UI, no ÷ button, `/` rejected |
| `demo-after` | After — dark mode toggle + division |
