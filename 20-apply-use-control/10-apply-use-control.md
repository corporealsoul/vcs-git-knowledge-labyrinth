### 1. Getting Started

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git config --global user.name "[Your Name]"`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git config --global user.email "[Your Email]"`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git config --global color.ui auto`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git init [project_name]`


### 2. Tracking Changes

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git add [file_name]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git add .`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git add -- :!*.txt`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git reset HEAD [file_name]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git status`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git diff`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git diff --staged`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git commit -m "[Commit Message]"`


### 3. Branching and Merging

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git branch`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git branch -a`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git branch [branch_name]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git checkout [branch_name]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git merge [branch_name]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git difftool --dirstats --stat index [branch_name]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git rebase`
 

### 4. Remote Repositories

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git clone https://docs.github.com/articles/cloning-a-repository`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git remote add origin https://docs.github.com/articles/cloning-a-repository`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git push origin [branch_name]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git fetch origin`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git merge origin/[branch_name]`


### 5. Undoing Changes

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git reset HEAD [file_name]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git reset HEAD --hard`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git commit --amend`


### 6. Advanced Git Commands

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> .gitignore` 

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git stash`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git stash pop`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git tag [tag_name] [commit_hash]`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git tag`


### 7. Git Snapshots

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git log`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git tag`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git stash`


### 8. Managing History in Git

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git reset`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git revert`

`PS D:\GITRepos\vcs-git-knowledge-labyrinth\20-apply-use-control> git bisect`