# ALTER.md

Rules for AI agents contributing to this Alter documentation repository.

## About This Project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## 1) First Principles

- Follow progressive disclosure.
- Keep `SKILL.md` short and routing-focused.
- Put detailed content in `references/`, `how-to/`, `guides/`, `use-cases/`, and `common-issues/`.
- Do not invent product facts. If unsure, mark as needing verification.

## 2) Content Placement

- `references/`: stable canonical information and FAQs.
- `how-to/`: short task instructions.
- `guides/`: full walkthroughs.
- `use-cases/`: scenario playbooks.
- `common-issues/`: symptoms, causes, fixes, verification.

When adding a new file, update the relevant `INDEX.md`.

## 3) Assets And Links

- Bundle media under `images/` directory.
- In docs, reference media with relative paths (e.g., `/images/getting-started/open-notch.gif`).
- Use local asset paths, not external URLs.

## 4) Writing Quality

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- AI-assisted content is welcome, but must be fact-checked.
- Avoid low-signal filler or repetitive "AI slop".
- Keep answers digestible and useful for the community.
- External resources (social posts, YouTube, personal blogs) are allowed when clearly relevant.

## 5) Templates And Naming

- Use folder templates prefixed with `_`, for example `_TEMPLATE.md`.
- Keep filenames descriptive and kebab-case.

## 6) Commits

Use [Conventional Commits](https://www.conventionalcommits.org/).

Examples:

- `docs(guides): add callback integration examples`
- `fix(common-issues): clarify device-limit troubleshooting`
- `chore(assets): add callback screenshot to manifest`

## Terminology

- Use "workspace" not "project"
- Use "action" for AI-powered tasks
- Use "context" for files/app data sent to AI

## Content Boundaries

- Document user-facing features only
- Don't document internal admin features
- Keep troubleshooting focused on common user issues
