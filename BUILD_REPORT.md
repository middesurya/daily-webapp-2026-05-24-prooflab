# Build Report: ProofLab

## Date: 2026-05-24

## What Was Built
ProofLab — Interactive Neural Theorem Proving & Formal Verification Laboratory
- 6 interactive modules covering the full spectrum of automated theorem proving
- Zero-dependency single HTML file (61KB)
- In-browser neural network training for tactic prediction
- Canvas-based proof tree and SAT graph visualization

## Idea Source
- MIT Technology Review 2026 Breakthrough Technologies (Mechanistic Interpretability)
- Google DeepMind AlphaProof (Lean4 IMO silver medal)
- Bay Area AI Safety research (Anthropic, DeepMind formal verification)
- LeanDojo/Lean Copilot ecosystem explosion

## Tech Decisions
- Single HTML file for zero-dependency deployment
- Vanilla JS neural network (8→16→6, ReLU+Softmax, SGD)
- Canvas rendering for proof trees and SAT implication graphs
- CSS Grid + dark scientific theme
- No build step needed

## Deployment
- GitHub: https://github.com/middesurya/daily-webapp-2026-05-24-prooflab
- Vercel: https://prooflab-omega.vercel.app

## Lessons
1. Canvas-based tree rendering works well for proof trees (recursive structure)
2. Simplified DPLL/CDCL is educational even without full implementation
3. Curry-Howard playground needs careful type parsing for interactive use
4. Neural tactic predictor demonstrates the core concept with minimal architecture

## Not Duplicated From Existing Repos
Checked all 70+ repos — no existing project covers theorem proving, formal verification,
SAT solving, or the Curry-Howard correspondence. Closest was neurosym-lab (neuro-symbolic AI)
but that focuses on visual reasoning, not formal proofs.
