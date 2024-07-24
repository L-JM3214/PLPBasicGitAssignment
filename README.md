# PLPBasicGitAssignment
Git and GitHub Workflow
This document outlines the steps and commands used for managing a Git repository, including setting up a repository, making changes, committing, and pushing to GitHub.

Steps and Commands
1. Setting Up the Repository
Clone the Repository (if applicable):

sh
Copy code
git clone https://github.com/your-username/your-repository.git
Navigate to the Repository Directory:

sh
Copy code
cd your-repository
Check the Current Branch:

sh
Copy code
git branch
2. Making Changes
Create or Edit Files:

Example: Create a file named hello.txt.
Check the Status of Your Repository:

sh
Copy code
git status
3. Committing Changes
Add Files to the Staging Area:

sh
Copy code
git add filename
Example:

sh
Copy code
git add hello.txt
Commit the Changes:

sh
Copy code
git commit -m "Your commit message"
Example:

sh
Copy code
git commit -m "Add hello.txt with a greeting"
4. Pushing Changes
Set Upstream Branch (if needed):

sh
Copy code
git push --set-upstream origin branch-name
Example:

sh
Copy code
git push --set-upstream origin main
Push Changes to the Remote Repository:

sh
Copy code
git push
5. Handling Issues
Pull Changes from Remote:

sh
Copy code
git pull origin branch-name
Example:

sh
Copy code
git pull origin main
Handle Merge Conflicts:

Edit the conflicted files to resolve conflicts.
Add the resolved files to the staging area:
sh
Copy code
git add filename
Complete the merge commit:
sh
Copy code
git commit
Update Remote Repository:

sh
Copy code
git push origin branch-name
Additional Resources
