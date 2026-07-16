# 💻 Practical Lab – Top 20 Linux Commands

## 🎯 Objective

This lab is designed to help you practice the most commonly used Linux commands in a real DevOps environment.

By the end of this lab, you will be able to:

- Navigate directories
- Create and manage files
- Modify permissions
- Search files
- Monitor processes
- Check disk usage

---

# 🖥️ Lab Scenario

You have joined a company as a Junior DevOps Engineer.

Your Team Lead asks you to prepare a Linux workspace before deploying an application.

---

## Step 1 – Create a Workspace

```bash
mkdir DevOps-Lab
cd DevOps-Lab
pwd
```

Expected Output

```
/home/ubuntu/DevOps-Lab
```

---

## Step 2 – Create Project Files

```bash
touch app.py
touch Dockerfile
touch Jenkinsfile
```

Verify

```bash
ls
```

---

## Step 3 – Create Directories

```bash
mkdir logs
mkdir backup
mkdir configs
```

Verify

```bash
ls
```

---

## Step 4 – Copy Files

```bash
cp app.py backup/
```

Verify

```bash
ls backup
```

---

## Step 5 – Rename Files

```bash
mv app.py application.py
```

Verify

```bash
ls
```

---

## Step 6 – Display File Contents

```bash
cat Dockerfile
```

---

## Step 7 – Change Permissions

```bash
chmod 755 application.py
```

Verify

```bash
ls -l
```

---

## Step 8 – Change Ownership

```bash
sudo chown ubuntu:ubuntu application.py
```

---

## Step 9 – Monitor Processes

```bash
ps -ef
```

```bash
top
```

---

## Step 10 – Disk Usage

```bash
df -h
```

```bash
du -sh .
```

---

## Step 11 – Search Files

```bash
find . -name application.py
```

---

## Step 12 – Search Text

Create sample file

```bash
echo "Docker is awesome" > notes.txt
```

Search

```bash
grep Docker notes.txt
```

---

# 🎯 Challenge

Complete these tasks without referring to the cheat sheet.

✔ Create a folder

✔ Create 5 files

✔ Rename one file

✔ Copy two files

✔ Delete one file

✔ Give execute permission

✔ Search a file

✔ Check disk usage

---

Congratulations!

You have completed the Linux Commands Practical Lab.
