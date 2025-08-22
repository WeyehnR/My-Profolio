# Hostinger Deployment Checklist

## Pre-Upload Checklist ✅
- [x] index.html exists and redirects to html/portfolio.html
- [x] All CSS files are in css/ folder
- [x] Profile photo (me.jpg) is in assets/ folder
- [x] Resume (Weyehn_Reeves_Resume.pdf) is in assets/ folder
- [x] portfolio.js exists in root
- [x] All links in HTML point to correct paths

## Files to Upload to public_html:
```
public_html/
├── index.html
├── html/
│   └── portfolio.html
├── css/
│   ├── main.css
│   ├── base.css
│   ├── components/
│   │   ├── navigation.css
│   │   └── tech-tags.css
│   └── sections/
│       ├── hero.css
│       ├── about.css
│       ├── skills.css
│       ├── tools.css
│       ├── projects.css
│       ├── experience.css
│       ├── contact.css
│       └── footer.css
├── assets/
│   ├── me.jpg
│   └── Weyehn_Reeves_Resume.pdf
├── portfolio.js
└── README.md
```

## After Upload Testing:
1. Visit: paleviodetred-jay-841218.hostingersite.com
2. Check if redirect works
3. Test all navigation links
4. Test download resume button
5. Test project GitHub links
6. Test mobile responsiveness
7. Check contact form (if functional)

## Troubleshooting:
- If site doesn't load: Check if index.html is in public_html root
- If images don't show: Check file paths in HTML
- If styles don't load: Check CSS file paths
- If resume doesn't download: Check assets/ folder upload

## Optional Improvements:
- Enable SSL certificate in Hostinger panel
- Set up custom domain
- Enable Cloudflare for better performance
- Add Google Analytics tracking
