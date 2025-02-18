Subversion and Mercurial Report
**Mastering Version Control: A Deep Dive into SVN & Mercurial (for Mac)**

📚 **Introduction to Version Control Systems**
Version Control Systems (VCS) manage software changes, enable collaboration, and maintain project history. This report focuses on using **Subversion (SVN)** and **Mercurial (Hg)** on a Mac.

✨ **Types of Version Control Systems:**
- **Centralized (CVCS):** A single central server stores all versions (e.g., SVN).
- **Distributed (DVCS):** Each user has a full repository copy (e.g., Mercurial).

🌟 **Why Use Version Control?**
✅ Tracks changes and history  
✅ Supports collaboration  
✅ Enables version rollbacks  
✅ Facilitates branching and merging  

---
🛠 **Installing and Setting Up on Mac**
- Install Homebrew (if not installed):
  ```bash
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```
- Install SVN:
  ```bash
  brew install svn
  ```
- Install Mercurial:
  ```bash
  brew install mercurial
  ```
---
🛠 **Subversion (SVN): Centralized VCS**
🔹 **Basic SVN Commands:**
| Command                | Description                         |
|-----------------------|-------------------------------------|
| `svn checkout <url>`   | Get a working copy                 |
| `svn update`           | Sync with the repository           |
| `svn add <file>`       | Add a file to version control      |
| `svn commit -m`        | Commit changes                     |
| `svn revert <file>`    | Undo local changes                 |
| `svn log`              | View commit history                |
| `svn diff`             | Show differences                   |

---
🌐 **Mercurial (Hg): Distributed VCS**
🔄 **Workflow:** Clone → Edit → Commit → Push → Pull & Merge
🔹 **Key Commands:**
| Command                | Description                         |
|-----------------------|-------------------------------------|
| `hg init`              | Create a repository                |
| `hg add`               | Add files to version control       |
| `hg commit -m`         | Commit changes locally             |
| `hg clone <url>`       | Clone a remote repository          |
| `hg pull`              | Get changes from a remote repo     |
| `hg merge`             | Merge branches                     |
| `hg log`               | View commit history                |

---
💻 **Hosting on GitHub Pages with README (for Mac):**
1. **Create a GitHub Repository and Push:**
```bash
git init
git add .
git commit -m "SVN & Mercurial Report"
git branch -M main
git remote add origin https://github.com/username/repo.git
git push -u origin main
```
2. **Enable GitHub Pages:** Settings → Pages → Source → `main` → Save.
3. **Create `README.md`:**
```markdown
# SVN & Mercurial Report
A guide for using SVN and Mercurial on Mac.
Hosted on GitHub Pages: [View Report](https://username.github.io/repo/)
```
4. **Push README:**
```bash
git add README.md
git commit -m "Added README"
git push
```
---

