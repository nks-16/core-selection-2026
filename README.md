# NISB Annual Budget Plan 2026 - Website

## Overview
This is a comprehensive, responsive website showcasing the annual budget plan for NISB (IEEE Student Branch) for the year 2026. Created as a pre-interview task for the NISB Core Selection Process 2026.

## Features
- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Professional color scheme
- ✅ Comprehensive budget breakdown
- ✅ Event-wise and month-wise planning
- ✅ Clean, modern UI/UX
- ✅ Print-friendly styling

## File Structure
```
Task - 1/
│
├── index.html          # Main HTML file
├── styles.css          # Stylesheet with responsive design
├── logo-left.png       # Left logo placeholder (add your NISB logo)
├── logo-right.png      # Right logo placeholder (add your IEEE logo)
└── README.md           # This file
```

## Setup Instructions

### 1. Add Your Logos
Replace the placeholder logo files with your actual logos:
- **logo-left.png**: Your NISB logo (recommended size: 200x200px or similar)
- **logo-right.png**: IEEE or institution logo (recommended size: 200x200px or similar)

### 2. Open the Website
Simply open `index.html` in any modern web browser:
- Google Chrome (recommended)
- Mozilla Firefox
- Microsoft Edge
- Safari

### 3. Deploy Options

#### Option A: GitHub Pages (Free)
1. Create a GitHub repository
2. Upload all files
3. Go to Settings → Pages
4. Select main branch and save
5. Your site will be live at `https://yourusername.github.io/repository-name`

#### Option B: Netlify (Free)
1. Visit netlify.com
2. Drag and drop the entire folder
3. Get instant deployment with custom URL

#### Option C: Local Hosting
- Simply open `index.html` directly in your browser
- No server required for frontend-only site

## Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2c3e50;      /* Main dark color */
    --secondary-color: #3498db;    /* Accent blue */
    --accent-color: #e74c3c;       /* Red accents */
    /* ... */
}
```

### Modifying Budget Data
All budget information is in `index.html`. Search for the specific sections:
- Executive Summary
- Major Events Budget
- Recurring Activities
- Month-wise Calendar

### Adding More Sections
Follow the existing section structure:
```html
<section class="section">
    <h2>Your Section Title</h2>
    <!-- Your content here -->
</section>
```

## Budget Summary
- **Total Annual Budget**: ₹12,85,000
- **Major Events**: 8 flagship fests
- **Recurring Activities**: 48 sessions throughout the year
- **Contingency Reserve**: ₹85,000

## Technology Stack
- Pure HTML5
- CSS3 with Flexbox & Grid
- No JavaScript dependencies
- No external frameworks
- Lightweight and fast

## Browser Compatibility
✅ Chrome 90+
✅ Firefox 88+
✅ Safari 14+
✅ Edge 90+
✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Responsive Breakpoints
- **Desktop**: 1024px and above
- **Tablet**: 768px - 1024px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## Performance
- Fast loading (no heavy dependencies)
- Optimized for all screen sizes
- Print-friendly layout

## Credits
Created for NISB Core Selection Process 2026
Pre-interview Task Submission

## License
Free to use and modify for NISB purposes

## Support
For any issues or questions, please contact the NISB recruitment team.

---
**Note**: Remember to replace the placeholder logos with your actual NISB and IEEE logos before deployment!
