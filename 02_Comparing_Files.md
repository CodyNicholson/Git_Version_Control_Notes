# Comparing Files

### Comparing working directory, staging area, and repository:

You can use "git add fileName" to copy a file from the working directory to the staging area.

Once in the staging area you can commit this file using "git commit" to copy the files in the staging area into the repository.

If a file is in the staging area but not in the repository you can use "git diff --staged" to view the differences between the files in staged and the files in the repository.

***

"git reset --hard" will discard any changes in either the working directory or the staging area. THIS IS PERMANENT!

"git diff" - compares working directory with staging area

"git diff staged" - compares staging area with the most recent commit

"git diff commit1 commit2" - compares commit1 with commit2

"git show commitId" - will show the changes between this commit and its parent. Useful after a merge when the commit history of one person is interweaved with the commit history of another person.
