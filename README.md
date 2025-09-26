# Devops Git Wrkflows 
# DevOps Git Workflows

This project demonstrates Git best practices for version control in a DevOps environment.  
It covers branching strategies, pull requests, tags, and documentation to simulate a real-world workflow.

---

##  Objective
Manage a DevOps project using Git and GitHub following standard workflows.

---

##  Tools Used
- **Git** – Version control system  
- **GitHub** – Remote repository hosting  

---

##  Workflow
1. **Initialize Repository**  
   - `git init`
   - `git add .`
   - `git commit -m "Initial commit"`
   - `git push -u origin main`

2. **Create Branches**
   - `git checkout -b dev`
   - `git checkout -b feature-1`

3. **Work on Feature Branch**
   - Add code changes
   - Commit & push changes
   - Open Pull Request (feature → dev)

4. **Merge Changes**
   - Review PR
   - Merge `feature → dev`, then `dev → main`

5. **Add .gitignore**
   - Ignore logs, temp files, etc.

6. **Add Tags**
   - `g
