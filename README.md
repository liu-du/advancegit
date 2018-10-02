# advancegit

__Remove files from staging area__

```
git reset 
```

__Revert to previous commit with changes staged__

```
git reset --soft <hash>
```

__Revert to previous commit with changes unstaged__

```
git reset (--mixed) <hash>
```

__Cloneing a remote repo to current directory__

```
git clone <url> .
```

__List tracked files__

```
git ls-tree master -r
```

__Remove (delete) untracked files__

```
git clean -df
```
	- -d: directory, -f: file

__Show recent referenced log__

```
git reflog
```

__Checkout a commit that's been deleted from commit history by hard reset__

```
git checkout <hash>
```

__Revert to a commit by creating a new commit__

```
git revert <hash>
```

__Compare to commit__
```
git diff <hash> <hash>
```

__Compare to branch__

```
git diff <branch> <branch (optional)>
```

__Remove initial commit__ (git reset HEAD~1 won't work)

```
git update-ref -d HEAD
```
__Add remote origin__ 

```
git remote add origin <remote_origin>
git push -u origin
```



