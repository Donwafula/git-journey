# Git Journey

This repository documents my hands-on practice with Git, GitHub, and basic command-line tools.  
The goal was to understand version control fundamentals and apply them through direct terminal usage.

### What I learned

### 1. Git basics
- `git init` – Initialize a local repository
- `git clone` – Copy a remote repository locally
- `git status` – Check working directory and staging area
- `git add` – Stage changes
- `git commit` – Create a snapshot of staged changes
- `git log` – View commit history
- `git diff` – Compare changes between commits

### 2. Staging variations
- `git add .`
- `git add -A`
- `git add --all`
- `git add <file_name>`
- `git add *`
Understanding the difference between staging specific files vs all tracked/untracked changes.

### 3. Undoing & resetting
- `git reset`
- `git reset HEAD~`
- `git reset --hard`
- `git restore`
- `git restore --staged`
Learned how to safely undo staging and revert working directory changes.

### 4. File removal
- `git rm <file_name>`
- `git rm -f <file_name>`
- `git rm --cached <file_name>`
- `git rm -r <folder>`
Understood the difference between removing from:
- Working directory
- Staging area
- Git tracking only

### 5. Branching & merging
- `git branch`
- `git branch <branch_name>`
- `git checkout <branch_name>`
- `git merge <branch_name>`
- `git checkout <commit_id>`
Practiced:
- Creating feature branches
- Switching branches
- Merging branches
- Working in detached HEAD state
- Resolving merge conflicts

### 6. Remote operations
- `git push origin <branch_name>`
- Pull Requests (GitHub)
Learned:
- How to push local branches to remote
- How to create pull requests
- The role of PRs in collaborative workflows

### 7. Stashing
- `git stash`
- `git stash pop`
- `git stash apply`
- `git stash list`
- `git stash drop`
Used stash to temporarily save work without committing.

### 8. History manipulation
- `git revert`
- `git rebase`
Understood:
- Safe history reversal with `revert`
- Linear history rewriting with `rebase`
- When NOT to rebase (shared branches)

### Command line practice (Vim + Shell)
I also practiced file and directory management:
- `touch` – Create files
- `mkdir` – Create directories
- `rm` – Remove files
- `echo` – Write text into files
- `cat` – Display file contents
Used `vim` as the primary editor for:
- Editing files
- Writing commit messages
- Creating this README

### Conceptual understanding
Through this session, I developed a clear mental model of:
Working Directory → Staging Area → Repository → Remote
Where:
- Working Directory = actual files
- Staging Area = selected changes
- Repository = committed snapshots
- Remote = shared repository on GitHub

### Sample workflow I practiced
1. Create file with `touch`
2. Modify with `vim`
3. Check status
4. Stage changes
5. Commit
6. Create branch
7. Make changes
8. Merge branch
9. Push to GitHub
10. Create Pull Request

### Key takeaways
- Git tracks changes, not files.
- Commits are snapshots.
- Branching enables safe experimentation.
- Staging gives granular control.
- Pull requests enable structured collaboration.
- Rewriting history requires caution.

---

This repository marks the beginning of my version control journey.
