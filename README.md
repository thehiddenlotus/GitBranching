## Git Branching

### Overview

Overview of Git Commands

### Basic Commands

* `git init` - Initialize local git repository
* `git add` - Stage local working directory for commit
* `git commit` - Commit staged files to local repository
* `git status` - Show status of repository
* `git rm --cached fileName` - Remove fileName from commit index
* `git log` - Show commit history
* `git log --oneline` - Show commit history (compact)

### Remote Repository Commands

* `git remote add origin remoteRepoUrl` - Link local repo to 'remoteRepoUrl'
* `git pull origin master` - Pull 'master' branch content from remote origin into current local branch
* `git push origin master` - Push current local branch to 'master' branch of remote origin

### Branching Commands

* `git Branching` - List local branches, highlight checked-out branch
* `git branch branchName` - Create branch 'branchName'
* `git checkout branchName` - Move to branch 'branchName'
* `git pull origin master` - Pull remote `master` into local branch (resolve conflicts)
