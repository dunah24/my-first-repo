# Project Memory

## People and Communication

- Project owner: Donald Unah.
- Refer to the project owner as Donald.
- Donald is learning DevOps, so explanations should be clear, practical, and beginner-friendly.

## Repository Context

- Workspace path: `C:\Users\unahd\OneDrive\Documents\New project`.
- Git default branch observed: `master`.
- Do not make changes on `master`.
- Documentation setup branch: `feature/project-documentation`.
- Initial repository state had no visible project files besides `.git`.

## Standing Decisions

- Feature branches must start with `feature/`.
- Do not delete files or directories that were not created during the current task without explicit approval.
- Do not modify secrets, credentials, keys, or environment files without explicit approval.
- Keep work scoped to the current request.
- Keep `SKILLS.md` and `MEMORY.md` updated as project rules and decisions evolve.

## Repeated Instructions

- Before file changes, explain what was found, what will change, why it matters, and which files are affected.
- After file changes, explain what changed, why it changed, how Donald can test it, and the DevOps lesson.
- If Donald asks to push or commit and push, commit and push directly without asking for confirmation.

## Notes

- Creating a feature branch may require elevated permission because the sandbox can block writes to Git metadata such as `.git/HEAD.lock`.
