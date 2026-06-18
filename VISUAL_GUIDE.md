# 🎯 Visual GitHub Upload Guide

## Overview

```
Your Computer          GitHub              Live Website
    ↓                    ↓                      ↓
[Portfolio Files] → [Repository] → [GitHub Pages]
  index.html          ashish-portfolio    your-name.github.io/
  style.css            (storage)            ashish-portfolio/
  script.js
```

---

## 🔧 INSTALLATION GUIDE

### For Windows Users

1. **Download Git for Windows**
   - Go to https://git-scm.com/download/win
   - Click the download link
   - Run the installer
   - Accept default settings and click through
   - Restart your computer

2. **Verify Installation**
   - Open Command Prompt (Win + R, type `cmd`)
   - Type: `git --version`
   - Should see: `git version 2.x.x...`

### For Mac Users

1. **Download Git for Mac**
   - Go to https://git-scm.com/download/mac
   - Click the Intel or Silicon (Apple) link
   - Run the installer

2. **Verify Installation**
   - Open Terminal
   - Type: `git --version`
   - Should see: `git version 2.x.x...`

### For Linux Users

```bash
sudo apt-get install git
git --version
```

---

## 📱 GITHUB SETUP VISUAL

```
1. Create Repository
   ┌─────────────────────────────────┐
   │  github.com/new                 │
   │                                 │
   │  Repository name:               │
   │  [ashish-portfolio]             │
   │                                 │
   │  ☐ Public  ☑ Private            │
   │                                 │
   │  [Create repository]            │
   └─────────────────────────────────┘

2. Copy This URL
   ┌─────────────────────────────────┐
   │  https://github.com/YOUR_NAME/  │
   │  ashish-portfolio.git           │
   │                                 │
   │  (You'll need this!)            │
   └─────────────────────────────────┘
```

---

## 💻 TERMINAL COMMANDS (Step by Step)

### For Windows Command Prompt

```
C:\> cd Desktop\ashish-portfolio
C:\Desktop\ashish-portfolio> git init
C:\Desktop\ashish-portfolio> git add .
C:\Desktop\ashish-portfolio> git commit -m "Initial commit"
C:\Desktop\ashish-portfolio> git branch -M main
C:\Desktop\ashish-portfolio> git remote add origin https://github.com/YOUR_USERNAME/ashish-portfolio.git
C:\Desktop\ashish-portfolio> git push -u origin main
```

### For Mac/Linux Terminal

```
$ cd ~/Desktop/ashish-portfolio
$ git init
$ git add .
$ git commit -m "Initial commit"
$ git branch -M main
$ git remote add origin https://github.com/YOUR_USERNAME/ashish-portfolio.git
$ git push -u origin main
```

---

## 📊 WHAT EACH COMMAND DOES

```
git init
├─ Creates a new Git repository
└─ Makes a hidden .git folder

git add .
├─ Stages all files for commit
└─ Tells Git to track changes

git commit -m "message"
├─ Creates a snapshot of your files
└─ Like saving a version

git branch -M main
├─ Names your main branch "main"
└─ Standard for modern Git

git remote add origin URL
├─ Connects your local folder to GitHub
└─ "origin" = GitHub repository

git push -u origin main
├─ Uploads files to GitHub
├─ -u = sets upstream tracking
└─ Next time just: git push
```

---

## 🌐 GITHUB PAGES ACTIVATION

### Visual Steps:

```
Repository Page
    ↓
[Settings] ⚙️
    ↓
Left Sidebar: [Pages]
    ↓
Source: [main branch] ▼
    ↓
[Save]
    ↓
Wait 1-2 minutes...
    ↓
Your site is LIVE! 🎉
```

### Your Live URL:

```
Before:  https://github.com/YOUR_USERNAME/ashish-portfolio
After:   https://YOUR_USERNAME.github.io/ashish-portfolio
         
This is your LIVE website!
```

---

## 🔄 UPDATE WORKFLOW

Every time you make changes:

```
1. Edit Files
   ├─ Edit index.html
   ├─ Edit style.css
   └─ Edit script.js

2. Check Status
   $ git status
   (Shows which files changed)

3. Add Changes
   $ git add .

4. Commit
   $ git commit -m "Update: [what you changed]"

5. Push
   $ git push origin main

6. Wait 30 seconds

7. Refresh Website
   https://YOUR_USERNAME.github.io/ashish-portfolio
```

---

## 🎨 CUSTOMIZATION QUICK REFERENCE

### Change Portfolio Content

**File**: `index.html`

```html
<!-- Change Name -->
<h1 class="hero-title">Hi, I'm <span class="accent">YOUR NAME</span></h1>

<!-- Add New Project -->
<div class="project-card">
    <div class="project-icon"><i class="fas fa-star"></i></div>
    <h3>Project Name</h3>
    <p>Description here</p>
</div>

<!-- Update Contact -->
<a href="mailto:your-email@gmail.com">Your Email</a>
```

### Change Colors

**File**: `style.css`

```css
:root {
    --primary-color: #00d4ff;      /* Change this */
    --secondary-color: #00ffaa;    /* Change this */
    --accent-color: #ff006e;       /* Change this */
    --bg-dark: #0a0e27;
    --bg-darker: #050812;
}
```

---

## 🐛 TROUBLESHOOTING

### Issue: "fatal: not a git repository"

```bash
# Make sure you're in the right folder
cd path/to/ashish-portfolio

# Then try again
git status
```

### Issue: "Authentication failed"

GitHub changed password login. Use **Personal Access Token** instead:

1. Go to GitHub Settings → Developer settings → Personal access tokens
2. Generate new token with "repo" scope
3. Copy the token
4. Use token as password when pushing

### Issue: "Everything up-to-date"

You haven't made any changes. Edit files first, then:

```bash
git add .
git commit -m "Update: [describe change]"
git push origin main
```

### Issue: Site shows 404

1. Wait 2-3 minutes (GitHub Pages takes time)
2. Check Settings → Pages (make sure main branch is selected)
3. Clear browser cache (Ctrl+Shift+R)

### Issue: Styles not loading

Paths might be wrong. Use relative paths:

```html
<!-- ✅ CORRECT -->
<link rel="stylesheet" href="style.css">

<!-- ❌ WRONG -->
<link rel="stylesheet" href="/Users/ashish/Desktop/style.css">
```

---

## 📋 CHECKLIST

- [ ] Git installed and working
- [ ] GitHub account created
- [ ] Portfolio files in one folder
- [ ] Repository created on GitHub
- [ ] Files pushed to GitHub
- [ ] GitHub Pages enabled in Settings
- [ ] Website is LIVE
- [ ] All links working (test them!)
- [ ] Tested on mobile
- [ ] Shared with others ✨

---

## 📞 USEFUL RESOURCES

| Topic | Link |
|-------|------|
| Git Docs | https://git-scm.com/doc |
| GitHub Help | https://docs.github.com/ |
| GitHub Pages | https://pages.github.com/ |
| Markdown Guide | https://www.markdownguide.org/ |
| Font Awesome Icons | https://fontawesome.com/icons |

---

## 🎓 GIT COMMAND CHEATSHEET

```bash
# Check status
git status

# View changes
git diff

# View commit history
git log

# Create new branch
git checkout -b feature-name

# Switch branch
git checkout main

# Merge branch
git merge feature-name

# Delete branch
git branch -d feature-name

# Pull latest from GitHub
git pull origin main

# Undo last commit (keep files)
git reset --soft HEAD~1

# View remote URLs
git remote -v
```

---

## ✅ SUCCESS CHECKLIST

When complete, you should have:

1. ✅ Git installed on your computer
2. ✅ GitHub account with repository
3. ✅ Portfolio files on GitHub
4. ✅ GitHub Pages enabled
5. ✅ Live website at: `https://YOUR_USERNAME.github.io/ashish-portfolio`
6. ✅ Easy way to update (just edit + push)

---

## 🚀 NEXT STEPS

1. **Set up locally** (follow steps above)
2. **Push to GitHub** (git commands)
3. **Enable GitHub Pages** (Settings → Pages)
4. **Share with others** (LinkedIn, email, etc)
5. **Keep updating** (add new projects, skills)
6. **Maintain it** (fix broken links, update info)

---

**Your portfolio is now a professional online presence! 🎉**

Need help? Re-read this guide or check the links above.