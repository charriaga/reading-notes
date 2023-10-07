# Git Basics

## Version Control

A **Version Control System** is a type of system which is used to organize, maintain, and revisit varient versions of code. This can allow you to revert a file to previous versions and compare changes made over time to code.

There are various types of version control.

- **Local Version Control** aka Local Version Control System (Local VCS). One database on a hard drive that stores versions to a file.

- **Centralized Version Control** aka Centralized Version Control System (CVCS). A database of all file versions saved to a server with multiple clients. This allows for smoother collaboration. However if the server fails, the system fails.

- **Distributed Version Control** aka Distributed Version Control System (DVCS). DVCS makes up for the system failure vulnerability of CVCS by allowing clients to create mirrors of repositories which can replace any data lost in an instance of server failure.

## What is Git?

Git is a DVCS that works by creating snapshot of files and storing references to it. A snapshot is created every time you commit a new version of your file.

Git is designed to minimize the potential loss of a file.

### File States

Files in Git have 3 main potential states:

- **Committed:** File version is stored in a local database.

- **Modified:** The file has been modified but has yet to be committed to a database.

- **Staged:** A flagged modified file set to be committed in the next snapshot.

### Cloning

Cloning creates a copy of a Git repository. The act of cloning copies not only the latest version of a file but all versions of a file.

## ACP

ACP stands for "Add, Commit, Push". It is the process of staging, tracking, committing, a file into git and then cloning it into GitHub.

### Tracking and Staging

Use the command `git add` on the command line to track and stage a file.

- To track and stage a single file, type the file name after the "git add" command.

- To track and stage all files, add `*` as an argument to the "git add" command.

- To track and stage all modified files, add `.` as an argument to the "git add" command.

### Committing

Use the `git commit` command to commit a file into Git.

- use the `-m` argument to add a message explaining what you did in the file version.

- use the `-a` argument to commit all modifications to tracked files.

### Pushing

Use the command `git push` to push changes to a separate remote repository.

- The argument `origin main` should be added in order to move the cloned repository from its origin to a "main" branch of the remote repository.
