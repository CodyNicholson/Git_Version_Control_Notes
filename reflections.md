# Reflections

How did viewing a diff between two versions of a file help you see the bug that was introduced?

It helped by only showing me the lines that were changed, and not the lines that remained the same. In a larger file this benefit is very important for efficiency.

-

How could having easy access to the entire history of a file make you a more efficient programmer in the long term?

It could help in the long term because if you wanted to change something back or see the history of your projects development you could.

-

What do you think are the pros and cons of manually choosing when to create a commit, like you do in Git, vs having versions automatically saved, like Google Docs does?

Convenience is the pro, the cons are that some auto-commits might have too little or too much code in them. Too little means your commit history will be cluttered, too much means that your commit will not be easy to fix if you made a mistake since you will have to look through a ton of code to find the problem.

-

Why do you think some version control systems, like Git, allow saving multiple files in one commit, while others, like Google Docs, treat each file separately?

In google docs one doc does not have any direct effects on another, but in Git when you are dealing with a software development project certain files will have effects on others. Due to this it is better to track them together rather than separately for debugging purposes.

-

How can you use the commands git log and git diff to view the history of files?

By comparing each commit to each other you can see how the code was altered over time in the development in the project. git log to view the commits over the history of the repository, and git diff to view the specific changes between two commits.

-

How might using version control make you more confident to make changes that could break something?

It will make you more confident because you know that you will always be able to revert your changes. You can take as many risks as you want!

-

Now that you have your workspace set up, what do you want to try using Git for?

Creating a ton of projects!

-

What happens when you initialize a repository? Why do you need to do it?

It creates a git repository so that it can start collecting the commit history and meta data

-

How is the staging area different from the working directory and the repository? What value do you think it offers?

Its a bridge between them. The staging area is the place files go from the working directory before they are committed to the repository.

-

How can you use the staging area to make sure you have one commit per logical change?

I can make changes to X > 1 amount of features, then stage and commit each one indvidually with a unique commit description

-

What are some situations when branches would be helpful in keeping your history organized? How would branches help?

Branches allow you to make risky changes without messing up the project because you can have the master branch safe with the working code while you run tests on the other branch

-

How do the diagrams help you visualize the branch structure?

They help because they show how all the branches come together and relate to one another on a single project. If not for the diagram you could forget the purpose and changes existing in another branch and waste your time.

-

What is the result of merging two branches together? Why do we represent it in the diagram the way we do?

By merging the two branches we can add color and coins to the game. We represent it in a diagram because this makes it easy to understand what happened.

-

What are the pros and cons of Git’s automatic merging vs. always doing merges manually?

Git's automatic merging allows the coder to see the conflicts and make a decision on what to keep and what to scrap. This is much more efficient than having to look over all the code manually.

-

When would you want to use a remote repository rather than keeping all your work local?

When working in a group or working from multiple machines.

-

Why might you want to always pull changes manually rather than having Git automatically stay up-to-date with your remote repository?

Giving the user the choice has a smaller margin for error.

-

Describe the differences between forks, clones, and branches. When would you use one instead of another?

Branches separate your project into different copies of the same code so that you can always have one branch with working code, and another branch with experimental code. You should create a new branch everry time you are working on creating a new feature. A clone is a copy of the code with the commit history included. this is different from a fork because you can clone to a local repository, you can only fork from a github profile to another github profile.

-

What is the benefit of having a copy of the last known state of the remote stored locally?

So you can compare it with your changes and changes made by others to merge correctly.

-

How would you collaborate without using Git or GitHub? What would be easier, and what would be harder?

No, I would use Git and GitHub because I think having a record of all the changes would come in very handy.

-

When would you want to make changes in a separate branch rather than directly in master? What benefits does each approach have?

It keeps the master safe, and I would do this when trying to fix a bug or add a new risky feature.
