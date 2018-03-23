<h1>Git Best Practice</h1>

### 1. push and create a remote branch
```
git checkout local_branch
git push origin local_branch:remote_branch
```

### 2. undo 'git add' before 'commit'
```
git reset <file>
```

### 3. remove remote branch
```
git push origin :remote_branch_name 
```
