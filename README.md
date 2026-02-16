# Git Skills Lab

This repo is a sandbox for learning Git. Your goal is to complete the tasks below while practicing real Git workflows.  

Do **not** ask for solutions — research, experiment, and read Git docs or guides if you get stuck.

---

## ✅ Checklist of Tasks

### 1. Create a Feature Branch
**Goal:** Practice branching and committing.

- Create a new branch for adding your first “user”.
- Update `data/users.json` with at least one entry.
- Commit your changes with a meaningful commit message.
- Push branch to remote (if connected).
- Research if needed: `git branch`, `git checkout`, `git switch`, `git add`, `git commit`.

---

### 2. Resolve a Merge Conflict
**Goal:** Learn how to handle conflicts.

- Simulate a situation where the same file is changed on two branches.
- Merge branches and resolve conflicts in `data/features.json`.
- Ensure the file remains valid JSON after merging.
- Research if needed: `git merge`, conflict markers, `git status`, `git add`, `git commit`.

---

### 3. Rebase and Squash Commits
**Goal:** Learn how to clean up commit history.

- Make multiple commits on a branch (e.g., multiple changes to `users.json`).
- Rebase your branch onto `main`.
- Squash commits into one clean commit with a meaningful message.
- Research if needed: `git rebase -i`, interactive rebase, squash commits.

---

### 4. Cherry-Pick a Commit
**Goal:** Practice moving a specific commit to another branch.

- Create a branch and make a commit to `features.json`.
- Create another branch from `main`.
- Cherry-pick the commit into the new branch.
- Merge the branch back into `main`.
- Research if needed: `git cherry-pick`, `git log` to find commit hashes.

---

### 5. Recover from a Hard Reset
**Goal:** Learn to recover lost commits safely.

- Make a commit on `main`.
- Simulate a mistake: reset the branch to a previous commit (`git reset --hard`).
- Use Git tools to recover the lost commit.
- Research if needed: `git reflog`, `git checkout <commit>`, recovering lost commits.

---

### 6. Update the Scoreboard
**Goal:** Track your progress.

- For each task you complete, update `scoreboard.json`:
  - Add your name
  - Mark task as completed
  - Update your score
- Keep commits meaningful and clean.

---

## 📚 Research Resources

If you get stuck, check:

- [Git documentation](https://git-scm.com/doc)
- [Atlassian Git tutorials](https://www.atlassian.com/git/tutorials)
- [Interactive Git playground](https://learngitbranching.js.org/)
- Google any Git commands you need, e.g., `git rebase interactive`, `git cherry-pick`, `git reflog`.

---







## ⚠️ Notes

- Experiment freely — this is a sandbox.
- Keep JSON files valid after each edit.
- Commit often, with meaningful messages.
- Your goal is **practice and understanding**, not speed.
