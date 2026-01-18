# 🚀 Quick Setup Guide - Gabby Cat Game

## Step 1: Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the **"+"** in the top right → **"New repository"**
3. Repository name: `gabby-cat-differences` (or your choice)
4. Make it **Public** (required for free GitHub Pages)
5. **Don't** check "Add a README file"
6. Click **"Create repository"**

## Step 2: Upload Your Files

### Method A: GitHub Website (Easiest! 👍)

1. On your new repository page, click **"uploading an existing file"**
2. Drag and drop these 3 files:
   - `index.html`
   - `image1.png`
   - `image2.png`
   - `README.md`
3. Commit message: "Add Gabby Cat Find the Differences game"
4. Click **"Commit changes"**

### Method B: Command Line (For Git Users)

```bash
cd path/to/your/folder
git init
git add .
git commit -m "Add Gabby Cat game"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/gabby-cat-differences.git
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. In your repository, click **"Settings"** (top tab)
2. Scroll down and click **"Pages"** in the left sidebar
3. Under **"Source"**, select:
   - Branch: **main**
   - Folder: **/ (root)**
4. Click **"Save"**
5. Wait 2-3 minutes for GitHub to build your site

## Step 4: Find Your Live Game URL

Your game will be live at:
```
https://YOUR-USERNAME.github.io/gabby-cat-differences/
```

**Example:** If your username is `sarahsmith42`:
```
https://sarahsmith42.github.io/gabby-cat-differences/
```

## 🎉 Success!

Your game is now live! Share the link with friends and family!

---

## 🔄 Making Updates Later

**Via GitHub Website:**
1. Click the file you want to edit
2. Click the pencil ✏️ icon
3. Make your changes
4. Click "Commit changes" at bottom
5. Wait 1-2 minutes for changes to go live

**Via Command Line:**
```bash
# After making changes to files
git add .
git commit -m "Update game"
git push
```

---

## 💡 Pro Tips

### Tip 1: Test Locally First
Before uploading, open `index.html` in your browser to test it works!

### Tip 2: Share on Social Media
Your GitHub Pages link works perfectly for sharing on Facebook, Twitter, etc.

### Tip 3: Custom Domain (Optional)
You can use your own domain name in the Pages settings!

### Tip 4: Track Visitors (Optional)
Add Google Analytics to see how many people play your game.

---

## 🐛 Troubleshooting

### Problem: "Page Not Found" Error
**Solutions:**
- Wait 3-5 minutes after enabling Pages
- Make sure repository is **Public**
- Check that `index.html` is in the root folder
- Try adding `/index.html` to the end of your URL

### Problem: Images Not Showing
**Solutions:**
- Verify files are named exactly `image1.png` and `image2.png`
- Check files are in the same folder as `index.html`
- Make sure you uploaded all files, not just the HTML

### Problem: Game Not Working
**Solutions:**
- Open browser console (press F12) to check for errors
- Make sure you uploaded the complete `index.html` file
- Try in a different browser (Chrome recommended)

### Problem: Can't Find Settings/Pages
**Solutions:**
- Make sure you're in your repository (not your profile)
- Pages option requires a Public repository
- Some new accounts have a 24-hour wait before Pages activates

---

## 📧 Still Need Help?

### Check These:
1. ✅ Repository is Public
2. ✅ All 3 files uploaded to root folder
3. ✅ Waited 3-5 minutes after enabling Pages
4. ✅ Tried the URL in an incognito/private browser window

### GitHub Pages Status
Visit: `https://YOUR-USERNAME.github.io/` 
If this works, your Pages is active!

---

## 🎯 Next Steps After Setup

### Add More Scenes
Create `scene2.html` with different Gabby Cat images!

### Customize Colors
Edit the CSS colors to match your preferences.

### Share the Fun
Send your link to friends who love Gabby Cat!

### Create a QR Code
Use a QR code generator with your GitHub Pages link for easy mobile access!

---

**Have fun, and happy gaming! 🐱✨**
