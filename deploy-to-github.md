# 🚀 Deploy Lemach Hotel Website to GitHub Pages

## Step-by-Step Guide

### 1. Create GitHub Repository
1. Go to [GitHub.com](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name it: `lemach-hotel-website`
5. Make it **Public** (required for free GitHub Pages)
6. Don't initialize with README (we already have files)
7. Click "Create repository"

### 2. Upload Files to GitHub
**Option A: Using GitHub Web Interface**
1. In your new repository, click "uploading an existing file"
2. Drag and drop all your website files:
   - `index.html`
   - `rooms.html`
   - `meetings-events.html`
   - `menu.html`
   - `bar-restaurant.html`
   - `about.html`
   - `contact.html`
   - `deals.html`
   - `booking.html`
   - `test-css.html` (for testing CSS loading)
   - `css/` folder
   - `js/` folder
   - `images/` folder
   - `README.md`
   - `.gitignore`
3. Add commit message: "Initial website upload"
4. Click "Commit changes"

**Option B: Using Git Commands (if you have Git installed)**
```bash
# Open terminal/command prompt in your website folder
git init
git add .
git commit -m "Initial website upload"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/lemach-hotel-website.git
git push -u origin main
```

### 3. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" section (in left sidebar)
4. Under "Source", select "Deploy from a branch"
5. Under "Branch", select "main" and "/ (root)"
6. Click "Save"
7. Wait 2-5 minutes for deployment

### 4. Access Your Website
Your website will be available at:
`https://YOUR_USERNAME.github.io/lemach-hotel-website`

## ✅ What This Solves
- ✅ No more local server issues
- ✅ Professional hosting
- ✅ HTTPS security
- ✅ Works on all devices
- ✅ Easy to share and access
- ✅ Automatic updates when you push changes

## 🔧 Custom Domain (Optional)
If you want a custom domain like `lemachhotel.com`:
1. Buy domain from domain registrar
2. In GitHub Pages settings, add custom domain
3. Update DNS records as instructed

## 📱 Test Your Website
Once deployed, test:
- [ ] Homepage loads correctly
- [ ] All navigation links work
- [ ] Images display properly
- [ ] Forms work (contact, booking)
- [ ] Mobile responsiveness
- [ ] All pages accessible

## 🎉 Success!
Your Lemach Hotel website will now be live and accessible to everyone!
