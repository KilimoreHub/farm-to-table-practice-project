Git and GitHub Assignment Documentation
Task 1: Cloning and Forking
1. Cloning a Repository:
Chose the repository "example-repo" from GitHub.
Cloned
git clone https://github.com/BrityHemming/farm-to-table-practice-project
Explored the repository's structure, files, and history using Git commands like git log, git status, and ls.
2. Forking a Repository:
Forked the repository "example-repo" to my GitHub account.
Cloned the forked repository to my local machine using:
git clone https://github.com/KilimoreHub/farm-to-table-practice-project.git

Task 2: Managing Branches
3. Creating and Switching Branches:
Created a new branch named feature-update
git checkout -b feature-update

4. Making Changes and Committing:
Made changes to README.md file.
Added changes to staging area and committed:
git add README.md
git commit -m "Updated README with Task 2 changes"

5. Merging Changes:
Switched back to the main branch:
git checkout main

Merged changes from feature-update branch
git merge feature-update

Task 3: Handling Conflicts
6. Creating Conflicts:
Made changes to the same lines in README.md both in local repository and forked repository.
Committed changes to forked repository.
7. Resolving Conflicts:
Created a new branch resolve-conflict.
Manually resolved conflicts in README.md.
Added resolved file to staging area and committed.
Merged resolve-conflict branch into main.
Task 4: GitHub Pages
8. Enabling GitHub Pages:
Created a simple HTML file named index.html in the forked repository.
Enabled GitHub Pages for the repository, setting the source branch to main.
9. Accessing the Published Page:
Visited the GitHub Pages URL for the repository (https://KilimoreHub.github.io/farm-to-table-practice-project) and verified that index.html was accessible online.
Task 5: Open Source Exploration
10. Exploring Open Source Projects:
Explored the "example-open-source-project" on GitHub.


