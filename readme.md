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

### 2) Commit your changes

`git commit -m "message"`