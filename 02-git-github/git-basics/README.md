# 🌱 Git Basics

## Daily workflow

```bash
git status
git add .
git commit -m "Describe the change"
git push
git pull
```

## Useful inspection commands

```bash
git log --oneline --decorate --graph
git diff
git show <commit>
git remote -v
git branch -a
```

## Good commit message examples

✅ `Add Terraform backend configuration`  
✅ `Document Azure Bastion troubleshooting`  
❌ `update`  
❌ `changes`

## Rule

Commit small, logical changes so the history explains how the system evolved.
