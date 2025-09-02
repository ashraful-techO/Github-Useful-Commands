# Github-Useful-Commands

<h1>1. Setup & Config</h1>

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --list
git config --global core.editor "code --wait"

```


<h1>2. Create / Clone Repository</h1>

```bash
git init                   # Initialize new repo
git clone <url>             # Clone existing repo
git remote -v               # Show remotes
git remote add origin <url> # Add remote

```

<h1>3. Basic Workflow</h1>

```bash
git status                  # Show file changes
git add <file>              # Stage file
git add .                   # Stage all changes
git commit -m "message"     # Commit staged changes
git push origin <branch>    # Push to remote
git pull origin <branch>    # Pull from remote

```

<h1>4. Branching</h1>

```bash
git branch                  # List branches
git branch <name>           # Create branch
git checkout <name>         # Switch branch
git switch <name>           # Alternative to checkout
git merge <branch>          # Merge branch into current
git branch -d <name>        # Delete branch

```
<h1>5. History & Logs</h1>

```bash
git log                     # Commit history
git log --oneline           # Compact history
git log --graph --all       # Visual commit graph
git diff                    # Unstaged changes
git diff --staged           # Staged changes
git show <commit>           # Show commit details

```

<h1>6. Undo & Reset</h1>

```bash
git restore <file>          # Discard changes
git restore --staged <file> # Unstage file
git reset --soft <commit>   # Reset but keep staged
git reset --hard <commit>   # Reset and discard changes
git revert <commit>         # Undo commit (new commit)

```
<h1>7. Stashing</h1>

```bash
git stash                   # Save changes
git stash list              # List stashes
git stash apply             # Apply last stash
git stash pop               # Apply and remove stash
git stash save "message"    # Save with name

```
<h1>8. Remote Management</h1>

```bash
git fetch origin             # Fetch remote changes
git push -u origin <branch>  # Push new branch with upstream
git push origin --delete <branch> # Delete remote branch

```
<h1>9. Tagging</h1>

```bash
git tag                      # List tags
git tag <name>               # Create tag
git push origin <name>       # Push tag
git push --tags              # Push all tags

```
<h1>10. Helpful Commands</h1>

```bash
git shortlog -s <branch>     # Contributions summary
git blame <file>             # Who changed each line
git clean -fd                # Remove untracked files/folders


```

