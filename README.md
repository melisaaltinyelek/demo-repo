# Demo

Some description!

## Subheader

Watch tutorial on Youtube,

## Most Important git Commands

**do once**
initially download remote repository to your desktop (local repository)
```
git clone https://.../URL/to/repo.git
```

**status stuff**
new stuff from remote available?
```
git fetch
```

get newest changes from remote repository
```
git pull
```

Did some local file change (red)?
Any files staged and ready to commit(green)?
```
git status
```

**during work and when work is done**

stage modified local files
```
git add path/to/some/file.txt
git add --all
```

commit local files
```
git commmit -m "some message"
```

upload to remote repository
```
git push origin main
```

```
git checkout path/to/accidentally/changed/file.txt
```

**you might need these command when you create a repo locally with git init instead of cloning from remote**
see current remote repository (pushing will upload to this repo)
```
git remote -v
```

add new remote repository (pushing will upload to this repo)
```
git remote add origin https://.../URL/to/repo.git
```

remove remote repo
```
git remote remove origin
```

historie ansehen
```
gitk
git log
```

.gitignore files (single source of truth)
node_modules
.zip
r chached files...


.gitattributes and git lfs
