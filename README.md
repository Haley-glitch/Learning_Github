# Git & GitHub Notes for Future Reference

## What Is Git?

Git is a **version control system** that lets you track changes to code, collaborate with others, and go back in time if needed.

---
## Learning Resource

This practice repo was created while following this excellent video:  
[Git & GitHub Crash Course – freeCodeCamp](https://youtu.be/RGOj5yH7evk?feature=shared)

## Basic Git Commands (Terminal)

```bash
git clone <repository-url>  # Clone a repository into a new directory
git status                   # Show the working tree status
git add <file>               # Add file contents to the index (staging area)
git commit -m "message"      # Record changes to the repository with a message
git push                      # Update remote refs along with associated objects
git pull                      # Fetch from and integrate with another repository or a local branch
git branch                    # List, create, or delete branches
git checkout <branch>        # Switch branches or restore working tree files
git merge <branch>           # Join two or more development histories together
```
### Initialize a Git Repo

```bash
git init
