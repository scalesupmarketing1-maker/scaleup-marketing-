# 🚀 ScaleUp Marketing – GitHub Pages Deployment Guide

Complete step-by-step guide to publish your website for FREE on GitHub Pages.

---

## 📁 Files in Your Project

```
scaleup-marketing/
├── index.html    ← Main website
├── style.css     ← All styling
├── script.js     ← Animations & interactions
└── README.md     ← This guide
```

---

## ✅ Step 1: Create a GitHub Account

1. Go to **https://github.com**
2. Click **Sign Up**
3. Choose a username (this will be part of your URL, e.g., `hanzala-scaleup`)
4. Enter your email and create a password
5. Verify your email

---

## ✅ Step 2: Create a New Repository

1. Once logged in, click the **"+"** icon (top right) → **"New repository"**
2. Fill in:
   - **Repository name:** `scaleup-marketing` *(or your GitHub username for a special URL)*
   - **Description:** ScaleUp Marketing – E-commerce Training & Business Scaling
   - **Visibility:** ✅ Public (required for free GitHub Pages)
   - Do NOT check "Add README" (we'll upload our own files)
3. Click **"Create repository"**

> 💡 **Pro Tip:** If you name the repo exactly `yourusername.github.io`  
> (e.g., `hanzala-scaleup.github.io`), your site will be at that URL directly!

---

## ✅ Step 3: Upload Your Files

### Option A – Upload via Browser (Easiest)

1. On your new empty repository page, click **"uploading an existing file"**
2. Drag and drop all 3 files:
   - `index.html`
   - `style.css`
   - `script.js`
3. Scroll down to **"Commit changes"**
4. Add a message: `Initial website launch 🚀`
5. Click **"Commit changes"**

### Option B – Using Git (Recommended for updates)

```bash
# Install Git: https://git-scm.com/downloads
# Then open Terminal / Command Prompt

# 1. Go into your project folder
cd path/to/your/project

# 2. Initialize Git
git init

# 3. Add all files
git add .

# 4. First commit
git commit -m "Initial website launch 🚀"

# 5. Connect to GitHub (replace URL with your repo)
git remote add origin https://github.com/YOUR-USERNAME/scaleup-marketing.git

# 6. Push to GitHub
git branch -M main
git push -u origin main
```

---

## ✅ Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** tab (top menu)
3. Scroll down to **"Pages"** in the left sidebar
4. Under **"Source"**, select:
   - Branch: **main**
   - Folder: **/ (root)**
5. Click **Save**
6. GitHub will show a banner: *"Your site is published at..."*

⏱ **Wait 1-3 minutes** for the site to go live.

---

## ✅ Step 5: Access Your Live Website

Your website will be live at:

```
https://YOUR-USERNAME.github.io/scaleup-marketing/
```

For example:
```
https://hanzala-mehmood.github.io/scaleup-marketing/
```

---

## 🔄 How to Update Your Website Later

Whenever you make changes to the files:

```bash
git add .
git commit -m "Updated services section"
git push
```

GitHub Pages will automatically update within 1-2 minutes.

---

## 🌐 Add a Custom Domain (Optional)

If you have a domain like `scaleupmarketing.com`:

1. Go to **Settings → Pages → Custom domain**
2. Enter your domain name
3. Click Save
4. Go to your domain registrar (GoDaddy, Namecheap, etc.)
5. Add a **CNAME record** pointing to `YOUR-USERNAME.github.io`
6. Enable **HTTPS** in GitHub Pages settings (checkbox)

---

## 📱 Before Going Live – Checklist

- [ ] Update phone number (`+92 300 123 4567`) with your real number
- [ ] Update email (`hello@scaleupmarketing.com`) with your real email
- [ ] Update WhatsApp link (`wa.me/923001234567`) with your WhatsApp number
- [ ] Update social media links (Facebook, Instagram, LinkedIn)
- [ ] Replace team initials with actual photos if available
- [ ] Update address if different from Lahore

---

## 🛠 Common Issues & Fixes

| Problem | Solution |
|---------|----------|
| Site shows 404 | Make sure file is named `index.html` (not `Index.html`) |
| CSS not loading | Confirm `style.css` is in the same folder as `index.html` |
| JS not working | Confirm `script.js` is in the same folder as `index.html` |
| Site not updating | Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac) |
| Images broken | Use relative paths, not absolute drive paths |

---

## 📧 Need Help?

Contact: hello@scaleupmarketing.com  
WhatsApp: +92 300 123 4567

---

*© 2024 ScaleUp Marketing – All rights reserved*
