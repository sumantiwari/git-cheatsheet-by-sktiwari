# 👨‍💻 Git Cheat Sheet by S K Tiwari

Helping developers master Git with practical commands 🚀

## 🔧 Setup

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --list
```

---

## 📁 Initialize Repository

```bash
git init
```

---

## 📂 Clone Repository

```bash
git clone git@github.com:username/repo.git
```

---

## 📌 Check Status

```bash
git status
```

---

## ➕ Add Changes

```bash
git add .
git add filename.txt
```

---

## 💾 Commit Changes

```bash
git commit -m "your message"
```

---

## ✏️ Amend Last Commit

```bash
git commit --amend
git commit --amend --no-edit
```

---

## 🌿 Branching

```bash
git branch
git branch branch-name
git checkout branch-name
git checkout -b new-branch
```

---

## 🔀 Merge Branch

```bash
git merge branch-name
```

---

## 🔄 Pull Latest Changes

```bash
git pull origin main
```

---

## 🚀 Push Code

```bash
git push origin main
git push -u origin main
```

---

## 🔗 Remote Repository

```bash
git remote -v
git remote add origin git@github.com:username/repo.git
git remote set-url origin git@github.com:username/repo.git
```

---

## 🧹 Stash Changes

```bash
git stash
git stash pop
```

---

## 📜 View History

```bash
git log
git log --oneline
```

---

## 🔍 Show Changes

```bash
git diff
```

---

## ❌ Undo Changes

### Unstage file

```bash
git restore --staged filename
```

### Discard changes

```bash
git restore filename
```

### Reset last commit

```bash
git reset --soft HEAD~1
git reset --hard HEAD~1
```

---

## 🔐 SSH Test

```bash
ssh -T git@github.com
```

---

## 🧠 Pro Tips

* Always run `git status` before commit
* Use meaningful commit messages
* Avoid pushing directly to `main`
* Use branches for features

---
