# Git Commands related to branch


### Branch
* List All branches
```
git branch
```
* Create New Branch
```
git branch <branchname>
```
* Create Remote Branch
```
git push --set-upstream origin <branchname> // origin is remote repo 
```
* Checkout or Switch to New Branch
```
git checkout <branchname>
```
* Create a branch and checkout to new branch
```
git checkout -b <branchname>
```

### Managing Branch

_Before merging,Always ensure the local repository branches are updated using_ ```git pull```
_After merge make sure to_ do push using ```git push``` _to see changes in remote branch._

* Copying changes from master to branch.

```
git checkout <branchname>
git merge master
```
* Copying changes from branch to master
```
git checkout master
git merge <branchname>
```

* Delete remote branch
```
git push origin --delete <branchname>
```
* Delete local branch
```
git checkout -b <branchname>
```
