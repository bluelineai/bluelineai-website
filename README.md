# Blueline AI Website

This folder contains your new Blueline AI website, ready to deploy.

## What's Included

- `index.html` - Your complete website (single file, no dependencies except Tailwind CDN)

## How to Deploy

### Option 1: Netlify (Easiest - Recommended)

1. Go to [netlify.com](https://netlify.com)
2. Sign up for a free account
3. Click "Add new site" → "Deploy manually"
4. Drag this entire folder into the upload area
5. Your site will be live at `your-site.netlify.app`
6. Go to "Domain settings" to connect your custom domain `bluelineai.com`

### Option 2: Vercel

1. Go to [vercel.com](https://vercel.com)
2. Sign up for a free account
3. Click "Add New Project"
4. Upload this folder
5. Follow their domain connection guide for `bluelineai.com`

### Option 3: GitHub Pages

1. Create a new GitHub repository
2. Upload these files
3. Go to Settings → Pages
4. Enable GitHub Pages
5. Configure custom domain

## Customization

### Update Contact Form

The contact form currently shows an alert. To connect it to a real backend:

**Option A: Netlify Forms (if hosting on Netlify)**

Replace the `<form>` tag on line 374 with:
```html
<form name="contact" method="POST" data-netlify="true" class="max-w-md mx-auto space-y-4">
```

**Option B: Formspree**

1. Sign up at [formspree.io](https://formspree.io)
2. Get your form endpoint
3. Replace the `<form>` tag with:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="max-w-md mx-auto space-y-4">
```

### Update Content

All content is in the `index.html` file. Search for specific text to find and update:

- Company stats (search for "95%", "10x", "24/7")
- Progress percentages (search for "65%", "45%", "75%")
- Social media links (search for "twitter.com" and "linkedin.com")
- Email address (search for "info@bluelineai.com")

### Update Colors

The site uses a cyan/blue color scheme. To change colors, search for:
- `cyan-400`, `cyan-500` - Primary accent color
- `purple-400`, `pink-600` - Secondary accent color
- `slate-950`, `slate-900`, `slate-800` - Background colors

## Technical Details

- **Framework**: Vanilla HTML/CSS/JS
- **Styling**: Tailwind CSS (via CDN)
- **Icons**: Heroicons (via inline SVG)
- **Font**: Manrope (via Google Fonts)
- **Performance**: ~100KB total size, loads in <1 second

## Support

For issues or questions, contact the developer or refer to:
- Netlify Docs: https://docs.netlify.com
- Vercel Docs: https://vercel.com/docs
- Tailwind CSS: https://tailwindcss.com

## License

This website is proprietary to Blueline AI.
