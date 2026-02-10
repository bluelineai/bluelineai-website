# Blueline AI Website

Modern, investor-focused website for Blueline AI with your custom logo and working contact form.

## Quick Start

This folder contains everything you need to deploy your new website:
- `index.html` - Your complete website
- `icon.png` - Your Blueline AI logo
- `README.md` - This file

## ✅ What's Already Configured

✓ Your logo is integrated throughout the site (navbar, footer)
✓ Contact form sends emails to **info@bluelineai.com**
✓ Responsive design (works on mobile, tablet, desktop)
✓ Professional dark theme optimized for investor audience
✓ All content focused on Evidence Management and EnforceEye

## 📧 Contact Form - How It Works

The contact form is **already set up** to send emails to info@bluelineai.com using Formspree.

### IMPORTANT: First-Time Activation

**The first time someone submits the form**, Formspree will send a confirmation email to info@bluelineai.com. 

**You MUST click the confirmation link** in that email to activate the form.

After that, all form submissions will automatically arrive in your inbox!

### What You'll Receive

When someone fills out your contact form, you'll get an email with:
- Their name
- Their email address
- Their organization
- Their message

You can reply directly to respond to inquiries.

### Optional: Formspree Dashboard

If you want to view all submissions in a dashboard:

1. Sign up at [formspree.io](https://formspree.io) using info@bluelineai.com
2. All submissions will appear in your dashboard
3. Free tier: 50 submissions/month

**The form works either way** - with or without a Formspree account!

## 🚀 Deployment Instructions

### Option 1: Netlify (Recommended - Easiest)

1. Go to [netlify.com](https://netlify.com) and sign up (free)
2. Click "Add new site" → "Deploy manually"
3. **Drag this entire folder** into the upload area
4. Your site will be live at `your-site.netlify.app`
5. Go to "Domain management" to connect `bluelineai.com`

**That's it!** Your site is live.

### Option 2: Vercel

1. Go to [vercel.com](https://vercel.com) and sign up (free)
2. Click "New Project"
3. Upload this folder
4. Follow their guide to connect your custom domain

### Option 3: GitHub Pages

1. Create a new GitHub repository
2. Upload these files
3. Go to Settings → Pages
4. Enable GitHub Pages
5. Configure custom domain

## 🎨 Customization Guide

All content is in the `index.html` file. Here's how to update common elements:

### Update Company Stats

Search for these values in index.html:
- `95%` - Reduction in Report Time
- `10x` - Faster Case Linking  
- `24/7` - Automated Processing

### Update Progress Bars

In the "Vision" section, search for:
- `width: 65%` - Evidence Management Platform progress
- `width: 45%` - EnforceEye Smart Camera progress
- `width: 75%` - AI Model Training progress

### Update Social Links

Search for:
- `https://twitter.com/bluelineAI`
- `https://linkedin.com/company/bluelineai`

Replace with your actual social media URLs.

### Update Colors

The site uses Tailwind CSS classes. To change the color scheme:
- `cyan-400`, `cyan-500` - Primary accent (currently cyan/blue)
- `purple-400`, `pink-600` - Secondary accent (currently purple/pink)
- `slate-950`, `slate-900`, `slate-800` - Background colors

## 📁 File Structure

```
bluelineai-website/
├── index.html          # Your complete website
├── icon.png           # Your logo
└── README.md          # This file
```

## 🔧 Technical Details

- **Size**: ~100KB total (ultra-fast loading)
- **Framework**: Pure HTML/CSS/JavaScript
- **Styling**: Tailwind CSS (loaded from CDN)
- **Icons**: Heroicons SVG
- **Font**: Manrope (Google Fonts)
- **Dependencies**: None (all loaded from CDN)

## 🎯 Features

- Smooth scroll navigation
- Mobile-responsive menu
- Animated hero section
- Hover effects on cards
- Progress indicators
- Working contact form
- Professional typography
- Fast loading speed

## ⚡ Performance

- No build process required
- Loads in under 1 second
- Optimized for Core Web Vitals
- Works on all modern browsers

## 📞 Need Help?

### Formspree Issues
- Check spam folder for confirmation email
- Verify email is sent to info@bluelineai.com
- Visit formspree.io/support for help

### Deployment Issues
- Netlify: https://docs.netlify.com
- Vercel: https://vercel.com/docs
- GitHub Pages: https://docs.github.com/pages

### General Questions
- All content is in one file (index.html)
- Search for text to find and update
- Logo is referenced as "icon.png"

## 📄 License

© 2025 Blueline AI. All rights reserved.
