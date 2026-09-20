# FM CodeRabbit + OpenCode Review Protocol

## Purpose
Use two independent layers for FM-safe changes: CodeRabbit for independent PR review and OpenCode for controlled analysis/fixes.

## Review sequence

1. **PR opened — CodeRabbit**
   - Review once after the initial PR commit.
   - Check correctness, bugs, security, regressions, maintainability, and obvious test gaps.
   - Do not repeatedly trigger reviews for the same unchanged commit.

2. **PR opened — OpenCode read-only review**
   - Use the `review` agent.
   - Confirm intended behavior, risks, affected files, governance constraints, and test coverage.
   - No file edits, commits, pushes, or destructive actions.

3. **After fixes / new commit — CodeRabbit**
   - Review the updated commit when substantive code changes were made.
   - Prioritize newly changed areas and unresolved findings.

4. **Before merge — OpenCode verification**
   - Re-check the final diff and CI result.
   - Confirm no unexpected files or permission changes.
   - Confirm the requested FM safety controls remain intact.

5. **Merge**
   - Merge only after required CI/reviews are satisfied and the current PR head SHA is verified.
   - Preserve history; do not use destructive conflict resolution.

## Role boundary

- **CodeRabbit:** independent reviewer; findings/comments.
- **OpenCode review agent:** read-only analysis.
- **OpenCode build/fix agent:** only after explicit approval; changes must go through the normal PR + CI path.
- **Human approval:** required for production/destructive/governance-sensitive actions.

## Rate-limit rule

If CodeRabbit is rate-limited, do not spam manual review triggers. Continue with OpenCode read-only analysis and CI, then request CodeRabbit again on the next substantive commit/window.

## Required evidence before merge

- Current PR head SHA verified.
- CI checks successful.
- CodeRabbit review/findings checked when available.
- OpenCode read-only review completed.
- No unresolved critical safety issue.
