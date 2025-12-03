# Git Cheat Sheet (Beginner Friendly)

These are the core Git commands you’ll use for uni projects. Keep it simple.

---

## 1. One-time setup

Set your identity:

git config --global user.name "Your Name"
git config --global user.email "you@example.com"

---

## 2. Everyday workflow

### Check what changed
git status

### Add your changes
Add everything:
git add .

Or add one file:
git add filename.ext

### Commit your work
git commit -m "Your message here"

Examples:
git commit -m "Finish assignment notes"
git commit -m "Add Python starter code"

---

## 3. Connecting to GitHub

### Clone a repo (first time)
git clone <REPO_URL>

Example:
git clone https://github.com/your-username/student-github-starter-kit.git

### Push your work to GitHub
git push

If it asks for a branch the first time:
git push -u origin main

### Pull latest changes
git pull

---

## 4. Branching (optional)

Create a new branch:
git checkout -b feature-update

Switch back:
git checkout main

Merge:
git merge feature-update

---

## 5. Common issues

### “Nothing to commit”
You haven’t changed anything.

### “Updates were rejected”
Someone (or you on another device) pushed changes first:

git pull
# fix any conflicts
git add .
git commit -m "Resolve merge"
git push

---

Stick to these and you’ll be fine for all student-level projects.
