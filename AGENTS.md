# Agent instructions — tiantech-content-agent

## TianTech GitHub & AI Engineering Standard (organization policy)

- Default GitHub organization is `TiantechDev` (https://github.com/TiantechDev). Use `kaptangece53` only for explicitly personal or legacy references. Verify repository and branch before any write.
- Prefer the connected GitHub Agent for inspection, focused edits, commits and pull requests. Use GitHub CLI for unsupported administration only; avoid unnecessary user-side commands.
- Use Codex only when substantial software engineering, complex debugging or multi-file refactoring requires it. Read only task-relevant files and context, avoid repeat repository-wide scans, and keep responses concise.
- Use included, verified GitHub Enterprise features where helpful. Never activate paid add-ons, new licenses, metered usage or billing without explicit user approval.
- Keep GitHub Actions runner consumption minimal, preserve manual execution preferences, and do not trigger workflows for documentation-only work. Do not change workflow triggers without assessing impact.
- Never deploy production, publish releases, modify DNS, rotate live secrets or change production access without explicit authorization.
- Follow least privilege, protect secrets and confidential data, and respect branch protection, review requirements and environment policies.
- Make changes minimal, testable and reversible. Preserve repository-specific `AGENTS.md`, nested rules, architecture documents and established workflows; if conflicts arise, report them rather than silently overriding safeguards.
- First verify current state, avoid repeating confirmed research or already-successful tests, and run only relevant validation. Report completed changes, verification, checks not run, and remaining risks.
