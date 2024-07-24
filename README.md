# PLPBasicGitAssignment

This document outlines the steps and commands used for managing a Git repository, including setting up a repository, making changes, committing, and pushing to GitHub.

Steps and Commands
1.Create a Remote Repository
Go to GitHub and create a new repository.
Note the repository URL (e.g., https://github.com/your-username/your-repository.git).

###Initialize Local Directory
Create a new directory for your project:
mkdir your-project-directory

###Navigate to the directory:
cd your-project-directory
###Initialize a new Git repository:
git init
###Add Remote Repository
Add the remote repository URL:
git remote add origin https://github.com/your-username/your-repository.git


##2. Making Changes
###Create or Edit Files:
Example: Create a file named hello.txt.
###Check the Status of Your Repository:
git status

##3. Committing Changes
###Add Files to the Staging Area:
git add filename
###Example:
git add hello.txt
###Commit the Changes:
git commit -m "Your commit message"
###Example:
git commit -m "Add hello.txt with a greeting"

##4. Pushing Changes
###Set Upstream Branch (if needed):
git push --set-upstream origin branch-name
###Example:
git push --set-upstream origin main
###Push Changes to the Remote Repository:
git push

##5. Handling Issues
###Pull Changes from Remote:
git pull origin branch-name
###Example:
git pull origin main
###Handle Merge Conflicts:
Edit the conflicted files to resolve conflicts.
###Add the resolved files to the staging area:
git add filename
###Complete the merge commit:
git commit
###Update Remote Repository:
git push origin branch-name

