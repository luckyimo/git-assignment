# git-assignment
# Git and Version Control Fundamentals

## 1. What is Version Control?
Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. It allows multiple people to work on the same project simultaneously, tracks who made which changes, and provides a safety net to revert to previous states if something goes wrong.

## 2. Git vs. GitHub: The Difference
* **Git:** A local software tool (CLI) that handles version control. It tracks the history of your files on your actual computer.
* **GitHub:** A cloud-based hosting service for Git repositories. It provides a web interface, collaboration tools (like Pull Requests), and a place to store your code online.

## 3. GitHub Alternatives
1.  **GitLab**
2.  **Bitbucket**
3.  **Azure DevOps**

## 4. Git Fetch vs. Git Pull
* **Git Fetch:** Downloads the latest changes from the remote server to your local machine but **does not** merge them into your working files. It’s a "safe" way to see what others have done.
* **Git Pull:** This is essentially `git fetch` followed immediately by `git merge`. It downloads the changes and automatically integrates them into your current branch.

## 5. Git Rebase
**In simple terms:** Imagine you and a teammate both started from the same point. Rebase "plucks" your branch's changes and moves them to the very tip of your teammate's latest changes. It keeps the project history looking like a straight line instead of a tangled web.

**Command:**
```bash
git rebase <branch-name>