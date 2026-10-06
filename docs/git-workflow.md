\# Git Workflow



\## Overview



This project uses Git best practices to manage DevOps project changes.



\## Main Branch



The `main` branch contains stable and reviewed project changes.



\## Feature Branch



New features are developed in separate branches.



Example:



```bash

git checkout -b feature/ci-documentation

Initial DevOps project setup
Add CI/CD documentation
Document Git-based deployment strategy
git checkout main
git merge feature/ci-documentation
git remote add origin <github-repository-url>
git push origin main