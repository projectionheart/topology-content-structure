# Finding Content Gaps with Persistent Homology

A self-contained essay on applying topological data analysis — Vietoris–Rips
filtrations and persistent homology — to content-graph gap-finding, with a
working interactive demo (point cloud, ε slider, live β₀/β₁ via boundary-matrix
rank over GF(2), Betti curve chart). No libraries, no build step, no external
dependencies — a single `index.html`.

## Run it

Open `index.html` directly in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
