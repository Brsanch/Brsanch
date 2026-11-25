# Bryan Sanchez — Independent Researcher

Models fail where truth is surprising. I build tools and exact verifiers that measure where language models and heuristics deviate from ground truth — and fix them.

---

### Packages

| Package | What it does |
|---------|-------------|
| [noethersolve](https://pypi.org/project/noethersolve/) | 300+ verified computational calculators, conservation-law checks, and CoT-consistency fact verification (`mush_v2`) for AI agents via MCP and CLI. |
| [rho-eval](https://pypi.org/project/rho-eval/) | Behavioral auditing and shortcut-detection toolkit for LLMs (`rho-audit`, `rho-score`, `rho-gain-audit`, `rho-unlock`) across 8 behavioral dimensions using 1,826 offline confidence probes. |

### Selected Papers

- **Contrastive Pretraining Teaches Format Generation, Not Behavioral Knowledge** (*CAISc 2026*)
  Contrastive pairs in 5% of training blocks (0.11% of tokens) break the free-generation bottleneck in small language models, beating 5× larger vanilla models on bias and sycophancy via format enablement rather than new factual storage.
  [Code & Paper](https://github.com/Brsanch/contrastive-pretraining)

- **Confidence Cartography: Teacher-Forced Token Probability as a False-Belief Sensor** (2026)
  Teacher-forced token confidence ratios correlate with human false-belief prevalence ($\rho = 0.652, p = 0.016$) across Pythia 160M–12B and generalize out-of-distribution to medical myths (88%).
  [Paper (Zenodo)](https://doi.org/10.5281/zenodo.18703506)

- **Rho-Guided Supervised Fine-Tuning & Grassmann Geometry of Behavioral Entanglement** (2026)
  Post-training repair of calibration damage and subspace-geometry analysis across Qwen, Llama, and Mistral model families.
  [Rho-Guided SFT](https://doi.org/10.5281/zenodo.18854943) · [Grassmann Geometry](https://doi.org/10.5281/zenodo.18865861)

### Public Repositories

| Repo | What it does |
|------|-------------|
| [contrastive-pretraining](https://github.com/Brsanch/contrastive-pretraining) | Code, multi-seed replications, and paper for *CAISc 2026* contrastive pretraining study. |
| [hp-folding](https://github.com/Brsanch/hp-folding) | 2D HP-lattice protein folding via exact CP-SAT routability, with unconditional global optimality proofs on S5, S7, S8, and S9. |
| [hadamard-maxdet](https://github.com/Brsanch/hadamard-maxdet) | Exact algebraic Gram feasibility (Hasse–Minkowski, integer Farkas), 15-dual Cauchy-interlaced Seidel B&B, and unconditional Hadamard maximal-determinant upper bounds. |
| [jacobian-lean-challenge](https://github.com/Brsanch/jacobian-lean-challenge) | Lean 4 + mathlib formalization strict-closing 14/24 items of Buzzard's Jacobians challenge (`Pic⁰`, genus finiteness, Cauchy–Pompeiu, residue theorem), zero `sorry`. |
| [sqg-lean-proofs-fourier](https://github.com/Brsanch/sqg-lean-proofs-fourier) | Axiom-free Lean 4 + mathlib Fourier analysis on $\mathbb{T}^2$: Littlewood–Paley, paraproducts, Kato–Ponce commutator, and Sobolev embeddings (with [sqg-lean-proofs](https://github.com/Brsanch/sqg-lean-proofs) Theorem 1 shear–vorticity identity). |
