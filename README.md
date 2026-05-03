<div align="center">

# 🌐 Zensical Projects

### **A Portfolio of AI-Powered Documentation & Specialized Tools**

*A growing archive of my Zensical documentation sites.*

[![Zensical](https://img.shields.io/badge/Built_with-Zensical-FF6B6B?style=flat-square&logo=markdown&logoColor=white)](https://zensical.org)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

---

**A collection of my Zensical documentation sites.**

This repository archives the documentation for various projects I've built using [Zensical](https://zensical.org) — each with its own specialized domain and focus.

</div>

---

## Deployed Documentation Sites

| Project | Documentation |
|---------|---|
| **InteFL** | [ajbarea.github.io/phalanx-fl](https://ajbarea.github.io/phalanx-fl/) |
| **VelocityFL** | [ajbarea.github.io/vFL](https://ajbarea.github.io/vFL/) |
| **Kourai Khryseai** | [ajbarea.github.io/kourai-khryseai](https://ajbarea.github.io/kourai-khryseai/) |
| **Orchestrate Triage** | [ajbarea.github.io/orchestrate-triage](https://ajbarea.github.io/orchestrate-triage/) |
| **Cosmic Horror** | [victor-lockwood.github.io/Hackathon-2026-Cosmic-Horror](https://victor-lockwood.github.io/Hackathon-2026-Cosmic-Horror/) |

---

## Documentation Archive

### InteFL

**Federated learning execution and research framework**

- 🚀 [Get Started](intefl/docs/getting-started.md) — Install with Docker or locally
- 🏗️ [Architecture](intefl/docs/architecture.md) — API, Celery, Flower, React UI
- ⚙️ [Configuration](intefl/docs/configuration.md) — StrategyConfig field reference
- 📊 [Datasets](intefl/docs/datasets.md) — FEMNIST, FLAIR, MedMNIST, HuggingFace text
- 🛡️ [Strategies](intefl/docs/strategies.md) — FedAvg, Krum, Bulyan, PID, Trust, RFA, ArKrum
- ⚡ [Attacks](intefl/docs/attacks.md) — Label flipping, backdoors, poisoning, Byzantine
- 📡 [API Reference](intefl/docs/api.md) — REST endpoints for simulations

**Tech Stack:** Flower (FL orchestration) · Ray (compute) · PyTorch · FastAPI · Celery · React · Zensical

---

### VelocityFL

**Rust-backed federated learning core with Python ergonomics — "the uv of FL"**

- 🚀 [Get Started](vfl/docs/getting-started.md) — Install and run your first simulation
- 🧭 [CLI Reference](vfl/docs/cli.md) — Command overview and examples
- 🏗️ [Architecture](vfl/docs/architecture.md) — Rust core, PyO3 bridge, and execution flow
- ⚙️ [Configuration](vfl/docs/configuration.md) — Runtime settings and defaults
- 🛡️ [Strategies](vfl/docs/strategies.md) — Aggregation strategies (FedAvg, FedProx, Krum, MultiKrum, Bulyan, GeometricMedian)
- ⚡ [Attacks](vfl/docs/attacks.md) — Adversarial scenario modeling
- 📡 [API Reference](vfl/docs/api.md) — Programmatic interface details
- 📊 [Convergence](vfl/docs/convergence.md) — Stability and convergence notes
- 🏁 [Benchmarks](vfl/docs/benchmarks.md) — Performance and scaling observations
- 🧠 [Skills](vfl/docs/skills.md) — Project skill documentation

**Tech Stack:** Rust · PyO3 · Python · HuggingFace · PEFT · PyTorch · Zensical

---

### Kourai Khryseai

**Six AI specialists collaborating through the A2A protocol**

- 🚀 [Get Started](kourai-khryseai/docs/getting-started.md) — Prerequisites, setup, Docker
- 💡 [How It Works](kourai-khryseai/docs/overview.md) — The A2A protocol and agent architecture
- ⚙️ [Configuration](kourai-khryseai/docs/configuration.md) — Environment variables and settings
- 🔧 [CLI Guide](kourai-khryseai/docs/cli.md) — Command usage and pipelines
- 🏗️ [Architecture](kourai-khryseai/docs/architecture/index.md) — System design and layers
- 🧠 [Agents](kourai-khryseai/docs/agents/index.md) — Hephaestus, Metis, Techne, Dokimasia, Kallos, Mneme

**The Agents:**

| Emoji | Agent | Role | Port |
|-------|-------|------|------|
| 🔥 | **Hephaestus** | Orchestrator — routes requests through the pipeline | :10000 |
| 📐 | **Metis** | Planner — converts ideas to detailed implementation specs | :10001 |
| ⚙️ | **Techne** | Coder — implements code from specs, edits files intelligently | :10002 |
| 🧪 | **Dokimasia** | Tester — writes pytest suites targeting 80%+ coverage | :10003 |
| ✨ | **Kallos** | Stylist — runs ruff, enforces style guides, cleans code | :10004 |
| 📜 | **Mneme** | Scribe — generates conventional commit messages from diffs | :10005 |

**Tech Stack:** A2A Protocol · LiteLLM · FastAPI · MCP · OpenTelemetry · Docker · uv · Python 3.12+

---

### Orchestrate Triage

**Multi-domain support-triage AI agent for the HackerRank Orchestrate hackathon (May 2026)**

- 🚀 [Get Started](orchestrate-triage/docs/getting-started.md) — Install with `uv`, configure `ANTHROPIC_API_KEY`, run on the sample tickets
- 💡 [Overview](orchestrate-triage/docs/overview.md) — Problem framing, why corpus-stuffing not RAG, what's deliberately cut
- 🏗️ [Architecture](orchestrate-triage/docs/architecture/index.md) — System diagram, file map, design pillars
- 📚 [Corpus & Caching](orchestrate-triage/docs/architecture/corpus.md) — Per-domain stuffing math, stripping, 1h-TTL economics
- 🛡️ [Prompt-Injection Defense](orchestrate-triage/docs/architecture/safety.md) — Spotlighting, structural sanitization, observed real-case behavior
- 💰 [Cost & Determinism](orchestrate-triage/docs/architecture/cost.md) — Model-tier strategy, Batch API economics, determinism without temperature
- 📡 [Reference](orchestrate-triage/docs/reference.md) — Module-by-module API

**The Ecosystems Triaged:**

| Ecosystem | Tokens (after stripping) | Test tickets |
|-----------|--------------------------|--------------|
| 🟢 **HackerRank Support** | ~580K | 14 |
| 🟧 **Claude Help Center** | ~540K | 7 |
| 🟦 **Visa Support** | ~18K | 6 |
| ⚫ None / cross-domain | — | 2 |

**Tech Stack:** Claude Opus 4.7 (1M context) · Anthropic Message Batches API (50% off) · prompt caching (1h extended-TTL beta) · pydantic strict-mode tool use · spotlighting for prompt-injection defense · uv · pytest · ruff · Zensical

---

### Cosmic Horror

**Biological electrical pulses transformed into haunting melodies**

- 🚀 [Wake the Ancient](hackathon-2026-cosmic-horror/docs/getting-started.md) — Setup and hardware
- 🏗️ [Architecture](hackathon-2026-cosmic-horror/docs/architecture.md) — Signal pipeline, gesture classification, synthesis
- 🎹 [MIDI Engine](hackathon-2026-cosmic-horror/docs/midi-engine.md) — FluidSynth, instruments, voice switching
- 🎵 [Playlist](hackathon-2026-cosmic-horror/docs/playlist.md) — The six cursed melodies

**Capabilities:**

| Feature | Details |
|---------|---------|
| **Gestures** | 8 physical incantations (fist, palm, arm, peace) classified from raw muscle static in real time |
| **Voices** | 6 spectral instruments (piano, nylon guitar, steel guitar, electric guitar, strings, pad) |
| **Melodies** | Save Your Tears, Blinding Lights, Careless Whisper, Love Story, Firework, Secrets |
| **Engine** | Direct neural synthesis via FluidSynth — no DAW, no external host |

**Tech Stack:** BioRadio · RandomForest (gesture classification) · FluidSynth · MIDI · Python · RIT BioRadio Hackathon 2026

---

## Repository Structure

```
zensical-projects/
├── intefl/
│   ├── docs/                    # Zensical documentation site
│   ├── src/                     # Flask API, Celery workers, React UI
│   └── tests/                   # Unit & integration tests
├── vfl/
│   ├── docs/                    # Zensical documentation site
│   ├── overrides/               # Material theme overrides (OG card)
│   └── zensical.toml            # Site config (palette, nav, plugins)
├── kourai-khryseai/
│   ├── docs/                    # Zensical documentation site
│   ├── agents/                  # Six specialist agents
│   ├── shared/                  # Common config, LLM, tracing
│   ├── mcp_servers/             # Tool servers (fs, git, shell)
│   └── tests/                   # Unit & integration tests
├── orchestrate-triage/
│   ├── docs/                    # Zensical documentation site
│   ├── overrides/               # Material theme overrides (OG card)
│   └── zensical.toml            # Site config (palette, nav, plugins)
├── hackathon-2026-cosmic-horror/
│   ├── docs/                    # Zensical documentation site
│   ├── src/                     # Signal processing, gesture classification, MIDI engine
│   └── data/                    # Playlists and gesture models
└── README.md
```

---

## About Zensical

Each project's documentation is built with **[Zensical](https://zensical.org)** — a modern documentation generator that produces beautiful, MkDocs-compatible sites with:

- ✨ Material Design styling and interactive components
- 🎨 Customizable CSS and JavaScript
- 📊 Mermaid diagrams for architecture visualization
- 🚀 Static site generation for zero server overhead
- 🔗 Organized navigation and SEO-friendly URLs

All my projects follow the same philosophy: **documentation that's as polished as the code.**

---

## License

All projects are licensed under [MIT](LICENSE).

---

<div align="center">
<sub>A collection of <a href="https://github.com/ajbarea">AJ Barea's</a> Zensical projects · Documented with <a href="https://zensical.org">Zensical</a></sub>
</div>
