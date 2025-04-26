## 📚 All Important Git Commands

# Initialize a new Git repository
git init

# Check status of files
git status

# Add specific file to staging
git add filename.txt

# Add all files to staging
git add .

# Commit changes with a message
git commit -m "your commit message"

# Show commit history
git log

# Show differences (unstaged changes)
git diff

# List branches
git branch

# Create a new branch
git branch branch-name

# Switch to a branch
git checkout branch-name

# Create and switch to a new branch
git checkout -b branch-name

# Merge another branch into current branch
git merge branch-name

# Reset repository to a previous commit (Dangerous)
git reset --hard commit-id

# Stash uncommitted changes
git stash

# Apply stashed changes
git stash pop

# Clone a remote repository
git clone https://github.com/username/repository.git

# Pull latest changes from remote
git pull

# Push commits to remote repository
git push

------------------------------------------------------------



# Add a remote repository (link local repo to GitHub)
git remote add origin https://github.com/username/repository.git

# Push code for the first time to main branch
git push -u origin main

# Push a specific branch to GitHub
git push origin branch-name

# Pull latest changes from GitHub (main branch)
git pull origin main
