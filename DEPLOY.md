# 🚀 Portfolio Deployment Guide

## Option 1: Netlify Drop (Easiest - No CLI Required)

### Steps:
1. **Go to**: https://app.netlify.com/drop
2. **Drag and drop** the entire `/Users/sijo/Documents/Portfolio` folder
3. **Done!** You'll get a live URL instantly (e.g., `https://your-site.netlify.app`)

### Custom Domain (Optional):
- Click "Domain settings" → "Add custom domain"
- Use your own domain or keep the free `.netlify.app` subdomain

---

## Option 2: Vercel (Fast & Free)

### Steps:
1. **Install Vercel CLI**:
   ```bash
   # If you have npm
   npm install -g vercel
   
   # Or use curl
   curl -sf https://vercel.com/install | sh
   ```

2. **Deploy**:
   ```bash
   cd /Users/sijo/Documents/Portfolio
   vercel --prod
   ```

3. **Follow prompts** to link your project

---

## Option 3: GitHub Pages (Already Set Up)

### Steps:
1. **Push changes**:
   ```bash
   cd /Users/sijo/Documents/Portfolio
   git push origin main
   ```

2. **Wait 1-2 minutes** for deployment

3. **Visit**: https://infiniteevolution.github.io

### Authentication Issue?
If push fails, use a Personal Access Token:
```bash
# Generate token at: https://github.com/settings/tokens
git remote set-url origin https://YOUR_TOKEN@github.com/InfiniteEvolution/Portfolio.git
git push origin main
```

---

## Option 4: Firebase Hosting (Google)

### Steps:
1. **Install Firebase CLI**:
   ```bash
   # Install Node.js first from: https://nodejs.org
   npm install -g firebase-tools
   ```

2. **Initialize**:
   ```bash
   cd /Users/sijo/Documents/Portfolio
   firebase login
   firebase init hosting
   ```

3. **Deploy**:
   ```bash
   firebase deploy
   ```

---

## 🎯 Recommended: Netlify Drop

**Why?** 
- ✅ No installation required
- ✅ Instant deployment (< 30 seconds)
- ✅ Free SSL certificate
- ✅ Global CDN
- ✅ Automatic HTTPS

**Just drag and drop your folder at**: https://app.netlify.com/drop

---

## 📊 Current Local Preview

Your portfolio is running at: **http://localhost:8000**

To stop the local server:
```bash
# Press Ctrl+C in the terminal
# Or kill the process
pkill -f "python3 -m http.server"
```
