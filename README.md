# DevOps Internship – Task 4
## Build a Version-Controlled DevOps Project with Git

### 📌 Objective
To manage a DevOps project using Git best practices and understand version control workflows.

---

### ⚙️ Tools Used
- Git
- GitHub

---

### 📂 Project Setup & Workflow

1. **Repository Initialization**
   - Create a new GitHub repository.
   - Initialize with `git init`.
   - Push to GitHub using `git remote add origin`.

2. **Branching Strategy**
   - `main` → Production-ready code.
   - `dev` → Active development branch.
   - `feature/` → Feature-specific branches (e.g., `feature-login`).

3. **Collaboration Workflow**
   - Create feature branches from `dev`.
   - Commit changes with meaningful messages.
   - Raise **Pull Requests** (PRs) for merging into `dev`.
   - Merge `dev` into `main` after successful testing.

4. **.gitignore Usage**
   - Exclude unnecessary files (logs, cache, IDE settings).

5. **Tags**
   - Use `git tag v1.0` for release versions.

6. **Documentation**
   - Project documented using **Markdown (README.md)**.

---

### ✅ Outcome
- Hands-on experience with Git workflows.
- Ability to manage multiple branches, pull requests, merge conflicts, tags, and `.gitignore`.

---

### ❓ Interview Questions & Key Notes

1. **What is Git?**
   Git is a distributed version control system that tracks code changes.

2. **Difference between Merge and Rebase?**
   - *Merge*: Combines histories, creates a new commit.
   - *Rebase*: Reapplies commits on top of another branch, keeps history linear.

3. **What is a Pull Request (PR)?**
   A request to merge code from one branch into another, often with review.

4. **How to resolve merge conflicts?**
   - Edit conflicting files.
   - Mark conflict resolution.
   - Commit changes.

5. **What are Git Tags?**
   Mark specific points in history (commonly used for releases).

6. **What is Git Workflow?**
   A structured process of collaboration using branches, commits, and PRs.

7. **Explain `git stash`.**
   Temporarily saves uncommitted changes for later use.

8. **What is the use of `.gitignore`?**
   Prevents tracking of unnecessary files (e.g., logs, temp files).

---

