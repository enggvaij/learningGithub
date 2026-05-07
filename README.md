
<a name="top"></a>
# Git - GitHub Actions Using Python code Example
This article is for beginners who are willing to start to use Git and Github actions on their projects.
In this example we learn step by step how to use Git and Github actions.


## Table of contents
* [General info](#general-info)
* [Tech stack](#tech-stack)
* [Prerequisite](#prerequisite)
* [Setup](#setup)

## General info
This project is simple project to learn basics about Git and Git Hub actions


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
$ git clone https://github.com/[your-github-account-name]/[your-repository-name].git

```
#### Check list of files, folders present in to the github repository
List all files, folders present in to the github repository
```bash
$ ls
```


#### Go to Repository directory

```bash
$ cd [your-repository-name]

```

#### create new py file to build python sample codefile using any editor like vs code, pycharm
Save the file into the Repository directory


#### Add file to staging area
```bash
$ git add samplefile.py

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

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

[Back to top](#top)
