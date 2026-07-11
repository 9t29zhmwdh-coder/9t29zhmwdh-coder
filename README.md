<div align="center">
  <img src="RayStudio.png" alt="RayStudio" width="100"/>

  ## Hey, I'm Rafael

</div>

**ICT Infrastructure Engineer · Developer Tools Creator · Open Source**

Workplace Engineer @ [novosys.ch](https://www.novosys.ch)  
I build practical tools and use AI deliberately: local-first by default, cloud only where it earns its place. Everything governed, tested and verifiable.

![Rust](https://img.shields.io/badge/Rust-CE422B?logo=rust&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?logo=dotnet&logoColor=white) ![Swift](https://img.shields.io/badge/Swift-F05138?logo=swift&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white) ![Microsoft 365](https://img.shields.io/badge/Microsoft-M365-0078d4?logo=microsoft&logoColor=white) ![Azure](https://img.shields.io/badge/Microsoft-Azure-0078d4?logo=microsoftazure&logoColor=white) ![Entra ID](https://img.shields.io/badge/Microsoft-Entra_ID-0078d4?logo=microsoftazure&logoColor=white) ![Apple Silicon](https://img.shields.io/badge/Apple-Silicon-000000?logo=apple&logoColor=white) ![AI | Claude Code](https://img.shields.io/badge/AI-Claude_Code-black?logo=anthropic&logoColor=white) ![AI | Copilot](https://img.shields.io/badge/AI-Copilot-black?logo=github&logoColor=white) ![AI | Ollama](https://img.shields.io/badge/AI-Ollama-black?logo=ollama&logoColor=white)

[🇩🇪 Deutsche Version](README.de.md)

---

## Featured

**[NetSweep](https://github.com/9t29zhmwdh-coder/NetSweep)** [![CI](https://github.com/9t29zhmwdh-coder/NetSweep/actions/workflows/ci.yml/badge.svg)](https://github.com/9t29zhmwdh-coder/NetSweep/actions) [![Release](https://img.shields.io/github/v/release/9t29zhmwdh-coder/NetSweep?color=3F8E7E)](https://github.com/9t29zhmwdh-coder/NetSweep/releases)  
Network storage audit & cleanup for NAS, SharePoint and DFS. Ships a signed Windows installer, download and run.

**[MailPilot](https://github.com/9t29zhmwdh-coder/MailPilot)** [![CI](https://github.com/9t29zhmwdh-coder/MailPilot/actions/workflows/ci.yml/badge.svg)](https://github.com/9t29zhmwdh-coder/MailPilot/actions) [![Release](https://img.shields.io/github/v/release/9t29zhmwdh-coder/MailPilot?color=3F8E7E)](https://github.com/9t29zhmwdh-coder/MailPilot/releases)  
Local AI email organizer for macOS: on-device classification, IMAP sync, nothing leaves the machine. macOS installer on the Releases page.

**[LifePlanner](https://github.com/9t29zhmwdh-coder/LifePlanner)** [![CI](https://github.com/9t29zhmwdh-coder/LifePlanner/actions/workflows/ci.yml/badge.svg)](https://github.com/9t29zhmwdh-coder/LifePlanner/actions) [![Release](https://img.shields.io/github/v/release/9t29zhmwdh-coder/LifePlanner?color=3F8E7E)](https://github.com/9t29zhmwdh-coder/LifePlanner/releases)  
Fully offline AI life planner: events, tasks and deadlines, extracted from plain text. macOS and Windows installers on the Releases page.


## How I Work

- Every public repo follows my published [engineering standards](https://github.com/9t29zhmwdh-coder/engineering-standards): security-first checklists, testing strategy, semantic releases.
- Branch protection is technically enforced on every repo via GitHub rulesets (no direct pushes, PR flow, no force-push), including against myself.
- AI-assisted development (Claude Code, Copilot) is governed by those standards, not the other way around.
- Releases are verified before publishing: builds, test suites and functional smoke tests documented in the release notes.

**Versioning.** Every repo follows [Semantic Versioning](https://semver.org) (`MAJOR.MINOR.PATCH`), with one house rule stricter than the spec: `MAJOR`/`v1.0.0` is reserved for a genuinely finished, installable or runnable product (a real installer, packaged app, or Docker image), not just "feature-complete in the source." A CLI-only tool stays below `v1.0.0` regardless of how complete it is. `PATCH` covers fixes and docs, `MINOR` covers new features. Full rule in [engineering-standards](https://github.com/9t29zhmwdh-coder/engineering-standards/blob/main/CLAUDE.md), section 3.

**Change workflow.** Every change, including a docs-only fix, goes through the same sequence: branch, commit, push, pull request, CI checks, merge (squash), tag, GitHub Release with notes; no shortcuts, even for small fixes. Merge risk is handled explicitly: low-risk changes (docs, CI config, tests) are self-merged and reported afterward; anything touching business logic, security, or secrets waits for a deliberate review before merging, even on a solo-maintained repo.

---
## What I Work With

### Infrastructure & Automation
- **Network:** Ubiquiti UniFi (Cloud Gateway, UDM Pro, WiFi 6/7)
- **Automation:** Home Assistant, Raspberry Pi, Zigbee, Matter, Z-Wave
- **Storage:** Synology/UGREEN NAS, Microsoft 365, Exchange Online
- **Devices:** Apple Silicon (macOS), Surface Laptop 7 (Snapdragon X Elite, Windows 11), Linux servers

### Development Stack

| Layer | Technology |
|---|---|
| **Desktop Apps** | Rust + Tauri, C# + WPF (.NET 8), Swift (macOS/iOS) |
| **Web/Frontend** | TypeScript, React, Tailwind CSS |
| **Backend** | Rust async (Tokio), Python, PowerShell 7 |
| **Data** | SQLite with FTS5, PostgreSQL |
| **AI** | Ollama (local), Qwen 3.5, Claude Code, Copilot CoWork, Windows Copilot |
| **IDE / Tools** | Visual Studio 2022, Visual Studio Code, Xcode, Windows Terminal |
| **DevOps** | Git/GitHub, Docker, GitHub Actions |

## Projects

### Rust + Tauri Desktop Apps

| Project | Description |
|---|---|
| **[LifePlanner](https://github.com/9t29zhmwdh-coder/LifePlanner)** | Offline AI life planner: events, tasks, goals |
| **[LifeSort](https://github.com/9t29zhmwdh-coder/LifeSort)** | AI-powered file organizer: rules, duplicates, automation |
| **[CleanFlow](https://github.com/9t29zhmwdh-coder/CleanFlow)** | Smart disk cleanup: temp files, caches, duplicates |
| **[ClarityDesk](https://github.com/9t29zhmwdh-coder/ClarityDesk)** | Captures the screen, reads text with OCR and explains it with local AI (translate, explain code, analyze logs) |
| **[DeviceHealth](https://github.com/9t29zhmwdh-coder/DeviceHealth)** | Scans processes, hardware and network, spots problems and explains the fix in plain language, fully offline |
| **[MailPilot](https://github.com/9t29zhmwdh-coder/MailPilot)** | Local email client that auto-sorts every message with on-device AI; nothing leaves your machine |
| **[BugRadar](https://github.com/9t29zhmwdh-coder/BugRadar)** | Live watch over logs, containers and metrics; groups anomalies into incidents with AI root-cause fixes |

### Rust CLI & Backend

| Project | Description |
|---|---|
| **[LogLens](https://github.com/9t29zhmwdh-coder/LogLens)** | Collects and searches logs from files, Docker and system, clusters errors and explains them with local AI |
| **[StateForge](https://github.com/9t29zhmwdh-coder/StateForge)** | Extracts state machines from code, logs or plain-language descriptions, draws them as diagrams and regenerates clean code |
| **[agent-governance-console](https://github.com/9t29zhmwdh-coder/agent-governance-console)** | Ingests AI-agent execution traces, enforces governance policies per step and writes immutable audit records; exports to Azure Monitor and Sentinel |
| **[private-model-orchestrator](https://github.com/9t29zhmwdh-coder/private-model-orchestrator)** | Deploys, versions and serves on-device Core ML models across managed Apple fleets; no data leaves the device |

### Swift for macOS & iOS

| Project | Description |
|---|---|
| **[SwiftAgent](https://github.com/9t29zhmwdh-coder/SwiftAgent)** | Dependency-free Swift framework for running local LLM agents (Ollama, llama.cpp) via async/await |
| **[CodeWhisper](https://github.com/9t29zhmwdh-coder/CodeWhisper)** | macOS assistant: select code in any editor, right-click to explain or refactor it with local AI |

### C# + WPF Windows Tools

| Project | Description |
|---|---|
| **[NetSweep](https://github.com/9t29zhmwdh-coder/NetSweep)** | Network storage audit & cleanup: NAS, SharePoint, DFS, Windows |
| **[NetDashboard](https://github.com/9t29zhmwdh-coder/NetDashboard)** | Network & mail diagnostics: DNS, M365/Exchange Online, Windows |

### Python

| Project | Description |
|---|---|
| **[SiliconMark](https://github.com/9t29zhmwdh-coder/SiliconMark)** | Benchmarks local LLMs on Apple Silicon: tokens/s, RAM and Neural Engine (ANE) activity per model |
| **[NetScanX](https://github.com/9t29zhmwdh-coder/NetScanX)** | Cross-platform network discovery & diagnostics CLI |
| **[GardenFlow](https://github.com/9t29zhmwdh-coder/GardenFlow)** | Home garden automation: reads sensors over MQTT, runs rules and controls pumps via a live dashboard |
| **[HomePortal](https://github.com/9t29zhmwdh-coder/HomePortal)** | Lightweight self-hosted start page and dashboard for a NAS or home server (FastAPI, Docker) |
| **[azure-cost-forecasting-engine](https://github.com/9t29zhmwdh-coder/azure-cost-forecasting-engine)** | Azure cost analysis, forecasting and optimization recommendations via Consumption API |
| **[eventhub-otlp-mapper](https://github.com/9t29zhmwdh-coder/eventhub-otlp-mapper)** | Map Azure EventHub messages to OpenTelemetry Traces and Metrics (OTLP, JSON/Avro/Protobuf, Azure Monitor) |

### Infrastructure & Security

| Project | Description |
|---|---|
| **[entra-access-graph-engine](https://github.com/9t29zhmwdh-coder/entra-access-graph-engine)** | Entra ID privilege access graph: detect escalation paths, hidden admin chains, and risk scores (Rust, Graph API) |
| **[entra-least-privilege-analyzer](https://github.com/9t29zhmwdh-coder/entra-least-privilege-analyzer)** | Read-only Rust CLI for Entra ID privilege analysis, PIM gap detection and role overlap reporting |
| **[azure-policy-drift-detector](https://github.com/9t29zhmwdh-coder/azure-policy-drift-detector)** | Read-only Rust CLI to detect Azure Policy drift, prioritize non-compliant resources and generate remediation reports |
| **[github-actions-security-sandbox](https://github.com/9t29zhmwdh-coder/github-actions-security-sandbox)** | Static analysis and attack simulation for GitHub Actions workflows: injection, Pwn Request, unpinned actions |
| **[engineering-standards](https://github.com/9t29zhmwdh-coder/engineering-standards)** | Public engineering standards governing all my repos: security-first checklists, testing strategy, enforced branch protection rulesets |

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
- Claude Code: CLI-based AI pair programmer for architecture, code review and multi-file refactors.
  Governed by my public [engineering standards](https://github.com/9t29zhmwdh-coder/engineering-standards)
  (security-first rules, risk-based merge policy, branch protection enforced via GitHub rulesets on every repo)
- Copilot CoWork: GitHub Copilot integrated across Visual Studio, VS Code and JetBrains for enterprise .NET, WPF, PowerShell and M365 automation
- Windows Copilot on Surface Laptop 7 (Snapdragon X Elite, ARM-native): daily companion for
  drafting, research and hands-on testing of Microsoft AI features on Windows on ARM

**Integration & testing:**
- All my tools with AI features (LifePlanner, LogLens, MailPilot, CodeWhisper and others) speak the
  same OpenAI-compatible interface for both local Ollama models and cloud APIs
- No local GPU? Point any tool at a free cloud tier (Google AI Studio, Groq, Mistral, OpenRouter)
  through that same interface, no code change; switch back to local Ollama when privacy matters
- The tools expose the local-vs-cloud choice instead of forcing it, so the setup fits the need,
  not a dogma
- The goal: find where a well-tuned local model is good enough and where cloud capability
  actually justifies the tradeoff

---

## Background

**20+ years** in logistics & supply chain management  
**3+ years** in ICT infrastructure & support

Translated from logistics mindset: **systems thinking, process optimization, hands-on engineering.**

---

## Connect

- **Website:** [raystudio.ch](https://raystudio.ch)
- **Work:** [novosys.ch](https://www.novosys.ch)

---

**All software repos are open source (MIT license); [engineering-standards](https://github.com/9t29zhmwdh-coder/engineering-standards) is documentation, licensed under CC BY 4.0. Issues & PRs welcome.**
