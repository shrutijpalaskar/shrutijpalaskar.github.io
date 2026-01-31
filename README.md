# Personal Academic Website

A clean, modern personal website inspired by minimalist academic portfolios.

## Features

- 🎨 Clean, minimalist design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Fast loading - pure HTML/CSS/JS, no frameworks
- 🎯 Easy to customize
- 🚀 Ready for GitHub Pages deployment

## Quick Start

### Local Testing

1. Open `index.html` in your browser, or
2. Use a local server:
   ```bash
   # Python 3
   python3 -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js (if you have npx)
   npx serve
   ```
3. Visit `http://localhost:8000` in your browser

### Customization

1. **Profile Image**: Replace `profile.jpg` with your photo
2. **Personal Info**: Edit `index.html`:
   - Update name, title, affiliation
   - Update email and social links
   - Add your bio in the About section
   - Add your news items
   - Add your publications

3. **Styling**: Modify `styles.css` to change:
   - Colors (see CSS variables at top)
   - Fonts
   - Layout spacing

4. **CV**: Add your `cv.pdf` file to the directory

## Deployment to GitHub Pages

### Option 1: Replace Your Existing Site

1. Copy all files from `new-website/` to your `shrutijpalaskar.github.io` repository
2. Commit and push:
   ```bash
   cd shrutijpalaskar.github.io
   git add .
   git commit -m "Update website with new design"
   git push origin main
   ```
3. Your site will be live at `https://shrutijpalaskar.github.io`

### Option 2: Test in a New Repository First

1. Create a new repository on GitHub (e.g., `new-website-test`)
2. Push these files to that repository
3. Enable GitHub Pages in repository settings
4. Test at `https://yourusername.github.io/new-website-test`
5. Once satisfied, move to your main repository

## File Structure

```
new-website/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # Interactive features
├── profile.jpg         # Your profile photo
├── cv.pdf             # Your CV (add this)
└── README.md          # This file
```

## Interactive Features

- Click profile image for a fun animation
- Smooth scrolling
- Fade-in animations on scroll
- Email copy-to-clipboard
- Responsive navigation
- Press 'h' key to scroll to top

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Tips

- Keep content concise and scannable
- Use high-quality profile photo (square, at least 400x400px)
- Update news section regularly
- Link to paper PDFs, code repositories, and project pages
- Keep CV updated

## License

Free to use and modify for personal use.