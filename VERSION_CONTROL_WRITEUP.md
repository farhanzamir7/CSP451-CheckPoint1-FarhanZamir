# Version Control Systems: Understanding Git and GitHub

## Introduction to Version Control
Version control is a system that helps developers track, manage, and organize changes made to files over time. In software development, projects often change many times as bugs are fixed, features are added, and documentation is improved. Without version control, developers may lose track of what changed, who changed it, and why the change happened. Git is one of the most common version control tools because it allows developers to save project history through commits and work safely without overwriting important files.

## How Version Control Tracks Changes
Git tracks changes by recording snapshots of a project. Each saved snapshot is called a commit. A commit captures the files that changed, the author of the change, the date and time, and a message explaining the purpose of the change. Git identifies each commit with a unique hash value, commonly called a SHA. This makes every point in the project history traceable. For example, if a student adds an HTML page and later breaks the navigation, Git can show exactly which commit introduced the issue. This helps developers compare versions, review old code, and restore previous work when needed.

## Three Collaboration Benefits with Examples

### 1. Parallel Work Through Branching
Git allows multiple developers to work on separate branches at the same time. For example, one developer can work on a login page while another improves the homepage. Their work stays separate until it is ready to be merged. This reduces the chance of unfinished code affecting the main project.

### 2. Code Review Through Pull Requests
GitHub supports pull requests, which allow team members to review changes before they are merged. For example, a student can create a pull request for an about page, and the instructor or teammate can review the code, suggest improvements, and approve it before it becomes part of the main branch.

### 3. Safer Recovery When Problems Happen
Version control helps teams recover from mistakes. For example, if a commit removes important CSS styles by accident, Git can compare the old and new versions and restore the missing code. This is safer than manually guessing what changed.

## Git's Backup and Recovery Mechanisms
Git stores project history inside the hidden `.git` folder. This folder contains commits, branches, configuration, and references needed to rebuild the project history. Git is distributed, meaning every cloned repository contains a full copy of the project history. If GitHub is unavailable or one computer fails, another clone can still contain the full repository. Git also provides recovery commands. `git reflog` can show recent branch movements, `git reset` can move a branch back to an earlier commit, `git revert` can safely undo a commit by creating a new commit, and `git fsck` can help check repository object integrity.

## Difference Between Git and GitHub

| Git | GitHub |
|---|---|
| Version control software | Online hosting platform |
| Runs locally on a computer | Runs in the cloud through a website |
| Can work offline | Requires internet for remote collaboration |
| Tracks commits and branches | Adds pull requests, issues, reviews, and repository settings |
| Used through command line or tools | Used through browser, GitHub CLI, and integrations |

## Conclusion
Version control is important because it gives developers a clear history of project changes, supports collaboration, and provides recovery options when mistakes happen. Git manages the local version control system, while GitHub provides an online platform for sharing, reviewing, and managing repositories.
