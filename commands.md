# Git Commands Cheat Sheet

| Command | Description |
|---------|-------------|
| `git config --global user.name "Your Name"` | Set global username |
| `git config --global user.email "your.email@example.com"` | Set global email |
| `git init` | Initialize a new Git repository |
| `git clone <repo-url>` | Clone a remote repository |
| `git status` | Show current status of files |
| `git add <file>` | Stage a specific file |
| `git add .` | Stage all changes |
| `git commit -m "message"` | Commit staged changes with a message |
| `git log` | Show commit history |
| `git log --oneline` | Show compact commit history |
| `git branch <branch>` | Create a new branch |
| `git checkout <branch>` | Switch to another branch |
| `git switch <branch>` | Switch to another branch (new syntax) |
| `git checkout -b <branch>` | Create and switch to a new branch |
| `git merge <branch>` | Merge a branch into the current one |
| `git branch -d <branch>` | Delete a branch |
| `git branch -D <branch>` | Force delete a branch |
| `git pull` | Fetch and merge latest changes from remote |
| `git pull origin <branch>` | Pull from specific branch |
| `git push origin <branch>` | Push changes to remote branch |
| `git remote add origin <repo-url>` | Set remote repository |
| `git remote remove origin` | Remove remote repository |
| `git stash` | Save changes temporarily |
| `git stash apply` | Apply last stashed changes |
| `git stash list` | List all stashes |
| `git revert <commit-hash>` | Revert a commit |
| `git reset --hard <commit-hash>` | Reset repository to specific commit |
| `git diff` | Show unstaged changes |
| `git diff <branch1> <branch2>` | Show differences between two branches |

---
✅ **Tip:** Always run `git status` before committing to see what will be staged.
