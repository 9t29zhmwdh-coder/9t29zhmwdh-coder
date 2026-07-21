<div align="center">
  <img src="RayStudio.png" alt="RayStudio" width="90"/>

  # Rafael Yilmaz
</div>

[🇩🇪 Deutsche Version](README.de.md)

## About

ICT Infrastructure Engineer at [novosys.ch](https://www.novosys.ch), building local-first developer tools in Rust, Swift, and Python. I run a hands-on AI practice: benchmarking local models against Claude and Copilot to find where a lightweight model is reliable enough for everyday tasks like explaining logs, bugs, and mail, and where cloud capability earns its place. Every repo in this portfolio follows the same published engineering standards.

## Currently Building

- **[NetSweep](https://github.com/9t29zhmwdh-coder/NetSweep)**: network storage audit and cleanup for NAS, SharePoint, and DFS, ships a signed Windows installer.
- **[MailPilot](https://github.com/9t29zhmwdh-coder/MailPilot)**: local AI email organizer for macOS, on-device classification, nothing leaves the machine.
- **[LifePlanner](https://github.com/9t29zhmwdh-coder/LifePlanner)**: fully offline AI life planner, events and tasks extracted from plain text.
- **[BugRadar](https://github.com/9t29zhmwdh-coder/BugRadar)**: live log and metric watcher, groups anomalies into incidents with AI root-cause analysis.
- **[AdapterForge](https://github.com/9t29zhmwdh-coder/AdapterForge)**: local QLoRA adapter training pipeline for Ollama models on Apple Silicon, from dataset prep through GGUF export to Ollama deploy in one CLI.

## Pinned Projects

| Project | What it does |
|---|---|
| **[private-model-orchestrator](https://github.com/9t29zhmwdh-coder/private-model-orchestrator)** | Deploys and manages on-device Core ML models across Apple device fleets |
| **[NetScanX](https://github.com/9t29zhmwdh-coder/NetScanX)** | Cross-platform network discovery and diagnostics CLI, asset inventory, drift detection |
| **[entra-access-graph-engine](https://github.com/9t29zhmwdh-coder/entra-access-graph-engine)** | Maps Entra ID privilege graphs, detects escalation paths and hidden admin chains |
| **[SwiftAgent](https://github.com/9t29zhmwdh-coder/SwiftAgent)** | Dependency-free Swift framework for running local LLM agents |
| **[CleanFlow](https://github.com/9t29zhmwdh-coder/CleanFlow)** | AI-powered file organizer with rule-based cleanup automation |
| **[engineering-standards](https://github.com/9t29zhmwdh-coder/engineering-standards)** | The security-first standards that govern every repo in this portfolio |

See [all repositories](https://github.com/9t29zhmwdh-coder?tab=repositories) for the full list.

## Tech Focus

- **Languages:** Rust, Swift, C#, Python, TypeScript
- **Platforms:** Apple Silicon (macOS), Windows (.NET 8 / WPF), Microsoft 365, Azure
- **AI:** Local inference (Ollama, llama.cpp), Claude Code, GitHub Copilot
- **Practices:** Semantic Versioning, enforced branch protection, security-first CI/CD

## Security Posture

Not a certification, just what actually runs on every active repository: GitHub scans the code for known vulnerability patterns on every push (CodeQL) and flags outdated or risky dependencies automatically (Dependabot). A scheduled OpenSSF Scorecard scan scores supply-chain hygiene (pinned actions, branch protection, dependency update tooling) on the same schedule, and every repo now self-certifies against the [OpenSSF Best Practices](https://www.bestpractices.dev) checklist. GitHub itself blocks a merge if any of these checks are red, that's not a house rule, it's enforced by branch protection. Anyone who finds a security issue reports it privately through GitHub, not as a public issue (details in [engineering-standards](https://github.com/9t29zhmwdh-coder/engineering-standards/blob/main/standards/ci-cd.md), "Automated Security Signals"). See it live on two pinned repos:

**entra-access-graph-engine:** [![CodeQL](https://github.com/9t29zhmwdh-coder/entra-access-graph-engine/actions/workflows/github-code-scanning/codeql/badge.svg)](https://github.com/9t29zhmwdh-coder/entra-access-graph-engine/security/code-scanning) [![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/9t29zhmwdh-coder/entra-access-graph-engine/badge)](https://securityscorecards.dev/viewer/?uri=github.com/9t29zhmwdh-coder/entra-access-graph-engine) [![OpenSSF Best Practices](https://www.bestpractices.dev/projects/13710/badge)](https://www.bestpractices.dev/projects/13710)

**CleanFlow:** [![CodeQL](https://github.com/9t29zhmwdh-coder/CleanFlow/actions/workflows/github-code-scanning/codeql/badge.svg)](https://github.com/9t29zhmwdh-coder/CleanFlow/security/code-scanning) [![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/9t29zhmwdh-coder/CleanFlow/badge)](https://securityscorecards.dev/viewer/?uri=github.com/9t29zhmwdh-coder/CleanFlow) [![OpenSSF Best Practices](https://www.bestpractices.dev/projects/13714/badge)](https://www.bestpractices.dev/projects/13714)

## How This Portfolio Works

```
repo/
├── src/                  the tool itself
├── CLAUDE.md              AI-pair-programmer instructions (from engineering-standards)
├── ROADMAP.md             what's shipped, what's next
├── SECURITY.md            vulnerability reporting, security design
└── .github/workflows/     CI: lint, test, security audit, release
```

Every repo follows the same [engineering standards](https://github.com/9t29zhmwdh-coder/engineering-standards): PR-only merges with enforced branch protection, [Semantic Versioning](https://semver.org) with one house rule stricter than the spec (`v1.0.0` is reserved for a genuinely installable or runnable product, not just "feature-complete in the source"), and a risk-based merge policy, low-risk changes are self-merged and reported, anything touching business logic or security waits for a deliberate review.

## Contact

- **Website:** [raystudio.ch](https://raystudio.ch)
- **LinkedIn:** [Rafael Yilmaz](https://www.linkedin.com/in/rafael-yilmaz-b38474122/)
- **Work:** [novosys.ch](https://www.novosys.ch)

---

All software repos are open source (MIT license); [engineering-standards](https://github.com/9t29zhmwdh-coder/engineering-standards) is documentation, licensed under CC BY 4.0. Issues and PRs welcome.
