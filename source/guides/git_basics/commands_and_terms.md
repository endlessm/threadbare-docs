# Git Commands and Terms

## Git Commands

### Setup & Basics

`git --version` – check to ensure proper installation

`git init` – create a local repo here

`git status` – show changed files

### Working with Existing Repos

`git clone [URL]` – copy remote repo locally

`git remote -v` - displays name of remote repo

### Branching & Updating

`git switch` – switch between branches

`git switch` -c [branch] – create & switch to new branch

`git pull` – get latest changes from remote

`git branch` – list local branches

`git branch -a` – list all branches (local & remote)

### Staging & Discarding

`git add .` – stage all changes

`git add <file>` – stage select files

`git restore .` – discard unstaged changes

`git clean -fd` – remove untracked files/dirs

### Committing & Pushing

`git commit -m` "msg" – commit staged changes

`git push --set-upstream origin [branch]` – push changes to a new branch for the first time

`git push origin [branch]` – push feature branch changes

### History & Reset

`git log` – commit list

`git log --oneline` – short/condensed view of commit list

`git reset --hard [hash]` – revert to a specific commit

## GitHub and Git Terminology

**Repository (Repo)** - On GitHub and locally, it’s the project folder with all code and history.

**Fork** - On GitHub, a copy of someone’s repository that is stored on your own account.

**Clone** - On your computer, a local copy of a GitHub repo you can work on offline, but can still stay connected with the GitHub repo.

**Branch** - On GitHub and locally, a separate version of the project for features/fixes without touching the main code.

**Commit** - Created locally, visible on GitHub after pushing; a saved snapshot of changes with a message.

**Pull Request (PR)** - On GitHub, a request for others to review and approve merging your branch’s changes into another.

**Merge** - On GitHub, after PR approval, combine your branch’s changes into the main project.

**Collaborator** - On GitHub repo settings, a person who can directly change a repo and review code.

**Issues** - On GitHub’s “Issues” tab, a place to discuss and track bugs, tasks, or ideas.

**README** - On a repo’s main GitHub page, a file explaining the project, how to use it, and how to contribute.
