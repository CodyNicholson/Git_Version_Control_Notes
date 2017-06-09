# Git Tutorial for SE450

### Agenda:

- What is Git? Why should we use it? Why is it important in the context of Object Oriented Software Development? - A way for us to develop incrementally, and makes bugs easy to track and fix which saves us time

<img src="https://github.com/CodyNicholson/Software_Development/blob/master/Git_Version_Control/featureComparisonChart.jpg" style="width: 20px;">

- Installing Git, setting up your workspace, follow video links

Windows - [https://www.youtube.com/watch?v=IfLhXM4RnB4](https://www.youtube.com/watch?v=IfLhXM4RnB4 "Link to Windows Git setup video")

<a href="https://www.youtube.com/watch?v=IfLhXM4RnB4" target="_blank"><img src="http://img.youtube.com/vi/IfLhXM4RnB4/0.jpg" alt="A link to Windows Git setup video" width="240" height="180" border="10" /></a>

Mac/Ubuntu - [https://www.youtube.com/watch?v=s_eFuGauy6k](https://www.youtube.com/watch?v=s_eFuGauy6k "Link to Mac/Ubuntu Git setup video")

<a href="https://www.youtube.com/watch?v=s_eFuGauy6k" target="_blank"><img src="http://img.youtube.com/vi/s_eFuGauy6k/0.jpg" alt="A link to Mac/Ubuntu Git setup video" width="240" height="180" border="10" /></a>

***

## Using Git locally


- Creating a git repository using: git init

- The .git folder that stores all your changes

- Basic command line commands navigate through directories, move files, and delete files: cd, mv, rm, mkdir

- Showing the status of your repository using: git status

- Compares your working directory to the directory saved in the .git folder

- Adding files to staging and tracking files with git using: git add "file, or '.' to add all untracked files in dir"

![alt tag](https://github.com/CodyNicholson/Software_Development/blob/master/Git_Version_Control/workingdirStagingGitdir.png)

```
- Commiting code to the .git directory using: git commit -m 'Commit Message'

- Viewing your commit history using: git log

- Notice author, dates, commit Id

- Finding the difference between commits using: git diff <old commit id> <newer commit id>

- Shorthand command to view the difference between the past and current commit: git show

- This is all great, but what happens when we find an error?!

- Reverting back to a previous commit using: git checkout <commit id>

- The most important benefit for our project and for working on a team, branches: git checkout -b 'New feature name'

- Why make a branch?

- Switching between branches using: git checkout 'branch name'

- Commit tree on the board. Shows all the commits and the place when the branch splits off

- Merging the new feature branch back into the master branch (Only merge when you are in the master branch) using: git merge master 'branch name'

- Is this useful for the final project? It will help with counting hours, and it will help you develop an important skill. Since you should be working alone on this project it won't be completely necessary, but you should be able to imagine how helpful Git would be if you used in on a team.
```
***

## How to put all this stuff online using Github

```
- Create an empty repository on Github to put your project in

- Copy the url for the repository by clicking the "Clone or Download" button in your empty repository on Github

- Create a git remote for your local git repository using: git remote add 'name' 'url from Github clone or download button'

- Upload all of your code to the github repository online by using: git push 'remote name' 'branch name'

- Check out your uploaded code online!
```
