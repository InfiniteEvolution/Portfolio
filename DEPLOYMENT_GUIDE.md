# Portfolio Deployment Guide

## 🎨 What's New

Your portfolio has been completely redesigned with a modern **Bento Grid** layout featuring:

### ✅ New Sections
1. **Apps Portfolio** - Showcasing 8 professional apps:
   - AlertPoint Mobile
   - K-Pak
   - Illuminati Magic
   - Manorama SSO
   - Manorama Reporters
   - BarChip
   - Bushnell Trailcamera
   - Bushnell Golf

2. **Contributions** - Open-source & technical achievements:
   - SSO & Session Management Library (CocoaPods/SPM)
   - SwiftNetwork (Modern networking library)
   - Canvas Framework (Privacy-first AI)
   - MVVM-C Architecture implementation

### ✅ Updated Information
- Correct LinkedIn: https://www.linkedin.com/in/sijo-p-t-53a35b10a/
- Correct GitHub: https://github.com/InfiniteEvolution/
- Title: "Experienced iOS Developer"
- Focus Areas: Offline Storage, Architecture
- Removed inaccurate certifications

### ✅ Design Features
- Dark theme with ambient gradient background
- Card-based Bento Grid layout
- Glassmorphic effects
- Smooth hover animations
- Fully responsive (desktop, tablet, mobile)

---

## 🚀 Deploy to GitHub Pages

All changes are committed locally. To deploy:

### **Step 1: Authenticate with GitHub**

Choose one method:

#### Option A: Personal Access Token
```bash
# 1. Generate token at: https://github.com/settings/tokens
# 2. Select scope: repo (full control)
# 3. Copy the token and run:

cd /Users/sijo/Documents/Portfolio
git remote set-url origin https://YOUR_TOKEN@github.com/InfiniteEvolution/Portfolio.git
git push origin main
```

#### Option B: SSH
```bash
cd /Users/sijo/Documents/Portfolio
git remote set-url origin git@github.com:InfiniteEvolution/Portfolio.git
git push origin main
```

#### Option C: GitHub Desktop
- Open GitHub Desktop
- Select the Portfolio repository
- Click "Push origin"

### **Step 2: Wait for Deployment**
- GitHub Pages rebuilds automatically (1-2 minutes)
- Visit: https://infiniteevolution.github.io

---

## 📱 Local Preview

Your portfolio is running at: **http://localhost:8000**

To stop the server:
```bash
# Press Ctrl+C in the terminal, or:
pkill -f "python3 -m http.server"
```

---

## 📊 File Changes Summary

**Commits ready to push:**
1. `Add modern Bento portfolio design with Apps Portfolio section`
2. `Replace certifications with contributions section`

**Files modified:**
- `index.html` - Complete redesign with Bento Grid
- `Style.css` - Modern dark theme styling
- `images/avatar.png` - Your professional photo
- `images/canvas.png` - Canvas project image
- `images/swiftnetwork.png` - SwiftNetwork project image

---

## 🎯 Next Steps

1. **Push to GitHub** (use one of the methods above)
2. **Verify deployment** at https://infiniteevolution.github.io
3. **Optional**: Add custom domain in GitHub repo settings

---

## 🔗 App Store Links (Optional Enhancement)

If you want to add direct links to your apps, update the HTML with:
- Bushnell Golf: https://apps.apple.com/app/bushnell-golf/
- Manorama Reporters: https://apps.apple.com/app/manorama-online-reporters/
- AlertPoint: (Add if available on App Store)

---

Built with ❤️ | Modern Bento Design | 2025
