# Git Commands with Uses

# 1. Initial Setup

# Create a Directory and Navigate to it
mkdir shahbaz-git  # Creates a new directory named 'shahbaz-git'
cd shahbaz-git/   # Changes the current directory to 'shahbaz-git'

# Initialize a Git Repository
git init  # Initializes a new Git repository in the current directory

# 2. File Operations

# Create Files
touch nibba.txt  # Creates an empty file named 'nibba.txt'
touch nibbi.txt  # Creates an empty file named 'nibbi.txt'

# Check File Status
git status  # Displays the state of the working directory and staging area

# 3. Staging and Unstaging Files

# Stage Files
git add nibbi.txt  # Adds 'nibbi.txt' to the staging area
git add nibba.txt  # Adds 'nibba.txt' to the staging area

# Unstage a File
git rm --cached nibba.txt  # Removes 'nibba.txt' from the staging area

# 4. Committing Changes

# Commit Staged Files
git commit -m "Adding Nibba Nibbi"  # Commits the staged changes with a message

# Additional Commits
git commit -m "Demo file adding"  # Commits with a message
git commit -m "changes"  # Commits with a message

# 5. Configuring Git

# Set Global User Information
git config --global user.name "Shahbaz-Valsangkar"  # Sets the global username for Git
git config --global user.email "vshahbaz555@gmail.com"  # Sets the global email for Git

# 6. Viewing the Log

# View Commit History
git log  # Displays the commit history of the repository
git log --oneline  # Shows the commit history in a condensed form

# 7. Branch Management

# Create a New Branch
git checkout -b dev  # Creates and switches to a new branch named 'dev'

# Switch Between Branches
git checkout master  # Switches to the 'master' branch
git checkout dev  # Switches to the 'dev' branch

# View All Branches
git branch  # Lists all branches in the repository

# 8. Restore Files

# Restore Modified Files
git restore shahbaz.txt  # Restores 'shahbaz.txt' to the last committed state

# 9. Adding Remote Repository

# Add Remote Repository
git remote add origin git@github.com:Shahbaz-Valsangkar/dev.git  # Connects local repository to remote
