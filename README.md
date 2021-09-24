## Git Branching Practice and Cheat Sheet

### Basic commands
* 'git init' - initialize a local git repo in current folder
* 'git add .' - stage current changes for commit
* 'git commit -m "message"' - commit staged changes to local repository

### Informational commands
* 'git status' - show stays of working folder and repo

* 'git log' - show log of commits
* 'git log --oneline' - compact commit history
* 'git config -l' - list git configuartion

### Branching commands
* 'git branch' - list local branches, show which branch we are on
* 'git branch -M branchname' - rename current to branchname

* 'git branch newBranch' - create local branch 'newBranch'
* 'git chechout branchName' - got to branch 'branchName'

### Remote commands
* 'git remod add origin SomeRemoteRepoUrl' - link local repo with remote 'SomeRemoteRepoUrl'
* ' git push origin main' - push local commits to remote branch Informational
* ' git push origin branchName' - push to remote branch 'branchName'
