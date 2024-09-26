# These are the commands i used in this project
## Git Commands

### `init`
Initializes a new Git repository in the current directory. This creates a `.git` subdirectory that contains all the necessary metadata for the repository.

### `add`
Adds changes in the working directory to the staging area. You can specify individual files or use `.` to add all changes.

### `commit`
Records the changes in the staging area to the repository with a descriptive message. This creates a new commit with a unique ID.

### `checkout -b`
Creates and switches to a new branch. This is useful for starting new features or working on separate tasks without affecting the main codebase.

### `merge`
Combines changes from one branch into another. Typically used to integrate features or bug fixes from a feature branch into the main branch.

### `rebase`
Reapplies commits on top of another base tip. This is often used to keep a feature branch up to date with the main branch.

### `revert`
Creates a new commit that undoes the changes of a previous commit. This is useful for undoing changes without altering the commit history.

### `reset --hard`
Resets the current branch to a specific state, discarding all changes in the working directory and staging area. This is a destructive operation and should be used with caution.

### `remote add origin`
Adds a remote repository URL to your local repository. This is typically used to link your local repository to a repository hosted on a service like GitHub.