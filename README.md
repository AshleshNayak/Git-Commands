# 🚀 GitHub Setup Guide

## 🔑 Generating New SSH Key

1. ssh-keygen -t ed25519 -C "youremail@example.com"
2. press enter
3. press enter
4. clip < ~/.ssh/id_ed25519.pub
5. settings->ssh and gpg keys->add the new ssh key (note:C:\Users\username OR pc name\.ssh)

## 💻 Pushing Code to GitHub Using GitBash

### 1. Initialize git in your folder ⚡
```bash
git init
```

### 2. Add GitHub repository URL 🔗
```bash
git remote add origin YOUR_GITHUB_REPOSITORY_URL
# Example: git remote add origin https://github.com/username/repository.git
```

### 3. Add all your files 📁
```bash
git add .
```

### 4. Commit your files 💾
```bash
git commit -m "first commit"
```

### 5. Change to main branch 🌿
```bash
git branch -M main
```

### 6. Push to GitHub ⬆️
```bash
git push -u origin main
```

## ⚠️ If Any Error Occurred

```bash
# Pull first
git pull origin main --allow-unrelated-histories

# Then push again
git push -u origin main
```

## ✏️ Merge Commit Message Editor (VIM)

1. Press i (to enter insert mode)
2. Type: Merging remote changes (without any quotes)
3. Press Esc
4. Type :wq and press Enter

Or simply:

Just press :wq and Enter to use the default message
