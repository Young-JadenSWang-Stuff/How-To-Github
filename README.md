# Quick Rundown on How-To Github
It is highly recommended that you read through this entire readme before working on any repo

### Here you'll learn 
* to fork a repo
* to create a branch
* to switch between branches
* to create pull requests

#### Github Basics
* _git pull_ retreives the most current version of the branch (may result in merge conflicts)
* _git add --all_ stages all changes to be commited
* _git commit_ -m "message" packages staged changes for push
* _git commit_ -a -m "message" combines the last two commands
* _git push_ pushes all changes to the repo

#### Forking a repository
You won't always be given write permissions on repositories for the following reasons
* avoid griefing (malicious changes)
* avoid code colisions
* simultaneous access of code from unrelated parties

To avoid this, you'll have to *fork a repository*
Essentially, you are making a copy of a repository which you can manipulate and change to your heart's content

![Alt Text](https://media.giphy.com/media/3d4Ib9vKxMmjhJh7Q5/giphy.gif))

#### Creating and navigating branches
Sometimes, You want to categorize your work, ie. creating a menu or optimizing game-winning calculation

To do this, you'll have to do something called branching. 
A branch allows you to - well, branch - off from your master (branch), do some work, and merge the branch together again. 

In console, after cd'ing to your target repository, go through the following commands
>> git checkout 

this command shows you which branch you are currently 

>> git checkout [branchname]

this command switches you to [branchname]

>> git checkout -b [branchname]

this _creates_ a new branch
