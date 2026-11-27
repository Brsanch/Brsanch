# Bryan Sanchez

Independent Researcher · Applied PDEs, Combinatorial Optimization, Computer-Assisted Proofs & LLM Evaluation

ORCID: [0009-0000-6080-5407](https://orcid.org/0009-0000-6080-5407)

Research in singular self-similar blowup for nonlocal fluid equations, exact algebraic and spectral bounds in combinatorics, computer-assisted proofs with interval/ball arithmetic and SAT/CP-SAT certification, and mechanistic evaluation of language model behavior.

---

### Selected Manuscripts & Publications

- **Algebraic Gram Feasibility and Spectral Branch-and-Bound for the Hadamard Maximal Determinant Problem** (*Submitted to Designs, Codes and Cryptography*, 2026)  
  Infinite-family Gram obstruction for $n = 4k + 2 \ge 10$, upper bounds below Ehlich–Wojtas for all exceptional $n \equiv 2 \pmod 4 \le 100$, the full integer-step bound $D(34) < 65 \cdot 32^{16}$, and exact algebraic closures at $n = 29$ and $n = 33$.  
  [Code & Manuscript](https://github.com/Brsanch/hadamard-maxdet)

- **Computer-Assisted Enclosures for the Critical 1D Generalized SQG Profile and Algebraic Compactification for Half-Plane Profiles** (*Submitted to SIAM Journal on Applied Dynamical Systems*, 2026)  
  60-digit interval- and FLINT/Arb ball-arithmetic computer-assisted proof of local uniqueness, support-radius enclosure $L^*(1/2) \in [14.30328480,\, 14.30329784]$, global positivity on $[0, 1)$, and leading eigenvalue enclosure for the critical $\alpha = 1/2$ 1D gSQG profile, together with algebraic compactification for half-plane profiles.  
  [Code & Manuscript](https://github.com/Brsanch/sqg-selfsimilar-cap)

- **Certified Optimality and a Spanning-Tree Core Diameter Bound for 2D HP Lattice Protein Folding** (*Submitted to Constraints*, 2026)  
  Exact spanning-tree H-core diameter bound over $\mathbb{Z}^2$ and independent multi-solver (CP-SAT, HiGHS, PicoSAT, CaDiCaL) DRAT/LRAT certification establishing unconditional optimality for canonical 2D HP benchmarks S5–S9, including $C^*(\mathrm{S6}) = 19$.  
  [Code & Manuscript](https://github.com/Brsanch/hp-folding)

- **Linear Stability, Exact Mellin Conjugation, and Nonlinear Stability of Singular Self-Similar Profiles in the Generalized Constantin–Lax–Majda Model** (*Submitted to Journal of Differential Equations*, 2026)  
  Exact Mellin stability spectra across $a < 0$, a second singular self-similar family intersecting Branch I transcritically at $a = -1$, exact two-Gamma conjugation, weighted Sobolev nonlinear stability from non-analytic data, and WENO5 dynamic-rescaling simulations.  
  [Code & Manuscript](https://github.com/Brsanch/gclm-singular-stability)

- **Stability Spectra and Nonlinear Co-Moving Bootstrap for the Singular Self-Similar Profile of the 1D Hou–Luo Model** (*Submitted to Journal of Nonlinear Science*, 2026)  
  Edge-resolved moving-frame stability spectra, exact Mellin conjugation to damped transport, and nonlinear co-moving bootstrap for the singular $(X - 1)^{-1/2}$ 1D Hou–Luo blowup profile.  
  [Code & Manuscript](https://github.com/Brsanch/singular-blowup-1d)

- **Contrastive Pretraining Teaches Format Generation, Not Behavioral Knowledge** (*Proceedings of the 1st Conference For AI Scientists, CAISc 2026*)  
  Contrastive pairs in 5% of training blocks (0.11% of tokens) break the free-generation behavioral bottleneck in small language models, outperforming 5× larger vanilla models on bias and sycophancy via format enablement rather than new factual storage.  
  [Code & Paper](https://github.com/Brsanch/contrastive-pretraining)

---

### Software Packages

| Package | Description |
|---------|-------------|
| [noethersolve](https://pypi.org/project/noethersolve/) | Verified computational calculators, conservation-law checks, and consistency-based claim verification for AI agents (MCP and CLI). |
| [rho-eval](https://pypi.org/project/rho-eval/) | Behavioral auditing and shortcut-detection toolkit for language models across 8 behavioral dimensions using offline confidence probes. |
