# Git practice project for Lexicon

Lexicon git practice project

# Git Commands Used in This Project

## git init

Initializes a new local Git repository in the project folder.

## git status

Shows the current state of the working directory and staging area.

## git add <file>

Stages specific files so they are ready to be committed.

## git add .

Stages all modified and new files in the project.

## touch <file_name>

Creates a new empty file.

## git commit -m "message"

Creates a snapshot of staged changes with a meaningful message.

## git branch -M main

Renames the default branch to main.

## git remote add origin <url>

Links the local repository to a remote GitHub repository.

## git push -u origin main

Pushes local commits to GitHub and sets the upstream branch.

## git push

Uploads committed changes to the remote repository.

## git reset --hard HEAD^

Resets current branch to the previous commit (HEAD^) and permanently discards all changes from the most recent commit.

## git push origin -f

Force pushes the local branch to the remote repository.

## .gitignore

Specifies files and folders that Git should ignore and not track.

## git log

Displays the commit history of the current branch, showing a list of commits in reverse chronological order.

---

# Task 3 – Branching and Merging

### git checkout -b feature-update

Creates a new branch and switches to it.

### git add <file>

Stages changes made in the new branch.

### git commit -m "message"

Commits changes in the feature branch.

### git merge feature-update

Merges the feature branch into the main branch.

### git branch <branch-name>

Creates a new branch with the given name at the current commit.

### git push --set-upstream origin <branch-name>

Pushes the local feature-update branch to the remote repository

### git checkout <branch-name>

Switches the working directory to the specified branch.
