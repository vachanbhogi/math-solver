# Math Solver

Static linear-equation solver for demo purposes.

| Surface | URL |
|---------|-----|
| **Before** (`main`) | https://vachanbhogi.github.io/math-solver/ |
| **After** (`demo-after`) | https://vachanbhogi.github.io/math-solver/after/ |

`main` is intentionally missing dark mode and division. Those land via demo PRs (`feat/dark-mode`, `feat/division-button`) and are pre-merged on `demo-after`.

## Local

```bash
# before (main)
python3 -m http.server 8080

# after
git checkout demo-after
python3 -m http.server 8081
```

## Branches

| Branch | What |
|--------|------|
| `main` | Before — light UI, no ÷ button, `/` rejected |
| `demo-after` | After — dark mode toggle + division |
| `feat/dark-mode` | Expected eng PR branch (dark mode only) |
| `feat/division-button` | Expected eng PR branch (÷ / `/` only) |
