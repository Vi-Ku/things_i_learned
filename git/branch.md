Branching Commands
Here are the details of various branching commands in Git along with their options:

git branch:

Usage: git branch [options] [branch-name]

Options:

-d, --delete: Deletes the specified branch.

-D: Forces deletion of the specified branch, even if it has unmerged changes.

-m, --move: Renames the specified branch.

-r, --remote: Lists or operates on remote-tracking branches.

-a, --all: Lists both local and remote branches.

-v, --verbose: Shows more verbose output.

--list: Lists available branches.

--merged: Lists branches that are fully merged into HEAD.

--no-merged: Lists branches that are not fully merged into HEAD.

git checkout:

Usage: git checkout [options] [branch-name]

Options:

-b, --create: Creates a new branch and switches to it.

-f, --force: Forces checkout, discarding local changes if necessary.

-m, --merge: Merges changes from the specified branch into the current branch.

-t, --track: Sets up tracking for a remote branch.

-p, --patch: Interactively select hunks from the difference between the index and the working tree and apply them to the current working tree.

--detach: Detaches HEAD from the current branch, leaving the branch unchanged.

git merge:

Usage: git merge [options] [branch-name]

Options:

--no-ff: Forces a merge commit even if the merge could be resolved as a fast-forward.

--ff-only: Refuses to merge and exits with a non-zero status unless the current HEAD is already up to date or the merge can be resolved as a fast-forward.

--squash: Creates a new commit with the changes but without committing them immediately.

-X, --strategy: Specifies which merge strategy to use.

-S, --gpg-sign: GPG-sign the resulting merge commit.

git rebase:

Usage: git rebase [options] [branch-name]

Options:

-i, --interactive: Opens an interactive rebase editor to squash, reorder, edit, or drop commits.

--onto: Reapplies commits onto a new base branch instead of the current branch.

-p, --preserve-merges: Preserves merges instead of rebasing them.

-x, --exec: Executes a shell command after each rebased commit.

--continue: Continues the rebase operation after resolving conflicts.

git fetch:

Usage: git fetch [options] [remote]

Options:

--all: Fetches all branches from the remote repository.

-f, --force: Forces updating of remote-tracking branches.

-p, --prune: Prunes remote-tracking branches that no longer exist on the remote repository.

-t, --tags: Fetches tags from the remote repository.

These are some of the most commonly used branching commands in Git along with their options. Understanding these commands and options is essential for effectively managing branches in your Git workflow.
