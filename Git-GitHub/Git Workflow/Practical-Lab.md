# 💻 Practical Lab – Git Workflow for Beginners

## 🎯 Objective

Learn the complete Git workflow by creating a repository, tracking changes, committing code, and pushing it to GitHub.

---

# Scenario

You joined a DevOps team and need to upload a sample application to GitHub.

---

## Step 1 – Create Project Folder

```bash
mkdir Git-Workflow-Lab
cd Git-Workflow-Lab
```

---

## Step 2 – Initialize Git

```bash
git init
```

Verify

```bash
git status
```

---

## Step 3 – Create Sample File

```bash
touch index.html
```

---

## Step 4 – Check Status

```bash
git status
```

---

## Step 5 – Stage File

```bash
git add index.html
```

or

```bash
git add .
```

---

## Step 6 – Commit Changes

```bash
git commit -m "Initial Commit"
```

---

## Step 7 – Connect Remote Repository

```bash
git remote add origin <repository-url>
```

---

## Step 8 – Push Code

```bash
git push -u origin main
```

---

## Step 9 – Clone Repository

```bash
git clone <repository-url>
```

---

## Step 10 – Create Feature Branch

```bash
git checkout -b feature/login
```

---

## Step 11 – Switch Branch

```bash
git checkout main
```

---

## Step 12 – Merge Branch

```bash
git merge feature/login
```

---

## Step 13 – Pull Latest Changes

```bash
git pull origin main
```

---

## 🎯 Challenge

✔ Create repository

✔ Add two files

✔ Commit changes

✔ Push to GitHub

✔ Create feature branch

✔ Merge into main

Congratulations!

You completed the Git Workflow Practical Lab.
