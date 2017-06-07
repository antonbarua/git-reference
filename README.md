# Git Reference

### 1. Initialize a local repository

#### git init
```bash
mkdir git-reference
cd git-reference/
git init
```
### 2. Check the status of the repository

#### git status
```bash
git status
```

### 3. Add files to be committed

#### git add < filename >
```bash
git add README.md
```

### 4. Commit the changes to the staging area

#### git commit -m "< message >"
```bash
git commit -m "first commit"
```

### 5. Create a branch

#### git branch < branchname >
#### git checkout -b < branchname >
```bash
git branch edit
git checkout -b edit
```

### 6. Show branches

#### git branch
```bash
git branch
```

### 7. Connect with a remote repository

#### git remote add origin < remote_repo >
```bash
git remote add origin git@github.com:antonbarua/git-reference.git
```

### 8. Push a branch 

#### git push origin < branchname >
```bash
git push origin master
git push -u origin master //track changes
```

### 9. Pull changes from a repo

#### git pull origin < branchname >
```bash
git pull origin master
pit pull //argument-less git pull, uses current branch and origin
```