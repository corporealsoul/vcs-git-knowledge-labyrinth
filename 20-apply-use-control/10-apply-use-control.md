### 1. Getting Started

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git config --global user.name "[Your Name]"`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git config --global user.email "[Your Email]"`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git config --global color.ui auto`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git init [project_name]`


### 2. Tracking Changes

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git add [file_name]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git add .`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git add -- :!*.txt`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git reset HEAD [file_name]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git status`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git diff`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git diff --staged`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git commit -m "[Commit Message]"`


### 3. Branching and Merging

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git branch`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git branch -a`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git branch [branch_name]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git checkout [branch_name]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git merge [branch_name]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git difftool --dirstats --stat index [branch_name]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git rebase`
 

### 4. Remote Repositories

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git clone https://docs.github.com/articles/cloning-a-repository`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git remote add origin https://docs.github.com/articles/cloning-a-repository`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git push origin [branch_name]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git fetch origin`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git merge origin/[branch_name]`


### 5. Undoing Changes

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git reset HEAD [file_name]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git reset HEAD --hard`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git commit --amend`


### 6. Advanced Git Commands

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> .gitignore` 

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git stash`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git stash pop`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git tag [tag_name] [commit_hash]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git tag`


### 7. Git Snapshots

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git log`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git tag`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git stash`


### 8. Managing History in Git

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git reset`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git revert`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth> git bisect`