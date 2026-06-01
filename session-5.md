# 1. Write the Git command for each: initialize a repo, stage all files, commit with a message, push to remote, pull latest changes.


**a) Initialize a Git repository**


git init


**b) Stage all files**


git add .


**c) Commit with a message**


git commit -m "Initial commit"


**d) Push to remote repository**


git push origin main


**e) Pull latest changes**


git pull origin main


# 2. Difference Between `git fetch` and `git pull`

 1. **git fetch** downloads the latest changes from the remote repository but does not merge them into your local branch.
2. **git pull** downloads the latest changes and automatically merges them into your current local branch.



# 3. Create a GitHub Repository and Share the Link


https://github.com/PriyanshiTilva/Overview-of-IT-industry


# 4. Difference Between a Fork and a Pull Request

1.  A **Fork** is a personal copy of another user's repository in your GitHub account.
2.  A **Pull Request (PR)** is a request to merge your changes from a fork or branch into another repository or branch.



# 5. Create a new branch named feature-test, make one commit on it, and merge it back to the main branch. Write the commands you used.

**Commands  I have Used:**
# Create and switch to a new branch
git checkout -b feature-test

# Make changes and stage them
git add .

# Commit changes
git commit -m "Added feature-test changes"

# Switch back to main branch
git checkout main

# Merge the branch into main
git merge feature-test




