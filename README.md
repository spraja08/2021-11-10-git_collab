# 2021-11-10 Git Collaboration

#git clone

- `git clone <REMOTE URL>` : Clones the repo from the remote to the local. Sets all the origin and remote parameters

- `git branch <NAME>` : creates a new branch <NAME> from the HEAD
	- `git branch -a` : Lists all the branches, local and remote
- `git switch <BRANCH.` : Moves to the <BRANCH>
- `git checkout <BRANCH>` : "older" way to switch

#branches

#Branching
- `git checkout -b <BRANCH>` : create a new branch. Work on the branch. Push the branch and create the pull request.
- `git push origin <BRANCH>` : Push the local branch to remote
- `git fetch --prune` : Update the meadata on the local computer
- `git delete -b <BRANCH>` : To delete the local branch.

# Rebase
1. 'git switch <BRANCH>`
2. `git rebase main` : this will rebase the current branch against main
