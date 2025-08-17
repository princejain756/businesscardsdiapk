# 🚀 Deployment Guide

## Option 1: Vercel (Recommended) ⭐

### Why Vercel is Better:
- ✅ **Proper MIME types** for .vcf files (`text/vcard`)
- ✅ **Custom headers** for file downloads
- ✅ **Faster global CDN** 
- ✅ **Automatic HTTPS**
- ✅ **Better mobile support**

### Steps to Deploy:

1. **Install Vercel CLI:**
   ```bash
   npm i -g vercel
   ```

2. **Login to Vercel:**
   ```bash
   vercel login
   ```

3. **Deploy from your repo:**
   ```bash
   vercel --prod
   ```

4. **Or connect GitHub repo:**
   - Go to [vercel.com](https://vercel.com)
   - Import your GitHub repo
   - Vercel will auto-detect the config

### Your Vercel URLs will be:
```
https://your-project.vercel.app/dinesh_marudhar.vcf
https://your-project.vercel.app/neerajj_lotus.vcf
https://your-project.vercel.app/dipak_maninfini.vcf
https://your-project.vercel.app/dipak_meghdoot.vcf
https://your-project.vercel.app/parsmal_gotewala.vcf
https://your-project.vercel.app/manish_enterprises.vcf
```

## Option 2: GitHub Pages

### Steps:
1. Go to repo Settings → Pages
2. Source: "Deploy from a branch"
3. Branch: "main"
4. Folder: "/docs"
5. Save

### URLs:
```
https://princejain756.github.io/businesscardsdiapk/dinesh_marudhar.vcf
```

## 🔧 What vercel.json Does:

- **Sets correct MIME types** for all file types
- **Forces .vcf files** to be recognized as contact cards
- **Routes all requests** to the docs folder
- **Handles file downloads** properly
- **Ensures mobile compatibility**

## 📱 Mobile Testing:

After deployment, test on both:
- **Android:** Should prompt "Add to Contacts"
- **iPhone:** Should open in Contacts app
- **Desktop:** Should download properly

## 🎯 Best Practice:

Use **Vercel** for production contact cards because:
- Better MIME type handling
- Faster global delivery
- Professional hosting
- Better mobile experience
