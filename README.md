# Git Intro Project

A hands-on practice repo for learning the basics of **Git** and **GitHub**: making commits, working with branches, merging, ignoring files, and opening pull requests.

## What I practiced

- Creating a repository and making my first commits
- Writing clear commit messages
- Ignoring unwanted files (like log files) with `.gitignore`
- Creating and switching between branches
- Merging branches and keeping a feature branch up to date with `main`
- Opening and merging a pull request on GitHub

## Branches

| Branch | Purpose |
|---|---|
| `main` | The main branch where finished work is merged |
| `feature-greeting` | Adds `greeting.txt` |
| `feature-improvement` | Adds `improvement.txt`, then merged into `main` through a pull request |

## Files

| File | Description |
|---|---|
| `README.md` | This file |
| `.gitignore` | Tells Git to ignore log files |
| `greeting.txt` | Added on the `feature-greeting` branch |
| `improvement.txt` | Added on the `feature-improvement` branch |
| `message.txt` | Practice file used while merging `main` into `feature-improvement` |

## Commands I used

```bash
git init                        # start a new repository
git status                      # see what changed
git add <file>                  # stage a file
git commit -m "message"         # save a snapshot
git branch <name>               # create a branch
git checkout <name>             # switch to a branch
git checkout -b <name>          # create a branch and switch to it
git merge <branch>              # merge another branch into the current one
git log --oneline --graph       # view the commit history
git push origin <branch>        # upload a branch to GitHub
git pull                        # get the latest changes
```

## Author

**Ahmed Alharbi** – [@O1Wg](https://github.com/O1Wg)
