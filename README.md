# understanding_git

Version control: Version control systems are software tools that help software teams manage changes to source code over time.

Git and GitHub: Git is a version control system that lets you manage and keep track of your source code history while GitHub is a cloud-based hosting service that lets you manage Git repositories.

GitHub alternatives:

1. Gitea
2. Launchpad
3. Beansstalk

`git fetch` and `git pull`: Git pull copies changes from a remote repository directly into your working directory, while git fetch does not. The git fetch command only copies changes into your local Git repo. The git pull command does both.

`git rebase`: Git Rebase is one of two Git utilities designed to integrate changes from one branch onto another. Rebasing is the process of combining or moving a sequence of commits on top of a new base commit. Git rebase is the linear process of merging.

The command for _Git rebase_:
Here is a summary of the commands used for Git rebase;

- `git rebase --d` The commit gets discarded from the final combined commit block during playback.
- `git rebase --p` This leaves the commit alone, not modifying the content or message, and keeping it as an individual commit in the branches’ history.
- `git rebase --x` This executes a command line shell script for each marked commit during playback.
- `git status` Checks the rebase status.
- `git rebase --continue` Continue with the changes that you made.
- `git rebase --skip` skip the changes.

Explain `cherry-picking`: Cherry-picking is the act of picking a commit from a branch and applying it to another.

The command for cherry-picking: `git cherry-pick <commit-hash>`
