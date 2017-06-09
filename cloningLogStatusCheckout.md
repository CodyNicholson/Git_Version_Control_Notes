# Cloning, Log, Status, Checkout

Repository - A group of files that you want to track together, for example: a .html file and a .css file to style it should go into the same repository since they will be affected by each others changes.

"git init" - creates a repository

"git status" - shows which files have changed since the last commit. Also shows what branch you are on. Displays the most recent commit.

-

A commit is a snapshot of every file in your repository, even if some of the files were not touched since the last commit they will be recommitted

-

"git log --stat" - will show the git log with additional details about which files were changed in the repository because of the "--stat".

"git log -nX" - will show git commit history with only X amount of commits in the log.

-

Cloning a repository - By typing "git clone URLtoGitRepository" you can download a repository with its commit history intact.

-

"git checkout commitID" - temporarily change files back to an earlier commit state.

"git checkout master" will return you from any previous commit state to the most recent commit state.

-

Detached HEAD state - The HEAD in Git is the most recent commit. When you do a git checkout, you will be in detached head state because you are no longer dealing with the most recent project code, you will be dealing with past project code.
