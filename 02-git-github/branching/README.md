# 🌿 Git Branching

Branches let you develop safely without changing the production-ready branch directly.

## Suggested flow

```text
main
  └── feature/terraform-network
          ├── commit
          ├── commit
          └── pull request → review → merge
```

## Commands

```bash
git switch -c feature/my-change
git add .
git commit -m "Add network module"
git push -u origin feature/my-change
```

## Topics

- Feature branches
- Pull requests
- Merge conflicts
- Rebase
- Branch protection
- Release tags
