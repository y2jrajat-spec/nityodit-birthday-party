# 🚀 Quick Start - Deploy in 5 Minutes!

## What You'll Get
Your birthday invitation will be live on the internet with a URL like:
`https://nityodit-birthday.vercel.app`

## Prerequisites (2 minutes)
1. ✅ Create a **GitHub account** (free): https://github.com/signup
2. ✅ Create a **Vercel account** (free): https://vercel.com/signup
   - **Pro Tip:** Sign up with your GitHub account for easier integration!

---

## 🎯 Simple Method (For Beginners)

### STEP 1: Create GitHub Repository (2 minutes)

1. Go to https://github.com/new
2. Fill in:
   - **Repository name:** `nityodit-birthday-party`
   - **Description:** "Birthday invitation website"
   - ✅ Check: "Add a README file"
   - Choose: **Public**
3. Click **"Create repository"**

### STEP 2: Upload Files (1 minute)

1. Click **"Add file"** → **"Upload files"**
2. Drag and drop these 3 files:
   - ✅ `index.html` (your birthday invitation)
   - ✅ `vercel.json` (configuration)
   - ✅ `README.md` (description)
3. Click **"Commit changes"**

### STEP 3: Deploy to Vercel (2 minutes)

1. Go to https://vercel.com/new
2. Click **"Continue with GitHub"** (if not already connected)
3. You'll see your repository listed
4. Click **"Import"** next to `nityodit-birthday-party`
5. Keep all settings as default
6. Click **"Deploy"**
7. ⏳ Wait 30 seconds...
8. 🎉 **DONE!** Your site is live!

### STEP 4: Get Your URL

You'll see a screen with:
- ✅ Deployment successful!
- 🔗 Your URL: `https://nityodit-birthday-party.vercel.app`

**Click "Visit"** to see your live invitation!

---

## 📝 Making Updates Later

Anytime you want to change something:

1. Go to your GitHub repository
2. Click on `index.html`
3. Click the **pencil icon** ✏️ to edit
4. Make your changes
5. Scroll down and click **"Commit changes"**
6. Vercel automatically updates your site in ~30 seconds!

---

## 🎨 Fixing the Image Issue

Your birthday invitation currently references an image path that won't work online. Here's how to fix it:

### Option 1: Upload Images to GitHub (Recommended)

1. In your GitHub repository, click **"Add file"** → **"Upload files"**
2. Upload the birthday photo (`Untitled.png`)
3. In your `index.html`, change the image paths from:
   ```html
   <img src="/mnt/user-data/uploads/Untitled.png" alt="Nityodit">
   ```
   To:
   ```html
   <img src="./Untitled.png" alt="Nityodit">
   ```

### Option 2: Use Image Hosting (Easier)

1. Upload your image to **Imgur** (https://imgur.com) or **ImgBB** (https://imgbb.com)
2. Copy the direct image URL
3. Replace the image path in `index.html` with the URL:
   ```html
   <img src="https://i.imgur.com/YOUR-IMAGE-ID.png" alt="Nityodit">
   ```

---

## ✅ Success Checklist

After deployment, your invitation should have:
- ✅ Working URL that you can share
- ✅ Birthday party details visible
- ✅ RSVP form that works
- ✅ Beautiful animations
- ✅ Mobile-friendly design

---

## 🎊 Sharing Your Invitation

Once live, you can share your URL via:
- 📱 WhatsApp
- 📧 Email
- 📱 SMS
- 👨‍👩‍👧‍👦 Social Media

Just send them: `https://nityodit-birthday-party.vercel.app`

---

## 🆘 Common Issues & Solutions

### ❌ "404 - Page Not Found"
**Fix:** Make sure your file is named `index.html` (not `birthday_invite.html`)

### ❌ Images not showing
**Fix:** Follow the image fixing steps above

### ❌ Can't find repository in Vercel
**Fix:** 
1. Go to https://vercel.com/dashboard
2. Click your profile → "Settings"
3. Click "Git Integrations"
4. Click "Configure" next to GitHub
5. Make sure your repository has access

### ❌ Changes not reflecting
**Fix:** 
1. Check if you committed changes to GitHub
2. Go to Vercel dashboard → Your project → "Deployments"
3. You should see a new deployment after each GitHub commit
4. Wait 30-60 seconds for deployment to complete

---

## 🎯 Pro Tips

💡 **Custom Domain:** Want `nityodit.com` instead of `.vercel.app`?
   - Buy domain from Namecheap/GoDaddy ($10-15/year)
   - Add in Vercel: Settings → Domains

💡 **Test Before Sharing:** Open your URL in incognito/private mode to see it as guests will

💡 **Monitor RSVPs:** Check browser console or add a form backend later if you want to collect responses

💡 **Backup:** Your code is safe on GitHub. You can always revert changes!

---

## 📞 Need Help?

If you get stuck:
1. Check the full DEPLOYMENT_GUIDE.md for detailed steps
2. Google: "How to deploy static site to Vercel"
3. Vercel Support: https://vercel.com/support

---

🎉 **Congratulations!** You're about to have a live birthday invitation website!

Share it with pride and let the party planning begin! 🎂🎈
