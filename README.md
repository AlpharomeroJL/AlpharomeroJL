# Hi, I'm Josef 👋

**Systems architecture | Autonomous engineering research | Applied AI | Rust | Hardware and software systems**

I'm a systems architect, independent researcher, and technical founder based in Austin, Texas. I've been programming since 2014, starting with software, security experimentation, reverse engineering, networking, and electronics. I still like understanding systems all the way down to the hardware.

I spent five years working on commercial building infrastructure, from wiring high-rise installations to programming networks, integrating hardware and software, commissioning systems, and diagnosing field failures. That experience still shapes how I engineer: understand the whole system, verify the work, and account for what happens outside a development environment.

### Engineering with voice assistance

A progressive neurological condition affecting my hands made physical field work increasingly difficult, which is why I moved away from hands-on field roles. I use voice-assisted input, dictation, and conversational AI tools as part of my software development workflow. They help me keep designing, programming, and validating complex systems while adapting to changing physical capabilities.

Today my work spans autonomous software engineering, private AI infrastructure, distributed systems, and engineering tools. Some of it is open source; much of the current research and commercial implementation is private.

## What I'm focused on

### Adjoint Hypergraph Rewriting Loop (AHRL) | Independent research

AHRL is my compiler-inspired approach to autonomous software engineering. Instead of relying on models to plan, generate, and judge their own work in an open-ended loop, it represents requirements, engineering state, dependencies, and provenance explicitly. Work is coordinated through bounded rewrites, deterministic verification, and backward-chained fault localization and repair.

I wrote a **59-page research manuscript in August 2026** documenting the original architecture, mathematical foundations, and early experiments. The proprietary implementation has since developed far beyond that initial paper. The manuscript is independent research, not a peer-reviewed publication.

**My focus is the engineering around the model: state, contracts, execution, verification, and recovery. Models are replaceable. Those guarantees should not be.**

### [VaultScribe™](https://vaultscribe.app/) | The private AI command center for law firms

**Your firm's data doesn't have to live in someone else's cloud.**

VaultScribe™ is a private AI operating layer for confidential legal work, designed to run on the firm's own workstations and servers. The goal is to bring conversations, documents, matter knowledge, and legal workflows together without scattering privileged information across cloud services.

The platform is being built around bot-free meeting and deposition transcription, local AI processing, source-cited matter Q&A, document drafting, chronologies, and controlled integrations with existing practice tools. Its security architecture is designed for customer-held keys, isolated matter workspaces, logged and policy-gated outbound requests, auditable activity, and hybrid post-quantum protections for device-to-server communication. Optional external services are controlled by firm policy rather than assumed by default.

**No bot in the call. No mandatory cloud AI. Your infrastructure, your data.**

**Status:** Pre-release, in active commercial development. The implementation is private.

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
