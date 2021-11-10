# 2021-11-10-git_collab

#git clone

- `git clone <REMOTE URL>` : Clones the repo from the remote to the local. Sets all the origin and remote parameters

- `git branch <NAME>` : creates a new branch <NAME> from the HEAD
	- `git branch -a` : Lists all the branches, local and remote
- `git switch <BRANCH.` : Moves to the <BRANCH>
- `git checkout <BRANCH>` : "older" way to switch

#Branching
- `git checkout -b <BRANCH>` : create a new branch. Work on the branch. Push the branch and create the pull request.
- `git push origin <BRANCH>` : Push the local branch to remote
- `git fetch --prune` : Update the meadata on the local computer
- `git delete -b <BRANCH>` : To delete the local branch.
