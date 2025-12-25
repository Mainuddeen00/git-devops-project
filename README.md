# Git DevOps Project

## 📌 Project Overview
This project demonstrates the practical usage of **Git Bash** and **GitHub** for version control as part of the **Fundamentals of DevOps (INT331)** course.

The main objective is to implement Git concepts in a real-world workflow, including repository initialization, branching strategies, merging, conflict resolution, and maintaining a clean commit history.

---

## 🎯 Project Focus & Evaluation
* **Git Workflow:** Proper use of local and remote repositories.
* **Branching Strategy:** Industry-standard branch management.
* **Commits:** Meaningful and atomic commit history.
* **Merges & Conflict Resolution:** Handling code integration and manual conflict fixes.
* **GitHub Usage:** Repository management and synchronization.

---

## 🚀 Features (Sample Application)
* Interactive calculator UI with responsive design.
* Keyboard input support.
* Memory functions (MC, MR, M+, M-).
* Error handling (e.g., division by zero).
* Runs completely in the browser (No backend required).

---

## 🛠️ Technologies Used
* **Git Bash** (Command Line Interface)
* **GitHub** (Remote Hosting)
* **HTML / CSS / JavaScript** (Application Stack)
* **GitHub Pages** (Deployment)

---

## 🧠 Git Concepts Covered
- [x] Repository initialization (`git init`)
- [x] Feature-based branching strategy
- [x] Merging branches into `main`
- [x] Merge conflict resolution
- [x] Commit history tracking
- [x] Remote repository synchronization
- [x] GitHub Pages deployment

---

## 🌿 Branching Strategy
The project uses multiple branches to simulate a real development lifecycle:

| Branch Name | Purpose |
| :--- | :--- |
| `main` | Stable, production-ready code |
| `feature-ui-enhancement` | UI improvements and feature additions |
| `qa-testing` | Testing and verification changes |
| `hotfix-validation-error` | Bug fixes and urgent corrections |
| `experimental-refactor` | Experimental and refactoring changes |

---

## 📁 Project File Structure
```text
git-devops-project/
│
├── index.html     # Main application file
├── README.md      # Project documentation
└── .git/          # Git configuration folder
```
## 💻 Git Commands Used (Step-by-Step)

---

### 1. Project Setup
```bash
# Create and enter directory
mkdir git-devops-project
cd git-devops-project

# Initialize Git
git init

# Create initial file and commit
touch index.html
git add .
git commit -m "Initial project setup"
```
### 2. Branch Management
```bash
# Create branches
git branch feature-ui-enhancement
git branch qa-testing
git branch hotfix-validation-error
git branch experimental-refactor

# Switch between branches
git checkout feature-ui-enhancement
```
### 3. Merging & Conflict Resolution
```bash
# Merge a feature into main
git checkout main
git merge feature-ui-enhancement

# Manual Conflict Resolution Steps:
# 1. Open conflicting file
# 2. Remove conflict markers (<<<<, ====, >>>>)
# 3. Save the file
git add .
git commit -m "Resolved merge conflict"
```
### 4. GitHub Remote Sync
```bash
# Connect and Push
git remote add origin [https://github.com/Mainuddeen00/git-devops-project.git](https://github.com/Mainuddeen00/git-devops-project.git)
git push -u origin main
```
## 🌐 Deployment (GitHub Pages)

---

* **The project is live at:**

* [👉 Live URL](https://github.com/Mainuddeen00/git-devops-project)

* Steps to Deploy:
* Navigate to Repository Settings > Pages.

* Select Branch: main and /root folder.

* Click Save.

---

## 📝 Learning Outcomes & Conclusion

Through this project, I have gained a strong understanding of Git fundamentals and practical conflict resolution skills. It reflects real-world software development environments where version control is critical for team collaboration and code integrity.

---
## Author: **Mainuddeen**
## Course: **Fundamentals of DevOps (INT331)**

         



