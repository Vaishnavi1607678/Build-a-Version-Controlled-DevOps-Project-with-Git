# Build-a-Version-Controlled-DevOps-Project-with-Git

1. What is Version Control?
Version control, also known as source control, is the practice of tracking and managing changes to software code. It allows multiple contributors to work on a project without overwriting each other's changes. Version control also stores a complete history of modifications, so developers can easily roll back to previous versions if needed.

For example, imagine a team of five developers working on a single project. Without version control, managing the contributions, updates, and potential errors would be chaotic. Version control systems (VCS) like Git help resolve these problems by enabling smooth collaboration.

2. Why Version Control is Important in DevOps
In a DevOps workflow, rapid development and continuous integration are key. Version control ensures that code updates are tracked, tested, and integrated efficiently without disrupting the development process.

Version control systems like Git:
Promote collaboration: Multiple developers can work on different parts of the same project without stepping on each other’s toes.
Enhance transparency: Everyone on the team can see changes in real time and review the history of the codebase.
Enable rollback: If an update breaks something, you can easily revert to a previous working state.

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

