# Mfanafuthi Magcaba — Junior Software Developer Portfolio

A clean, modern, responsive portfolio website showcasing projects, skills, and experience.

## Features

- **Responsive Design**: Adapts seamlessly to mobile, tablet, and desktop screens.
- **Accessible**: Includes skip-to-content link, keyboard navigation, focus states, and semantic HTML.
- **Dark Theme**: Modern gradient background with glassmorphism card design.
- **Mobile Menu**: Hamburger navigation menu on smaller screens.
- **Smooth Scroll**: Internal navigation links scroll smoothly to sections.
- **SEO-Ready**: Meta tags for search engines and social sharing.

## File Structure

```
portfolio/
├── mfanafuthi_magcaba_portfolio.html  (Main HTML file)
├── styles.css                          (Stylesheet)
├── scripts.js                          (JavaScript enhancements)
├── README.md                           (This file)
└── favicon.ico                         (Optional: add your favicon here)
```

## Quick Start

### Local Preview

1. Open the `mfanafuthi_magcaba_portfolio.html` file in your browser.
   - **Windows**: Double-click the file or right-click → Open with → your preferred browser.
   - **macOS/Linux**: Double-click or open with your preferred browser.

2. Or, use a simple local server (Python 3):
   ```bash
   cd c:\Users\mfanafuthi\Documents\portfolio
   python -m http.server 8000
   ```
   Then open `http://localhost:8000` in your browser.

### Customization

- **Colors**: Edit the CSS variables in `styles.css` (`:root` section) to change the theme.
- **Content**: Edit text, projects, skills, and experience directly in the HTML.
- **Fonts**: Update the font family in `styles.css` or add a Google Fonts link in the `<head>`.
- **Contact**: Update email and phone links in the HTML, or replace with a contact form service (see below).

## Deployment

### GitHub Pages (Recommended)

1. Create a GitHub repository named `portfolio` or `mfanafuthi_magcaba_portfolio`.
2. Push the files (`.html`, `.css`, `.js`) to the repository.
3. Go to **Settings** → **Pages** → set source to `main` branch.
4. Your portfolio will be live at `https://<your-username>.github.io/portfolio`.

**Push to GitHub:**
```bash
cd c:\Users\mfanafuthi\Documents\portfolio
git init
git add .
git commit -m "Initial commit: portfolio site"
git branch -M main
git remote add origin https://github.com/<your-username>/portfolio.git
git push -u origin main
```

### Netlify

1. Sign up at [netlify.com](https://netlify.com).
2. Drag and drop the portfolio folder onto Netlify, or:
   - Connect your GitHub repository.
   - Netlify auto-deploys on every push.

### Other Hosting

- **Vercel**: Push to GitHub, connect Vercel, auto-deploys.
- **Self-hosted**: Upload files to your web server via FTP/SSH.

## Contact Form (Optional)

To add a contact form that sends emails without a backend:

### Option 1: Netlify Forms (Easiest)

1. Update the contact section HTML to use a `<form>` with `netlify` attribute:
   ```html
   <form name="contact" method="POST" netlify>
     <input type="text" name="name" placeholder="Your name" required />
     <input type="email" name="email" placeholder="Your email" required />
     <textarea name="message" placeholder="Your message" required></textarea>
     <button type="submit">Send</button>
   </form>
   ```
2. Deploy to Netlify (see above).
3. Submissions appear in your Netlify dashboard.

### Option 2: Formspree

1. Visit [formspree.io](https://formspree.io).
2. Create an account and set up a form endpoint.
3. Update the contact form `action` to your Formspree endpoint.

## Accessibility

- **Skip Link**: Press `Tab` at the top to skip to main content.
- **Keyboard Navigation**: All links and buttons are keyboard-accessible.
- **Focus Indicators**: Clear focus outlines for keyboard users.
- **Semantic HTML**: Proper heading hierarchy and landmark regions.

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Tips

- Add project screenshots or thumbnails by replacing the project descriptions with images.
- Update the favicon by adding a `favicon.ico` file to the portfolio folder.
- Track analytics with Google Analytics: add the tracking code to the `<head>`.
- Test on mobile devices to ensure responsive design.

## License

This portfolio is your personal project. Feel free to customize and share.

---

**Questions or improvements?** Update the HTML, CSS, or JavaScript files as needed. Redeploy to see changes live.
