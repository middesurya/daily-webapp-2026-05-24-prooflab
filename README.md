# ProofLab — Interactive Neural Theorem Proving & Formal Verification Laboratory

An interactive web laboratory exploring how AI proves mathematical theorems through neural proof search, tactic prediction, SAT solving, and the Curry-Howard correspondence.

## 6 Modules

1. **🌳 Proof Tree Explorer** — Visualize proof search: goals, tactics, branching, backtracking
2. **🧠 Neural Tactic Predictor** — Train a mini neural network to predict proof tactics (AlphaProof-style)
3. **⚡ SAT→Proof Visualizer** — DPLL/CDCL algorithm with conflict-driven clause learning
4. **λ Curry-Howard Playground** — Propositions-as-types: construct proofs by building λ-terms
5. **📊 Difficulty Estimator** — Predict theorem difficulty from structural features
6. **🏟️ Verification Arena** — Race neural vs classical proof search on benchmarks

## Why This Matters (May 2026)

- MIT Technology Review named mechanistic interpretability a **2026 Breakthrough Technology**
- Google DeepMind's **AlphaProof** achieved IMO silver-medal performance in Lean4
- **Lean4** is becoming the competitive edge in AI safety verification
- Neural theorem proving combines LLMs with formal verification for trustworthy AI
- Anthropic aims to "reliably detect AI problems by 2027" via interpretability + formal methods

## Tech

- Zero dependencies — single HTML file
- In-browser neural network training (vanilla JS gradient descent)
- Canvas-based proof tree and SAT graph rendering
- Dark theme, scientific aesthetic

## Live Demo

[prooflab.vercel.app](https://prooflab.vercel.app)

## License

MIT — Built with Claude Code | middesurya
