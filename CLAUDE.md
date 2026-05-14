# Git Branch Policy

Always commit and push directly to the `main` branch. Never create new branches unless explicitly asked by the user.

# Pull Request Policy

Whenever a PR is created (by you or by the system), immediately enable auto-merge on it using `mcp__github__enable_pr_auto_merge` with `mergeMethod: SQUASH`. Do this without asking the user.
