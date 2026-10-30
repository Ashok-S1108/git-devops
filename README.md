# Build a Version-Controlled DevOps Project with Git

## Project Overview

This project demonstrates how to manage a DevOps project using Git and GitHub version control best practices.

It covers repository initialization, branch management, meaningful commits, Pull Requests, merging branches, and project documentation.

## Objectives

- Understand Git and GitHub workflows.
- Initialize and manage a Git repository.
- Create and manage multiple branches.
- Track project changes using meaningful commits.
- Use Pull Requests to merge branches.
- Maintain project documentation using Markdown.
- Understand Git tags and `.gitignore`.

## Tools and Technologies

- Git
- GitHub
- Ubuntu Linux
- Markdown

## Project Structure

```text
task-4-git-devops/
│
├── README.md
├── .gitignore
│
├── docs/
│   └── git-workflow.md
│
├── src/
│   └── app.js
│
└── screenshots/
```

## Git Branching Strategy

This project uses three main branches:

### 1. Main Branch
Contains the stable and final version of the project.

### 2. Dev Branch
Used for development and integration of features.

### 3. Feature Branch
Used to develop new features and make changes before merging into the development branch.

## Git Workflow

The following workflow is used:

1. Initialize a local Git repository.
2. Create a GitHub repository.
3. Connect the local repository to GitHub.
4. Create `main`, `dev`, and `feature` branches.
5. Make changes in the feature branch.
6. Stage and commit changes.
7. Push the feature branch to GitHub.
8. Create a Pull Request from `feature` to `dev`.
9. Merge the feature branch into dev.
10. Create a Pull Request from `dev` to `main`.
11. Merge the development branch into main.

## Git Commands Used

| Command | Description |
|---|---|
| `git init` | Initialize repository |
| `git add .` | Stage changes |
| `git commit -m "message"` | Commit changes |
| `git branch` | List branches |
| `git switch` | Switch branches |
| `git push` | Push changes to GitHub |
| `git pull` | Pull remote changes |
| `git merge` | Merge branches |
| `git log --oneline` | View commit history |
| `git tag v1.0.0` | Create a version tag |
| `git stash` | Temporarily save changes |

## Pull Request Workflow

Pull Requests are used to review and merge code changes.

The project follows this process:

- `feature` → `dev`
- `dev` → `main`

This workflow helps maintain organized development and stable project code.

## Project Deliverables

- GitHub repository.
- Three Git branches: main, dev, and feature.
- Meaningful commit history.
- Pull Requests and merged branches.
- README.md documentation.
- `.gitignore` configuration.
- Git version tags.
- Markdown project documentation.

## Learning Outcomes

Through this project, I learned:

- Git repository management.
- Branching and merging strategies.
- GitHub collaboration workflows.
- Creating and managing Pull Requests.
- Tracking changes through commits.
- Maintaining project documentation.

