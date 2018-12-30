# Working directory
- area where all our files and directories are living all the time
- git status        whats going on at this time
- files in red are not tracked

# add files to staging area
- files and directories are explicity added to stating area
- git add <file-name>       stage file
- git rm --cached <file>    unstage file

# commit to .git repo
- this is where all our snapshots are stored
- git commit -m "<message>"     move file from staging area to .git repository

# add certain file extentions
- git add .<extension

# add all files to stage
- git add -A

# Ignore files
- make a directory call .gitignore
- add the file make to it

# list branches
- git branch

# create feature branch
- git checkout -b feature1

# change from branch to branch
- git checkout <branch name>

# Merge branches together
- git merge <branch name>

# delete branch
- git 

# github
- git remote add origin <url>
- git remote -v
- git push -u origin master