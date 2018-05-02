# Git Workflow

## Workflow [1]

### Local Branch Setup
```bash
master
development
production
```

### Local Flow
- Create topic development branch e.g. development-branch-new-feature
- Once featured complated and tested locally. Merge master into topic branch first. While still in tipic branch to make sure up to date.
```bash
git merge development
git checkout development
git merge development-branch-new-feature
git branch -d development-branch-new-feature
git push origin development
```
### Server Flow
- Pull the latest updates
```bash
git pull origin development
```

Once development has been approved then we can deploy production.

### Local
```bash
git checkout development
git merge master
git checkout master
git merge development
```

### Production 
```bash
git pull origin master
```

