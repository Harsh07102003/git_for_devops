# Git Commands Cheat Sheet

## 📌 Basic Commands

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

---

## 🚀 Advanced Commands

| Command | Description |
|---------|-------------|
| `git stash` | Save changes temporarily |
| `git stash apply` | Apply last stashed changes |
| `git stash list` | List all stashes |
| `git stash pop` | Apply and remove last stash |
| `git revert <commit-hash>` | Revert a commit without altering history |
| `git reset --soft <commit-hash>` | Reset to commit but keep changes staged |
| `git reset --mixed <commit-hash>` | Reset to commit and unstage changes |
| `git reset --hard <commit-hash>` | Reset repository to specific commit and discard changes |
| `git diff` | Show unstaged changes |
| `git diff <branch1> <branch2>` | Show differences between two branches |
| `git cherry-pick <commit-hash>` | Apply specific commit to current branch |
| `git rebase <branch>` | Reapply commits on top of another branch |
| `git rebase -i HEAD~n` | Interactive rebase for last n commits |
| `git tag <tag-name>` | Create a new tag |
| `git tag -a <tag-name> -m "message"` | Create annotated tag |
| `git push origin <tag-name>` | Push tag to remote |
| `git push origin --tags` | Push all tags to remote |
| `git fetch` | Download objects and refs from remote |
| `git fetch --prune` | Remove deleted branches from remote tracking |
| `git remote -v` | List remote repositories |
| `git clean -f` | Remove untracked files |
| `git clean -fd` | Remove untracked files and directories |
| `git blame <file>` | Show who changed each line of a file |
| `git shortlog -sn` | Show commit count per contributor |
| `git reflog` | Show history of branch references |
| `git show <commit-hash>` | Show details of a commit |

---

✅ **Pro Tip:** Use `git log --graph --oneline --decorate --all` for a beautiful visual commit history.
