# What is Git?

- Version Control System (VCS) for tracking changes in computer files
- Distributed version control
- Who made what changes and when
- Revert back at any time
- Local and remote repositories

* You have a repository on your local machine where you do your work, and then you push your changes to the remote repo. \*

# Concepts of Git

- Keeps track of code history
- Take "snapshots" of your files
- You decide when to take a snapshot by making a "commit"
- You can visit any snapshot at any time
- You can stage files before committing

# COMMANDS

# Initialize Local Git Repository

git init

# Add Files to Index

git add [file]
i.e. git add index.html

# Check Status of Working Tree

git status

# Commit Changes to Index

git commit

# Push to Remote Repository

git push

# Pull Latest Changes From Remote Repository

git pull

# Clone Repository Into Current Directory

git clone [link]

# Install Git

http://git-scm.com/download/win

- Git Bash > Command Line. \*

# Check Version

git --version

# Create File

touch [filename]
i.e. touch index.html

- Create your file // touch index.html
- Write your code
- Open Git Bash in the same directory
- Run 'git init'

# Set Your Name and Email w/ Git

git config --global user.name 'Chris Wick'
git config --global user.email 'cwickwriting@gmail.com'

# Add File to Git Repository

git add [filename]
i.e. git add app.js

# Check File Status

git status

# Remove File From Repository

git rm --cached [filename]
i.e. git rm --caches app.js

# Add All Files w/ Specific Extension to Repository

git add _[extension]
i.e. git add _.html

# Add All Files to Repository

git add .

# General Flow

- Make changes to file(s)
- Add files to repository // git add [filename]
- Commit changes // git commit
- Add description of changes // 'Added Login Form.'
- Close editor window
  ALTERNATIVELY
- Make changes to file(s)
- Add files to repository // git add [filename]
- Commit changes AND add description // git commit -m 'Added Login Form'

- Create '.gitignore' to exclude certain files/folders from being pushed to the respositories // touch .gitignore
- Add file name // log.txt
- Add folder name // /dir2 (Ensure you are in the right folder, i.e. you might have to type './dir2')
- Alternatively, ignore all of a certain file type // \*.txt

* Create branches so you can make changes without affecting the original code. // git branch [branchname]
  i.e. git branch login

# Commit Changes to Master

git merge [branch]
i.e. git merge login

# Display Remote Repository

git remote

# Add GitHub Repository

git remote add origin [link]

# Push Changes

git push -u origin main

- Now, you can just type 'git push' to push directly to the main repository. \*

# Add README

touch README.md
