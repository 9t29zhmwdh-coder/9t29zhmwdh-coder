<div align="center">
  <img src="RayStudio.png" alt="RayStudio" width="90"/>

  # Rafael Yilmaz
</div>

🇬🇧 [English Version](README.md)

## Über mich

ICT Infrastructure Engineer bei [novosys.ch](https://www.novosys.ch), ich baue local-first Developer-Tools in Rust, Swift und Python. Ich betreibe eine praxisnahe KI-Testpraxis: lokale Modelle gegen Claude und Copilot benchmarken, um herauszufinden, wo ein leichtes Modell für Alltagsaufgaben wie das Erklären von Logs, Bugs und Mails zuverlässig genug ist, und wo Cloud-Fähigkeit den Aufwand wert ist. Jedes Repo in diesem Portfolio folgt denselben publizierten Engineering-Standards.

## Woran ich gerade arbeite

- **[NetSweep](https://github.com/9t29zhmwdh-coder/NetSweep)**: Netzlaufwerk-Audit und -Cleanup für NAS, SharePoint und DFS, mit signiertem Windows-Installer.
- **[MailPilot](https://github.com/9t29zhmwdh-coder/MailPilot)**: lokaler KI-E-Mail-Organizer für macOS, On-Device-Klassifikation, nichts verlässt das Gerät.
- **[LifePlanner](https://github.com/9t29zhmwdh-coder/LifePlanner)**: vollständig offline KI-Lebensplaner, Termine und Aufgaben aus reinem Text extrahiert.
- **[BugRadar](https://github.com/9t29zhmwdh-coder/BugRadar)**: Live-Log-/Metrik-Beobachtung, gruppiert Anomalien zu Incidents mit KI-Root-Cause-Analyse.

## Pinned Projects

| Projekt | Was es macht |
|---|---|
| **[private-model-orchestrator](https://github.com/9t29zhmwdh-coder/private-model-orchestrator)** | Verteilt und verwaltet On-Device Core-ML-Modelle über Apple-Geräteflotten |
| **[NetScanX](https://github.com/9t29zhmwdh-coder/NetScanX)** | Cross-Platform Netzwerk-Discovery- und Diagnose-CLI, Asset-Inventar, Drift-Detection |
| **[entra-access-graph-engine](https://github.com/9t29zhmwdh-coder/entra-access-graph-engine)** | Mappt Entra-ID-Privilegien-Graphen, erkennt Eskalationspfade und versteckte Admin-Ketten |
| **[SwiftAgent](https://github.com/9t29zhmwdh-coder/SwiftAgent)** | Abhängigkeitsfreies Swift-Framework für lokale LLM-Agenten |
| **[CleanFlow](https://github.com/9t29zhmwdh-coder/CleanFlow)** | KI-gestützter Datei-Organizer mit regelbasierter Cleanup-Automatisierung |
| **[engineering-standards](https://github.com/9t29zhmwdh-coder/engineering-standards)** | Die Security-First-Standards, die jedes Repo in diesem Portfolio regeln |

Alle Repositories: [vollständige Liste](https://github.com/9t29zhmwdh-coder?tab=repositories).

## Tech Focus

- **Sprachen:** Rust, Swift, C#, Python, TypeScript
- **Plattformen:** Apple Silicon (macOS), Windows (.NET 8 / WPF), Microsoft 365, Azure
- **KI:** Lokale Inferenz (Ollama, llama.cpp), Claude Code, GitHub Copilot
- **Praktiken:** Semantic Versioning, erzwungene Branch-Protection, Security-First-CI/CD

## Wie dieses Portfolio funktioniert

```
repo/
├── src/                  das eigentliche Tool
├── CLAUDE.md              KI-Pair-Programmer-Instruktionen (aus engineering-standards)
├── ROADMAP.md             was fertig ist, was als Nächstes kommt
├── SECURITY.md            Schwachstellen-Meldung, Security-Design
└── .github/workflows/     CI: Lint, Test, Security-Audit, Release
```

Jedes Repo folgt denselben [Engineering-Standards](https://github.com/9t29zhmwdh-coder/engineering-standards): reiner PR-Merge mit erzwungener Branch-Protection, [Semantic Versioning](https://semver.org) mit einer Verschärfung gegenüber der Spezifikation (`v1.0.0` ist ausschließlich einem wirklich installierbaren oder lauffähigen Produkt vorbehalten, nicht nur "feature-complete im Quellcode"), und eine risikobasierte Merge-Policy, niedriges Risiko wird selbst gemergt und gemeldet, alles mit Business-Logik- oder Security-Bezug wartet auf eine bewusste Prüfung.

## Kontakt

- **Website:** [raystudio.ch](https://raystudio.ch)
- **LinkedIn:** [Rafael Yilmaz](https://www.linkedin.com/in/rafael-yilmaz-b38474122/)
- **Arbeit:** [novosys.ch](https://www.novosys.ch)

---

Alle Software-Repos sind Open Source (MIT-Lizenz); [engineering-standards](https://github.com/9t29zhmwdh-coder/engineering-standards) ist Dokumentation, lizenziert unter CC BY 4.0. Issues & PRs willkommen.
