# Metric-Spaces
Interactive visual introduction to metric spaces — covering axioms, metrics (Euclidean, Manhattan, Chebyshev, discrete), open/closed sets, ε-δ continuity, sequence convergence, completeness, and the Banach Fixed Point Theorem.
# Metric Spaces

An interactive, single-file website that teaches metric spaces from scratch using live canvas visualisations. No frameworks, no build step — just open `index.html` in a browser.

## Live Demo

Open `index.html` directly, or host it on GitHub Pages via **Settings → Pages → Deploy from branch**.

## What's Covered

| Section | Topics |
|---|---|
| §01 The Axioms | Non-negativity, symmetry, triangle inequality — with a draggable interactive proof |
| §02 Examples | Euclidean, Manhattan, Chebyshev, and discrete metrics; animated unit balls |
| §03 Topology | Open and closed sets, boundary breathing-room demo, ε-δ continuity visualiser |
| §04 Sequences | Convergence, spiral/zig-zag/divergent animations, Cauchy sequences |
| §05 Completeness | ℝ vs ℚ hole demo, Banach Fixed Point Theorem cobweb diagram |

## Usage

```bash
git clone https://github.com/your-username/metric-spaces.git
cd metric-spaces
open index.html   # macOS
# or just drag the file into any browser
```

No dependencies. No npm install. No server needed.

## File Structure

```
metric-spaces/
└── index.html      # Everything — HTML, CSS, and canvas JS in one file
└── README.md
```

## Contributing

Found a bug or want to add a new section (compactness? connectedness? normed spaces)? PRs are welcome. Each visualisation is a self-contained IIFE in the `<script>` block — easy to extend.

## Further Reading

- Rudin, *Principles of Mathematical Analysis* (Baby Rudin) — the classic
- Munkres, *Topology* — for the broader topological picture
- Sutherland, *Introduction to Metric and Topological Spaces* — gentler entry point

