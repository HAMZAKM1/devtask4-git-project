# Task 4: Git Version-Controlled DevOps Project

## Objective
Manage a DevOps project using Git best practices.

## Project Structure

## Files Overview
- **script.sh** – Demo shell script simulating a DevOps task.
- **config.yaml** – Sample configuration file for the project.
- **.gitignore** – Ignores logs, temp files, VSCode settings, and node_modules.

## Steps Completed
1. Initialized Git repository locally.
2. Created project structure and added `.gitignore`.
3. Committed changes with meaningful messages.
4. Created branches:
   - `main` – production-ready branch
   - `dev` – development branch
   - `feature` – feature branch for new changes
5. Pushed all branches to GitHub.
6. Demonstrated pull request workflow (`feature → dev → main`).
7. Added Git tags for versioning (e.g., `v1.0`).

## Commands Used
```bash
git init
git add .
git commit -m "Initial commit: add project structure"
git branch dev
git branch feature
git push -u origin main
git push -u origin dev
git push -u origin feature
git tag v1.0
git push origin v1.0
