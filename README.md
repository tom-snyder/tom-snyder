<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img src="assets/banner-light.svg" alt="Thomas Snyder — Useful software. Fewer plot twists." width="100%">
</picture>

**I'm Tom — a software developer working across AI systems, backend engineering, and infrastructure.**

I build tools that connect the pieces: applications, runtimes, models, and the contracts between them. I like my interfaces clear, my systems self-hosted, and my breaking changes announced in advance.

<sub>Clarks Summit, PA · <a href="https://github.com/Susquehanna-Syntax">Susquehanna Syntax</a> · <a href="mailto:xtommygunzz@gmail.com">Say hello</a></sub>

## Selected work

### [Anvil](https://github.com/Susquehanna-Syntax/Anvil) · security tooling

An open-source, self-hostable project for finding vulnerabilities in Linux servers and code repositories and proposing fixes. Deterministic checks handle detection; local models are intended for remediation.

**In development:** scanning and remediation workflows are implemented; model patch quality and live dynamic validation remain unmeasured. A proposed fix and a verified fix get different labels. Confidence is not a test suite.

<sub>Go · Linux · SQLite · SARIF · <a href="https://github.com/Susquehanna-Syntax/Anvil#what-it-does">Read the approach ↗</a></sub>

### [DesignRNG](https://github.com/tom-snyder/DesignRNG) · 3D authoring

A desktop editor for building reusable 3D parts and exporting procedurally generated content packs. Electron and React Three Fiber handle the editor; a Python sidecar handles validation and export.

The editor and runtime live in separate repositories. Shared fixtures, schema checks, and recorded design decisions keep their agreement explicit as both evolve.

<sub>TypeScript · Electron · React Three Fiber · Python · <a href="https://github.com/tom-snyder/DesignRNG/tree/main/docs/adr">Design decisions ↗</a></sub>

### [Arms NG](https://github.com/tom-snyder/Arms-NG) · procedural runtime

A Minecraft Forge mod that assembles weapons from authored content packs. Separate Java codebase, shared wire contract, and schema checks in CI.

**The loot is random. The contract isn't.**

<sub>Java · Minecraft Forge · Gradle · <a href="https://github.com/tom-snyder/Arms-NG/blob/main/docs/COMPATIBILITY_CONTRACT.md">Wire contract ↗</a></sub>

<sub>More projects will join this page as they become public.</sub>

## How I work

- **Make the boundaries explicit.** Versioned schemas, shared fixtures, and compatibility checks.
- **Leave a paper trail.** ADRs, glossaries, and useful handoffs. “It made sense at the time” is not a maintenance plan.
- **Make AI earn its place.** Measure the result before adding another model to the diagram.
- **Care about the interface.** Using the tool should be easier than reading its architecture notes.

<details>
<summary><strong>The toolbox</strong></summary>

| Area | Tools |
| :--- | :--- |
| Applications | TypeScript · React · Electron · React Three Fiber · three.js |
| Backend & runtimes | Python · Java · Go · JSON-RPC · ASGI · SQLite |
| Infrastructure | Linux · systemd · GitHub Actions |
| Verification | pytest · Vitest · shared fixtures · schema checks |

</details>

## On the workbench

Self-hosted infrastructure, local model serving, and experiments in agent routing and evaluation. I like ambitious ideas with results you can actually inspect.

## Away from the workbench

Usually somewhere in a heavily modded Minecraft instance: dependency management with better scenery. Building the mod *and* its authoring tool is apparently how I relax.

---

Have a useful problem or a good side quest? **[Let's talk.](mailto:xtommygunzz@gmail.com)**
