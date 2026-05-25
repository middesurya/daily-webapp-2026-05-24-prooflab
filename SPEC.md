# ProofLab — Interactive Neural Theorem Proving & Formal Verification Laboratory

## Vision
An interactive web laboratory that lets users explore how AI proves mathematical theorems, visualize proof search trees, experiment with tactic prediction, and understand the Curry-Howard correspondence — all in the browser with zero dependencies.

## Why This Matters (May 2026)
- MIT Technology Review named mechanistic interpretability a 2026 breakthrough
- Google DeepMind's AlphaProof achieved IMO silver-medal performance in Lean4
- Lean4 is becoming the "new competitive edge" in AI safety
- Neural theorem proving combines LLMs with formal verification
- Anthropic aims to "reliably detect AI problems by 2027" using interpretability + verification

## 6 Modules

### 1. Proof Tree Explorer
Visualize how proof search works: goal states, tactic applications, branching, backtracking, and successful paths. Interactive tree with animation.

### 2. Neural Tactic Predictor
Train a tiny in-browser model (via gradient descent visualization) that learns to predict the next proof tactic given a goal state. Shows how AlphaProof-style systems work.

### 3. SAT → Proof Visualizer
Watch the DPLL/CDCL algorithm solve satisfiability problems step by step with conflict-driven clause learning. Shows how neural guidance accelerates search.

### 4. Curry-Howard Playground
Interactive demonstration of propositions-as-types: construct proofs by building programs in a simple type theory. λ-calculus meets logic.

### 5. Proof Difficulty Estimator
Predict how hard a theorem is to prove using structural features. Visualize the "proof progress" landscape that neural provers use.

### 6. Verification Arena
Race neural proof search vs. classical tactics on benchmark theorems. Compare strategies, see win rates, analyze where neural approaches excel.

## Tech Stack
- Single HTML file with inline JS/CSS
- Canvas-based proof tree rendering
- CSS Grid for module layout
- No external dependencies
- Dark theme, scientific aesthetic

## Deployment
- GitHub: middesurya/daily-webapp-2026-05-24-prooflab
- Vercel: prooflab.vercel.app
