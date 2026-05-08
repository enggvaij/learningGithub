
<a name="top"></a>
# Git - GitHub Actions Using Python code Example
This article is for beginners who are willing to start to use Git and Github actions on their projects.
In this example we learn step by step how to use Git and Github actions.


## Table of contents
* [General info](#general-info)
* [Tech stack](#tech-stack)
* [Prerequisite](#prerequisite)
* [Setup](#setup)
* [Git Branch](#gi-branch)
*  [Delete the branch](#delete-the-branch)  
* [Final Statement](#final-statement)

## General info
This project is simple project to learn basics about Git and Git Hub actions

In this git tutorial we will learn how to commit a code change locally using git commit and how to upload it to remote using git push. Here is the list of topics we are covering in this git tutorial,
1) how to create new github repository
2) push code to this repository using git push command
3) go over these commands in detail,
git add
git commit
git push
git difftool


## Tech Stack

**Client:** python

**Server:** local machine, command promt, git bash

**Website Account** https://github.com/

## Prerequisite
1. Login into your computer.
2. Go to [Git](https://github.com/)
3. Sign in or create the new account onto the link.
4. create the respositatiory in to your account . 
5. Install git on your computer using website https://git-scm.com/install/
6. Launch the git bash promt
   
$ 

7. using cd [working directry name] command , Go to the project directory

```bash
  cd [d:code]my-project
```

   
	
## Setup

### Run Locally


#### Clone the project
To connect with your working directory to the github account website remotely,copy and run the below command on your git bash promt . Make the required changes as per your account relative.

```bash
$ git clone https://github.com/enggvaij[your-github-account-name]/learningGitHub[your-repository-name].git

```
#### Check list of files, folders present in to the github repository
List all files, folders present in to the github repository
```bash
$ ls
```


#### Go to Repository directory

```bash
$ cd learninggithub
```

#### create new py file to build python sample codefile using any editor like vs code, pycharm
Save the file into the Repository directory


#### Add file to staging area
```bash
$ git add gittest.py

```

#### Commit file to version database on local computer 
```bash
$ git commit -m "New file sample file commited inntialy"

```
#### push finally to github remote repository website
```bash
$ git push
```

#### check status 
```bash
$ git status
```

#### check log 
```bash
$ git log
```

## Git Branch
### List available branch
```bash
$ git branch
```

### List create new branch
```bash
$ git branch new-branch-name
```

### Switch to new branch
```bash
$ git checkout new-branch-name
```

OR 

```bash
$ git switch new-branch-name
```

### Create and Switch to new branch
```bash
$ git checkout -b new-branch-name
```


### Switch to main branch
```bash
$ git checkout main
```

OR 

```bash
$ git switch main
```
## Make changes / edit the file in new branch

### Step 1:  

```bash
$ git checkout new-branch-name
```

OR 

```bash
$ git switch new-branch-name
```

### Step 2:  
 Edit the code changes / other changes to file in new-branch-name


 ### Step 3:  
 Add file to staging area
 
```bash
$ git add gittest.py
```
 ### Step 4:  
Commit file to database 
 
```bash
$ git commit -m "chnages made 1"
```

 ### Step 5:  
Merge changes to main branch

Swtich to main branch
```bash
$ git checkout main
```
 
```bash
$ git merge new-branch-name
```
 ### Step 6:  
Push Main branch files to Git hub remote space cloud

```bash
$ git push
```

 ### Step 7:  
Push the created new branch in my case new branch name is thirsty to github remote cloud

```bash
$ git push --set-upstream origin thirsty[new-branch-name]
```

 ### Delete the branch  

```bash
$ git branch -d dummy[branch name]
```

## Final Statement

I have created the git hub account on github website.
I have installed the git for local machine. 
Created the sample python simplae code file and add commit push to the remote cloud sotoreage on github website.

[Back to top](#top)
