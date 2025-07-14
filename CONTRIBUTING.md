# Contributing to Stationeering Systems

This repository is not self-contained.

Engineering standards, system behavior, and control architecture are documented externally at:

📘 **Source of Truth – Archive Protocol**  
https://stationeering.substack.com/p/source-of-truth-archive-protocol

Do not edit, fork, or contribute to any module without first verifying its canonical definition on Substack.

---

## Repository Purpose

Each repository in this organization reflects a specific *Stationeers* playthrough configuration (environment, difficulty, landing kit). It hosts:

- `docs/`: formal documentation (syncs with Substack)
- `docs_ic10/`: in-game readable documentation
- `ic10/`: control scripts and automation logic

This structure supports assistant tooling, code audits, and modular upgrades—but **does not replace** the canonical design layer.

---

## Versioning & Change Discipline

All changes are tracked via semantic versioning at the repository level. A modification to any module—however small—triggers a version bump for the entire repository.

Version tags are managed via GitHub releases.  
Filenames do not encode version numbers.  
See the Archive Protocol for detailed versioning rules.

---

## Assistant Guidance

Assistant agents and automated tooling must:

- Treat Substack posts as the canonical source for documentation, system behavior, and naming conventions.
- Validate assumptions against the latest Archive Protocol.
- Avoid duplicating logic or introducing undocumented dependencies between systems.
- Never infer system behavior from GitHub directory contents alone.

---

This repository is an artifact cache, not a design platform.  
Assist accordingly.
