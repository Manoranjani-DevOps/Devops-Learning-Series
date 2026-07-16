# 🚀 Production Scenario – Linux Commands

## Scenario

A developer reports:

> "The deployment script is available on the server, but it is not executing."

As a DevOps Engineer, how would you troubleshoot?

---

## Step 1 – Verify Current Directory

```bash
pwd
```

---

## Step 2 – Check Whether File Exists

```bash
ls -l
```

---

## Step 3 – Check Permissions

Example

```
-rw-r--r--
```

The file is **not executable**.

---

## Step 4 – Grant Execute Permission

```bash
chmod +x deploy.sh
```

or

```bash
chmod 755 deploy.sh
```

---

## Step 5 – Verify Owner

```bash
ls -l
```

If required

```bash
sudo chown ubuntu:ubuntu deploy.sh
```

---

## Step 6 – Check Running Processes

```bash
ps -ef
```

or

```bash
top
```

---

## Step 7 – Kill Stuck Process

```bash
kill <PID>
```

or

```bash
kill -9 <PID>
```

---

## Step 8 – Check Disk Space

```bash
df -h
```

If disk is full

```bash
du -sh *
```

---

## Step 9 – Search Configuration File

```bash
find /etc -name nginx.conf
```

---

## Step 10 – Search Error Logs

```bash
grep ERROR application.log
```

---

# Production Best Practices

✔ Never use **777** permissions.

✔ Always follow the Principle of Least Privilege.

✔ Verify ownership before changing permissions.

✔ Check disk usage before deployments.

✔ Monitor processes before restarting services.

✔ Use logs to identify root cause instead of guessing.

---

# Learning Outcome

You have used:

- ls
- pwd
- chmod
- chown
- ps
- top
- kill
- df
- du
- grep
- find

These commands are frequently used by DevOps Engineers while supporting production environments.
