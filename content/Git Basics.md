---
title: Git Basics
tags: 
- ref
---









# Start



#### Check Version

`git --version`



#### Get help

`git --help`



#### Initialize a local repository

```

cd ~/Desktop/git-demo-example  

git init

```



![gitAddAndCommit](https://miro.medium.com/max/630/1*wEl8mJCopfqwyvaAcqExPA.png)



#### To add files to staging area

```

git add a.xxx

git add a.xxx b.xxx

git add .

```



#### Check files in the staging area

`git status`



#### Commit

`git commit -m “your commit message”`



#### Review All Commits Made

`git log`

- ##### Put in one line

	`git log --pretty=oneline`

- ##### - filter by author

	`git log — author=username`



# Branching



![gitBranch](https://miro.medium.com/max/630/1*ceMLgxzNfGhJJVOEijEGYw.png)



#### Create a branch

`git branch test`



#### Check what branch you are on

`git branch`



#### Move to a certain branch

`git checkout test`



#### Check the difference between branches

*source branch first, target branch second*

`git diff test master`



#### Merge to master branch

*You need to move to master branch(target branch) and merge another branch into itself*

```

git checkout master  

git merge test

```



#### Delete a branch

`git branch -d <branch>`



# Remote pushing



![gitPushPull](https://miro.medium.com/max/630/1*-dwyb19VcyMWgrRTGcr0ZQ.png)



#### Link to a remote git repository

`git remote add origin [repository url]`



#### Move code in local repository to remote repository

`git push -u origin master`



#### pull from the remote master branch

`git pull origin master` 



#### Cloning a remote repository to local

*Do this when you don't have any local files*

`git clone [repository url]`







## 🗂 Resources 



Git cheat sheet

[https://education.github.com/git-cheat-sheet-education.pdf](https://education.github.com/git-cheat-sheet-education.pdf)





