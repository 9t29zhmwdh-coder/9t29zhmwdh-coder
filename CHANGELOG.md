# Changelog

All notable changes to this profile README will be documented here.
Format based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

---

## [0.2.5] - 2026-07-31

### Fixed

- Three tool descriptions contradicted the repositories they link to. NetSweep was said to ship a signed Windows installer; its own README says the installer is unsigned and SmartScreen warns on first run. MailLoom was said to keep everything on-device; that is the default since its 1.4.0, but Claude is a supported choice that transmits sender, subject and the first 800 characters, so naming only the default read as a guarantee the software does not make. CleanFlow was called an AI-powered file organizer; it is the rule-based one, and LifeSort is the one that runs a vision model.

### Note

- Ten changes were merged between 0.2.4 and this entry without a version of their own, including the repository lifecycle diagram and the three tool renames. They are in the git history but not in this file. Rather than reconstructing ten entries after the fact, the gap is recorded here.

---

## [0.2.4] - 2026-07-12

### Added

- New "Security Posture" section (README.md, README.de.md), with live CodeQL badges from two pinned repos (entra-access-graph-engine, CleanFlow), linking to engineering-standards' Automated Security Signals documentation.

## [0.2.3] - 2026-07-11

### Fixed

- Replaced an eszett (ß) in README.de.md with "ss"; the account uses Swiss German orthography. Also removed an eszett and em-dashes from TEMPLATE_NOTES.md.

## [0.2.2] - 2026-07-11

### Changed

- Rewrote the About paragraph: "local models by default, cloud only where it earns its place" overstated personal daily AI usage (Copilot is a daily driver, Claude a regular secondary for writing) even though it accurately describes the tools built. Replaced with an honest description of the actual practice: benchmarking local models against Claude and Copilot for everyday tasks.

## [0.2.1] - 2026-07-11

### Fixed

- Removed the email from Contact; the previous redesign PR was merged one commit before this removal landed. LinkedIn and the website are sufficient contact channels.

## [0.2.0] - 2026-07-11

### Changed

- Redesigned README.md/README.de.md from scratch: concise About, Currently Building, a curated Pinned Projects table, a compact Tech Focus list, a portfolio file-tree/structure diagram, and Contact (added LinkedIn). Removed the badge row and the exhaustive per-category project catalog in favor of a shorter, recruiter- and reviewer-scannable structure; the full project list remains one click away via the GitHub repositories tab.

## [0.1.1] - 2026-07-11

### Added

- Expanded "How I Work" / "Wie ich arbeite" with the versioning rule (SemVer with a stricter MAJOR bar) and the change workflow (branch/commit/push/PR/CI/merge/tag/release, risk-based merge policy).

### Fixed

- Corrected the footer license claim: engineering-standards is CC BY 4.0, not MIT.

## [0.1.0] - 2026-07-11

### Fixed

- Corrected README hero section: only the profile image and the greeting headline stay centered, the tagline and bio text below are now left aligned like the rest of the document
