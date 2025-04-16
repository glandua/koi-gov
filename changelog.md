# KOI Naming Convention Changelog

This changelog tracks all officially ratified changes and updates to the KOI (Knowledge Organization Infrastructure) naming conventions stewarded by Regen Network Development, PBC.

---

## ⏳ Timeline Overview

- ✅ 2025-04-07: v1.0.0 – Initial KOI naming schema established
- ✅ 2025-04-16: v1.1.0 – Added property-based KOI naming format for Notion, GDocs, GitHub

---

## 🗂️ Version History

### [v1.1.0] - 2025-04-16 ✅

#### New Feature: Property-Based KOI Naming

- KOI objects may now be expressed using **semantic metadata fields** in tools like Notion, Google Docs, and GitHub
- This includes separating the `title` from properties such as `KOI Name`, `Type`, `Version`, `Status`, etc.
- Improves searchability, machine parsing, and human readability
- See new guide: [`docs/semantic-naming-properties.md`](./docs/semantic-naming-properties.md)

### [v1.0.0] - 2025-04-07 ✅

#### Initial Release

- Established initial semantic naming convention:
  ```
  [relevance].[type].[subject].vX.Y.Z
  ```

#### Relevance Tiers
- **`core.`** – Canonical, foundational documents
- **`relevant.`** – Actively cited or influential docs
- **`background.`** – Supportive, ambient, or historical material

#### Object Types
- `memo` – Strategic or operational thinking
- `analysis` – Quantitative/qualitative breakdowns
- `notes` – Raw or exploratory ideas
- `readme` – Canonical directory or pattern documentation

#### Semantic Versioning Guidelines
- `vX.0.0`: Major conceptual shifts or naming structure changes
- `vX.Y.0`: Additions or updates to existing tiers/types
- `vX.Y.Z`: Editorial or minor clarifications

#### Governance Process
- Proposed via markdown docs and GitHub PRs
- Piloted and discussed in KOI syncs
- Approved by consensus during governance calls

---

## ✍️ How to Update This Changelog

- Add new entries to the top of the list
- Be concise but clear: what changed, why, and what version bump was made
- Link related guides or proposals when possible

---

## 🤝 Contribution & Governance

To propose changes:

- Submit a Pull Request following [`CONTRIBUTING.md`](./CONTRIBUTING.md)
- Include examples, reasoning, and whether the change is major, minor, or a patch
- Attend a KOI sync call for live review

Thank you for contributing to the clarity and coherence of KOI Governance!

