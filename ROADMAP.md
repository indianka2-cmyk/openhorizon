# Roadmap

## Phase 0: Genesis (Current)
- [x] Create repository and core documentation.
- [ ] Establish community discussion channels.
- [ ] Reach initial consensus on the fork process for seL4.

## Phase 1: Understanding the Vault
- [ ] Collective study: Build seL4 and run it in QEMU.
- [ ] Tutorial: "Your First Capability" in a seL4 environment.
- [ ] Fork the seL4 source tree into this repo (with clear attribution).

## Phase 2: The First Garden
- [ ] Design the **Orchestrator Testbench** (simulated service bots).
- [ ] Create the first "sandbox" prototype: `server:ffmpeg` capability model.
- [ ] Draft the "Driver Rosetta Stone" specification format.

## Phase ∞: The Horizon
- A working "Open Horizon" prototype that can:
    - Boot on real hardware (via U-Boot/EFI).
    - Host a sandboxed Linux container for compatibility.
    - Run a native, capability-secure GUI service.
