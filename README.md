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
| **Cosmic Horror** | [victor-lockwood.github.io/Hackathon-2026-Cosmic-Horror](https://victor-lockwood.github.io/Hackathon-2026-Cosmic-Horror/) |

---

## Documentation Archive

### InteFL

**Federated learning execution and research framework**

- 🚀 [Get Started](intefl/docs/getting-started.md) — Install with Docker or locally
- 🧭 [CLI Reference](intefl/docs/cli.md) — Command overview and examples
- 🏗️ [Architecture](intefl/docs/architecture.md) — API, Celery, Flower, React UI
- ⚙️ [Configuration](intefl/docs/configuration.md) — StrategyConfig field reference
- 📊 [Datasets](intefl/docs/datasets.md) — FEMNIST, FLAIR, MedMNIST, HuggingFace text
- 🛡️ [Strategies](intefl/docs/strategies.md) — FedAvg, Krum, Bulyan, PID, Trust, RFA, ArKrum
- ⚡ [Attacks](intefl/docs/attacks.md) — Label flipping, backdoors, poisoning, Byzantine
- 📡 [API Reference](intefl/docs/api.md) — REST endpoints for simulations

**Tech Stack:** Flower (FL orchestration) · Ray (compute) · PyTorch · FastAPI · Celery · React · Zensical

---

### Kourai Khryseai

**Six AI specialists collaborating through the A2A protocol**

- 🚀 [Get Started](kourai-khryseai/docs/getting-started.md) — Prerequisites, setup, Docker
- 💡 [How It Works](kourai-khryseai/docs/overview.md) — The A2A protocol and agent architecture
- ⚙️ [Configuration](kourai-khryseai/docs/configuration.md) — Environment variables and settings
- 🔧 [CLI Guide](kourai-khryseai/docs/cli.md) — Command usage and pipelines
- 🖥️ [GUI Reference](kourai-khryseai/docs/gui.md) — Pygame GUI interface
- 📖 [VN Reference](kourai-khryseai/docs/vn.md) — Ren'Py visual novel interface
- 🏗️ [Architecture](kourai-khryseai/docs/architecture/index.md) — System design and layers
- 🧠 [Agents](kourai-khryseai/docs/agents/index.md) — Hephaestus, Metis, Techne, Dokimasia, Kallos, Mneme
- 💰 [Pricing](kourai-khryseai/docs/pricing.md) — Cost model and token budgets

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

### VelocityFL

**Federated learning project documentation**

- 🚀 [Get Started](vfl/docs/getting-started.md) — Install and run your first simulation
- 🧭 [CLI Reference](vfl/docs/cli.md) — Command overview and examples
- 🏗️ [Architecture](vfl/docs/architecture.md) — Rust core, Python bridge, and execution flow
- ⚙️ [Configuration](vfl/docs/configuration.md) — Runtime settings and defaults
- 🛡️ [Strategies](vfl/docs/strategies.md) — Aggregation strategies and behavior
- ⚡ [Attacks](vfl/docs/attacks.md) — Fault and adversarial scenario modeling
- 📡 [API Reference](vfl/docs/api.md) — Programmatic interface details
- 📊 [Convergence](vfl/docs/convergence.md) — Stability and convergence notes
- 🏁 [Benchmarks](vfl/docs/benchmarks.md) — Performance and scaling observations
- 🧠 [Skills](vfl/docs/skills.md) — Project skill documentation

**Tech Stack:** Rust · Python · pyo3 · Zensical

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
├── kourai-khryseai/
│   ├── docs/                    # Zensical documentation site
│   ├── agents/                  # Six specialist agents
│   ├── shared/                  # Common config, LLM, tracing
│   ├── mcp_servers/             # Tool servers (fs, git, shell)
│   └── tests/                   # Unit & integration tests
├── hackathon-2026-cosmic-horror/
│   ├── docs/                    # Zensical documentation site
│   ├── src/                     # Signal processing, gesture classification, MIDI engine
│   └── data/                    # Playlists and gesture models
├── vfl/
│   └── docs/                    # Zensical documentation site
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
