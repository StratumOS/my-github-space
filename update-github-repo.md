Working on existing project on Github. 
Project name in this example: “busy4.me” 
User name in Github: “system66”

START: Install 'git' package on local computer.

1. Get project from Github:

```
git clone https://github.com/system66/busy4.me.git
```

# or…

```
git clone git://github.com/system66/busy4.me.git
```

2. Do some changes, add file, add folders, edit code, etc.

```
cd busy4.me
git add .
git status # check if something for commit
git commit -m “Comment”
git remote rm origin
git remote add origin git@github.com:system66/busy4.me
```

3. Send changes to Github:

```
git push -u origin master
```


