# Deploy RevealJS Presentation to GitHub Pages

## Prerequisites

- GitHub account (free)
- Git installed on your computer
- Your presentation files (index.html, etc.)

## Step-by-Step Deployment

### Step 1: Create GitHub Repository

1. Go to [github.com](https://github.com)
2. Click **"New repository"** button (top right, + icon)
3. Repository name: `quarterly-earnings-presentation`
4. Description: "Q4 2025 Earnings Report - Interactive RevealJS Presentation"
5. **Select Public** (so GitHub Pages works)
6. Do NOT initialize with README, .gitignore, or license
7. Click **"Create repository"**

### Step 2: Initialize Local Repository

Navigate to your presentation directory
cd /path/to/quarterly-earnings-presentation
Initialize git
git init
Add all files
git add .
Create initial commit
git commit -m “Initial commit: Q4 2025 earnings presentation"


### Step 3: Connect to GitHub

Add GitHub repository as remote
git remote add origin https://github.com/YOUR-USERNAME/quarterly-earnings-presentation.git
Rename branch to main (GitHub Pages standard)
git branch -M main
Push to GitHub
git push -u origin main

### Step 4: Enable GitHub Pages

1. Go to your repository: `https://github.com/YOUR-USERNAME/quarterly-earnings-presentation`
2. Click **Settings** tab (right side)
3. Click **Pages** in left sidebar
4. Under **Source**:
   - Select **Deploy from a branch**
   - Choose branch: **main**
   - Choose folder: **/ (root)**
5. Click **Save**

### Step 5: Verify Deployment

After 1-2 minutes, your presentation will be live at:

https://YOUR-USERNAME.github.io/quarterly-earnings-presentation/

Example:
- GitHub username: `techconsultant`
- URL: `https://techconsultant.github.io/quarterly-earnings-presentation/`

## ✅ Verification Checklist

- [ ] Repository created on GitHub
- [ ] Files pushed to main branch
- [ ] GitHub Pages enabled in Settings
- [ ] URL follows format: `https://USERNAME.github.io/REPO/`
- [ ] Presentation loads in browser
- [ ] All slides render correctly
- [ ] Navigation works (arrow keys)
- [ ] Speaker notes accessible (press 'S')

## 📝 Making Updates

After initial deployment, update your presentation:

Make changes to index.html
Example: Update email, add slides, etc.
Commit changes
git add index.htmlgit commit -m “Update: Q4 metrics with final numbers”
Push to GitHub
git push origin main


**Shortened URL** (optional):
- Use bit.ly, tinyurl, or similar service
- Example: `https://bit.ly/q4-2025-earnings`

## 📊 Presentation Mode for Meetings

1. Open the GitHub Pages URL
2. Press **F** for fullscreen
3. Press **S** to open speaker notes (in separate window)
4. Use arrow keys or spacebar to navigate
5. Click on speaker view window to see your notes

## 🔐 Privacy & Security

- Presentation is **publicly accessible** (GitHub Pages)
- No sensitive data should be included
- Repository is public but you can make it private
- To make private: Settings → Privacy settings

## 🆘 Troubleshooting

### Presentation not loading
**Solution:**
- Wait 2-3 minutes after enabling Pages (deployment takes time)
- Hard refresh browser (Ctrl+Shift+R or Cmd+Shift+R)
- Check URL spelling

### GitHub Pages not enabled
**Solution:**
- Go to Repository → Settings → Pages
- Verify "Deploy from a branch" is selected
- Check branch is "main" and folder is "/ (root)"

### Files not updating
**Solution:**
- Verify push was successful: `git log` shows your commits
- Hard refresh browser: Ctrl+Shift+R
- Wait 1-2 minutes for GitHub Pages rebuild

### URL format incorrect
**Solution:**
- Correct format: `https://USERNAME.github.io/REPO-NAME/`
- Check GitHub username (Settings → Account)
- Check repository name (Settings → General)

## 📚 Advanced Options

### Custom Domain
1. Buy domain (GoDaddy, Namecheap, etc.)
2. In Repository Settings → Pages → Custom domain
3. Enter your domain
4. Update DNS records with provided info

### HTTPS (Automatic)
- GitHub Pages automatically provides HTTPS
- Certificate managed by GitHub (Let's Encrypt)
- Enable "Enforce HTTPS" in Pages settings

## 🎓 Additional Resources

- [GitHub Pages Documentation](https://pages.github.com/)
- [RevealJS GitHub Repository](https://github.com/hakimel/reveal.js)
- [Git Command Reference](https://git-scm.com/docs)

---

**Your presentation is now live on the internet! 🎉**

Share the URL with stakeholders and present with confidence.
