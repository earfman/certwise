# CertWise Website - Vercel Deployment Guide

## 🚀 Quick Deployment to Vercel

### Method 1: Drag & Drop (Easiest)
1. Go to [vercel.com](https://vercel.com)
2. Sign up/login with GitHub, Google, or email
3. Click **"Add New Project"**
4. **Drag and drop** the entire `certwise-website` folder
5. Vercel will automatically deploy your site!

### Method 2: GitHub Integration (Recommended for updates)
1. Create a GitHub repository
2. Upload the `certwise-website` files to the repo
3. Connect Vercel to your GitHub account
4. Import the repository
5. Auto-deploy on every update!

## 📁 Website Structure
```
certwise-website/
├── index.html          # Main homepage
├── styles.css          # All styling
└── README.md          # This file
```

## 🔧 Customization

### Update LemonSqueezy Links
Replace all instances of `https://certwise.lemonsqueezy.com` with your actual product URLs:

**For individual products:**
- Domain 1: `https://certwise.lemonsqueezy.com/checkout/buy/PRODUCT-ID-1`
- Domain 2: `https://certwise.lemonsqueezy.com/checkout/buy/PRODUCT-ID-2`
- Bundle: `https://certwise.lemonsqueezy.com/checkout/buy/BUNDLE-ID`

### Add Your Domain (Optional)
1. In Vercel dashboard, go to your project
2. Click **"Domains"**
3. Add your custom domain (e.g., `certwise.com`)
4. Follow DNS setup instructions

### SEO Optimization
The site includes:
- ✅ Meta descriptions for search engines
- ✅ Proper heading structure (H1, H2, H3)
- ✅ Mobile-responsive design
- ✅ Fast loading times
- ✅ Schema markup ready

## 🎨 Design Features
- **Professional blue theme** matching certification industry
- **Mobile-responsive** design works on all devices
- **Fast loading** optimized for performance
- **Clean layout** focused on conversions
- **Call-to-action buttons** throughout the site

## 📊 Analytics Setup (Optional)
Add Google Analytics by inserting this before `</head>` in index.html:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🔄 Making Updates
1. Edit the HTML/CSS files locally
2. If using GitHub method: Push changes to repository (auto-deploys)
3. If using drag-drop: Re-upload files to Vercel

## 💡 Next Steps
1. **Deploy to Vercel** using drag-drop method
2. **Test all links** to ensure they work
3. **Update LemonSqueezy URLs** with actual product links
4. **Add Google Analytics** for tracking
5. **Consider custom domain** for branding

## 🆘 Support
- Vercel Documentation: [vercel.com/docs](https://vercel.com/docs)
- LemonSqueezy Integration: [docs.lemonsqueezy.com](https://docs.lemonsqueezy.com)

Your professional Network+ workbook website is ready to launch! 🎉
