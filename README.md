<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img src="assets/banner-light.svg" alt="Thomas Snyder — Software developer. AI systems, backend, and infrastructure." width="100%">
</picture>

**I'm Tom, a software developer working on AI systems, backend software, and infrastructure.**

I like well-made tools and software I can run myself. Lately that’s meant local AI, security tooling, and a Minecraft project that needed its own 3D editor.

<sub>Clarks Summit, PA · <a href="https://github.com/Susquehanna-Syntax">Susquehanna Syntax</a> · <a href="mailto:xtommygunzz@gmail.com">Say hello</a></sub>

## Selected work

### [Anvil](https://github.com/Susquehanna-Syntax/Anvil) · security tooling

A self-hosted security project for Linux servers and code repositories. Deterministic scanners find candidates; the remediation workflow is designed to use local models to propose patches for review.

<sub>In development. Model patch quality and live dynamic validation remain unmeasured.</sub>

<sub>Go · Linux · SQLite · SARIF · <a href="https://github.com/Susquehanna-Syntax/Anvil#what-it-does">Read the approach ↗</a></sub>

### [DesignRNG](https://github.com/tom-snyder/DesignRNG) · 3D authoring

The authoring side of my procedural-content projects: a desktop 3D editor for reusable parts, snap points, and content packs. Built with Electron and React Three Fiber, with a Python sidecar for validation and export.

<sub>TypeScript · Electron · React Three Fiber · Python · <a href="https://github.com/tom-snyder/DesignRNG/tree/main/docs/adr">Design decisions ↗</a></sub>

### [Arms NG](https://github.com/tom-snyder/Arms-NG) · procedural runtime

The Minecraft Forge runtime that consumes those packs and assembles weapons from authored parts. DesignRNG and Arms NG share a versioned wire contract, with fixtures and schema checks keeping the two sides aligned.

<sub>Java · Minecraft Forge · Gradle · <a href="https://github.com/tom-snyder/Arms-NG/blob/main/docs/COMPATIBILITY_CONTRACT.md">Wire contract ↗</a></sub>

## How I work

I write down the decisions that matter, test how the pieces fit together, and spend time on the interface. For AI work, I’m interested in what the model improves and what it costs to get there.

<details>
<summary><strong>Tools I use</strong></summary>

| Area | Tools |
| :--- | :--- |
| Applications | TypeScript · React · Electron · React Three Fiber · three.js |
| Backend & runtimes | Python · Java · Go · JSON-RPC · ASGI · SQLite |
| Infrastructure | Linux · systemd · GitHub Actions |
| Verification | pytest · Vitest · shared fixtures · schema checks |

</details>

## Lately

Local model serving, agent routing, and evaluation. Some of this work is still private; I’ll add it here as it becomes public.

## Off the clock

I play heavily modded Minecraft. It’s responsible for a fair amount of the code on this page.

---

[Get in touch](mailto:xtommygunzz@gmail.com) — always happy to talk tools, local AI, or something you’re building.
