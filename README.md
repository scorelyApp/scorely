# Scorely Privacy Policy & Terms Website

This directory contains the privacy policy and terms of service website for Scorely, hosted via GitHub Pages.

## 🌐 Live URL

Once deployed, the privacy policy will be available at:
```
https://scorelyapp.github.io/scorely/privacy-policy.html
```

Or if using a custom domain:
```
https://scorely.app/privacy-policy.html
```

## 📁 Files

- **index.html** - Landing page with app information
- **privacy-policy.html** - Comprehensive privacy policy (required for App Store)
- **terms-of-service.html** - Terms of service agreement
- **styles.css** - Styling matching Scorely's brand colors

## 🚀 Deployment Instructions

### Step 1: Push to GitHub

This folder is already part of your repository. Simply push it:

```bash
git add docs/
git commit -m "Add privacy policy and terms of service website"
git push origin main
```

### Step 2: Enable GitHub Pages

1. Go to your GitHub repository: https://github.com/scorelyApp/scorely
2. Click on **Settings** (top right)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/docs`
5. Click **Save**
6. Wait 2-3 minutes for deployment

Your website will be live at: `https://scorelyapp.github.io/scorely/`

### Step 3: Add URL to App Store Connect

1. Go to [App Store Connect](https://appstoreconnect.apple.com)
2. Select Scorely
3. Go to **App Information**
4. Under **Privacy Policy URL**, enter:
   ```
   https://scorelyapp.github.io/scorely/privacy-policy.html
   ```
5. Save changes

## 🎨 Brand Colors Used

The website uses Scorely's brand colors:
- Primary Background: `#0D1B2A`
- Primary Accent: `#FFB100`
- Secondary Accent: `#00C2A8`
- Neutral Surface: `#F4F4F9`

## 📝 Updating Content

To update the privacy policy or terms:

1. Edit the relevant HTML file in `/docs`
2. Update the "Last Updated" date
3. Commit and push changes
4. GitHub Pages will auto-deploy (takes 2-3 minutes)

## 🔗 Custom Domain (Optional)

If you own `scorely.app` or another domain:

1. Add a `CNAME` file in `/docs` with your domain:
   ```
   scorely.app
   ```
2. Configure DNS at your domain registrar:
   - Add a CNAME record pointing to `scorelyapp.github.io`
3. Enable HTTPS in GitHub Pages settings

## ✅ What's Included

The privacy policy covers:
- ✅ What data you DON'T collect (no PII)
- ✅ What anonymous data you DO collect (via Firebase Analytics)
- ✅ Why you collect data (improve features, prioritize games)
- ✅ User controls (opt-out in Settings)
- ✅ Third-party services (Firebase, BGG, Apple)
- ✅ Children's privacy (COPPA compliance)
- ✅ GDPR compliance for EU users
- ✅ Contact information

The terms of service covers:
- ✅ License to use
- ✅ User content and data
- ✅ Intellectual property rights
- ✅ Board game trademarks disclaimer
- ✅ Age requirements
- ✅ Bluetooth multiplayer
- ✅ Disclaimer of warranties
- ✅ Limitation of liability
- ✅ Apple App Store compliance

## 📧 Contact

Questions? Contact: ScorelyApp@gmail.com

---

Made with ❤️ for board game enthusiasts

