# devops-practice 
# Day 2: Branching and Merging
Practicing  safe changes on a feature branch before merging to main.
Sylvia's DevOps Learning Journey

Welcome to my DevOps practice repository. This is where I document my daily progress as I learn Git, branching, merging, and other DevOps fundamentals.

---

## Day 1: Git Basics
- *git config --global user.name "Sylvia"* → set my Git username
- *git config --global user.email "your@email.com"* → link commits to my GitHub account
- *git clone [repo-url]* → copy a remote repo to my local machine
- *git add [file]* → stage changes for commit
- *git commit -m "message"* → save a snapshot of staged changes
- *git status* → check current repo state
- *git push* → send local commits to GitHub

---

## Day 2: Branching and Merging
Practicing safe changes on a feature branch before merging into main.

Steps:
1. Create a new branch:  
   git checkout -b day2-practice
2. Edit README.md and add notes.
3. Stage and commit changes:  
   git add README.md  
   git commit -m "Add Day 2 notes"
4. Merge back into main:  
   git checkout main  
   git merge day2-practice
5. Push updates to GitHub:  
   git push origin main

---

## Practice Runs
### Practice Run 1
- Created branch: practice-branch-1
- Edited README locally
- Committed changes via terminal
- Merged into main

### Practice Run Clean
- Restarted workflow to build confidence
- Confirmed edits and commits
- Synced with GitHub successfully

---

## Notes
- I am learning step by step, repeating commands until they feel natural.
- Each day I add new sections here to track my progress.
- This README doubles as both documentation and a personal learning journal.
## Day 3: Remote collaboration
- Practiced fetch,pull,push
- Created a feature branch for a teamwork
## Teammate Notes
- Added collaboration practice section
Today I practiced working with remote repositories and simulating teamwork.

### Key Commands
- *git remote -v* → check which GitHub repo my project is connected to
- *git fetch origin* → download changes from GitHub without merging
- *git pull origin main --rebase* → sync my local branch with GitHub cleanly
- *git push origin main* → upload my commits to GitHub
- *git checkout -b feature-day3* → create a new branch for collaboration
- *git merge feature-day3* → merge changes back into main

### What I Learned
- How to connect my local repo with GitHub and confirm the remote.
- The difference between fetch, pull, and push.
- How to keep commit history clean using --rebase.
- How to create, push, and merge feature branches for teamwork.
- Simulated collaboration by pretending a teammate added changes.

### Notes
Day 3 helped me understand how developers sync their work with GitHub and collaborate using branches. This is the foundation for real teamwork in DevOps projects.