# IntelliQR Scanner - Vercel Deployment Guide

## 🚀 Quick Deploy via Vercel Dashboard

Since the CLI has interactive prompts, the **easiest way** to deploy is through Vercel's web dashboard:

### Steps:

1. **Go to Vercel**: https://vercel.com/login
2. **Login** with GitHub account (christiankethaguacito-code)
3. **Import Project**: Click "Add New..." → "Project"
4. **Select Repository**: Find and select `IntelliQR` from your repositories
5. **Configure Project**:
   - Framework Preset: Other
   - Root Directory: `website`
   - Build Command: (leave empty)
   - Output Directory: (leave empty or `.`)
   - Install Command: (leave empty)
6. **Deploy**: Click "Deploy"
7. **Wait**: Takes about 30-60 seconds
8. **Done!** Your site will be live at: `https://intelliqr-scanner.vercel.app` or similar

---

## 🔧 Alternative: CLI Non-Interactive Deploy

If you want to use CLI without interactive prompts:

```powershell
cd website
vercel --yes --name intelliqr-scanner --prod --force
```

---

## ✅ GitHub Repository

Already pushed to: https://github.com/christiankethaguacito-code/IntelliQR

---

## 📦 Project Structure

```
scanner/
├── website/              ← Deploy this folder!
│   ├── index.html
│   ├── style.css
│   ├── script.js
│   ├── favicon.ico
│   └── icon.png
├── intelligent_scanner.py
├── IntelliQR.spec
└── installer_output/
    └── IntelliQR_Scanner_v2.0_Setup.exe
```

---

## 🌐 What Gets Deployed

- Beautiful maroon-themed website
- 18 feature showcases
- Animated statistics section
- Download section with installer link
- About section with highlighted developer name (USER)
- Responsive design for all devices

---

## 📝 Notes

- The website is static HTML/CSS/JS - no build process needed
- Vercel will auto-deploy on future GitHub pushes to `main` branch
- Domain will be: `https://<project-name>.vercel.app`
- You can add custom domain later in Vercel dashboard

---

Created by **USER** ⭐
IntelliQR Scanner v2.0 - SKSU Isulan
