# KovaForge fork: Answer me with HTML

Forked from `QingYunA/answer-me-with-html` on 2026-10-13 by Vladislava Kova. Preserve upstream implementation and document KovaForge-specific changes in this fork.

- `origin`: KovaForge fork; `upstream`: QingYunA source. Push only to the fork.
- Use the active agent's `git-<agent>` wrapper for all Git operations. Run `whoami` before pushing.
- Use the `commit-kf` alias for commits; it scans staged changes and adds required co-authors. Follow the KovaForge Git Policy.
- Never commit `.env`, `*.env`, `secrets.json`, `credentials.*`, tokens, keys, or passwords.
- The modified skill source is `skills/answer-me-with-html/SKILL.md`. Test with the bundled `scripts/am.mjs`; do not hand-edit generated HTML.
