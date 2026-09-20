# FM CodeRabbit + OpenCode Review Protocol

## Purpose

Use two independent layers for FM-safe changes: CodeRabbit for independent PR review and OpenCode for controlled analysis/fixes.

## Review sequence

1. **PR opened — CodeRabbit**
   - Review once after the initial PR commit.
   - Check correctness, bugs, security, regressions, maintainability, and obvious test gaps.
   - Do not repeatedly trigger reviews for the same unchanged commit.
   - CodeRabbit is an advisory review layer, not a merge blocker unless the repository explicitly requires its check.

2. **PR opened — OpenCode read-only review**
   - Use the `review` agent.
   - Confirm intended behavior, risks, affected files, governance constraints, and test coverage.
   - No file edits, commits, pushes, or destructive actions.

3. **After fixes / new commit — CodeRabbit**
   - Review the updated commit when substantive code changes were made.
   - Prioritize newly changed areas and unresolved findings.
   - If CodeRabbit is unavailable or rate-limited, do not delay the PR solely for that review.

4. **Before merge — OpenCode verification**
   - Re-check the final diff and CI result.
   - Confirm no unexpected files or permission changes.
   - Confirm the requested FM safety controls remain intact.

5. **Merge**
   - Merge only after required repository CI/reviews are satisfied and the current PR head SHA is verified.
   - CodeRabbit is non-blocking when unavailable or rate-limited unless its check is explicitly configured as a required repository status check.
   - Preserve history; do not use destructive conflict resolution.

## Role boundary

- **CodeRabbit:** independent advisory reviewer; findings/comments.
- **OpenCode review agent:** read-only analysis.
- **OpenCode build/fix agent:** only after explicit approval; changes must go through the normal PR + CI path.
- **Human approval:** required for production/destructive/governance-sensitive actions.

## Rate-limit rule

If CodeRabbit is rate-limited, do not spam manual review triggers. Continue with OpenCode read-only analysis and CI. Do not hold a PR indefinitely for CodeRabbit. Request CodeRabbit again only on the next substantive commit/window.

## Required evidence before merge

- Current PR head SHA verified.
- Required CI checks successful.
- CodeRabbit review/findings checked when available; absence or rate limiting is not a blocker unless explicitly required by repository rules.
- OpenCode read-only verification completed when the FM workflow requires it and the runtime is available.
- No unresolved critical safety issue.
