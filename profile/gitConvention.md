# Git Conventions

## Branch Naming Convention

Use the following format:

`your-name/feature-or-task`

**Example:**  
If Alicia is going to fix code related to the goal point:

`alicia/goal_fix`

---

## Issue Convention

Use the following format:

`Feature #IssueNumber`

- Use the issue number automatically assigned when the GitHub Issue is created.

---

## Commit Convention

Use the following format:

`[CommitTag] : Description #IssueNumber`

**Example:**

`add : Add a new code file for the goal algorithm #1`

### Commit Tags

- `add` : Add a new file
- `feat` : Add a new feature to an existing file
- `fix` : Fix a feature or bug
- `docs` : Update documentation (e.g., README files)
- `comment` : Add or update comments
- `test` : Add test code or refactoring tests
- `merge` : Merge another branch
- `refactor` : Refactor code, including changes to types or variable names
- `style` : Change code style without changing functionality
- `remove` : Remove code, files, or resources
- `setting` : Change the package or project structure

---

## Pull Request (PR) Convention

Use the following format:

`Feature / Description of Work`

---

## Pull Request & Merge Workflow

1. Create a new branch.
2. Complete your work, then `add`, `commit`, and `push` your changes.
3. Create a Pull Request (PR).
4. Continue working and committing changes to the same branch if necessary.
5. Once the feature or task is complete, request a code review.
6. Every team member except the author should review the changes.
7. Merge the PR after all team members have reviewed and approved it.
8. Let the team know that the PR has been merged.
9. All team members should `pull` the latest changes from `main` before continuing their work.