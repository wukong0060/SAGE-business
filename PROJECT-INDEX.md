# SAGE Master Project Index

**GitHub owner:** [wukong0060](https://github.com/wukong0060)  
**Sources reviewed:** Existing GitHub repositories, retained ChatGPT context, and Gmail project correspondence  
**Repository policy:** Keep all existing repositories and create dedicated repositories for distinct planned projects. Do not duplicate a project that is already assigned to an existing codebase.

> This is a working inventory, not a complete export of every ChatGPT conversation, Gmail message, shared project, or attachment. Projects based only on an archive name or shared-project notification are marked for source review. A planned repository is not proof that the project is already implemented.

## Existing repositories

| Repository | Visibility | Responsibility |
|---|---|---|
| [S.A.G.E](https://github.com/wukong0060/S.A.G.E) | Private | Core AI, orchestration, memory, skills, API, permissions and audit |
| [SAGE-business](https://github.com/wukong0060/SAGE-business) | Public | Business hub, master index, cross-project planning and specifications |
| [SAGE-OS-](https://github.com/wukong0060/SAGE-OS-) | Public | Windows optimization, customization and PC performance tooling |
| [SAGE-Droid](https://github.com/wukong0060/SAGE-Droid) | Private | Android SAGE platform, Termux Companion and device modules |
| [SAGE-Brawlhalla-Trainer](https://github.com/wukong0060/SAGE-Brawlhalla-Trainer) | Private | SAGE FORGE, Brawlhalla replay analysis, coaching and training tools |
| [Base-SAGE](https://github.com/wukong0060/Base-SAGE) | Public | Base44-style AI/no-code app builder platform |

## Planned projects with dedicated repositories

There are now **17 planned repositories** in the creation catalogue. New repositories default to private.

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
| `SAGE-Business-OS` | SAGE Business OS product and application, with a referenced 7.0.0 production package requiring source verification and import. |
| `Sonic-Atlas-Gaming` | Game development project associated with a Sonic Atlas Gaming source archive; original source needs review before its scope can be documented. |
| `Shunom-The-Unbound` | Original PC fighting-game project with Shunom as a featured character and a data-driven character, match-session, UI, animation, and rendering architecture. |
| `GOH-Roblox-Battlegrounds` | Roblox battlegrounds game-design project inspired by God of High School, with ranked PvP, battlegrounds, tournaments, progression, and a full game-design document. |
| `Kotodama-Manga` | Original manga project titled Kotodama, with an existing text manuscript attachment to be organized into a versioned creative-writing workspace. |
| `Chess-Variant-Game` | Game-design research project exploring ways to improve or extend the classic chess experience; the full shared design brief still needs review. |

## Gmail discoveries added in this revision

- **SAGE Business OS:** A message references a 7.0.0 production archive and companion SHA-256 file. This is separate from the SAGE-business planning hub; source import and checksum verification are required.
- **Sonic Atlas Gaming:** A source archive named `Sonic_Atlas_Gaming_Source.zip` was identified. Its contents were not accessible through the Gmail message view, so the project scope must be established by auditing the archive.
- **Shunom: The Unbound:** A character-sheet attachment and a game-architecture handoff identify a separate original PC fighting-game project. Its repository README documents abstract video-game systems only, not real-world fighting instruction.
- **God of High School-inspired Roblox battlegrounds:** A design inquiry documents Ranked PvP, Battlegrounds, Tournaments, progression, character/power design, and UI. Treat as a fan-concept until rights are established; prefer original IP and assets.
- **Kotodama:** A Gmail note calls this the user's manga and includes a `Kotodama.txt` manuscript attachment.
- **Chess Variant Game:** A shared-project notification identifies a design inquiry about improving on chess. The complete shared design artifact still needs review.

## Items deliberately not queued yet

| Candidate | Why it is pending |
|---|---|
| Teller Town Autumn / Pokkén Tournament | Gmail contains a title/reference but no clear brief or build request. Keep it visible until its intended scope is confirmed. |

## External GitHub invitations found in Gmail

These appear in invitation notifications but are not confirmed as repositories owned by this account. They are **not** included in the new-repository creation workflow.

- `NIIT-Port-Harcourt/intro-to-git-and-github-KingJin0060`
- `NIIT-Port-Harcourt/react-dashboard-support-page-KingJin0060`
- `Teekay-Dev/Bunnix`

Invitation notification does not prove acceptance or current access. Check the GitHub invitations page before treating these as part of the owned-repository inventory.

## Existing project notes

- **S.A.G.E:** README documents the core loop, SQLite memory, skill routing, OpenAI gateway, local HTTP API, and permission/audit layer.
- **SAGE OS:** README documents v3.6.4 Customization Studio and outstanding native Windows validation.
- **SAGE FORGE:** README documents a staged v9.5.2 source import and explicitly says the full 576-file application source tree is not yet in that branch.
- **SAGE Droid and Base-SAGE:** Their current README files are minimal and need implementation audits.

## Repository factory

[Open the Create Planned SAGE Project Repositories workflow](https://github.com/wukong0060/SAGE-business/actions/workflows/create-project-repositories.yml)

The workflow is manual-only. It requires typing `CREATE`, defaults new repositories to private, skips exact-name repositories that already exist, and adds a starter README. It does not modify or delete existing repositories.

### Required Actions secret

Add `SAGE_REPO_CREATOR_TOKEN` under [SAGE-business Actions secrets](https://github.com/wukong0060/SAGE-business/settings/secrets). Use a fine-grained token owned by `wukong0060` with **Repository creation: write** and **Contents: write** permissions, or a classic token with the required `repo` scope. Never put the token in chat or source files.

## Operating rules

1. Preserve existing repositories and their Git history.
2. One distinct planned project gets one dedicated repository.
3. Shared features remain modules unless separately listed as independent projects.
4. Keep cross-project planning and portfolio coordination in SAGE-business.
5. Never commit API keys, populated `.env` files, personal data, proprietary game binaries/assets, or private replay recordings.
6. Review source archives before describing features or implementation status.
7. Update this index as project names, scope, status, or repository assignments change.

Structured catalogue: [projects.json](./projects.json).
