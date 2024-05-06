# Configure global username and email (should match Github account for remote access)
git config --global user.name "my-name"
git config --global user.email "my-name.email@example.com"

# Initialize local Git repository from project folder
git init

# Add new remote repository URL under the name 'origin'
git remote add origin https://github.com/my-name/new-repo.git

# Stage all changes in working directory for the next commit
git add .

# Commit staged files with message detailing list of changes
git commit -m "Description of changes"

# Set default upstream branch for 'git push' to 'main'
git push --set-upstream origin main

# Push local commits to GitHub & update the 'main' branch
git push

# Pull latest changes from GitHub to local repository
git pull origin main
