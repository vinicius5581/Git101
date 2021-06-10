# Git Basics

## Creating a new project (git repository) on computer

### 1) Create folder
`mkdir projectFolderName`

### 2) Go inside the folder
`cd projectFolderName`

### 3) Make folder a git repository

This step will add a `.git` folder to your projectFolderName.

`git init`



## Commiting changes to git repository

### 1) Create a file and add content to it

`touch example.txt`

Create a file and add content to it. For example, create `example.txt` and type `Hello World` in it.

### 2) Add file to stage

You can add individual files:
`git add example.txt` 

You can add multipe files:
`git add example.txt file-2 file-3 file-4` 

You can add all the files:
`git add .`

### 3) Commit your changes

`git commit -m "message"`


### 4) View log

`git log`


## Creating repository on github and sync with local

### 1) Create repository on github

### 2) Setup local repository origin

`git remote add origin project-github-url`

example:
`git remote add origin https://github.com/vinicius5581/Git101.git`

### 3) Pushing commits from local to github

`git push origin master`

