# Git,Github and Linux 
Sumary of Git and Github command line

https://rogerdudler.github.io/git-guide/
https://www.notion.so/zarkom/Introduction-to-Git-ac396a0697704709a12b6a0e545db049

### git config
- show git user name: git config user.name
- show git user email:  git config user.email
- set git user name: git config --global user.name "tên cc gì đó"
- set git user email: git config --global user.name tênemail
- open help to see more command: git config --help

### git init
-> initialize a repository

###  git status
-> check change in files since last commit

### git add
- thêm file vào stage để chuẩn bị commit: git add tênfile (git add text1.txt)
+ add all file with the txt extension: git add *txt
+ add all file: git add --all (toàn bộ files trong toàn bộ folder)

### git commit
-> save snapshot: git commit -m "message"
- skip stage area: git commit -am "message"

### git ls-files
- show information about files in the index and the working tree

### git rm 
- delete file (still need to commit to 100% delete): git rm tenfile

### git log
-> view history of commit
- git log --author=tenauthor: view history of commit of specific author

### git clone
- create a working copy of a local repository: git clone duonglink 

### git branch
-> check all branches
- git branch ten_branch: create new branch
- git checkout ten_branch: move HEAD to different branch

### git restore
- remove files from stage before commit: git restore --staged filename

### git checkout
- return to the git commit hash : git checkout commit-hash (git checkout 2ac7e955f9a53b0b67de6d492f8492e868eea41e)
-> git checkout master: move HEAD back to master

### git reflog
- toàn bộ lịch sử git
- git checkout HEAD@{...} (trong 3 chấm điền số) để quay lại

### git push (up code lên github)
- git branch main
- git remote add origin https://github.com/minhkhangIT/cvgh.git (cái link của git)
- git push -u origin main

## Linux:
- rm file_name: delete the file (rm file1.txt)

