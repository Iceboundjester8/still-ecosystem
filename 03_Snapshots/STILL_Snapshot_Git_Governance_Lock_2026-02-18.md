# STILL — SNAPSHOT — GIT GOVERNANCE LOCK
Date: 2026-02-18
Status: ACTIVE
Repo Root (Source-of-Truth): C:/Users/Archon/Desktop/Still/[Still-Eco]/Still

## What is enforced
- PRs required to merge into main (branch protection).
- Status checks required: Codex Enforcement / enforce
- PR body must include Final Gate checklist + checkbox lines.
- Hard-cut term scan active (excluding governance/snapshot directories to prevent self-trips).
- Direct pushes to main restricted.
- Force-push blocked; branch deletion prevented.

## Files involved
- .github/workflows/codex-enforce.yml
- .github/pull_request_template.md

## Notes
- Paths containing [Still-Eco] require -LiteralPath in PowerShell for file cmdlets.
