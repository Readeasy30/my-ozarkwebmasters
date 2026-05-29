# CODEX-WORKFLOW.md

Last updated: 2026-05-29

## Operating workflow

Use ChatGPT 5.5 and Codex as the production workflow.

No local Git. No terminal Git. No VS Code requirement. No manual file creation, replacement, or paste updates.

Workflow:

1. ChatGPT 5.5 manages the plan.
2. Codex performs repository work.
3. GitHub stores files and commits.
4. Cloudflare Pages publishes from GitHub when connected.

## Main rule

Codex should handle repository file work directly.

Do not ask Gerry to paste, create, replace, or manually update repo files.

Work in useful batches. Report only after several commits or a real blocker.

## Use Codex for

- multi-file updates
- repo audits
- HTML/CSS/JS fixes
- README/status/workflow files
- sitemap.xml and robots.txt
- SEO metadata
- navigation/footer cleanup
- safe content pages
- service page planning
- local SEO planning
- project queue continuation

## Use ChatGPT GitHub connector for

- small direct file updates
- repo checks
- status verification
- emergency fixes
- when Codex is awkward or blocked

## Safe work allowed

- README updates
- AGENTS.md updates
- CODEX-WORKFLOW.md updates
- CODEX-CURRENT-TASK.md updates
- PROJECT-STATUS.md updates
- CHANGELOG.md updates
- HTML/CSS/JS fixes
- navigation/footer fixes
- sitemap.xml
- robots.txt
- titles/meta/canonical URLs
- accessibility/mobile improvements
- safe content pages
- documentation cleanup
- local business/service copy drafts
- manual test checklists

## Do not add without direct approval

- API keys
- private keys
- live ads
- tracking scripts
- payment setup
- affiliate links
- public AI tools
- upload systems
- user accounts
- ordering integrations
- framework rebuilds
- major code deletion

## Cloudflare Pages

Cloudflare only connects to GitHub and publishes.

Recommended setup:

- Production branch: main
- Build command: blank
- Output directory: .
- No manual Cloudflare file uploads

## If blocked

Record the blocker in `PROJECT-STATUS.md` if possible.

Move to the next safe task or next repository. Do not ask Gerry to do manual file work.
