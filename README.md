## Git Branching Exercise

Git cheat sheet and branching practice.

### Basic Commands
* `git init` - initialize local git repository in current folder (working directory)
* `git add . ` - stage all changes for commit
* `git commit -m "message"` - commit staged changes to local repository  

### Info Commands
* `git status` - show current status of working directory
* `git log` - show local commit history
* `git log --oneline` - show local commit history, compact format

### Remote Commands
* `git remote add alias URL` - connect local repo to remote, using name `alias` for remote repository  ` URL`
* `git push alias branchName` - push local commits to remote repository `alias` on branch `branchName` 