# Hi, I'm Josef 👋

**Systems architecture | Autonomous engineering research | Applied AI | Rust | Hardware and software systems**

I'm a systems architect, independent researcher, and technical founder based in Austin, Texas. I've been programming since 2014, starting with software, security experimentation, reverse engineering, networking, and electronics. I still like understanding systems all the way down to the hardware.

Alongside software, I spent five years working on commercial building infrastructure, from pulling cable and wiring high-rise installations to network programming, integration, advanced diagnostics, commissioning, and field repairs. That experience shaped how I build: understand the whole system, verify the work, and account for what happens outside a development environment.

Today my work spans autonomous software engineering, local-first AI infrastructure, distributed systems, and engineering tools. Some of it is open source. Much of the current research and commercial implementation is private.

## What I'm focused on

### Adjoint Hypergraph Rewriting Loop (AHRL) | Independent research

AHRL is my compiler-inspired approach to autonomous software engineering. Instead of relying on models to plan, generate, and judge their own work in an open-ended loop, it represents requirements, engineering state, dependencies, and provenance explicitly. Work is coordinated through bounded rewrites, deterministic verification, and backward-chained fault localization and repair.

I wrote a **59-page research manuscript in August 2026** documenting the original architecture, mathematical foundations, and early experiments. The proprietary implementation has since developed far beyond that initial paper. The manuscript is independent research, not a peer-reviewed publication.

**My focus is the engineering around the model: state, contracts, execution, verification, and recovery. Models are replaceable. Those guarantees should not be.**

### [VaultScribe™](https://vaultscribe.app/) | Private AI infrastructure for law firms

I'm building a Rust-based, local-first AI workspace for legal professionals, designed around customer-controlled infrastructure and data boundaries.

The platform brings together on-device transcription without meeting bots, source-linked retrieval, matter-level knowledge, document workflows, and agent-assisted drafting. The architecture emphasizes isolation, auditable outbound integrations, and policy-controlled access.

**Status:** Active commercial development. The core implementation is private.

### [Reticle](https://github.com/AlpharomeroJL/reticle) | Integrated circuit layout and EDA

A Rust and WebAssembly engineering platform with native and browser targets, GPU-accelerated rendering, hierarchical IC layout, out-of-core streaming, design-rule checking, routing, extraction, and agent-assisted verification.

The [public repository](https://github.com/AlpharomeroJL/reticle) and [browser demo](https://alpharomerojl.github.io/reticle/) show part of that work. The public build is experimental and has known limitations; a more advanced implementation remains private. Reticle is still in development, currently at a lower priority than my other work.

## Public repositories

| Project | What it demonstrates |
| --- | --- |
| [Reticle](https://github.com/AlpharomeroJL/reticle) | Rust/WASM, GPU rendering, computational geometry, EDA, streaming, and verification. [Try the demo](https://alpharomerojl.github.io/reticle/). |
| [InvariantEval](https://github.com/AlpharomeroJL/invarianteval) | Deterministic safety-invariant gates and provenance checks for structured AI workflows, with local evaluation and MCP integration. |
| [Speakspec](https://github.com/AlpharomeroJL/speakspec) | Local voice-to-architecture tooling that generates specifications, agent context, decision records, and validated diagrams. |
| [Crypto-Anaylzer](https://github.com/AlpharomeroJL/Crypto-Anaylzer) | Reproducible quantitative research infrastructure with deterministic identities, lineage, and fail-closed promotion gates. An earlier project, typo and all. |

## How I approach engineering

- **Ground the work.** Requirements, constraints, and assumptions should be explicit and tied to actual system state.
- **Separate execution from judgment.** Model output is a proposal, not proof that a system works.
- **Make integration verifiable.** Define interfaces and test both sides before dependent work is merged.
- **Localize failures.** Trace defects to the decisions and dependencies that caused them, rather than blindly regenerating artifacts.
- **Preserve evidence.** Benchmarks, regression tests, reproducible experiments, and honest limitations matter more than impressive descriptions.

I've worked across product strategy, customer discovery, hands-on engineering, and business ownership. I like problems that connect physical systems, software architecture, and real operational constraints.

Earlier work also includes **Pi-box**, a self-hosted conversational agent and remote execution platform using a Raspberry Pi control plane and GPU worker nodes. I discontinued that standalone project as commercial agents gained similar remote-control capabilities.

## Connect

- [LinkedIn](https://www.linkedin.com/in/joseflong/)
- [VaultScribe™](https://vaultscribe.app/)
- [Email](mailto:josefdean@pm.me)

If you find the public engineering work useful, [GitHub sponsorship](https://github.com/sponsors/AlpharomeroJL) helps support its development, testing, documentation, and maintenance.
