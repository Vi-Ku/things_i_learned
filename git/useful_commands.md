Here's a list of commonly used GitHub commands along with their descriptions:

git clone:

Usage: git clone <repository-url>

Description: Clones a repository from GitHub to your local machine, creating a local copy of the repository.

git init:

Usage: git init

Description: Initializes a new Git repository in the current directory, creating a new .git directory to store version control metadata.

git add:

Usage: git add <file(s)>

Description: Adds changes in the specified file(s) to the staging area in preparation for the next commit.

git commit:

Usage: git commit -m "<commit-message>"

Description: Commits the staged changes to the local repository with the specified commit message.

git push:

Usage: git push <remote-name> <branch-name>

Description: Pushes the committed changes from the local repository to the remote repository specified by <remote-name> and <branch-name>.

git pull:

Usage: git pull <remote-name> <branch-name>

Description: Fetches and merges changes from the remote repository specified by <remote-name> and <branch-name> into the current branch.

git status:

Usage: git status

Description: Displays the current status of the working directory, including modified, staged, and untracked files.

git branch:

Usage: git branch

Description: Lists all local branches in the repository.

git checkout:

Usage: git checkout <branch-name>

Description: Switches to the specified branch, updating the working directory to match the branch's state.

git merge:

Usage: git merge <branch-name>

Description: Merges changes from the specified branch into the current branch.

git log:

Usage: git log

Description: Displays a log of commit history, showing commit messages, authors, timestamps, and commit IDs.

git remote:

Usage: git remote -v

Description: Lists all remote repositories associated with the current repository, along with their URLs.

git reset:

Usage: git reset <file(s)>

Description: Unstages changes in the specified file(s) from the staging area, without modifying the working directory.

git stash:

Usage: git stash

Description: Temporarily stores changes in the working directory that are not ready to be committed, allowing you to switch branches or perform other operations.

git tag:

Usage: git tag <tag-name>

Description: Creates a lightweight tag at the current commit with the specified <tag-name>.

git fetch:

Usage: git fetch <remote-name>

Description: Fetches changes from the remote repository specified by <remote-name> without merging them into the current branch.

git remote add:

Usage: git remote add <remote-name> <repository-url>

Description: Adds a new remote repository with the specified name and URL.

git rebase:

Usage: git rebase <branch-name>

Description: Reapplies commits from the current branch onto the specified branch, incorporating changes from the specified branch into the current branch.

git tag -a:

Usage: git tag -a <tag-name> -m "<tag-message>"

Description: Creates an annotated tag at the current commit with the specified <tag-name> and <tag-message>.

git remote show:

Usage: git remote show <remote-name>

Description: Displays detailed information about the remote repository specified by <remote-name>, including its URL and branches.

git branch -d:

Usage: git branch -d <branch-name>

Description: Deletes the specified local branch from the repository.

git push --tags:

Usage: git push --tags

Description: Pushes all local tags to the remote repository.

git cherry-pick:

Usage: git cherry-pick <commit-hash>

Description: Applies the changes introduced by the specified commit to the current branch, allowing you to pick individual commits from one branch and apply them to another.

git reflog:

Usage: git reflog

Description: Displays a log of reference updates, including commits that may not be accessible through other means, such as branches or tags.

git clean:

Usage: git clean [-n | -f]

Description: Removes untracked files from the working directory. Use -n for a dry run to see which files would be removed, and -f to force the removal of untracked files.

These commands are essential for working with Git repositories hosted on GitHub and are used frequently by developers for version control and collaboration.
