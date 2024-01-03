### 1. Getting Started

-   **Installation:**
    -   Download and install Git for your operating system:  [https://git-scm.com/downloads](https://git-scm.com/downloads)
-   **User Configuration:**
    -   Set your global username and email:
        -   `git config --global user.name "[Your Name]"`
        -   `git config --global user.email "[Your Email]"`
    -   (Optional) Enable colorized output:
        -   `git config --global color.ui auto`
-   **Initializing a Repository:**
    -   Create a new local repository in the current directory:
        -   `git init [project_name]`  (optional)

### 2. Tracking Changes

-   **Staging Files:**
    -   Add a file to the staging area for the next commit:
        -   `git add [file_name]`
    -   Add all tracked files in the current directory:
        -   `git add .`
    -   Add specific files (excluding patterns):
        -   `git add -- :!*.txt`  (adds all except TXT files)
    -   Unstage a file from the staging area:
        -   `git reset HEAD [file_name]`
-   **Viewing File Differences:**
    -   Show modified files in the working directory:
        -   `git status`
    -   Show difference between working directory and staging area:
        -   `git diff`
    -   Show difference between staging area and last commit:
        -   `git diff --staged`
-   **Committing Changes:**
    -   Create a new commit with a descriptive message:
        -   `git commit -m "[Commit Message]"`

### 3. Branching and Merging

-   **Listing Branches:**
    -   Show all local branches:
        -   `git branch`
    -   Show all branches (local and remote):
        -   `git branch -a`
-   **Creating Branches:**
    -   Create a new branch:
        -   `git branch [branch_name]`
    -   Switch to an existing branch:
        -   `git checkout [branch_name]`
-   **Merging Branches:**
    -   Merge another branch into the current branch:
        -   `git merge [branch_name]`
    -   Check for potential merge conflicts before merging:
        -   `git difftool --dirstats --stat index [branch_name]`
-   **Reapply Commits:**
    -   Reapply commits on top of another base tip:
        -   `git rebase`
 
### 4. Remote Repositories

-   **Cloning a Repository:**
    -   Download a remote repository to your local machine:
        -   `git clone https://docs.github.com/articles/cloning-a-repository`
-   **Adding a Remote Repository:**
    -   Connect your local repository to a remote repository:
        -   `git remote add origin https://docs.github.com/articles/cloning-a-repository`
-   **Pushing Changes to Remote:**
    -   Push your local commits to the remote branch:
        -   `git push origin [branch_name]`
-   **Pulling Changes from Remote:**
    -   Fetch all changes from the remote repository:
        -   `git fetch origin`
    -   Merge fetched changes into the current branch:
        -   `git merge origin/[branch_name]`

### 5. Undoing Changes

-   **Unstaging Files:**
    -   Revert changes and remove them from the staging area:
        -   `git reset HEAD [file_name]`
-   **Undoing Commits:**
    -   Unstage all changes and reset to the HEAD commit:
        -   `git reset HEAD --hard`
    -   Discard the last commit without affecting the working directory:
        -   `git commit --amend`

### 6. Advanced Git Commands

-   **Ignoring Files:**
    -   Prevent specific files from being tracked:
        -   Add patterns to a  `.gitignore`  file in the repository root directory.
-   **Stashing Changes:**
    -   Temporarily save uncommitted changes for later use:
        -   `git stash`
    -   Apply stashed changes back to the working directory:
        -   `git stash pop`
-   **Tagging Releases:**
    -   Create a tag for a specific commit:
        -   `git tag [tag_name] [commit_hash]`
    -   List all tags:
        -   `git tag`

### 7. Git Snapshots

-   **Snapshots:**
    -   Show commit logs:
        -   `git log`
    -   Create, list, delete or verify a tag object signed with GPG:
        -   `git tag`
    -   Stash the changes in a dirty working directory away:
        -   `git stash`

### 8. Managing History in Git

-   **Manage History:**
    -   Reset current HEAD to the specified state:
        -   `git reset`
    -   Revert some existing commits:
        -   `git revert`
    -   Use binary search to find the commit that introduced a bug:
        -   `git bisect`