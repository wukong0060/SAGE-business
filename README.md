# SAGE Business & Project Hub

Central coordination hub for the SAGE ecosystem.

## Master Project Portfolio

**[Open SAGE Master Project Index](./PROJECT-INDEX.md)**

The index distinguishes six existing repositories from eleven planned projects that each have a dedicated repository entry and starter README queued for creation.

## Repository Factory

**[Open Create Planned SAGE Project Repositories](https://github.com/wukong0060/SAGE-business/actions/workflows/create-project-repositories.yml)**

Manual-only workflow. It requires the `SAGE_REPO_CREATOR_TOKEN` Actions secret, confirmation value `CREATE`, and a visibility choice. New repositories default to private. Existing repositories are skipped, never deleted or overwritten.

### One-time token setup

1. Create a fine-grained personal access token owned by `wukong0060`.
2. Grant **Repository creation: write** and **Contents: write** permissions.
3. Open [SAGE-business Actions secrets](https://github.com/wukong0060/SAGE-business/settings/secrets).
4. Add repository secret `SAGE_REPO_CREATOR_TOKEN` and paste the token value there. Never commit or share the token.
5. Open the workflow above, select **Run workflow**, enter `CREATE`, and choose visibility. Private is the default.

## Catalogue files

- [PROJECT-INDEX.md](./PROJECT-INDEX.md): human-readable map of existing and planned repositories.
- [projects.json](./projects.json): structured catalogue consumed by the workflow.

## Scope note

The catalogue is based on project details available in retained ChatGPT context and recent discussions, not a complete account-wide export. A starter repository documents a planned concept; it does not claim that the application is already implemented.
