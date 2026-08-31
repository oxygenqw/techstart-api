# Remote Repository Setup

## Current Remotes
backup  git@github.com:oxygenqw/techstart-api-backup.git (fetch)
backup  git@github.com:oxygenqw/techstart-api-backup.git (push)
origin  git@github.com:oxygenqw/techstart-api.git (fetch)
origin  git@github.com:oxygenqw/techstart-api-backup.git (push)
origin  git@github.com:oxygenqw/techstart-api.git (push)

## Tracking Branches
  develop 3789eb6 1.1.0-dev
* main    f34aa0e Merge branch 'main' of github.com:oxygenqw/techstart-api

## Fork Workflow Summary
- Original repository: https://github.com/oxygenqw/awesome-calculator
- Fork repository: https://github.com/testorgwe/awesome-calculator
- Upstream configuration: git remote add upstream git@github.com:oxygenqw/awesome-calculator.git

## Backup Strategy
- Primary remote: origin
- Backup remote: backup
- Sync command:  git push origin main

## Lessons Learned
Удобно связывать локальный репозиторий с несколькими удаленными репозиториями, иначе видимо приходилось бы клонировать каждый отдельно.
