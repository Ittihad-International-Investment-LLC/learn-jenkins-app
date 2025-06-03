# Git Commands to Initialize and Push Project to GitHub

This document outlines the steps to initialize a local Git repository and push it to the GitHub repository:  
`https://github.com/Ittihad-International-Investment-LLC/learn-jenkins-app.git`

## 🔧 Steps

```bash
# Initialize Git repository
git init

# Create a new branch named 'main' and switch to it
git checkout -b main

# Add all files to the staging area
git add .

# Commit the files
git commit -m "Initial commit"

# Add the remote GitHub repository
git remote add origin https://github.com/Ittihad-International-Investment-LLC/learn-jenkins-app.git

# Push the code to GitHub
git push -u origin main

# (Optional) If a Git repository was mistakenly nested inside this one
# Remove the embedded Git repo from staging
git rm --cached -r learn-jenkins-app
