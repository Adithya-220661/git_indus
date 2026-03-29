# Git Industry Commands Practice

## 1. Git Configuration Commands

### git config --global user.name
- Syntax: git config --global user.name "Your Name"
- Purpose: Set username
- Example: git config --global user.name "Adi"

### git config --global user.email
- Syntax: git config --global user.email "email@example.com"
- Purpose: Set email
- Example: git config --global user.email "adi@gmail.com"

### git config --list
- Syntax: git config --list
- Purpose: View config

### git config --unset
- Syntax: git config --unset user.name
- Purpose: Remove config

---

## 2. Repository Setup Commands

### git init
- Syntax: git init
- Purpose: Initialize repo

### git clone
- Syntax: git clone URL
- Purpose: Clone repo

### git clone --branch
- Syntax: git clone --branch main URL
- Purpose: Clone specific branch

### git clone --depth
- Syntax: git clone --depth 1 URL
- Purpose: Shallow clone

---

## 3. Repository Status & Inspection

### git status
- Syntax: git status
- Purpose: Show status

### git log
- Syntax: git log
- Purpose: Commit history

### git log --oneline
- Syntax: git log --oneline
- Purpose: Short history

### git log --graph
- Syntax: git log --graph
- Purpose: Graph view

### git show
- Syntax: git show
- Purpose: Commit details

### git diff
- Syntax: git diff
- Purpose: Show changes

### git diff --staged
- Syntax: git diff --staged
- Purpose: Staged changes

### git blame
- Syntax: git blame file
- Purpose: Line history

### git reflog
- Syntax: git reflog
- Purpose: Reference history

### git shortlog
- Syntax: git shortlog
- Purpose: Summary

---

## 4. File Tracking Commands

### git add
- Syntax: git add file
- Purpose: Add file

### git add .
- Syntax: git add .
- Purpose: Add all

### git add -p
- Syntax: git add -p
- Purpose: Partial add

### git restore
- Syntax: git restore file
- Purpose: Restore file

### git restore --staged
- Syntax: git restore --staged file
- Purpose: Unstage

### git rm
- Syntax: git rm file
- Purpose: Remove file

### git mv
- Syntax: git mv old new
- Purpose: Rename

---

## 5. Commit Commands

### git commit
- Syntax: git commit
- Purpose: Commit changes

### git commit -m
- Syntax: git commit -m "msg"
- Purpose: Commit with message

### git commit --amend
- Syntax: git commit --amend
- Purpose: Edit last commit

### git commit --no-edit
- Syntax: git commit --no-edit
- Purpose: Keep message

---

## 6. Branch Management

### git branch
- Syntax: git branch
- Purpose: List branches

### git branch -a
- Syntax: git branch -a
- Purpose: All branches

### git branch -d
- Syntax: git branch -d name
- Purpose: Delete branch

### git branch -D
- Syntax: git branch -D name
- Purpose: Force delete

### git checkout
- Syntax: git checkout branch
- Purpose: Switch branch

### git checkout -b
- Syntax: git checkout -b new
- Purpose: Create + switch

### git switch
- Syntax: git switch branch
- Purpose: Switch branch

### git switch -c
- Syntax: git switch -c new
- Purpose: Create + switch

---

## 7. Merge Commands

### git merge
- Syntax: git merge branch
- Purpose: Merge

### git merge --no-ff
- Syntax: git merge --no-ff branch
- Purpose: Force merge commit

---

## 8. Remote Commands

### git remote
- Syntax: git remote
- Purpose: Show remotes

### git remote -v
- Syntax: git remote -v
- Purpose: Detailed remotes

### git remote add
- Syntax: git remote add origin URL
- Purpose: Add remote

### git remote remove
- Syntax: git remote remove origin
- Purpose: Remove remote

### git fetch
- Syntax: git fetch
- Purpose: Get updates

### git fetch --all
- Syntax: git fetch --all
- Purpose: Fetch all

### git pull
- Syntax: git pull
- Purpose: Fetch + merge

### git pull --rebase
- Syntax: git pull --rebase
- Purpose: Fetch + rebase

### git push
- Syntax: git push
- Purpose: Push changes

### git push -u origin branch-name
- Syntax: git push -u origin branch
- Purpose: Set upstream

### git push --force
- Syntax: git push --force
- Purpose: Force push

---

## 9. Stash Commands

### git stash
- Syntax: git stash
- Purpose: Save changes

### git stash list
- Syntax: git stash list
- Purpose: View stashes

### git stash pop
- Syntax: git stash pop
- Purpose: Apply + remove

### git stash apply
- Syntax: git stash apply
- Purpose: Apply stash

### git stash drop
- Syntax: git stash drop
- Purpose: Delete stash

### git stash clear
- Syntax: git stash clear
- Purpose: Clear all

---

## 10. Reset & Undo Commands

### git reset
- Syntax: git reset
- Purpose: Reset

### git reset --soft
- Syntax: git reset --soft HEAD~1
- Purpose: Keep staged

### git reset --mixed
- Syntax: git reset --mixed HEAD~1
- Purpose: Unstage

### git reset --hard
- Syntax: git reset --hard HEAD~1
- Purpose: Delete changes

### git revert
- Syntax: git revert commit
- Purpose: Undo safely

### git clean -f
- Syntax: git clean -f
- Purpose: Remove files

### git clean -fd
- Syntax: git clean -fd
- Purpose: Remove dirs

---

## 11. Rebasing Commands

### git rebase
- Syntax: git rebase branch
- Purpose: Reapply commits

### git rebase -i
- Syntax: git rebase -i HEAD~3
- Purpose: Interactive

### git rebase --continue
- Syntax: git rebase --continue
- Purpose: Continue

### git rebase --abort
- Syntax: git rebase --abort
- Purpose: Cancel

---

## 12. Cherry Pick & Patch

### git cherry-pick
- Syntax: git cherry-pick commit
- Purpose: Copy commit

### git format-patch
- Syntax: git format-patch -1
- Purpose: Create patch

### git apply
- Syntax: git apply file.patch
- Purpose: Apply patch

### git am
- Syntax: git am file.patch
- Purpose: Apply email patch

---

## 13. Tagging Commands

### git tag
- Syntax: git tag
- Purpose: List tags

### git tag -a
- Syntax: git tag -a v1.0 -m "msg"
- Purpose: Annotated tag

### git tag -d
- Syntax: git tag -d v1.0
- Purpose: Delete tag

### git push origin --tags
- Syntax: git push origin --tags
- Purpose: Push tags

---

## 14. Submodule Commands

### git submodule add
- Syntax: git submodule add URL
- Purpose: Add submodule

### git submodule init
- Syntax: git submodule init
- Purpose: Init

### git submodule update
- Syntax: git submodule update
- Purpose: Update

---

## 15. Debugging Commands

### git bisect
- Syntax: git bisect
- Purpose: Find bug

### git bisect start
- Syntax: git bisect start
- Purpose: Start

### git bisect good
- Syntax: git bisect good
- Purpose: Mark good

### git bisect bad
- Syntax: git bisect bad
- Purpose: Mark bad

---

## Final Commands

git add git_industry_commands.md
git commit -m "Added industry level Git commands practice"
git push
