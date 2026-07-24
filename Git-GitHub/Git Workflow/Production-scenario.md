# 🚀 Production Scenario – Git Workflow

## Scenario

A development team is working on an e-commerce application.

Three developers are simultaneously working on different features:

- Login Module
- Payment Module
- Order Module

As the DevOps Engineer, how would you ensure that everyone's code is managed safely without affecting the production branch?

---

## Recommended Workflow

### Step 1

Clone the repository

```bash
git clone <repository-url>
```

---

### Step 2

Create a feature branch

```bash
git checkout -b feature/payment
```

---

### Step 3

Develop the feature

---

### Step 4

Check changes

```bash
git status
```

---

### Step 5

Stage changes

```bash
git add .
```

---

### Step 6

Commit changes

```bash
git commit -m "Added payment API"
```

---

### Step 7

Push feature branch

```bash
git push origin feature/payment
```

---

### Step 8

Raise Pull Request

Developer reviews code.

---

### Step 9

Merge into Main

Only after successful review.

---

## Production Best Practices

✔ Never commit directly to Main.

✔ Use feature branches.

✔ Pull latest code before starting work.

✔ Write meaningful commit messages.

✔ Review code before merging.

✔ Resolve conflicts carefully.

✔ Delete merged branches.

---

## Learning Outcome

This workflow ensures:

- Safe collaboration
- Version control
- Easy rollback
- Clean history
- Stable production deployments
