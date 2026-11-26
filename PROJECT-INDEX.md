# SAGE Master Project Index

**Owner:** [wukong0060](https://github.com/wukong0060)  
**Reviewed:** 26 November 2026  
**Repository policy:** Six existing repositories only. No new repositories are to be created for the projects listed here.

This is the central map for SAGE's existing codebases and the additional projects discussed in ChatGPT. A project assigned to `SAGE-business` is being tracked as a plan, product specification, or research track there. That does **not** mean a separate application or implementation already exists.

## Existing GitHub repositories

| Repository | Role | What belongs here |
|---|---|---|
| [S.A.G.E](https://github.com/wukong0060/S.A.G.E) | Core AI platform | Assistant runtime, orchestration, memory, skills, Mail Intelligence integration, voice/perception/HUD modules |
| [SAGE-business](https://github.com/wukong0060/SAGE-business) | Business and project hub | This index, product specifications, project planning, market research and business experiments |
| [SAGE-OS-](https://github.com/wukong0060/SAGE-OS-) | Windows platform | PC optimization, customization, diagnostics and safe performance profiles |
| [SAGE-Droid](https://github.com/wukong0060/SAGE-Droid) | Android platform | Android SAGE, Termux Companion, diagnostics and device modules |
| [SAGE-Brawlhalla-Trainer](https://github.com/wukong0060/SAGE-Brawlhalla-Trainer) | SAGE FORGE | Brawlhalla trainer, replay review, coaching, training labs and analytics |
| [Base-SAGE](https://github.com/wukong0060/Base-SAGE) | App-builder platform | Base44-style AI/no-code app-builder competitor |

## Project portfolio

### Core AI and assistant systems

- **S.A.G.E Core Assistant** → [S.A.G.E](https://github.com/wukong0060/S.A.G.E). Personal AI runtime, orchestration, persistent memory, skills, LLM gateway, local API and permission/audit layer.
- **SAGE Mail Intelligence** → [S.A.G.E](https://github.com/wukong0060/S.A.G.E). Planned module for read-only Gmail intelligence, project monitoring, thread summaries and approval-gated drafts. It does not get its own repository.
- **SAGE Droid / Termux Companion** → [SAGE-Droid](https://github.com/wukong0060/SAGE-Droid). Android companion, diagnostics and modular device tooling.

### Operating systems and gaming tools

- **SAGE OS** → [SAGE-OS-](https://github.com/wukong0060/SAGE-OS-). Windows optimization, customization, PC diagnostics and gaming-performance tooling.
- **SAGE FORGE / Brawlhalla Trainer** → [SAGE-Brawlhalla-Trainer](https://github.com/wukong0060/SAGE-Brawlhalla-Trainer). Replay analysis, AI coaching research, fundamentals, pro training, movement, dodge/counterplay, edgeguard and weapon labs.
- **NEXUS Gaming Platform** → [SAGE-business planning](https://github.com/wukong0060/SAGE-business). Gaming launcher/library platform and PC optimization ecosystem; concept stage.
- **BBR-X** → [SAGE-business planning](https://github.com/wukong0060/SAGE-business). Beach Buggy Racing enhancement concept; research and planning only at this stage.
- **SAGE Gaming Network NG** → [SAGE-business planning](https://github.com/wukong0060/SAGE-business). Nigeria-focused gaming connectivity concept; feasibility and market research.

### App builder and commercial products

- **Base-SAGE** → [Base-SAGE](https://github.com/wukong0060/Base-SAGE). Base44-style AI app builder/platform.
- **SAGE EventKit** → [SAGE-business planning](https://github.com/wukong0060/SAGE-business). Premium event toolkit with one-time customer purchase and activation.
- **SAGE Lead Generation Tools** → [SAGE-business planning](https://github.com/wukong0060/SAGE-business). Small practical lead-generation products.
- **SAGE Barber Template Studio** → [SAGE-business planning](https://github.com/wukong0060/SAGE-business). Barber forms, price lists, workflows and digital templates.
- **SAGE Digital Business Portfolio** → [SAGE-business](https://github.com/wukong0060/SAGE-business). Umbrella for product ideas, launch plans, pricing and distribution.

### Training, lifestyle and creative projects

- **SAGE Leveling to the West** → [SAGE-business planning](https://github.com/wukong0060/SAGE-business). Gamified martial arts and fitness app concept; specifications and design planning live here until implementation is assigned to an existing codebase.
- **Altair / Assassin's Creed Modding Lab** → [SAGE-business planning](https://github.com/wukong0060/SAGE-business). Research and design for modding the original game through available modding interfaces. No proprietary game binaries or assets should be committed.

## Repository facts and handoff notes

- The S.A.G.E README documents a working core loop, SQLite memory, skill routing, OpenAI gateway, local HTTP API, and permission/audit layer.
- The SAGE OS README documents the v3.6.4 Customization Studio, while noting that native Windows GUI/build validation remains outstanding.
- The SAGE FORGE README documents a staged v9.5.2 source import. It explicitly says the full 576-file application source tree is not yet in that GitHub branch.
- The SAGE Droid and Base-SAGE README files are currently minimal and should be expanded as their current implementation details are reviewed.
- A repository being used as a planning home is not proof that its planned project is implemented.

## Operating rules

1. Keep the six repositories. Do not generate a repository per idea.
2. Put cross-project planning and business specifications in `SAGE-business`.
3. Keep implementation code in the appropriate existing product repository.
4. Before moving code or restructuring directories, inspect the actual source tree and preserve history.
5. Never commit API keys, populated `.env` files, private data, proprietary game binaries/assets, or personal replay recordings.
6. Update this index when a project is renamed, merged, paused, or moved.

The structured companion file is [projects.json](./projects.json).
