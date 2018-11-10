Working on existing project on Github. 
Project name in this example: “busy4.me” 
User name in Github: “system66” with email: "info@system66.com"

## START: Install 'git' package on local computer.

# STEP 0. set account:
```
git config --global user.name "system66"
git config --global user.email "info@system66.com"
```
or set permanently with ssh-key

# 1. Get project from Github:

```
git clone https://github.com/system66/busy4.me.git
```

or…

```
git clone git://github.com/system66/busy4.me.git
```

# 2. Do some changes, add file, add folders, edit code, etc.

```
cd busy4.me
git add .
git status # check if something is for commit
git commit -m “Comment”
git remote rm origin
git remote add origin git@github.com:system66/busy4.me
```

# 3. Send changes to Github:

```
git push -u origin master
```

# Done
Your project is updated Github website.

# git package for Mac OS X
```
brew install git
```
or download from https://sourceforge.net/projects/git-osx-installer/files/

# git for Linux Debian Ubuntu based:
```
apt install git
```

# git for Linux Redhat CentOS based:
```
yum install git
```

# git for Windows
https://git-scm.com/download/win
