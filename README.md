## GIT


```
git init
git log
git show 09021388d15127b9e14c9efc4836e157c158772
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

## Git Tag
```
git tag -a v2.0 -m 'First version with tag. this is what we are running for a long time'
git tag -a v2.0 4b1b6559e92848dbc5
git push origin v2.0 (To push your tags)
or
git push origin --tags
git checkout v1.9
```
































