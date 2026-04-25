# Project Skills and Working Rules

## DevOps Collaboration

- Address the project owner as Donald.
- Explain each task before changing files.
- Keep explanations beginner-friendly and concrete.
- Point out mistakes respectfully, explain why they matter, and describe the fix.
- Work only inside this workspace unless Donald provides and approves an external path.

## Git Workflow

- Always check the current branch before making changes.
- Never work directly on default branches such as `main`, `master`, `develop`, or `trunk`.
- Use feature branches that start with `feature/`.
- Current documentation branch: `feature/project-documentation`.
- Use clear commit messages that describe the reason for the change.
- When Donald says `push`, `commit and push`, or `push commit and push`, stage the relevant changes, commit, and push without asking for confirmation.

## Safety Rules

- Do not delete existing files or directories unless Donald explicitly approves.
- Do not make unrelated changes.
- Do not modify secrets, credentials, keys, or environment files unless Donald explicitly asks.
- If a requirement is unclear and a safe assumption is not obvious, ask before changing files.

## Documentation Habits

- Keep `SKILLS.md` updated with working rules, project conventions, useful commands, and lessons learned.
- Keep `MEMORY.md` updated with project-specific context, decisions, branch names, deployment notes, and important reminders.
- Before changes, explain:
  - What was found
  - What will change
  - Why the change is needed
  - Which files are affected
- After changes, explain:
  - What changed
  - Why it changed
  - How to test it
  - A DevOps lesson from the work

## Useful Commands

Check the current branch:

```powershell
git branch --show-current
```

Check local changes:

```powershell
git status --short
```

Create and switch to a feature branch:

```powershell
git switch -c feature/example-branch-name
```

Stage documentation changes:

```powershell
git add SKILLS.md MEMORY.md
```

Commit staged changes:

```powershell
git commit -m "Add project working documentation"
```

Push the current branch:

```powershell
git push -u origin feature/project-documentation
```

## DevOps Lessons Learned

- A default branch is the stable shared branch. Feature work should happen on a separate branch so it can be reviewed before merging.
- A clean `git status` means there are no uncommitted tracked or untracked changes.
- Documentation is part of DevOps because it makes repeated work safer, clearer, and easier to hand off.
