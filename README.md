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

### Git Branch Workflow
1. Go to local `main` branch
	```
	git checkout main
	```
2. Pull remote main
	```
	git pull origin main
	```
3. Create and check out new branch
	```
	git checkout -b featureName
	```
4. Work on your branch, committing frequently
5. When task complete, pull main and fix merge conflicts
	```
	git add .
	git commit -m "Complete feature"
	git pull origin main
	```
	Fix any merg conflicts and commit the fix.
6. Push to your branch 
	```
	git push origin featureName
	```
7. Create pull request on Github
8. Merge pull request to main
9. Pull remote main to local main
