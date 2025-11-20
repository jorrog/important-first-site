# ImportantFirst Website

Simple, professional website for the ImportantFirst mobile app with all required legal pages for app store submission.

## 📁 Files

- **index.html** - Main landing page with features and download links
- **privacy.html** - Privacy Policy (required by App Store & Google Play)
- **terms.html** - Terms of Service (required by App Store & Google Play)
- **support.html** - Support & FAQ page
- **styles.css** - Responsive styles for all pages
- **icon.png** - App logo/favicon

## 🚀 Features

- **Fully responsive** - Works on desktop, tablet, and mobile
- **No dependencies** - Pure HTML/CSS (no frameworks needed)
- **App Store ready** - Includes all required legal documentation
- **Professional design** - Clean, modern UI with gradient hero section
- **SEO optimized** - Proper meta tags and semantic HTML

## 📋 What's Included

### Legal Pages (Required for App Stores)

✅ **Privacy Policy** - Comprehensive GDPR & CCPA compliant
- Data collection and usage
- Firebase/Google services disclosure
- User rights (access, deletion, export)
- Children's privacy (COPPA)
- International data transfers
- Contact information

✅ **Terms of Service** - Complete legal protection
- Account requirements
- Acceptable use policy
- Intellectual property
- Disclaimers and limitations
- Termination procedures
- Dispute resolution

✅ **Support Page** - User help center
- Comprehensive FAQ
- Contact information
- Troubleshooting guides
- Feature explanations

### Marketing Pages

✅ **Landing Page** - Professional homepage
- Hero section with value proposition
- 4-Quadrant explanation
- Feature showcase
- Download buttons (ready for app store links)

## 🌐 Deployment Options

### Option 1: GitHub Pages (Free)
```bash
# Create a new repo on GitHub
# Push this folder to the repo
# Enable GitHub Pages in repo settings
```

### Option 2: Netlify (Free)
```bash
# Drag and drop this folder to netlify.com
# Or connect to GitHub for auto-deploys
```

### Option 3: Vercel (Free)
```bash
# Import this folder to vercel.com
# Automatic SSL and global CDN
```

### Option 4: Firebase Hosting (Free tier available)
```bash
firebase init hosting
# Select this folder
firebase deploy
```

## 📝 Before Publishing

### Update Required URLs

1. **App Store Links** (in index.html)
   - Replace placeholder App Store button with real link
   - Replace placeholder Google Play button with real link

2. **Email Addresses** (in all pages)
   - Set up these email addresses or update to your actual emails:
     - support@importantfirst.app
     - privacy@importantfirst.app
     - legal@importantfirst.app
     - feedback@importantfirst.app
     - bugs@importantfirst.app

3. **Legal Information** (in terms.html)
   - Update "[Your Jurisdiction]" with your actual jurisdiction
   - Add your company name if applicable

## 🔗 App Store Requirements

### Apple App Store
- ✅ Privacy Policy URL (use privacy.html)
- ✅ Support URL (use support.html)
- ✅ Terms of Service (optional but recommended)

### Google Play Store
- ✅ Privacy Policy URL (required - use privacy.html)
- ✅ Support email/website (use support.html)

## 🎨 Customization

### Colors
Edit `styles.css` `:root` variables:
```css
--primary: #7C3AED;        /* Purple brand color */
--q1-red: #EF4444;         /* Q1 quadrant */
--q2-green: #10B981;       /* Q2 quadrant */
--q3-yellow: #F59E0B;      /* Q3 quadrant */
--q4-gray: #6B7280;        /* Q4 quadrant */
```

### Logo
The site uses the actual app icon (`icon.png`). To update it:
- Replace `icon.png` with your new logo
- Recommended size: 512x512px or larger
- Format: PNG with transparency

### Content
All content is in plain HTML - easy to edit without any build process.

## 📱 Testing Locally

Simply open any `.html` file in your browser:
```bash
# macOS
open index.html

# Or use a local server for best results
python3 -m http.server 8000
# Visit http://localhost:8000
```

## ✅ Validation Checklist

Before going live:
- [ ] All email addresses are set up and working
- [ ] App store download links are added
- [ ] Privacy policy reviewed by legal (if needed)
- [ ] Terms of service reviewed
- [ ] Contact forms tested
- [ ] All links work correctly
- [ ] Mobile responsive design tested
- [ ] SSL certificate enabled (automatic with most hosts)

## 📄 License

These legal documents are templates. Please have them reviewed by a legal professional before publishing, especially if you're collecting user data or operating in regulated industries.

## 🆘 Support

For questions about the website:
- Check the code comments
- All pages are standard HTML/CSS
- No build process or dependencies needed

---

**Ready to deploy!** Choose a hosting option above and your app will have a professional web presence with all required legal pages. 🚀
