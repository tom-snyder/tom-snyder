## Thomas Snyder

**Software developer working across application, backend, and infrastructure layers.**
Currently focused on self-hosted systems and local model serving.

<sub>Clarks Summit, PA · Member of <a href="https://github.com/Susquehanna-Syntax">Susquehanna Syntax</a></sub>

---

### What I build

**Desktop authoring tools.** Electron/React front ends over a Python domain core — 3D
editing with transform gizmos and snap-point geometry, schema validation, and packaged
export. Rendering through React Three Fiber and three.js; state in Zustand.

**Runtime systems on the JVM.** Java/Gradle mods that consume content packs produced by
those tools. The tool and the runtime are separate programs in different languages, so the
boundary between them is a versioned wire schema with its own fixtures and drift checks.

**Service-side infrastructure.** Python ASGI services, provider abstraction behind a single
API surface, SQLite-backed run history, and Linux deployment via systemd units and
image-build recipes.

### How I work

The habits matter more than any single repository:

- **Architecture Decision Records** — decisions get written down and locked, with supersession tracked
- **A domain glossary per project** — one agreed word per concept, so naming stays stable as the code grows
- **Versioned wire contracts** — cross-language boundaries are specified, fixture-tested, and drift-checked
- **Plan documents with progress ledgers** — long-horizon work tracked against explicit exit criteria
- **CI and release automation** — GitHub Actions for tests, schema checks, and packaged builds

### Current focus

**Self-hosted model serving.** A provider-agnostic broker that exposes one
Anthropic-Messages-compatible API and routes requests to hosted APIs or local CLI agents,
with preflight guardrails, run history, and a small companion UI. Target deployment is a
Raspberry Pi Zero 2 W running Pi OS Lite. *Status: working skeleton — not yet deployed.*

**GPU hardware evaluation.** Assessing RTX 3090-class hardware as the basis for a local
inference server, starting with a single-GPU build before deciding whether to expand.
*Status: evaluating — nothing purchased, benchmarked, or deployed.*

### Stack

| | |
|---|---|
| **Languages** | Python · Java · TypeScript · JavaScript · GLSL · Bash / PowerShell |
| **Application** | Electron · React · React Three Fiber · three.js · Zustand · Vite · PySide6 / Qt |
| **Backend** | ASGI / Uvicorn · httpx · JSON-RPC · SQLite · REST |
| **JVM** | Java 25 · Gradle (Groovy + Kotlin DSL) |
| **Infrastructure** | Linux · Raspberry Pi OS · systemd · image builds · GitHub Actions |
| **Testing** | pytest · Vitest · fixture + schema-drift verification |

### Contact

[Email](mailto:xtommygunzz@gmail.com)

<sub>Most of my current work lives in private repositories.</sub>
