# Git commands

### Delete Remote branch

```
git push origin --delete feature/login
```

### Update deleted files in Git

```
 git add -u 
```

### Remove a file from PR 
Basically update file from main branch and push, this will overwrite the file

```
git checkout master filename.txtgit
git  commit -m "removing file from PR"
git push
```
## Update file from origin master branch

```
git fetch
git checkout origin/main file.txt

```
