# Deploy to Vercel via GitHub - Step by Step Guide

## Prerequisites
- GitHub account (free)
- Vercel account (free) - sign up at https://vercel.com

## Step 1: Prepare Your Files

You'll need these files in your project:
1. `index.html` - Your birthday invitation page
2. `vercel.json` - Configuration file (optional but recommended)
3. `README.md` - Project description (optional)

## Step 2: Create a GitHub Repository

### Option A: Using GitHub Website
1. Go to https://github.com
2. Click the "+" icon in top right → "New repository"
3. Repository name: `nityodit-birthday-party` (or any name you prefer)
4. Description: "Birthday invitation for Nityodit's 6th birthday party"
5. Choose "Public" or "Private"
6. ✅ Check "Add a README file"
7. Click "Create repository"

### Option B: Using GitHub Desktop (Easier for beginners)
1. Download GitHub Desktop from https://desktop.github.com
2. Install and sign in with your GitHub account
3. File → New Repository
4. Name: `nityodit-birthday-party`
5. Local Path: Choose where to save on your computer
6. Click "Create Repository"

## Step 3: Add Your Files to the Repository

### Using GitHub Website:
1. In your repository, click "Add file" → "Upload files"
2. Drag and drop these files:
   - `index.html` (your birthday invitation)
   - `vercel.json` (configuration file)
   - Any image files if needed
3. Click "Commit changes"

### Using GitHub Desktop:
1. Copy your files into the repository folder
2. GitHub Desktop will show the changes
3. Add a commit message: "Add birthday invitation files"
4. Click "Commit to main"
5. Click "Push origin" to upload to GitHub

## Step 4: Deploy to Vercel

### Method 1: Connect via Vercel Dashboard (Recommended)
1. Go to https://vercel.com and sign in
2. Click "Add New" → "Project"
3. Click "Import Git Repository"
4. You may need to "Install Vercel for GitHub" - click and authorize
5. Find your repository `nityodit-birthday-party`
6. Click "Import"
7. Configure your project:
   - Framework Preset: **Other**
   - Root Directory: `./` (keep as is)
   - Build Command: (leave empty)
   - Output Directory: (leave empty)
8. Click "Deploy"
9. Wait 30-60 seconds for deployment
10. 🎉 Your site is live! You'll get a URL like: `nityodit-birthday-party.vercel.app`

### Method 2: Using Vercel CLI (Advanced)
```bash
# Install Vercel CLI
npm i -g vercel

# Navigate to your project folder
cd path/to/your/project

# Deploy
vercel

# Follow the prompts
```

## Step 5: Get Your Live URL

After deployment completes:
1. You'll see your live URL: `https://your-project-name.vercel.app`
2. Click "Visit" to view your site
3. Share this URL with your guests!

## Step 6: Custom Domain (Optional)

If you want a custom domain like `nityodit-birthday.com`:
1. In Vercel dashboard, go to your project
2. Click "Settings" → "Domains"
3. Add your custom domain
4. Follow the DNS configuration instructions

## Updating Your Site

Whenever you want to make changes:

### Using GitHub Website:
1. Go to your repository
2. Click on the file you want to edit
3. Click the pencil icon (Edit)
4. Make your changes
5. Click "Commit changes"
6. Vercel will automatically redeploy (takes ~30 seconds)

### Using GitHub Desktop:
1. Edit your files locally
2. GitHub Desktop shows changes
3. Commit and push
4. Vercel auto-deploys

## Troubleshooting

### Issue: "File not found" or blank page
**Solution:** Make sure your main file is named `index.html` (not `birthday_invite.html`)

### Issue: Images not loading
**Solution:** 
- Upload images to your GitHub repository
- Update image paths in your HTML to relative paths
- Or use image URLs from the uploaded files

### Issue: Can't find repository in Vercel
**Solution:**
- Make sure you authorized Vercel to access your GitHub
- Try refreshing the repository list
- Check if repository is public or grant Vercel access to private repos

### Issue: Deployment fails
**Solution:**
- Check the deployment logs in Vercel dashboard
- Ensure `index.html` exists in the root of your repository
- Remove any server-side code if present

## Tips for Success

✅ **DO:**
- Name your main file `index.html`
- Keep files in the root directory
- Test locally by opening `index.html` in a browser first
- Use relative paths for images and assets

❌ **DON'T:**
- Don't use server-side code (PHP, Node.js server files) - Vercel serves static files
- Don't use absolute file paths like `C:/Users/...`
- Don't forget to commit changes before expecting updates

## File Structure

Your repository should look like this:
```
nityodit-birthday-party/
├── index.html           (your invitation page)
├── vercel.json         (optional configuration)
├── README.md           (optional description)
└── assets/             (optional folder for images)
    └── images/
```

## Quick Reference Commands

```bash
# Clone your repository
git clone https://github.com/YOUR-USERNAME/nityodit-birthday-party.git

# Navigate to folder
cd nityodit-birthday-party

# Add files
git add .

# Commit changes
git commit -m "Update invitation"

# Push to GitHub (triggers Vercel deployment)
git push origin main
```

## Need Help?

- Vercel Documentation: https://vercel.com/docs
- GitHub Documentation: https://docs.github.com
- Vercel Discord: https://vercel.com/discord

---

🎉 Once deployed, share your Vercel URL with all the party guests!

**Example URL:** https://nityodit-birthday-party.vercel.app
