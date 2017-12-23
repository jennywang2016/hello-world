# Learning Git _Jenny's Note (Nov 17, 2017)

Git init: Create a new Git repository
Git status: inspects the contents of the working directory and staging area
Git add: adds files from the working directory to the staging area: git add filename
Git add filename_1 filename_2
Git diff: shows the difference between the working directory and the staging area
Git commit: permanetly stores file changes from the staging area in the repository: git commit -m "Notes"
Git log: shows a list of all previous commits
Git show HEAD
Git checkout HEAD filename
Git reset HEAD filename
Git reset commit_SHA: this command works by using the first 7 characters of the SHA of a previous commit.
Git branch: list all a Git project's branches
Git branch new_branch_name: create a new branch
Git checkout branch_name: switch branch, be now able to make commits on the branch that have no impact on master
Git merge branch_name: update master with the changes you made to new branch
Git branch -d branch_name: delete the branch specified
Git clone remote_location clone_name: remote_location tells git where to go to find the remote. This could be a web address, a filepath
Git remote -v:see a list of a git project's remotes 
Git fetch: to see if changes have been made to the remote and bring the changes down to your local copy 
Git merge origin/master: update local master branch with the upadted commits made from remote branch
Git push origin your_branch_name: after doing cd filename, git branch branch_name, git checkout branch_name, made some changes in the file, git add filename, git commit -m "notes", 

#End of notes

