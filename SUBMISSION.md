# Remote Repositories Assignment

## Repository Links

### Open Source Contribution
- Original repository: https://github.com/oxygenqw/awesome-calculator
- Fork repository: https://github.com/testorgwe/awesome-calculator (форк)
- Feature branch: feature/multiply

### Corporate Project  
- Main repository: https://github.com/oxygenqw/techstart-api
- Backup repository: https://github.com/oxygenqw/techstart-api-backup

## Verification Commands

Run these commands in techstart-api-local:
```
git remote -v | grep -c "push"
git branch -r | wc -l
```

---

git remote -v | grep -c "push"

output -> 3

```

backup git@github.com:oxygenqw/techstart-api-backup.git (fetch)

backup git@github.com:oxygenqw/techstart-api-backup.git (push)

origin git@github.com:oxygenqw/techstart-api.git (fetch)

origin git@github.com:oxygenqw/techstart-api-backup.git (push)

origin git@github.com:oxygenqw/techstart-api.git (push)

```

---

git branch -r | wc -l

output -> 3

```

origin/HEAD-> origin/main

origin/develop

origin/main

```

---

Expected output: 
- First command: 4 or more (multiple push URLs)
- Second command: number of remote branches

