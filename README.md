# {{REPO_NAME}}

A code repository template for software and tooling projects under clouatre-labs: REUSE compliance, Conventional Commits enforcement with a `CI Result` aggregate check, security hardening workflows, and AI agent scaffolding. Language-neutral by design; document the chosen language stack in `docs/REPO-STANDARDS.md` and `AGENTS.md` as the codebase lands.

## Quickstart

1. Clone the repository and install [gh](https://cli.github.com/); authenticate with `gh auth login`.
2. Run the bootstrap script to create standard labels and print the branch ruleset command:

   ```bash
   bash scripts/bootstrap.sh
   ```

3. Fill in the project placeholders: `{{REPO_NAME}}` in this README, the project overview and stack commands in `AGENTS.md`, and the contact URLs in `.github/ISSUE_TEMPLATE/config.yml`.
4. Open a feature branch and start contributing (see [CONTRIBUTING.md](CONTRIBUTING.md)): Conventional Commits, GPG signature, DCO sign-off, and REUSE SPDX headers on new files.

## Architecture

The architecture diagram convention is documented in [docs/diagrams/README.md](docs/diagrams/README.md): the diagram source is committed alongside its rendered `.svg`. No architecture diagram exists yet; add `docs/diagrams/architecture.*` as the codebase takes shape.

## Repository Standards

See [docs/REPO-STANDARDS.md](docs/REPO-STANDARDS.md) for the full artifact map, the security hardening reference, and where language-specific configuration (build tool, linters, dependency deny list) belongs once a stack is chosen.
