# Branches

A copy of the master branch that you can use for experimental work, like introducing a new feature that you are unsure of if it will work

-

Every branch will have its own unique commit history that is independent of other branches

The working main branch is called the master branch

If your feature ends up working out, then you can combine your experimental feature branch with your master branch in a process called merging

-

"git branch" will display all of the branches in a repository

"git branch branchName" will create a new branch with name "branchName" in this case

By typing "git checkout branchName" you can switch branches to the new branch I created using the above git command

-

Times to create new branches: moving on to a different piece of work, creating new features, fixing a bug

You can have a production branch of code that will always work and then a dev branch for developing new features

-

"remote branch" means it is a branch you did not create yourself

"git log --graph --oneline branch1 branch2" will display the commit history for two different branches named branch1 and branch2. --oneline will make sure that it displays as little information as possible while still provifing you with the commit ids and descriptions of each commit to each branch

"git checkout -b newBranchName" is the same as running "git branch newBranchName" and then "git checkout newBranchName"

-

When you merge a branch, say dev branch, into the master branch you can then delete the dev branch after the merge is complete. Doing this will only delete the label "dev", and will not effect the commit history because the dev branch commit history will be stored in the master branch after the merge is complete

Be careful when merging branches because if done carelessly you can lose access to the commit history of other branches by merging.

"git merge branchName1 branchName2" will merge the two branches together. Leave a description or accept the one that is provided for you by git.

"git branch -d branchName" - will delete the branch label branchName, but will keep the commit history of that branch.
