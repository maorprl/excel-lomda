# Git Safe Start

This repository is already initialized and already has a first commit.

## Safe commands

See what changed:

```powershell
git status
```

Save a checkpoint:

```powershell
git add .
git commit -m "Describe the completed checkpoint"
```

After a GitHub remote is connected:

```powershell
git push
```

## Commands to avoid unless you deliberately need them

Do not casually run:

- `git reset --hard`
- `git clean -fd`
- `git push --force`
- `git rebase`
- history-rewriting commands

If Git reports a conflict, stop and inspect it before changing anything.

## Connecting to GitHub later

Create an empty **private** GitHub repository, then from this folder run:

```powershell
git remote add origin <YOUR-GITHUB-REPO-URL>
git push -u origin main
```

No branches or advanced Git workflow are required for this project initially.
