### Setting up Git:

1. **Initialize a Git repository:**
    ```bash
    git init
    ```

2. **Clone a repository:**
    ```bash
    git clone <repository-url>
    ```

### Basic Git Commands:

3. **Check the status of your repository:**
    ```bash
    git status
    ```

4. **Stage changes for commit:**
    ```bash
    git add <file(s)>
    ```

5. **Commit changes:**
    ```bash
    git commit -m "Your commit message"
    ```

6. **Push changes to a remote repository:**
    ```bash
    git push origin <branch-name>
    ```

7. **Pull changes from a remote repository:**
    ```bash
    git pull origin <branch-name>
    ```

### Branching and Merging:

8. **Create a new branch:**
    ```bash
    git branch <branch-name>
    ```

9. **Switch to a branch:**
    ```bash
    git checkout <branch-name>
    ```

10. **Merge branches:**
    ```bash
    git merge <branch-name>
    ```

11. **Delete a branch:**
    ```bash
    git branch -d <branch-name>
    ```

### Working with Remotes:

12. **Add a remote repository:**
    ```bash
    git remote add <remote-name> <remote-url>
    ```

13. **Remove a remote repository:**
    ```bash
    git remote remove <remote-name>
    ```

14. **Fetch changes from a remote repository:**
    ```bash
    git fetch <remote-name>
    ```

### Handling Conflicts:

15. **Check for conflicts:**
    ```bash
    git diff
    ```

16. **Resolve conflicts and mark as resolved:**
    ```bash
    git add <conflicted-file(s)>
    ```

17. **Continue with the merge after conflicts:**
    ```bash
    git merge --continue
    ```

### Logging and History:

18. **View commit history:**
    ```bash
    git log
    ```

19. **View a specific commit:**
    ```bash
    git show <commit-hash>
    ```

20. **Undo the last commit (careful with this):**
    ```bash
    git reset --hard HEAD^
    ```

### Essential Commands:

```
git status: Checks the status of files in the working directory, staging area, and repository.
git add [file]: Adds a file or changes to the staging area.
git reset [file]: Unstages a file from the staging area.
git commit -m "[message]": Commits staged changes to the repository with a descriptive message.
git push origin [branch]: Pushes commits to a remote branch on GitHub.
git pull origin [branch]: Pulls changes from a remote branch to the local repository.

```

### Branching and Merging:

```git branch [branch-name]: Creates a new branch.
git checkout [branch-name]: Switches to a different branch.
git merge [branch-name]: Merges changes from another branch into the current branch.```
```

### Inspecting History:

```
git log: Shows a list of commits in the repository.
git diff [commit1] [commit2]: Shows the differences between two commits.
```

### Undoing Changes:

```
git reset --soft HEAD~1: Undoes the most recent commit, leaving changes in the staging area.
git reset --hard HEAD~1: Undoes the most recent commit, discarding uncommitted changes.
```

### Other Useful Commands:

```
git init: Initializes a new Git repository in a directory.
git clone [URL]: Clones an existing Git repository from a remote location.
git remote -v: Shows a list of remote repositories.
git config --global user.name "[name]": Sets the user's name for Git commits.
git config --global user.email "[email]": Sets the user's email address for Git commits.
```