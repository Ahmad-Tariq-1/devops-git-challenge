# Practical Verification Record

## 1. Repository Commit History
Git provides a record of the changes committed during the project.

Run the following command to display the commit history:
```bash
git log --oneline
```

- 5790a0f (HEAD -> main, origin/main) Merge pull request #1 from Ahmad-Tariq-1/development
- 09fa450 (origin/development, development) fix: resolved merge conflict
- 097c46c (origin/staging, staging) fix: staging label
- cceb3d4 feat: updated script with staging env
- 95a83fd feat: initial commit with deploy script


## 2. Git Reflection Answers

### Q1. Explain Git and GitHub.

Git is a distributed version control system used to track modifications to files and maintain project history. GitHub is a cloud-based platform that hosts Git repositories and helps developers collaborate. Git manages versions locally, while GitHub makes repositories accessible online.

### Q2. Describe the three stages of Git.

The Working Directory contains the current project files and any modifications. The Staging Area holds changes prepared for the next commit. The Local Repository saves committed versions of the project and maintains a history of previous changes.

### Q3. Compare `git stash pop` with `git stash apply`.

The `git stash pop` command restores saved changes and normally removes the corresponding stash entry when application succeeds. In contrast, `git stash apply` restores the changes while retaining the entry. Both commands are useful for temporarily putting unfinished work aside.

### Q4. Compare `git fetch` with `git pull`.

The `git fetch` command retrieves updates from a remote repository without merging them into the current branch. The `git pull` command retrieves remote changes and integrates them into the current branch. Fetch is useful for checking updates first, whereas pull is used to bring the local branch up to date.
