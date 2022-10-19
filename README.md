## Git Cheat Sheet

List of commands and practice with branching.
STUFF ADDED IN newBranch
### Basic Commands

* `git init` - initialize local repo in working directory
* `git add .` - stage changed files in current directory for commit
* `git commit -m "message"` - commit staged changes
* `git checkout SHA` - set working directory to state at commit `SHA`
* `git checkout {main/master}` - return to latest commit (either main or master depending on config)

### Information Commands
* `git status` - show current status of local repo/working directory
* `git log` - show commit history
* `git log --oneline` - show commit history (compact format)
* `git config -l` - list configuration for local repo

### Branch Commands
* `git branch` - list local branches
* `git branch branchName` - create local branch `branchName`
* `git checkout branchName` - switch to branch `branchName`
