# 📘 GitHub Upload Guide - Step by Step

## Prerequisites

1. **Git installed**: Download from https://git-scm.com/
2. **GitHub account**: Create one at https://github.com/
3. **Terminal/Command Prompt**: For running git commands

---

## Step 1: Create a GitHub Repository

1. Go to **https://github.com** and sign in
2. Click the **"+"** icon in the top-right corner
3. Select **"New repository"**
4. Fill in the details:
   - **Repository name**: `ashish-portfolio` (or your preferred name)
   - **Description**: "Professional portfolio website - Data Science & Python"
   - **Visibility**: Public (so others can see it)
   - **Initialize with**: Leave unchecked
5. Click **"Create repository"**

---

## Step 2: Set Up Git Locally

Open Terminal/Command Prompt and navigate to your portfolio folder:

```bash
cd /path/to/your/portfolio
```

Initialize git repository:

```bash
git init
```

Add all files:

```bash
git add .
```

Create initial commit:

```bash
git commit -m "Initial commit: Portfolio website with dark theme"
```

---

## Step 3: Connect to GitHub

Replace `USERNAME` with your GitHub username and `REPO_NAME` with your repository name:

```bash
git branch -M main
git remote add origin https://github.com/USERNAME/REPO_NAME.git
git push -u origin main
```

**You'll be prompted to enter:**
- GitHub username
- GitHub password (or personal access token)

### Using Personal Access Token (Recommended)

If you have two-factor authentication enabled:

1. Go to GitHub Settings → Developer settings → Personal access tokens
2. Click "Generate new token"
3. Select scopes: `repo` (full control of private repositories)
4. Copy the token
5. Use it as your password when pushing

---

## Step 4: Enable GitHub Pages (Host Your Portfolio)

1. Go to your repository on GitHub
2. Click **Settings** (gear icon)
3. Scroll to **Pages** section (left sidebar)
4. Under "Source":
   - Select branch: `main`
   - Select folder: `/ (root)`
5. Click **Save**
6. Wait 1-2 minutes for deployment
7. Your site will be available at: `https://USERNAME.github.io/REPO_NAME`

---

## Step 5: Verify Your Portfolio

1. Go to the URL shown in GitHub Pages settings
2. Your portfolio should load with the dark theme
3. Test all navigation links
4. Test responsiveness on mobile (use browser dev tools)

---

## Making Updates Later

Whenever you update your portfolio:

```bash
# Check status
git status

# Add all changes
git add .

# Commit with a message
git commit -m "Update: Added new project"

# Push to GitHub
git push origin main
```

---

## Troubleshooting

### Problem: "fatal: not a git repository"
**Solution**: Run `git init` in your folder first

### Problem: Authentication failed
**Solution**: 
- Update your credentials in Git settings
- Or use a personal access token instead of password

### Problem: Site not loading at GitHub Pages URL
**Solution**:
- Wait a few minutes, GitHub Pages takes time to deploy
- Check Settings → Pages to confirm it's enabled
- Clear browser cache (Ctrl+Shift+R)

### Problem: Styles/images not showing
**Solution**:
- Check file paths are relative (not absolute)
- Example: `<link rel="stylesheet" href="style.css">` ✓
- Not: `<link rel="stylesheet" href="/Users/ashish/style.css">` ✗

---

## Useful Git Commands

```bash
# Check git status
git status

# View commit history
git log

# View changes before committing
git diff

# Undo last commit (keep changes)
git reset --soft HEAD~1

# Create a new branch
git checkout -b feature-name

# Switch between branches
git checkout main
git checkout feature-name

# Merge branch into main
git checkout main
git merge feature-name

# Delete a branch
git branch -d feature-name

# Pull latest changes from GitHub
git pull origin main
```

---

## Custom Domain (Optional)

If you have a custom domain:

1. Create a `CNAME` file in your repository root with:
   ```
   yourdomain.com
   ```

2. Go to GitHub Settings → Pages
3. Under "Custom domain", enter your domain
4. Update your domain's DNS settings pointing to GitHub Pages

---

## Portfolio URL Formats

- **GitHub Pages**: `https://username.github.io/repository-name`
- **Custom Domain**: `https://yourdomain.com`

---

## Share Your Portfolio

After deployment, share your portfolio link:

- ✅ LinkedIn profile
- ✅ Resume/CV
- ✅ GitHub bio
- ✅ Email signature
- ✅ Job applications

---

## Maintenance Tips

1. **Update Projects**: Add new projects regularly
2. **Fix Typos**: Review and correct any spelling/grammar errors
3. **Keep Links Fresh**: Verify all external links work
4. **Update Contact Info**: Keep email and phone current
5. **Monitor Performance**: Check site speed periodically

---

## Next Steps

1. ✅ Create GitHub repository
2. ✅ Push code to GitHub
3. ✅ Enable GitHub Pages
4. ✅ Test your live portfolio
5. ✅ Share with others
6. ✅ Keep updating with new projects

---

## Support & Resources

- **Git Documentation**: https://git-scm.com/doc
- **GitHub Guides**: https://guides.github.com/
- **GitHub Pages Documentation**: https://pages.github.com/
- **Markdown Guide**: https://www.markdownguide.org/

---

**You're all set! Your portfolio is now live on the internet! 🚀**

Questions? Check your README.md or GitHub documentation.