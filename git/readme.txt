# Git – Version Control System

## Introduction

Git is a distributed version control system used to track changes in files and manage source code during software development. It helps developers maintain project history, recover previous versions, work on different features simultaneously, and collaborate efficiently.

As part of the Technical Writing (TW) course, I learned the fundamentals of version control, Git architecture, repository management, and various Git commands used in software development.

## Topics Covered

### 1. Introduction to Version Control
- Understanding version control and its importance.
- Need for tracking changes in software projects.
- Benefits of version control.
- Types of version control systems: Local, Centralized, and Distributed.

### 2. Introduction to Git
- Understanding Git as a distributed version control system.
- Difference between Git and GitHub.
- Understanding repositories, commits, and project history.
- Working with Git locally without an internet connection.

### 3. Git Installation and Configuration
- Installing Git on Windows, Linux, and macOS.
- Verifying installation using `git --version`.
- Configuring username and email using `git config`.
- Checking configuration using `git config --list`.

### 4. Creating and Managing Repositories
- Creating project directories using `mkdir`.
- Navigating directories using `cd`.
- Initializing repositories using `git init`.
- Understanding the hidden `.git` directory.
- Checking repository status using `git status`.

### 5. Git Architecture and Workflow
- Understanding the Working Directory, Staging Area, and Repository.
- Understanding how changes move between these three areas.
- Staging files using `git add`.
- Recording changes using `git commit`.
- Understanding commits as snapshots of project changes.

### 6. Tracking and Managing Files
- Adding individual files using `git add filename`.
- Staging all changes using `git add .`.
- Listing tracked files using `git ls-files`.
- Ignoring unnecessary files using `.gitignore`.
- Renaming files using `git mv`.
- Removing tracked files using `git rm`.

### 7. Viewing and Comparing Changes
- Checking changes using `git status`.
- Viewing commit history using `git log`.
- Viewing compact history using `git log --oneline`.
- Comparing changes using `git diff`.
- Comparing staged changes using `git diff --staged`.

### 8. Undoing and Reverting Changes
- Unstaging changes using `git restore --staged`.
- Discarding unstaged changes using `git restore`.
- Reverting a commit using `git revert`.
- Understanding the difference between restoring and reverting changes.

### 9. Branching and Merging
- Understanding branches and their importance.
- Creating and listing branches.
- Switching between branches using `git switch`.
- Creating and switching to a new branch using `git switch -c`.
- Merging branches using `git merge`.
- Understanding merge conflicts and their resolution.
- Understanding the difference between merging and rebasing.

### 10. Git Stash and Commit Management
- Temporarily storing uncommitted changes using `git stash`.
- Viewing and restoring stashed changes.
- Applying and managing commits.
- Writing meaningful commit messages.

### 11. Git Tags and Releases
- Understanding Git tags.
- Creating annotated tags using `git tag -a`.
- Viewing tag information using `git show`.
- Pushing tags to remote repositories.
- Understanding semantic versioning.

### 12. Remote Repository Operations
- Understanding local and remote repositories.
- Adding remote connections using `git remote add`.
- Checking remote connections using `git remote -v`.
- Uploading changes using `git push`.
- Downloading updates using `git fetch` and `git pull`.
- Cloning repositories using `git clone`.

### 13. Common Git Errors and Best Practices
- Understanding untracked files and staging errors.
- Handling rejected pushes and merge conflicts.
- Writing clear and meaningful commit messages.
- Committing changes frequently.
- Reviewing changes before committing.
- Avoiding passwords, API keys, and unnecessary generated files in repositories.

## Important Git Commands

| Command | Purpose |
|---|---|
| `git init` | Initialize a repository |
| `git status` | Check repository status |
| `git add .` | Stage all changes |
| `git commit -m "message"` | Create a commit |
| `git log` | View commit history |
| `git diff` | Compare changes |
| `git branch` | List branches |
| `git switch` | Switch branches |
| `git merge` | Merge branches |
| `git stash` | Temporarily save changes |
| `git restore` | Restore file contents |
| `git revert` | Reverse a commit |
| `git clone` | Clone a repository |
| `git push` | Upload commits |
| `git pull` | Fetch and integrate updates |
| `git fetch` | Download remote updates |
| `git remote -v` | View remote connections |
| `git tag` | View tags |

## Learning Outcome

Through this topic, I learned how to use Git for version control, manage repositories, track file changes, create commits, work with branches, resolve changes, and execute Git commands through the terminal. I also gained practical knowledge of maintaining project history and managing software development workflows.

