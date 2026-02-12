# Blueline AI Website

Modern, investor-focused website for Blueline AI emphasizing sovereign AI development and data independence.

## 🎯 Key Messaging

This website emphasises:
- **Sovereign AI**: Building proprietary models, not dependent on OpenAI, Anthropic, or other commercial LLMs
- **Data Independence**: Complete control over training data and model deployment
- **Evidence Management & EnforceEye**: Core product focus for law enforcement
- **Pre-Seed Stage**: Honest about current development phase (concept/design/research)
- **Fundraising**: Clear "Raising Seed Round" messaging for investors

**Language**: All content uses British English spelling and terminology.

## 📊 Current Status Reflected on Site

- **Stats**: Shown as "Target:", "Goal:", "Vision:" (aspirational, not achieved)
- **Progress**: 10-20% (realistic early-stage development)
- **Stage**: "Concept Phase", "Design Phase", "Research Phase"
- **Funding**: "Currently Raising Seed Round" badge clearly displayed

## Quick Start

This folder contains everything you need:
- `index.html` - Your complete website
- `icon.png` - Your Blueline AI logo
- `README.md` - This file

## ✅ Already Configured For GitHub Pages

✓ Single HTML file (no build process needed)
✓ All assets embedded or from CDN
✓ Contact form using FormSubmit (free, no API keys)
✓ Optimized for fast loading
✓ Mobile responsive

## 📧 Contact Form - How It Works

The contact form uses **FormSubmit** and is **fully configured** to send emails to info@bluelineai.com.

### ✅ Form Configuration Verified

The form is set up with:
- **Action**: `https://formsubmit.co/info@bluelineai.com`
- **Method**: POST
- **Email Subject**: "New Partnership Inquiry - Blueline AI"
- **Format**: Table layout for easy reading
- **Captcha**: Disabled for better user experience

### IMPORTANT: First-Time Activation

**The very first time someone submits the form**, FormSubmit will send a confirmation email to info@bluelineai.com with a link to activate.

**Steps:**
1. Someone fills out the form and clicks "Send Message"
2. Check info@bluelineai.com inbox (and spam folder)
3. You'll see an email from FormSubmit with subject "Please Confirm Form"
4. **Click the confirmation link** in that email
5. Done! All future submissions will arrive automatically

### What Happens After Activation

Once confirmed:
- Form submissions go straight to info@bluelineai.com
- You get an email with all the details:
  - Name
  - Email address
  - Organisation
  - Message
- You can reply directly to respond to inquiries
- No dashboard, no login needed - just emails in your inbox

### How to Test

1. Go to your website (bluelineai.com)
2. Scroll to the contact form
3. Fill it out with test data
4. Click "Send Message"
5. Check info@bluelineai.com (including spam folder)
6. Click the confirmation link (first time only)
7. Test again - should work instantly!

**Expected Email Content:**
```
From: FormSubmit <noreply@formsubmit.co>
Subject: New Partnership Inquiry - Blueline AI

Name: [Person's name]
Email: [Their email]
Organisation: [Their org]
Message: [Their message]
```

## 🔄 How to Update Your Site (GitHub Pages)

Since your site is hosted on GitHub Pages, here's how to make updates:

### Method 1: Edit Directly on GitHub (Quickest)

1. **Go to your GitHub repository**
2. **Click on index.html**
3. **Click the pencil icon** (✏️ Edit)
4. **Make your changes** in the editor
5. **Scroll down** and click **"Commit changes"**
6. **Wait 1-2 minutes** - changes appear on your live site

### Method 2: Upload New File

1. **Edit index.html** on your computer
2. **Go to GitHub** → Your repository
3. **Click on index.html** → **Delete file** (trash icon)
4. **Commit the deletion**
5. **Click "Add file"** → **"Upload files"**
6. **Upload your edited index.html**
7. **Commit changes**

### What Triggers Updates

- Any commit to your repository automatically rebuilds your site
- Changes typically appear within 1-2 minutes
- Check the "Actions" tab to see build status

## 🚀 Deployment (Already Done!)

Your site is hosted on GitHub Pages at:
- `https://yourusername.github.io/bluelineai-website/`
- Plus custom domain: `bluelineai.com` (if configured)

## 🎨 Customization Guide

All content is in `index.html`. Here's what you can easily update:

### Key Messaging

**Sovereign AI Emphasis:**
- Line 81: "Building Sovereign AI for Public Safety" (hero badge)
- Line 154: Technology intro emphasizing independence from commercial APIs
- Line 308-309: Sovereign AI Development section - highlights no dependency on third-party models

**To strengthen this message further**, search for "AI" in the file and add references to:
- "Proprietary models"
- "Independent of OpenAI/Anthropic"
- "In-house development"
- "Data sovereignty"

### Update Company Stats

Search for these values:
- `Target: 95%` - Aspirational reduction in report time
- `Goal: 10x` - Target for faster case linking  
- `Vision: 24/7` - Ultimate goal for automation

**Important**: These are shown as targets/goals, not achievements, since you're pre-seed.

### Update Development Progress

In the "Vision" section, find:
- `width: 15%` - Evidence Management Platform (concept phase)
- `width: 10%` - EnforceEye Smart Camera (design phase)
- `width: 20%` - AI Model Architecture (research phase)

Adjust these percentages as you make real progress.

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

- **Hosting**: GitHub Pages (free, unlimited bandwidth for reasonable use)
- **Size**: ~100KB total (ultra-fast loading)
- **Framework**: Pure HTML/CSS/JavaScript (no build required)
- **Styling**: Tailwind CSS (loaded from CDN)
- **Icons**: Heroicons SVG (inline)
- **Font**: Manrope (Google Fonts CDN)
- **Form**: FormSubmit (free email service)

### GitHub Pages Specifics

✅ **No deployment needed** - Changes go live automatically
✅ **HTTPS by default** - Free SSL certificate  
✅ **Custom domain support** - Can use bluelineai.com
✅ **Fast CDN** - Served globally by GitHub
✅ **99.9% uptime** - Reliable Microsoft infrastructure

### Performance Optimizations for GitHub Pages

- Single HTML file = instant page load
- No JavaScript frameworks = no bundle size
- CDN resources = parallel loading
- Minimal CSS = fast paint times
- Lazy loading not needed = simple codebase

## 💼 Investor-Ready Features

This website is designed to attract Series A investors by emphasizing:

### 1. **Sovereign AI Differentiation**
- Clear messaging: "Building proprietary AI models from the ground up"
- Emphasizes independence from OpenAI, Anthropic, Google
- Highlights data sovereignty and control
- Positions as deep-tech infrastructure play

### 2. **Market Positioning**
- Focus: Law enforcement (defined market)
- Products: Evidence Management + EnforceEye (specific solutions)
- Stage: R&D/Prototype (honest about current state)
- Vision: Foundational AI infrastructure

### 3. **Credibility Signals**
- Professional dark theme (tech-forward, serious)
- Progress indicators (shows momentum)
- Specific capabilities (not vague promises)
- Technical depth (sovereign AI, edge computing)

### 4. **Clear Call-to-Action**
- Three partnership types: Investors, Agency Partners, Tech Partners
- Simple contact form
- Direct email visible
- Low-friction engagement

## 🎯 Key Differentiators to Emphasize

When talking to investors, highlight:

1. **"We're building our own models"** - Not reselling OpenAI/Anthropic
2. **"Data never leaves the agency"** - Critical for gov contracts
3. **"Purpose-built for law enforcement"** - Not general-purpose AI
4. **"Complete stack control"** - From data collection (camera) to analysis (AI) to storage (evidence hub)

## 📞 Need Help?

### Form Issues
- **Not receiving emails?** Check spam/junk folder
- **Still waiting for confirmation?** First submission requires clicking link in confirmation email
- **Form not working?** Make sure you're connected to internet and try again
- Visit formsubmit.co/help for support

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
