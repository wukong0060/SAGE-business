# SAGE Business & Project Hub

Central coordination hub for the SAGE ecosystem.

## Master Project Portfolio

**[Open SAGE Master Project Index](./PROJECT-INDEX.md)**

The current portfolio catalogue contains:
- 6 existing repositories verified through the connected GitHub owner listing
- 17 planned project repositories, including additional projects found in Gmail
- Gmail-only external GitHub invitations, listed separately because ownership and acceptance are not verified
- One project candidate held for review because its email contains a title/reference but no usable brief

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

- [PROJECT-INDEX.md](./PROJECT-INDEX.md): human-readable map of existing and planned repositories, Gmail discoveries, and external invitations.
- [projects.json](./projects.json): structured catalogue consumed by the workflow.

## Scope note

The catalogue is based on the GitHub account listing, retained ChatGPT context, and Gmail project correspondence reviewed so far. It is not a complete account-wide export. Attachments or shared-project links that could not be inspected are flagged for review. A starter repository documents a planned concept; it does not claim that the application is already implemented.
