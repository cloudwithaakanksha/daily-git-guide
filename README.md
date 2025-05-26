# 🐙 Git & GitHub Guide

This guide is designed for beginners who want to understand **Git**, **GitHub**, and how to work with version control in real-world development scenarios. It includes clear definitions, essential commands, and practical workflows.

---

## 📘 What is Git?

**Git** is a **distributed version control system** that helps you track changes in files, collaborate with others, and manage source code efficiently.

### 🧩 Why Use Git?

- Track changes to your files over time
- Undo mistakes and roll back to earlier versions
- Collaborate without overwriting teammates' work
- Work on features independently using branches

### 🧠 Key Terms

| Term         | Description                                                       |
|--------------|-------------------------------------------------------------------|
| Repository   | A Git-managed project directory                                   |
| Commit       | A snapshot of your changes at a given point in time               |
| Branch       | A parallel line of development to isolate changes                 |
| Merge        | Combining changes from one branch into another                    |
| Remote       | A Git repo hosted online (e.g., on GitHub)                        |
| Clone        | Copying a remote repo to your local system                        |
| Push         | Sending your local changes to the remote repository               |
| Pull         | Bringing the latest changes from the remote to your local system  |

---

## 🌍 What is GitHub?

**GitHub** is a web-based platform where you can host Git repositories online, collaborate with others, and integrate with CI/CD pipelines.

### 🔧 Git vs GitHub

| Git              | GitHub                      |
|------------------|-----------------------------|
| Version control tool | Online hosting service for Git repos |
| Works locally     | Accessible globally         |
| Tracks changes    | Enables collaboration       |

---

## 🛠️ Essential Git Commands

### 🔄 Configuration

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
