# Git Utilities

## Installation

Just make sure all of the `git-*` are on the path.

## Usage

All files on the path that are in the format `git-some-command arguments` can be executed by running `git some-command arguments`.

### git-absolute

`git absolute` echoes the directory you are in with the name of the repository, or the first argument passed.

### git-branch-name

`git branch-name` echoes the branch name you are on.

### git-dir

`git dir` returns as exit code wether you are in a git repository.

### git-email

`git email` echoes the email git uses for actions.

### git-ignore

`git ignore` adds the arguments to the `.gitignore` file at the root of the repository with the correct paths.

### git-loglive

`git loglive` displays the `git log` but refreshes it every 20 seconds (default, argument 1 is the seconds).

### git-name

`git name` echoes the name git uses for actions.

### git-relative

same as `git absolute` but without the repository name.

### git-repo

`git repo` echoes the name of the repository.

### git-root

`git root` echoes the absolute path to the repository you are currently in.

### git-sclone

`git sclone` assumes you use github so you can just passthrough `org/repo`.

### git-sremote

`git sremote` assumes you use github so you can just passthrough `org/repo`, it pushes to that repo to the `main` branch.
 
