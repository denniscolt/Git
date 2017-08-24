# Git Basic

## Installation

### Check Git install and version 
```
git --version
```

### Configuration
```
git config --global user.name "Your Name"
git config --global user.email <Your Email Address>
```

### Check Git Config
```
git config --list
```

## Basic workflow

### Initialize Git or Clone existing project from remote repo
```
git init <Project Name>
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

### Link remote repository
```
git remote add origin <repositoryURL>
```

### Push commits to remote repository
```
git push -u origin master
```





