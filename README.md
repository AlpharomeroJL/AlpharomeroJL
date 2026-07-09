# Hi, I'm Josef 👋

I'm a software engineer in Austin, Texas. My discipline is **agentic engineering**: designing the loops, verification systems, and execution plans that let AI coding agents build serious software without the quality collapsing. The agents are swappable. The engineering is the part that holds.

Right now most of that energy goes into **[Reticle](https://github.com/AlpharomeroJL/reticle)**: a modern semiconductor CAD platform in Rust, GPU-accelerated, running in your browser. Chip design tooling is expensive, ancient, and locked down, and I think the layout editor of the next decade should be open, fast, and a URL away. So I'm building it.

Everything here is dated and tied to commits you can click. I'd rather show you the build log than tell you about it.

---

## 🚩 What I'm building

| Project | What it is | Status |
| ------- | ---------- | ------ |
| **[Reticle](https://github.com/AlpharomeroJL/reticle)** | Browser-native, GPU-accelerated IC layout platform in Rust/WASM. Layout, geometry, DRC, verification, and AI-assisted workflows, designed as a modular platform rather than a single editor. Built in multi-wave autonomous campaigns with benchmark regression gates between waves. [Live demo](https://alpharomerojl.github.io/reticle/). | v8 in active development |
| **[VaultScribe](https://vaultscribe.app)** | Fully offline meeting transcription for desktop (Tauri + local Whisper). Your audio never leaves your machine. | Release candidate |
| **[InvariantEval](https://github.com/AlpharomeroJL/invarianteval)** | Safety-invariant eval gates for agentic pipelines. The verification layer from my own loops, pulled out and published, because the guarantees have to hold no matter which model is executing. | v1, public |
| **[Speakspec](https://github.com/AlpharomeroJL/speakspec)** | Talk through a system design out loud, get a structured architecture spec back. Built because scoping is most of my job and I wanted it faster. | v1.0.0, public |
| **[Crypto-Anaylzer](https://github.com/AlpharomeroJL/Crypto-Anaylzer)** | My earliest public repo. Yes, the typo is permanent. It's a timestamp at this point. | Archive |

---

## 🔁 Agentic engineering, the way I practice it

The interesting problem in AI-assisted development isn't prompting. It's everything around the model: how work gets scoped, dispatched, verified, and merged so that one person can run what amounts to a build organization. I've run these loops on Claude Code, on my own Python orchestrator driving local models on my own hardware, and the method transfers because it was never about the harness.

What a campaign actually looks like before a single line of code is written:

- **Grounding.** Every premise in the plan is checked against the repo at a specific commit. Anything that can't be verified yet becomes an explicit placeholder that blocks execution until it's resolved. Plans don't run on assumptions.
- **Contracts.** Cross-lane interfaces are frozen up front as schemas with byte-level fixtures and cross-tests on both sides, so a dozen parallel work lanes can't drift against each other.
- **Gates.** Tests, benchmarks, and invariant checks run between every wave. If the numbers regress, the wave doesn't land. Baselines only move at gates.
- **Honest accounting.** Model tiers are assigned per task and calibrated against measured results. Quota throttling drains into a standing queue of unattended work instead of stalling the campaign. Every claim in the docs has to trace to a committed record.

My CI fails the build if the README contains marketing adjectives. "Blazing," "seamless," and "world-class" are literally banned strings. The execution plan for a single Reticle release runs longer than most projects' entire documentation, and I think that ratio is roughly correct.

If you're curious how far one careful person can push this, that's the whole experiment. You're watching it.

---

## ❤️ Sponsor this work

I'm building Reticle and everything above independently, without a company behind it. Sponsorship is what turns this from nights-and-weekends pace into sustained, full-time open-source engineering.

Concretely, sponsorship buys: new Reticle capabilities, performance work, documentation, testing and benchmarking infrastructure, and long-term maintenance. It also buys the thing I most want to publish more of: the campaign plans, loop designs, and verification tooling themselves, so other builders can run this method too.

[![Sponsor AlpharomeroJL](https://img.shields.io/badge/Sponsor-AlpharomeroJL-ea4aaa?logo=githubsponsors&logoColor=white)](https://github.com/sponsors/AlpharomeroJL)

Even small monthly sponsorships genuinely matter for a solo builder. Thank you.

---

📫 josefdean@pm.me · Austin, TX
