# Open Horizon

**Security is architecture, not patches.**

Open Horizon is a research & development project to build a sovereign, resilient operating system on a foundation of formal verification.

## The Architecture: The Vault and The Garden

1.  **The Vault:** A fork of the [seL4 microkernel](https://sel4.systems/), a formally verified, capability-secure kernel. It is our trust anchor—mathematically proven to enforce security policies correctly.
2.  **The Garden:** A user-sovereign ecosystem of isolated services (drivers, applications, managers) running on top of the vault, communicating via secure capabilities. Complexity is managed, not trusted.

## Why?
Modern operating systems are monuments to accidental complexity and perpetual patching. We start with a proven base and ask: *What kind of system can we build when the foundation is no longer the weakest link?*

## Get Started (Phase 1: Understanding the Vault)
We are currently in **Phase 1**. The first goal is to build and understand our trust anchor.
*   [Read our Vision and Architecture](VISION.md)
*   [Explore the seL4 documentation](https://docs.sel4.systems/)
*   [Build seL4 in QEMU](https://docs.sel4.systems/projects/sel4-tutorials/)

## Join the Rebuild
This is a collaborative, open-source rethink. We value **resilience, clarity, and sovereignty**.
*   **Discuss:** Start a [Discussion](https://github.com/yourusername/openhorizon/discussions) on a topic from our [VISION.md](VISION.md).
*   **Contribute:** See our [Contributing Guide](CONTRIBUTING.md).
*   **Follow:** Watch this repo for updates.

"The horizon is open. The first step is understanding the ground beneath us."
