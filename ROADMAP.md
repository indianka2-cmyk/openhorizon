# Roadmap: Building Understanding, Then Code

## Phase 0: Genesis (Current)
- [x] Create the Open Horizon repository and establish core philosophy.
- [x] Enable GitHub Discussions for collaborative design.
- [ ] Form initial consensus on the fork and contribution process.

## Phase 1: Collective Understanding of the Vault
**Goal:** Every contributor can build and run our trust anchor.
- [ ] **Tutorial 1:** Building the seL4 kernel and running it in QEMU.
- [ ] **Tutorial 2:** Understanding capabilities: creating a simple "Hello World" process in the seL4 environment.
- [ ] **Fork:** Create the official `seL4` fork within the Open Horizon organization with clear, reverent attribution.
- [ ] **Documentation:** Translate key seL4 concepts into the "Vault & Garden" metaphor.

## Phase 2: Blueprinting the Garden
**Goal:** Design the protocols for the world outside the Vault.
- [ ] **Specification:** Draft the "Orchestrator Testbench" — a simulated environment for managing isolated service bots.
- [ ] **Prototype 1:** The `server:ffmpeg` Sandbox. Design the capability set needed for a video decoding server.
- [ ] **Specification:** Create the "Driver Rosetta Stone" — a declarative format for describing hardware interfaces.
- [ ] **Prototype 2:** A capability-safe IPC library in Rust for writing Garden services.

## Phase 3: The First Synthesis
**Goal:** Demonstrate a complete, minimal Open Horizon "system" in simulation.
- [ ] Integrate a verified core (Vault 1), a simple policy engine (Vault 2), and a few Garden services (e.g., a console, a memory server).
- [ ] Run the "Orchestrator Testbench" on this synthetic system.
- [ ] Publish a whitepaper: "Open Horizon: From Verified Core to Managed Garden."

## Beyond: The True Horizon
- A self-hosting development environment.
- A compatibility layer for running Linux applications in a tightly confined container.
- Ports to real RISC-V and ARM hardware.
