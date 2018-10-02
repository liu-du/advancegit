# advancegit

- __remove files from staging area __

```
git reset 
```

- __revert to previous commit with changes staged__

```
git reset --soft <hash>
```

- __revert to previous commit with changes unstaged__

```
git reset (--mixed) <hash>
```

- __cloneing a remote repo to current directory__

```
git clone <url> .
```

- __List tracked files__

```
git ls-tree master -r
```

- __remove (delete) untracked files__

```
git clean -df
```
	- -d: directory, -f: file

- __show recent referenced log__

```
git reflog
```

- __checkout a commit that's been deleted from commit history by hard reset__

```
git checkout <hash>
```

- __revert to a commit by creating a new commit__

```
git revert <hash>
```

- __compare to commit__
```
git diff <hash> <hash>
```

- __compare to branch__

```
git diff <branch> <branch (optional)>
```

- __remove initial commit__ (git reset HEAD~1 won't work)

```
git update-ref -d HEAD
```
- __Add remote origin__ 

```
git remote add origin <remote_origin>
git push -u origin
```



