# Study on the Collatz Conjecture Using Ananta Graph Parameters

Source code accompanying the Ph.D. thesis *"Study on the Collatz Conjecture by Using
Ananta Graph Parameters"* (Vidyashree H R, REVA University, Department of Mathematics).

This repository contains the Python implementation used to generate all computed
results, figures, and tables reported in the thesis, covering graph construction,
visualization, structural parameter computation, cryptographic applications, and
multi-agent simulation based on the Collatz sequence.

## Contents

- **Ananta-graph construction** — builds the directed graph representation of a
  Collatz trajectory (fixed triangular head + variable tail) and computes structural
  parameters (radius, diameter, center, girth, clique number, independence number,
  omega invariant, density).
- **Derived graphs** — line, middle, Mycielskian, subdivision, total, core, power,
  splitting, and kernel graph constructions from a given Ananta-graph.
- **Flower Pattern Visualization** — polar-coordinate plotting of Collatz trajectories,
  including the radial variance, petal count, and curve-dissimilarity metrics used for
  quantitative comparison across convergence classes.
- **Two's complement mapping** — extension of the Collatz sequence to negative
  integers via fixed-width binary representation.
- **Cryptographic schemes** — the Collatz-based key transformation cipher and the
  modular Ananta-graph key exchange / XOR encryption scheme.
- **Collatz Rendezvous Model (CRM)** — multi-agent synchronization simulation.
- **GUI** — Tkinter-based interface for generating and inspecting sequences and graphs
  interactively.

## Requirements

- Python [3.x]
- NetworkX [version]
- NumPy [version]
- Bokeh [version]
- Tkinter (bundled with standard Python installations)

Install dependencies:

```bash
pip install -r requirements.txt
```

## Repository structure
