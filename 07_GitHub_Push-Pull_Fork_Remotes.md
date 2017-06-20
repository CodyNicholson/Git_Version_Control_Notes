# GitHub, Push, Pull, Fork, Remotes

Clicking the "commits" tab in a repository will show you the history of the changes to the repository like "git log" does

***

remote - This is short for remote repository, which refers to the URL address of a repository on GitHub. You can push and pull branches from local space to GitHub using a remote.

"git remote" - views remotes in repository

"git remote add remoteName remoteURL" - adds a remote named remoteName that connects the local repository to the github repository

"git remote -v" - views the remotes in the repository will more details like URL link for fetching and pushing

***

"git push remoteName branchName" - Will push the branch to the repository that the remote URL leads to on GitHub.

"git pull remoteName branchName" - Will pull the branch from the GitHub repository to the local repository

***

push - send branch and commit history to GitHub

pull - take branch and commit history from GitHub

***

Forking a repository - clones a GitHub repository to your GitHub profile for your own personal use that will not affect the original repository you forked

The original repository will simply display a number of times forked

You can then clone the repository you forked to your own local repository from your profile to make changes locally

Keeping a fork up to date - You should have a remote pointing to your fork, but you should also make a remote pointing to the original github repository you forked from called "upstream". fetch the up-stream to add the "upstream/master" branch to your local repository which you can merge into master.

***

To allow someone to push and pull to your repository you need to add them as a collaborator

***

Cloning from GitHub - There will be a clone link on the repository's main page. Use "git clone cloneURL" to clone a repository to your local repository.

Cloning like this^ from github will automatically create a remote for you to this repository on GitHub

***

"git fetch" - Like git pull, this will update your local repository with the latest information, but this will put the information in a new branch that will be named "remoteName/branchName"

"git pull remoteName branchName" = "git fetch remoteName" + "git merge branchName remoteName/branchName"

// "remoteName/branchName" is the branch created when you "git fetch remoteName", before you merge.
