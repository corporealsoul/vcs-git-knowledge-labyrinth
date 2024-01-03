### 1. Getting Started

`git config --global user.name "[Your Name]"`

`git config --global user.email "[Your Email]"`

`git config --global color.ui auto`

`git init [project_name]`


### 2. Tracking Changes

`git add [file_name]`

`git add .`

`git add -- :!*.txt`

`git reset HEAD [file_name]`

`git status`

`git diff`

`git diff --staged`

`git commit -m "[Commit Message]"`


### 3. Branching and Merging

`git branch`

`git branch -a`

`git branch [branch_name]`

`git checkout [branch_name]`

`git merge [branch_name]`

`git difftool --dirstats --stat index [branch_name]`

`git rebase`
 

### 4. Remote Repositories

`git clone https://docs.github.com/articles/cloning-a-repository`

`git remote add origin https://docs.github.com/articles/cloning-a-repository`

`git push origin [branch_name]`

`git fetch origin`

`git merge origin/[branch_name]`


### 5. Undoing Changes

`git reset HEAD [file_name]`

`git reset HEAD --hard`

`git commit --amend`


### 6. Advanced Git Commands

`.gitignore` 

`git stash`

`git stash pop`

`git tag [tag_name] [commit_hash]`

`git tag`


### 7. Git Snapshots

`git log`

`git tag`

`git stash`


### 8. Managing History in Git

`git reset`

`git revert`

`git bisect`