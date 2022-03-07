# GitHub Command Line Basics

`git status` checks for any updates or changes.

`git add .` adds all the files and folders with changes.

`git commit -m "your message here"` logs what changes you made.

`git push origin main` pushes the changes to the main branch.

`git checkout -b branchName` creates a new branch (you name the branchName whatever you want).

`git checkout -b addFrills` will create a branch named `addFrills`

`git push origin addFrills` pushes changes to a branch named `addFrills`.

`git checkout main` allows you to switch from `addFrills` to `main`. Remember you must first add, commit and push the changes made on `addFrills`.

After merging a branch with the main branch, you must `pull` the main branch from GitHub.com (the cloud) to your local drive. Use the following command:

`git pull main`
