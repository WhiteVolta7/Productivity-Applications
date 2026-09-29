# ⚡ Productivity Stack & Toolkit
> A curated collection of custom productivity applications, personal automation tools, and workflow frameworks designed to optimize focus, track progression, and streamline everyday outputs.
---
## 📌 Repositories & Application Hub

| Application | Domain / Purpose | Tech Stack | Status |
| :--- | :--- | :--- | :--- |
| **Skill Progress Tracker** | Logs practice hours, calculates focus metrics, and generates analytics. | Python, Pandas, GitHub Actions | `Active` |
| **Harmonix Vault** | Digital asset & audio file manager with document categorization. | TypeScript, React, Node.js | `In Development` |
| **Daily Workflow Automator** | Task batching, CLI logging, and daily summary generator. | Python, Shell | `Maintained` |

---
## 🎯 Architectural Philosophy
1. **Low Friction Input:** Logging metrics or creating tasks should take less than 10 seconds.
2. **Local-First Data:** Raw logs and historical entries remain in human-readable formats (`.csv`, `.json`, `.md`).
3. **Automated Insights:** Analytics scripts handle calculations on `git push` rather than requiring manual summaries.
4. **Minimal Dependencies:** Built on core, long-term stable libraries to ensure zero-maintenance longevity.
---
## 📁 Repository Navigation
```text
productivity-stack/
├── apps/                     # Application source code
│   ├── skill-tracker/        # Time tracking and analytics engine
│   └── harmonix-vault/       # Asset and document organization app
├── templates/                # Reusable schemas (CSVs, JSON configs)
├── automation/               # Global CLI scripts and workflow hooks
└── docs/                     # Specifications, roadmaps, and rubrics
