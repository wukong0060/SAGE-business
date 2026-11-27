# SAGE Master Project Index

**GitHub owner:** [wukong0060](https://github.com/wukong0060)  
**Repository policy:** Keep the six verified existing repositories and create a dedicated repository for each distinct planned project listed below.

> Compiled from retained ChatGPT context and recent discussions. This is not a complete export of every conversation. A planned repository is a place for its specifications and future code, not proof that it is already implemented.

## Existing repositories

| Repository | Visibility | Responsibility |
|---|---|---|
| [S.A.G.E](https://github.com/wukong0060/S.A.G.E) | Private | Core AI, orchestration, memory, skills, API, permissions and audit |
| [SAGE-business](https://github.com/wukong0060/SAGE-business) | Public | Business hub, master index, cross-project planning and business specifications |
| [SAGE-OS-](https://github.com/wukong0060/SAGE-OS-) | Public | Windows optimization, customization and PC performance tooling |
| [SAGE-Droid](https://github.com/wukong0060/SAGE-Droid) | Private | Android SAGE platform, Termux Companion and device modules |
| [SAGE-Brawlhalla-Trainer](https://github.com/wukong0060/SAGE-Brawlhalla-Trainer) | Private | SAGE FORGE, Brawlhalla replay analysis, coaching and training tools |
| [Base-SAGE](https://github.com/wukong0060/Base-SAGE) | Public | Base44-style AI/no-code app builder platform |

## Planned projects with dedicated repositories

| Planned repository | Project |
|---|---|
| `SAGE-Mail-Intelligence` | Email intelligence for the SAGE ecosystem: Gmail analysis, project monitoring, summaries, and approval-gated drafts. |
| `SAGE-EventKit` | Premium event toolkit web application for one-time purchases, secure activation, and reusable event deliverables. |
| `SAGE-Lead-Gen-Studio` | Standalone lead-generation products and business tools designed for useful delivery and one-time sales. |
| `SAGE-Barber-Template-Studio` | Barbering consultation forms, shop workflows, service menus, price lists, and marketing templates. |
| `SAGE-Leveling-to-the-West` | Gamified martial arts and fitness progression app with skill paths, training logs, mobility, conditioning, and recovery tracking. |
| `NOMSHU-DO` | Martial arts learning framework and personal training curriculum documenting fundamentals, principles, progression, and safe practice. |
| `BLAZEFORCE-Training-System` | Safe conditioning and athletic-development concept focused on fitness tracking, controlled progression, and recovery. |
| `BBR-X` | Beach Buggy Racing enhancement concept covering Windows delivery, competitive progression, and expanded multiplayer design research. |
| `NEXUS-Gaming-Platform` | Gaming ecosystem concept combining a unified game library, launcher-style experience, and PC performance tooling. |
| `SAGE-Gaming-Network-NG` | Nigeria-focused gaming connectivity and network-service concept covering latency measurement, market research, and technical feasibility. |
| `Altair-AC-Modding-Lab` | Research and tooling for modding the original Assassin's Creed game through available modding interfaces and a custom workflow. |

## Existing project notes

- **S.A.G.E:** README documents the core loop, SQLite memory, skill routing, OpenAI gateway, local HTTP API, and permission/audit layer.
- **SAGE OS:** README documents v3.6.4 Customization Studio and outstanding native Windows validation.
- **SAGE FORGE:** README documents a staged v9.5.2 source import and explicitly says the full 576-file application source tree is not yet in that branch.
- **SAGE Droid and Base-SAGE:** Their current README files are minimal and need implementation audits.

## Repository factory

[Open the Create Planned SAGE Project Repositories workflow](https://github.com/wukong0060/SAGE-business/actions/workflows/create-project-repositories.yml)

The workflow is manual-only. It requires typing `CREATE`, defaults new repositories to private, skips exact-name repositories that already exist, and adds a starter README. It does not modify or delete existing repositories.

### Required Actions secret

Add `SAGE_REPO_CREATOR_TOKEN` under [SAGE-business Actions secrets](https://github.com/wukong0060/SAGE-business/settings/secrets/actions). Use a fine-grained token owned by `wukong0060` with **Repository creation: write** and **Contents: write** permissions, or a classic token with the required `repo` scope. Never put the token in chat or source files.

## Operating rules

1. Preserve existing repositories and history.
2. One distinct planned project gets one dedicated repository.
3. Shared features remain modules unless separately listed as independent projects.
4. Use SAGE-business for cross-project planning and coordination.
5. Never commit API keys, populated `.env` files, personal data, proprietary game binaries/assets, or private replay recordings.
6. Update this index as project names, scope, status, or repository assignments change.

Structured catalogue: [projects.json](./projects.json).
