# Open Horizon: Vision & Architecture

## Core Philosophy
1.  **Sovereignty over Convenience:** The user's control over their hardware and data is the primary design constraint, not ease of use for corporations.
2.  **Resilience through Isolation:** Security is achieved by architectural isolation (the Vault) and the principle of least privilege, not by patching monolithic code.
3.  **Progress through Learned Failure:** The 0.01% error margin is not a flaw; it is the precise frontier where true understanding and system resilience are built.

## Technical Architecture: The Double Vault
1.  **Vault 1 (The Mechanism):** A formally verified microkernel (seL4 fork). Its only job is to enforce capability-based access control. It is small enough to be mathematically proven correct.
2.  **Vault 2 (The Policy):** A verified security monitor that defines the rules for capability creation and distribution. It separates the *mechanism* of security from the *policy*.
3.  **The Garden:** The world of untrusted, single-purpose services (drivers, file systems, applications) that run in isolated user-space compartments. An orchestrator (human or AI) manages the Garden's complexity, but operates strictly within the rules granted by Vault 2.

## The Socio-Economic Model: Proof-of-Maintenance
We propose a shift in how contribution is valued:
*   **Value Metric:** System resilience, user clarity, and freedom from obsolescence.
*   **Contribution Metric (Experimental):** **Resilience Points** — awarded for maintenance, documentation, debugging, and stewardship, not just new features.
*   **Legal Enforcer:** The **GNU General Public License v3.0+** ensures the project and its derivatives remain open and cannot be privatized into a tool of control.

## The Genesis Dialogue
This project was catalyzed by a discussion exploring the possibility of an OS built from first principles of safety and sovereignty. Key insights included:
*   The concept of AI managing complexity in the "Garden" outside a proven core.
*   The "Double Vault" as a governance model for AI/human orchestration.
*   Treating legacy compatibility via sandboxed "translator servers."
*   The recognition that the largest barrier is socio-economic, not technical.

