## GIT


```
git init
git log
git diff HEAD
git diff --staged
git reset test.py
```

## To unstaging the staged files
```
git reset test.py
```

## Retrurn to last commit
```
git reset test.py
git checkout -- test.py
```

## Git branches
```
git branch
git branch new_branch
git checkout -b new_branch (Last two line in this line is possible)
git rm file_name (Remove file from both git and file system)
git branch -d branch_name(Deleting branch)
```

## Git merge
```
git checkout master
git merge Addfunc (Bring new files and file modefied from Addfunc branch to master)
```

## Git clone
```
git clone [http url from github or gitlab ](This is uses instead of git init)
git push origin master
git pull origin master
```

## Git remote
```
git remote add origin_test http://github.com/test-repo
git remote
git remote -v
git push origin_test master
```


































