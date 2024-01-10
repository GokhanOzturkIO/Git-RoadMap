# Git-RoadMap `v1.0.0-alpha01`

**SETUP**

- git config --global [user.name](http://user.name/) “[firstname lastname]”
- git config --global user.email “[valid-email]”
- git config --global color.ui auto

**SETUP & INIT**

- git init
- git clone [url]

**STAGE & SNAPSHOT**

- git status
- git add [file]
- git reset [file]
- git diff
- git diff --staged
- git commit -m “[descriptive message]”

**BRANCH & MERGE**

- git branch
- git branch [branch-name]
- git checkout
- git merge [branch]
- git log

**INSPECT & COMPARE**

- git log
- git log branchB..branchA
- git log --follow [file]
- git diff branchB...branchA
- git show [SHA]

**TRACKING PATH CHANGES**

- git rm [file]
- git mv [existing-path] [new-path]
- git log --stat -M

**IGNORING PATTERNS**

- logs/
*.notes
pattern*/
- git config --global core.excludesfile [file]

**SHARE & UPDATE**

- git remote add [alias] [url]
- git fetch [alias]
- git merge [alias]/[branch]
- git push [alias] [branch]
- git pull

**REWRITE HISTORY**

- git rebase [branch]
- git reset --hard [commit]

**TEMPORARY COMMITS**

- git stash
- git stash list
- git stash pop
- git stash drop
