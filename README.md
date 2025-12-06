# Qelva Privacy Tests  
### Simulations & Analysis for the Qelva Privacy Stack

This repository contains **experiments, simulations, and analysis** focused on the privacy properties of Qelva:

- How well Split & Delay breaks naive chain heuristics
- How relayer behaviour affects linkability
- How personas help separate activity patterns
- Where metadata can still leak and how bad it is

This is **not** the main implementation repo.  
Core code lives in [`QelvaLabs/Qelva-core`](https://github.com/QelvaLabs/Qelva-core).

---

## 🎯 Goals

- Make our privacy assumptions **explicit**, not hand-wavy.
- Provide concrete **examples and scenarios** that can be reproduced.
- Show where Qelva helps — and where it doesn’t.
- Give researchers and devs a place to plug in their own heuristics.

---

## 📁 Structure (planned)

```txt
qelva-privacy-tests/
├─ scenarios/           → Human-readable scenarios & write-ups
├─ tools/               → Small scripts for graph / timing analysis
├─ notebooks/           → Jupyter / analysis notebooks (optional)
└─ docs/                → Methodology and explanations
