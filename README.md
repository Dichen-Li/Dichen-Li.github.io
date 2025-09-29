# Dichen Li - Personal Website

A clean, responsive personal website built with static HTML/CSS/JS for GitHub Pages.

## Features

- **Home Page**: Professional bio, research interests, publications, and news
- **CV Page**: Inline PDF viewer with download option
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Fast Loading**: Minimal dependencies, optimized for performance
- **SEO Optimized**: Meta tags, Open Graph, and semantic HTML

## File Structure

```
website/
├── index.html          # Home page
├── cv.html            # CV page with PDF viewer
├── cv.pdf             # Your CV document
├── assets/
│   ├── styles.css     # Main stylesheet
│   ├── headshot.jpg   # Professional photo (add this)
│   └── README.md      # Assets documentation
└── README.md          # This file
```

## Setup Instructions

1. **Add your headshot**: Place a square-cropped professional photo as `assets/headshot.jpg`
2. **Update content**: Edit `index.html` and `cv.html` with your information
3. **Deploy to GitHub Pages**:
   - Push to GitHub repository
   - Go to Settings → Pages
   - Source: Deploy from a branch
   - Branch: main / (root)
   - Your site will be available at `https://<username>.github.io/website/`

## Customization

- **Colors**: Edit CSS variables in `assets/styles.css`
- **Content**: Update HTML files with your information
- **Layout**: Modify the CSS for different layouts

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive design
- PDF viewing requires modern browser support

## Performance

- No build process required
- Minimal dependencies
- Optimized images recommended
- Fast loading on all devices
