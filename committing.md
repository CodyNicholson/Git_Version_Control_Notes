# Committing

Commit - Building block of Git, each one represents a version of the content at one point in time. User created checkpoint in the development of the project.

Commits: Fix off-by-one bugs, add new feature, and improve user docs

Type "git log" to view the commit history in the in the desired repository. This will display the commit id, author, date, and description of all of the commits.

To view the difference between two commits: Type "git diff OldCommitId NewCommitId". The commit Id does not include the word commit.

Commit often, every single unit of work should be committed separately to make the history organized for anyone who needs to go back and look at it later.

"git show commitId" - will show the changes between this commit and its parent. Useful after a merge when the commit history of one person is interweaved with the commit history of another person.
