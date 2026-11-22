> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- ChameleonDB, not "Chameleon"
- Schema Vault, with capitalized Vault
- integrity mode, in code formatting for values such as `readonly`
- `CHAMELEON.md`, not `README.md`, for the generated project guide
- mode password, not "admin password"
- machine-readable JSON, not "structured output"

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Use only behavior that is implemented or explicitly marked Planned or Future
- Name security threat limits; do not describe local modes or hashes as prevention or tamper-proof security

## Content boundaries

- Follow [ADR-0002](https://github.com/chameleon-db/chameleondb/blob/main/docs/adr/0002-honest-claims-policy.md): every public claim needs backed implementation or tests
- Mark roadmap features as Planned and never describe them in the present tense
- Keep release and CLI claims tied to the tested binary and the source commit
- Document credential separation and database roles honestly; local integrity modes are guards, not access control
