Git Industry Commands Practice

1. Git Configuration Commands

git config --global user.name
Syntax: git config --global user.name "Your Name"
Purpose: Set username
Example: git config --global user.name "Adi"

git config --global user.email
Syntax: git config --global user.email "email@example.com"
Purpose: Set email
Example: git config --global user.email "adi@gmail.com"

git config --list
Syntax: git config --list
Purpose: View config

git config --unset
Syntax: git config --unset user.name
Purpose: Remove config


2. Repository Setup Commands

git init
Syntax: git init
Purpose: Initialize repository

git clone
Syntax: git clone URL
Purpose: Clone repository

git clone --branch
Syntax: git clone --branch main URL
Purpose: Clone specific branch

git clone --depth
Syntax: git clone --depth 1 URL
Purpose: Shallow clone


3. Repository Status and Inspection

git status
Syntax: git status
Purpose: Show current status

git log
Syntax: git log
Purpose: Show commit history

git log --oneline
Syntax: git log --oneline
Purpose: Short commit history

git log --graph
Syntax: git log --graph
Purpose: Graph view

git show
Syntax: git show
Purpose: Show commit details

git diff
Syntax: git diff
Purpose: Show changes

git diff --staged
Syntax: git diff --staged
Purpose: Show staged changes

git blame
Syntax: git blame file
Purpose: Show line history

git reflog
Syntax: git reflog
Purpose: Show reference history

git shortlog
Syntax: git shortlog
Purpose: Summary of commits


4. File Tracking Commands

git add
Syntax: git add file
Purpose: Add file

git add .
Syntax: git add .
Purpose: Add all files

git add -p
Syntax: git add -p
Purpose: Add partial changes

git restore
Syntax: git restore file
Purpose: Restore file

git restore --staged
Syntax: git restore --staged file
Purpose: Unstage file

git rm
Syntax: git rm file
Purpose: Remove file

git mv
Syntax: git mv old new
Purpose: Rename file


5. Commit Commands

git commit
Syntax: git commit
Purpose: Save changes

git commit -m
Syntax: git commit -m "message"
Purpose: Commit with message

git commit --amend
Syntax: git commit --amend
Purpose: Edit last commit

git commit --no-edit
Syntax: git commit --no-edit
Purpose: Keep message same


6. Branch Management Commands

git branch
Syntax: git branch
Purpose: List branches

git branch -a
Syntax: git branch -a
Purpose: Show all branches

git branch -d
Syntax: git branch -d name
Purpose: Delete branch

git branch -D
Syntax: git branch -D name
Purpose: Force delete

git checkout
Syntax: git checkout branch
Purpose: Switch branch

git checkout -b
Syntax: git checkout -b new
Purpose: Create and switch

git switch
Syntax: git switch branch
Purpose: Switch branch

git switch -c
Syntax: git switch -c new
Purpose: Create and switch


7. Merge Commands

git merge
Syntax: git merge branch
Purpose: Merge branches

git merge --no-ff
Syntax: git merge --no-ff branch
Purpose: Force merge commit


8. Remote Commands

git remote
Syntax: git remote
Purpose: Show remotes

git remote -v
Syntax: git remote -v
Purpose: Detailed remotes

git remote add
Syntax: git remote add origin URL
Purpose: Add remote

git remote remove
Syntax: git remote remove origin
Purpose: Remove remote

git fetch
Syntax: git fetch
Purpose: Fetch updates

git fetch --all
Syntax: git fetch --all
Purpose: Fetch all repositories

git pull
Syntax: git pull
Purpose: Fetch and merge

git pull --rebase
Syntax: git pull --rebase
Purpose: Fetch and rebase

git push
Syntax: git push
Purpose: Push changes

git push -u origin branch-name
Syntax: git push -u origin branch
Purpose: Set upstream

git push --force
Syntax: git push --force
Purpose: Force push


9. Stash Commands

git stash
Syntax: git stash
Purpose: Save changes temporarily

git stash list
Syntax: git stash list
Purpose: View stashes

git stash pop
Syntax: git stash pop
Purpose: Apply and remove stash

git stash apply
Syntax: git stash apply
Purpose: Apply stash

git stash drop
Syntax: git stash drop
Purpose: Delete stash

git stash clear
Syntax: git stash clear
Purpose: Clear all stashes


10. Reset and Undo Commands

git reset
Syntax: git reset
Purpose: Reset changes

git reset --soft
Syntax: git reset --soft HEAD~1
Purpose: Keep staged changes

git reset --mixed
Syntax: git reset --mixed HEAD~1
Purpose: Unstage changes

git reset --hard
Syntax: git reset --hard HEAD~1
Purpose: Delete all changes

git revert
Syntax: git revert commit
Purpose: Undo commit safely

git clean -f
Syntax: git clean -f
Purpose: Remove untracked files

git clean -fd
Syntax: git clean -fd
Purpose: Remove untracked directories


11. Rebasing Commands

git rebase
Syntax: git rebase branch
Purpose: Reapply commits

git rebase -i
Syntax: git rebase -i HEAD~3
Purpose: Interactive rebase

git rebase --continue
Syntax: git rebase --continue
Purpose: Continue rebase

git rebase --abort
Syntax: git rebase --abort
Purpose: Cancel rebase


12. Cherry Pick and Patch Commands

git cherry-pick
Syntax: git cherry-pick commit
Purpose: Copy commit

git format-patch
Syntax: git format-patch -1
Purpose: Create patch

git apply
Syntax: git apply file.patch
Purpose: Apply patch

git am
Syntax: git am file.patch
Purpose: Apply patch from email


13. Tagging Commands

git tag
Syntax: git tag
Purpose: List tags

git tag -a
Syntax: git tag -a v1.0 -m "message"
Purpose: Create annotated tag

git tag -d
Syntax: git tag -d v1.0
Purpose: Delete tag

git push origin --tags
Syntax: git push origin --tags
Purpose: Push tags


14. Submodule Commands

git submodule add
Syntax: git submodule add URL
Purpose: Add submodule

git submodule init
Syntax: git submodule init
Purpose: Initialize submodule

git submodule update
Syntax: git submodule update
Purpose: Update submodule


15. Debugging Commands

git bisect
Syntax: git bisect
Purpose: Find bug

git bisect start
Syntax: git bisect start
Purpose: Start process

git bisect good
Syntax: git bisect good
Purpose: Mark good commit

git bisect bad
Syntax: git bisect bad
Purpose: Mark bad commit


Final Commands

git add git_industry_commands.md
git commit -m "Added industry level Git commands practice"
git push
