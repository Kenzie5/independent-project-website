## Contribute to the existing repository

### download a repository on GitHub to our machine
git clone https://github.com/Kenzie5/independent-project-website.git

### change into the `independent-project-website` directory
cd [directory for independent-project-website]

### create a new branch to store any new changes
git branch my-branch

### switch to that branch (line of development)
git checkout my-branch

### make changes, for example, edit `file1.md` and `file2.md` using the text editor

### stage the changed files
git add file1.md file2.md

### take a snapshot of the staging area (anything that's been added)
git commit -m "my snapshot"

### push changes to github
git push --set-upstream origin my-branch

## Contribute to an Existing Branch

### change into the `independent-project-website` directory
cd [directory for independent-project-website]

### update all remote tracking branches, and the currently checked out branch
git pull

### change into the existing branch called `feature-a`
git checkout feature-a

### make changes, for example, edit `file1.md` using the text editor

### stage the changed file
git add file1.md

### take a snapshot of the staging area
git commit -m "edit file1"

### push changes to github
git push