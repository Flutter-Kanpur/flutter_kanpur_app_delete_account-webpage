# GitHub Pages Setup Guide

## Step 1: Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name the repository: `flutter-kanpur-pages`
5. Make it **Public** (required for free GitHub Pages)
6. **Do NOT** initialize with README, .gitignore, or license (we already have files)
7. Click "Create repository"

## Step 2: Push Your Code to GitHub

Run these commands in your terminal (you're already in the right directory):

```bash
# Add the remote repository (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/flutter-kanpur-pages.git

# Push your code to GitHub
git branch -M main
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" section in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Click "Save"

## Step 4: Wait for Deployment

- GitHub will build and deploy your page
- This usually takes 1-2 minutes
- You'll see a green checkmark when it's ready

## Step 5: Access Your Page

Your account deletion page will be available at:
```
https://YOUR_USERNAME.github.io/flutter-kanpur-pages/
```

## Step 6: Use in Google Play Console

In your Google Play Console, use this URL:
```
https://YOUR_USERNAME.github.io/flutter-kanpur-pages/
```

## Features of Your Page

✅ **Clear Instructions**: Step-by-step process for account deletion
✅ **Contact Information**: Email address for requests
✅ **Data Policy**: What data will be deleted/retained
✅ **Processing Time**: 7 business days response time
✅ **Mobile Responsive**: Works on all devices
✅ **Form Integration**: Users can fill out a form that opens their email client

## Customization

You can edit the `index.html` file to:
- Change the email address
- Modify the processing time
- Update the data retention policy
- Change the styling/colors

## Updating the Page

To update your page:
1. Edit the `index.html` file
2. Run these commands:
   ```bash
   git add .
   git commit -m "Update account deletion page"
   git push origin main
   ```
3. GitHub Pages will automatically update

## Troubleshooting

- **Page not loading**: Check if GitHub Pages is enabled in repository settings
- **Changes not showing**: Wait 1-2 minutes for GitHub to rebuild
- **404 error**: Make sure the repository is public and GitHub Pages is enabled
