# TASK 4: Build a Version-Controlled DevOps Project with Git

**Objective:**  
Manage a DevOps project using Git best practices.

**Tools Used:**  
- Git  
- GitHub  

---

## 1. Repository Setup
- Initialized a new Git repository locally.
- Created a corresponding repository on GitHub.
- Linked local repo to GitHub remote (`origin`).
- Pushed initial commit to `main`.

---

## 2. Branching Strategy
- **Main branch (`main`)** → Production-ready code.
- **Development branch (`dev`)** → Integration and testing of new features.
- **Feature branches** → Used for individual features or fixes (e.g., `feature/add-readme-details`).

---

## 3. Workflow Diagram

![Git Branch Workflow](path/to/image.png)

---

## 4. Workflow Steps
1. **Initialize repo** and push to GitHub.  
2. **Create branches**: `main`, `dev`, and `feature/*`.  
3. **Develop changes** in feature branches.  
4. **Commit changes** with clear messages following conventional commits format.  
5. **Push feature branches** to GitHub.  
6. **Open Pull Requests** to merge feature branches into `dev`.  
7. **Test and review** on `dev` branch.  
8. **Merge `dev` into `main`** via Pull Request for release.  
9. **Tag releases** (e.g., `v1.0.0`) for version control.

---

## 5. Documentation
- Created `README.md` describing the project and setup instructions.
- Created `.gitignore` to exclude unnecessary files (e.g., logs, temp files).
- Maintained a `tasks.md` file with:
  - ✅ Completed tasks
  - 🚧 In-progress tasks
  - 📅 Planned tasks

---

## 6. Git Best Practices Followed
- No direct commits to `main`.
- Frequent commits with meaningful messages.
- Always branching from `dev` for new work.
- Used Pull Requests for all merges.
- Tagged stable releases.

---

## 7. Deliverables in Repository
- `README.md` → Project details and usage.
- `.gitignore` → Clean repo without unwanted files.
- `tasks.md` → Task tracking using Markdown checklists.
- Git commit history showing proper workflow.
- Tags marking project releases.

---

**Status:** ✅ **TASK 4 Completed Successfully**
