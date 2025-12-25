# Git DevOps Project

## Project Overview
This project demonstrates practical usage of **Git Bash and GitHub** for version control as part of the **Fundamentals of DevOps (INT331)** course.

The main objective of this project is to **understand and implement Git concepts in a real-world workflow**, including repository initialization, branching strategies, merging, conflict resolution, and maintaining a clean commit history.

A **professional calculator web application** built using **HTML, CSS, and JavaScript** is used only as a **sample application** to apply and visualize Git operations.  
The **primary focus of this project is Git**, not application complexity.

---

## Project Focus (Important)
- This is a **Git-based DevOps project**
- The application is used only as a **medium**
- Evaluation is focused on:
  - Git workflow
  - Branching strategy
  - Commits
  - Merging
  - Conflict resolution
  - GitHub usage

---

## Features Implemented (Application Side)
- Interactive calculator UI
- Keyboard input support
- Memory functions (MC, MR, M+, M-)
- Error handling (divide by zero)
- Responsive design
- Clean and professional UI styling
- Runs completely in the browser (no backend)

---

## Technologies Used
- **Git Bash**
- **GitHub**
- **HTML**
- **CSS**
- **JavaScript**
- **GitHub Pages (Deployment)**

---

## Git Concepts Covered
- Repository initialization
- Branch creation and management
- Feature-based branching strategy
- Switching between branches
- Merging branches into `main`
- Merge conflict creation and resolution
- Commit history tracking
- Remote repository synchronization
- Deployment using GitHub Pages

---

## Branching Strategy
The project uses multiple branches to simulate a real development workflow:

- `main`  
  Stable, production-ready code

- `feature-ui-enhancement`  
  UI improvements and feature additions

- `qa-testing`  
  Testing and verification changes

- `hotfix-validation-error`  
  Bug fixes and urgent corrections

- `experimental-refactor`  
  Experimental and refactoring changes

This branching strategy reflects **industry-level Git practices**.

---

## Commit Strategy
Each commit represents a **single meaningful change**, such as:
- UI enhancements
- Feature additions
- Bug fixes
- Merge conflict resolution
- Documentation updates


This ensures:
- Clean commit history
- Easy debugging
- Clear project progress tracking

---

## Project File Structure
git-devops-project/
│
├── index.html
├── README.md
└── .git/

## Git Commands Used (Step-by-Step)

### 1. Create Project Directory
```bash
mkdir git-devops-project
cd git-devops-project
2. Initialize Git Repository
git init
3. Create Initial File
touch index.html
4. First Commit
git add .
git commit -m "Initial project setup"
5. Create Branches
git branch feature-ui-enhancement
git branch qa-testing
git branch hotfix-validation-error
git branch experimental-refactor
6. Switch Between Branches
git checkout feature-ui-enhancement
git checkout qa-testing
git checkout main
8. Resolve Merge Conflicts
git add .
git commit -m "Resolved merge conflict"
9. Connect to GitHub
git remote add origin https://github.com/Mainuddeen00/git-devops-project.git
10. Push to GitHub
git push -u origin main

Deployment (GitHub Pages)

The project is deployed using GitHub Pages.

Steps:

Go to Repository Settings

Open Pages

Select:

Branch: main

Folder: /root

Save settings

Live URL:
https://mainuddeen00.github.io/git-devops-project/

Challenges Faced

Understanding branch-based workflow initially

Merge conflicts due to same file changes

Managing multiple branches correctly

Keeping commits clean and meaningful

These challenges helped build real-world Git confidence.

Learning Outcomes

Strong understanding of Git fundamentals

Hands-on experience with branching and merging

Practical conflict resolution

Real GitHub workflow exposure

Deployment using GitHub Pages

Conclusion

This project successfully demonstrates core Git and DevOps concepts through practical implementation.
It reflects how version control is used in real software development environments, making it a strong foundational Git-based DevOps project.

Author

Mainuddeen
Course: Fundamentals of DevOps (INT331)
