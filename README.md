# Build-a-Version-Controlled-DevOps-Project-with-Git
1. Initialize Repository
Create a new folder on your local machine.
Open terminal and run:git init
Create a new repository on GitHub.
Link the local repo to GitHub:git remote add origin https://github.com/your-username/your-repo.git

2. Create Branch Structure
Create the following branches:
git checkout -b main
git checkout -b dev
git checkout -b feature

Push branches to GitHub:
git push origin main
git push origin dev
git push origin feature

3. Add Project Files
Add files (scripts/configs/notes).

4. Use Pull Requests for Merging
Push changes to the feature branch.
Create a Pull Request (PR) on GitHub from feature → dev, then later dev → main.

