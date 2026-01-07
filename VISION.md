# Open Horizon: Vision & Architecture
> A summary of the principles and design from the foundational discussion.

## Core Philosophy
1.  User Sovereignty over Corporate Convenience
2.  Resilience through Isolation & Formal Verification
3.  Progress through Learned Failure (The 0.01% Rule)

## Technical Architecture: The Double Vault
1.  **Vault 1 (The Mechanism):** The verified seL4 microkernel. Enforces capabilities.
2.  **Vault 2 (The Policy):** A verified security monitor. Dictates capability rules.
3.  **The Garden:** Untrusted, isolated services + an orchestrator (AI/human) managing them.

## The Socio-Economic Model: Proof-of-Maintenance
*   Value measured in **system resilience** and **user clarity**.
*   Contribution measured in **Resilience Points** (for fixes, docs, stewardship).
*   License: GPLv3+ to enforce openness and prevent proprietary capture.

## Roadmap
See [ROADMAP.md](ROADMAP.md)
