## Term Definitions
### Stages of a tracked file
* Unmodified: The file is tracked, but it hasn't been modified since the last commit.
* Modified: The file has been changed since the last commit, but these changes aren't yet staged for the next commit.
* Staged: The file has been modified, and the changes have been added to the staging area (also known as the index). These changes are ready to be committed.
* Committed: The file is in the repository's database. It represents the latest committed version of the file.  

**pull request** - used to signal that the commits from a branch are ready to be merged to another branch. if approved, it is merged into the base branch.  



## Universal
`git status` check status of working tree  
`git add` tell Git to start keeping trach of changes in certain files  
`git log` see info about prev. commits  

## Commits
`git commit` save changes to a snapshot

## Branches
`git checkout - b <otherBranch>` | switch between branches, create new branches; "-b" creates and switches to the new branch  
`git branch` to see what branch you are on  
`git fetch origin` to see if local repo is up-to-date with remote repo  
`git branch -d <branch name>` delete the branch  


## Remotes

## Stashing

## Merging
