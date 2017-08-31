# Git Basic

## Installation

### Check Git install and version 
```
git --version
```

### Configuration
```
git config --global user.name "Your Name"
git config --global user.email <YourEmailAddress>
```

### Check Git Config
```
git config --list
```

## Basic workflow

### Initialize Git or Clone existing project from remote repo
```
git init <ProjectName>
```
```
git clone <RepositoryURL>
```

### Lists all new or modified files to be committed
```
git status
```

### Add file to be committed
```
git add <FilePath>
```
### Commit
```
git commit -m "Your Message"
```

### Check log
```
git log --oneline
```

### Checkout file(s) from earlier version
```
git checkout <CommitID> <FilePath>
```

### Undo previous commit
```
git reset HEAD <optional:FilePath>
```

### Checkout specific file
```
git checkout -- <FilePath>
```

## Remote repository workflow

### Check existing remote repository
```
git remote -v
```

### Link remote repository
`origin` is the most common alias
```
git remote add <RemoteAlias> <RepositoryURL>
```

### Push commits to remote repository
```
git push -u <RemoteAlias> master
```

### Remove remote repository
```
git remote rm <RemoteAlias>
```





