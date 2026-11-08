# Web_dev_lab

This repository contains the lab work for **Programming for Web Development – I**.

## Module 1: Terminal, Git & GitHub

### P1: Project folder and terminal navigation
Completed.

### P2: Portfolio repo with an initial commit
A simple personal portfolio page was created and committed.

### P3: Feature-branch Git workflow
This task demonstrates the Git feature branch workflow using a `feature/about-page` branch.

## P3 Git workflow

```bash
git checkout -b feature/about-page
git status
git add .
git commit -m "Add about section"
git checkout main
git merge feature/about-page
git push origin main
```

## Branch workflow summary
- Create a feature branch for a new change.
- Make edits and commit them.
- Switch back to `main`.
- Merge the feature branch into `main`.
- Push the final result to GitHub.
