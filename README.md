<div align="center">
  <img src="RayStudio.png" alt="RayStudio" width="100"/>

  ## Hey, I'm Rafael

  **ICT Infrastructure Engineer · Developer Tools Creator · Open Source**

  Workplace Engineer @ [novosys.ch](https://www.novosys.ch)  
  Building tools for practical problems. Everything runs local. Everything offline-first.
</div>

![Rust](https://img.shields.io/badge/Rust-orange?logo=rust)
![Swift](https://img.shields.io/badge/Swift-orange?logo=swift)
![Python](https://img.shields.io/badge/Python-orange?logo=python)
![C%23](https://img.shields.io/badge/C%23-orange?logo=dotnet)
![Tauri](https://img.shields.io/badge/Tauri-blue?logo=tauri)
![WPF](https://img.shields.io/badge/WPF-.NET%208-blue?logo=windows)
![Ollama](https://img.shields.io/badge/Ollama-local%20AI-lightgrey?logo=ollama)
![Azure](https://img.shields.io/badge/Azure-Monitor%20%7C%20Sentinel-blue?logo=microsoftazure)
![Platform](https://img.shields.io/badge/Apple%20Silicon-macOS-lightgrey?logo=apple)
![Claude](https://img.shields.io/badge/Claude-API-blue?logo=anthropic)

> 🇩🇪 [Deutsche Version](README.de.md)

---

## What I Work With

### Infrastructure & Automation
- **Network:** Ubiquiti UniFi (Cloud Gateway, UDM Pro, WiFi 6/7)
- **Automation:** Home Assistant, Raspberry Pi, Zigbee, Matter, Z-Wave
- **Storage:** Synology/UGREEN NAS, Microsoft 365, Exchange Online
- **Devices:** macOS (M-series), Surface Laptop, Linux servers

### Development Stack

| Layer | Technology |
|---|---|
| **Desktop Apps** | Rust + Tauri, C# + WPF (.NET 8), Swift (macOS/iOS) |
| **Web/Frontend** | TypeScript, React, Tailwind CSS |
| **Backend** | Rust async (Tokio), Python, PowerShell |
| **Data** | SQLite with FTS5, PostgreSQL |
| **AI** | Ollama (local), llama.cpp, offline-first models |
| **DevOps** | Git/GitHub, Docker, GitHub Actions |

---

## Projects

### Rust + Tauri Desktop Apps

| Project | Description |
|---|---|
| **[LifePlanner](https://github.com/9t29zhmwdh-coder/LifePlanner)** | Offline AI life planner: events, tasks, goals |
| **[LifeSort](https://github.com/9t29zhmwdh-coder/LifeSort)** | AI-powered file organizer: rules, duplicates, automation |
| **[CleanFlow](https://github.com/9t29zhmwdh-coder/CleanFlow)** | Smart disk cleanup: temp files, caches, duplicates |
| **[ClarityDesk](https://github.com/9t29zhmwdh-coder/ClarityDesk)** | Universal display interpreter: OCR + local AI |
| **[DeviceHealth](https://github.com/9t29zhmwdh-coder/DeviceHealth)** | Cross-platform system health monitor |
| **[MailPilot](https://github.com/9t29zhmwdh-coder/MailPilot)** | Offline-first email client with AI classification |
| **[BugRadar](https://github.com/9t29zhmwdh-coder/BugRadar)** | Real-time log analysis & AI-driven incident detection |

### Rust CLI & Backend

| Project | Description |
|---|---|
| **[LogLens](https://github.com/9t29zhmwdh-coder/LogLens)** | AI log aggregator: clustering, anomaly detection, FTS |
| **[StateForge](https://github.com/9t29zhmwdh-coder/StateForge)** | State machine analyzer: parse, visualize, generate |
| **[agent-governance-console](https://github.com/9t29zhmwdh-coder/agent-governance-console)** | AI agent governance, tracing & audit: Axum, OpenTelemetry, Azure Monitor / Sentinel |
| **[private-model-orchestrator](https://github.com/9t29zhmwdh-coder/private-model-orchestrator)** | Privacy-first foundation model orchestration for Apple device fleets |

### Swift for macOS & iOS

| Project | Description |
|---|---|
| **[SwiftAgent](https://github.com/9t29zhmwdh-coder/SwiftAgent)** | Native iOS AI chat interface: local model integration |
| **[CodeWhisper](https://github.com/9t29zhmwdh-coder/CodeWhisper)** | macOS AI code assistant with NSServices integration |

### C# + WPF Windows Tools

| Project | Description |
|---|---|
| **[NetSweep](https://github.com/9t29zhmwdh-coder/NetSweep)** | Network storage audit & cleanup: NAS, SharePoint, DFS, Windows |
| **[NetDashboard](https://github.com/9t29zhmwdh-coder/NetDashboard)** | Network & mail diagnostics: DNS, M365/Exchange Online, Windows |

### Python

| Project | Description |
|---|---|
| **[SiliconMark](https://github.com/9t29zhmwdh-coder/SiliconMark)** | Apple Silicon LLM benchmark suite: Token/s, RAM, ANE |
| **[NetScanX](https://github.com/9t29zhmwdh-coder/NetScanX)** | Cross-platform network discovery & diagnostics CLI |
| **[GardenFlow](https://github.com/9t29zhmwdh-coder/GardenFlow)** | Modular home garden automation (MQTT, FastAPI, Docker) |
| **[HomePortal](https://github.com/9t29zhmwdh-coder/HomePortal)** | Self-hosted home services portal (FastAPI, Docker) |

### Infrastructure & PowerShell

| Project | Description |
|---|---|
| **[M365-AdminTool](https://github.com/9t29zhmwdh-coder/M365-AdminTool)** | PowerShell toolkit for Microsoft 365 administration |
| **[JellyFin-MediaStack](https://github.com/9t29zhmwdh-coder/JellyFin-MediaStack)** | Self-hosted media server stack (Docker Compose) |

---

## Focus Areas

- Rust: Tauri desktop apps, async backends, CLI tools
- Python: automation, benchmarks, data processing
- C#: Windows desktop and enterprise tools
- Local AI: Ollama, llama.cpp, offline-first
- macOS/iOS: Swift development
- Microsoft / Azure: M365, WPF and enterprise integrations

---

## AI & LLM Lab

Running a local AI lab on Apple Silicon (laptop and desktop), testing open-source models and
comparing them against cloud APIs, integrated directly into my own tools.

**Local inference via Ollama:**
- Daily driver: Qwen 3.5 as the primary model and personal benchmark baseline
- Continuously testing new releases against it: LFM 2.5, Gemma 4, Qwen 2.5 and others
- SiliconMark (my own tool) to measure Token/s, RAM usage and ANE activity per model and runtime

**Autonomous agents:**
- Nous Hermes running as a 24/7 local agent for long-term workflow and reliability tests
- Handles multi-step pipelines, tool calling and unattended tasks entirely on-device
- qwen3-coder tested as a local coding agent against cloud-based coding tools
- Cloud counterpart: Claude API for agent benchmark comparison and production workflows

**Integration & testing:**
- All my tools with AI features (LifePlanner, LogLens, MailPilot, CodeWhisper and others) support
  both local Ollama models and cloud APIs
- The goal: find where a well-tuned local model is good enough and where cloud capability
  actually justifies the tradeoff

---

## Background

**20+ years** in logistics & supply chain management  
**3+ years** in ICT infrastructure & support  
**Certifications:** SIZ Informatik, ICT Power-User, Leadership

Translated from logistics mindset: **systems thinking, process optimization, hands-on engineering.**

---

## Connect

- **Website:** [raystudio.ch](https://raystudio.ch)
- **Work:** [novosys.ch](https://www.novosys.ch)

---

**All repos are open source (MIT license). Issues & PRs welcome.**
