# SAGE Business & Project Hub

Central index for the SAGE project portfolio and its repository-creation workflow.

## One-link project factory

**[Open the Project Factory workflow](https://github.com/wukong0060/SAGE-business/actions/workflows/create-project-repositories.yml)**

The workflow reads [projects.json](./projects.json), creates the missing repositories under `wukong0060`, initializes each with a project README, and skips exact-name repositories that already exist.

### One-time setup

1. Create a GitHub personal access token with permission to create repositories and write repository contents. For a fine-grained token, grant **Repository creation: write** and **Contents: write**, with access that covers the repositories the token must manage. A classic token needs the `repo` scope for private repositories.
2. In this repository, open **Settings → Secrets and variables → Actions**.
3. Add a repository secret named `SAGE_REPO_CREATOR_TOKEN` and paste the token value. Never put the token in a source file or commit it.
4. Open the [Project Factory workflow](https://github.com/wukong0060/SAGE-business/actions/workflows/create-project-repositories.yml), select **Run workflow**, type `CREATE`, and choose visibility. The default is **private**.

The workflow is manual-only. It will not create repositories just because this file is updated. Existing repositories are not modified. Repositories with matching names are skipped.

For details, see GitHub's [Create a repository REST API documentation](https://docs.github.com/en/rest/repos/repos#create-a-repository-for-the-authenticated-user).

## Existing repositories

| Repository | Project |
|---|---|
| [S.A.G.E](https://github.com/wukong0060/S.A.G.E) | Core AI assistant and orchestration |
| [SAGE-business](https://github.com/wukong0060/SAGE-business) | Business and project hub |
| [SAGE-OS-](https://github.com/wukong0060/SAGE-OS-) | Windows / PC optimization |
| [SAGE-Droid](https://github.com/wukong0060/SAGE-Droid) | Android assistant and device optimization |
| [SAGE-Brawlhalla-Trainer](https://github.com/wukong0060/SAGE-Brawlhalla-Trainer) | SAGE FORGE / Brawlhalla trainer |
| [Base-SAGE](https://github.com/wukong0060/Base-SAGE) | Base44-style app builder concept |

## Repositories queued for creation

| Repository | Project |
|---|---|
| `SAGE-EventKit` | Premium event toolkit, one-time purchase |
| `SAGE-Mail-Intelligence` | Gmail intelligence and approval-gated drafts |
| `SAGE-Leveling-to-the-West` | Gamified martial arts and fitness progression app |
| `BBR-X` | Beach Buggy Racing enhancement concept |
| `NEXUS-Gaming-Platform` | Gaming launcher, library, and PC optimization concept |
| `SAGE-Gaming-Network-NG` | Nigeria-focused gaming connectivity concept |
| `Altair-AC-Modding-Lab` | Original Assassin's Creed modding research and tooling |
| `SAGE-Barber-Template-Studio` | Barbering templates and digital products |

## Catalog scope

This list is based on the project details available in the saved conversation context and recent chats. It is not an export of every conversation in the account. Review [projects.json](./projects.json) before running the workflow if you want to rename, remove, or add projects.

