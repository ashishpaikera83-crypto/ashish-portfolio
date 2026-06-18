# ⚡ QUICK START - Upload to GitHub in 5 Minutes

## 📋 Prerequisites
- [Git installed](https://git-scm.com/) on your computer
- [GitHub account](https://github.com/signup) (free)

---

## 🚀 Step 1: Copy Files to a Folder

Create a folder called `ashish-portfolio` and put these files inside:
- `index.html`
- `style.css`
- `script.js`
- `README.md`
- `.gitignore`

---

## 🌐 Step 2: Create Repository on GitHub

1. Go to **https://github.com/new**
2. **Repository name**: `ashish-portfolio`
3. **Description**: Portfolio website with dark theme
4. **Public** (checkbox)
5. Click **"Create repository"**

Copy the URL you see (looks like: `https://github.com/YOUR_USERNAME/ashish-portfolio.git`)

---

## 💻 Step 3: Upload Code to GitHub (Copy & Paste Commands)

Open Terminal/Command Prompt, go to your folder, and run these commands:

```bash
# Navigate to your folder
cd ashish-portfolio

# Initialize git
git init

# Add all files
git add .

# Create first commit
git commit -m "Initial commit: Dark theme portfolio website"

# Set main branch
git branch -M main

# Add remote (replace with YOUR URL from Step 2)
git remote add origin https://github.com/YOUR_USERNAME/ashish-portfolio.git

# Push to GitHub
git push -u origin main
```

---

## 🌍 Step 4: Make It Live (GitHub Pages)

1. Go to your repository: `https://github.com/YOUR_USERNAME/ashish-portfolio`
2. Click **Settings** ⚙️
3. Click **Pages** (left sidebar)
4. Under "Source", select **main** branch
5. Click **Save**

✅ **Your portfolio is LIVE!**  
**URL**: `https://YOUR_USERNAME.github.io/ashish-portfolio`

---

## 📱 Test Your Portfolio

- Visit: `https://YOUR_USERNAME.github.io/ashish-portfolio`
- Test on mobile using browser DevTools (F12 → Ctrl+Shift+M)
- Share the link!

---

## ✏️ Making Updates Later

```bash
# Edit your files, then run:
git add .
git commit -m "Update: Added new project"
git push origin main
```

**Wait 30 seconds** and refresh your live site!

---

## 🆘 Common Issues & Fixes

| Problem | Solution |
|---------|----------|
| "Permission denied" | Use HTTPS URL, not SSH |
| "404 Not Found" | Wait 2 minutes for GitHub Pages to deploy |
| Styles not loading | Clear browser cache (Ctrl+Shift+R) |
| Can't see changes | Push to GitHub, wait, then refresh browser |

---

## 📞 Need Help?

- **Git issues?** → See `GITHUB_UPLOAD_GUIDE.md`
- **Portfolio content?** → Edit `index.html`
- **Colors/design?** → Edit `style.css`
- **Animations?** → Edit `script.js`

---

## 🎉 That's It!

Your portfolio is now:
✅ Online and live  
✅ Version controlled with Git  
✅ Shareable with anyone  
✅ Easy to update  
✅ Free hosting  

**Share your portfolio URL on LinkedIn, resume, and job applications!**

---

**Your portfolio URL:**
```
https://ashishpaikera83-crypto.github.io/ashish-portfolio
```

Replace `YOUR_USERNAME` with your actual GitHub username.