# Bryan Sanchez — Independent Researcher

Models fail where truth is surprising. I build tools and exact verifiers that measure where language models and heuristics deviate from ground truth — and fix them.

ORCID: [0009-0000-6080-5407](https://orcid.org/0009-0000-6080-5407)

---

### Packages

| Package | What it does |
|---------|-------------|
| [noethersolve](https://pypi.org/project/noethersolve/) | 300+ verified computational calculators, conservation-law checks, and CoT-consistency fact verification (`mush_v2`) for AI agents via MCP and CLI. |
| [rho-eval](https://pypi.org/project/rho-eval/) | Behavioral auditing and shortcut-detection toolkit for LLMs (`rho-audit`, `rho-score`, `rho-gain-audit`, `rho-unlock`) across 8 behavioral dimensions using 1,826 offline confidence probes. |

### Selected Papers

- **Stability Spectra and Nonlinear Co-Moving Bootstrap for the Singular Self-Similar Profile of the 1D Hou–Luo Model** (*Submitted to Journal of Nonlinear Science, Nov 2026*)
  Edge-resolved stability spectra, exact Mellin conjugation to damped transport, and nonlinear co-moving bootstrap for the singular $(X-1)^{-1/2}$ Hou–Luo blowup profile, with 10 `0 sorry` Lean 4.29 backbone modules.
  [Code, Lean 4 & Preprint](https://github.com/Brsanch/singular-blowup-1d)

- **Stability Spectra, Exact Two-Gamma Conjugation, and Zero-Analyticity Finite-Sobolev Nonlinear Closure for the Singular Self-Similar Profiles of the Generalized CLM Model** (*Submitted / under review, Nov 2026*)
  Exact Mellin stability spectra across $a < 0$, a new Branch II singular family intersecting Branch I transcritically at $a = -1$, exact two-Gamma conjugation under Gauge (c), unconditional finite-Sobolev nonlinear closure, and Lean 4 (`0 sorry`) + Python Gates 1–4 verification.
  [Code, Lean 4 & Preprint](https://github.com/Brsanch/singular-blowup-1d)

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
| [singular-blowup-1d](https://github.com/Brsanch/singular-blowup-1d) | Stability spectra, exact Mellin/two-Gamma conjugations, zero-analyticity finite-Sobolev nonlinear closures, Lean 4 (`0 sorry`) backbones, and RFC 3161 timestamps for 1D Hou–Luo and generalized CLM singular blowup profiles. |
| [hadamard-maxdet](https://github.com/Brsanch/hadamard-maxdet) | Exact algebraic Gram feasibility (Hasse–Minkowski, integer Farkas), 15-dual Cauchy-interlaced Seidel B&B, and unconditional Hadamard maximal-determinant upper bounds ($D(34) < 65 \cdot 32^{16}$, $n=58..94$). |
| [hp-folding](https://github.com/Brsanch/hp-folding) | 2D HP-lattice protein folding via exact CP-SAT routability, with unconditional global optimality proofs on S5, S7, S8, and S9. |
| [contrastive-pretraining](https://github.com/Brsanch/contrastive-pretraining) | Code, multi-seed replications, and paper for *CAISc 2026* contrastive pretraining study. |
| [jacobian-lean-challenge](https://github.com/Brsanch/jacobian-lean-challenge) | Lean 4 + mathlib formalization strict-closing 14/24 items of Buzzard's Jacobians challenge (`Pic⁰`, genus finiteness, Cauchy–Pompeiu, residue theorem), zero `sorry`. |
| [sqg-lean-proofs-fourier](https://github.com/Brsanch/sqg-lean-proofs-fourier) | Axiom-free Lean 4 + mathlib Fourier analysis on $\mathbb{T}^2$: Littlewood–Paley, paraproducts, Kato–Ponce commutator, and Sobolev embeddings (with [sqg-lean-proofs](https://github.com/Brsanch/sqg-lean-proofs) Theorem 1 shear–vorticity identity). |
