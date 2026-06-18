# Ashish PJ - Portfolio Website

A modern, responsive dark-themed portfolio website showcasing skills, projects, and achievements in data science and Python development.

## 🎨 Features

- **Modern Dark Theme**: Sleek dark UI with cyan and neon green accents
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: Interactive hover effects and scroll animations
- **Professional Design**: Clean layout with gradient backgrounds and glassmorphic elements
- **Optimized Performance**: Lightweight and fast-loading
- **SEO Friendly**: Proper semantic HTML structure

## 📁 File Structure

```
ashish-portfolio/
├── index.html          # Main HTML file
├── style.css           # Stylesheet with dark theme
├── script.js           # JavaScript for interactivity
├── README.md           # This file
└── .gitignore          # Git ignore file
```

## 🚀 Quick Start

### Option 1: Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ashish-portfolio.git
cd ashish-portfolio
```

2. Open `index.html` in your web browser:
```bash
# On macOS
open index.html

# On Windows
start index.html

# On Linux
xdg-open index.html
```

Or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if http-server is installed)
http-server
```

Then visit `http://localhost:8000` in your browser.

### Option 2: Deploy to GitHub Pages

1. Create a new repository on GitHub named `ashish-portfolio` (or any name you prefer)

2. Initialize git and push files:
```bash
git init
git add .
git commit -m "Initial commit: Portfolio website"
git branch -M main
git remote add origin https://github.com/yourusername/ashish-portfolio.git
git push -u origin main
```

3. Enable GitHub Pages:
   - Go to your repository on GitHub
   - Navigate to Settings → Pages
   - Under "Source", select `main` branch
   - Click Save
   - Your portfolio will be live at: `https://yourusername.github.io/ashish-portfolio`

## 🎯 Sections

### 1. **Hero Section**
- Eye-catching introduction
- Call-to-action buttons

### 2. **About Section**
- Personal overview
- Key statistics (CGPA, certifications, projects)

### 3. **Skills Section**
- Programming languages
- Development tools
- Data visualization & AI/ML expertise

### 4. **Projects Section**
- Featured project: Parkinson's Disease Detection
- Technology stack and project details

### 5. **Certifications & Achievements**
- Professional certifications
- Sports achievements

### 6. **Contact Section**
- Email, phone, and LinkedIn links
- Easy way to get in touch

## 🛠️ Customization

### Change Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --primary-color: #00d4ff;      /* Cyan */
    --secondary-color: #00ffaa;    /* Mint Green */
    --accent-color: #ff006e;       /* Pink/Magenta */
    --bg-dark: #0a0e27;
    --bg-darker: #050812;
    /* ... more variables */
}
```

### Update Content
Edit `index.html` to add:
- New projects
- Additional skills
- More certifications
- Update contact information

### Add More Projects
Duplicate the `.project-card` div and update the content.

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🔗 Links

- **Portfolio**: https://yourusername.github.io/ashish-portfolio
- **LinkedIn**: https://www.linkedin.com/in/ashish-paikera-44288a2a0
- **Email**: ashishpaikera83@gmail.com
- **Phone**: +91 9108980937

## 🎨 Design Details

- **Font**: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- **Icons**: Font Awesome 6.4.0
- **Colors**: Dark theme with cyan, mint green, and pink accents
- **Animations**: CSS transitions and keyframe animations
- **Backdrop Effects**: Glassmorphism with blur effects

## 📊 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Deployment Options

### GitHub Pages (Recommended)
- Free hosting
- Direct from GitHub repository
- Automatic deployment on push

### Other Platforms
- **Netlify**: Drag and drop deployment
- **Vercel**: Zero-config deployment
- **Firebase Hosting**: Google's hosting solution
- **AWS S3 + CloudFront**: Scalable solution

## 📝 License

This portfolio template is open source and available for personal and commercial use.

## 💡 Tips

1. **Update Regularly**: Keep your portfolio current with latest projects
2. **Mobile First**: Always test on mobile devices
3. **Accessibility**: Use semantic HTML and proper color contrast
4. **Performance**: Optimize images and minify CSS/JS for production
5. **SEO**: Add meta descriptions and keywords for better search visibility

## 🐛 Troubleshooting

**Images not loading?**
- Check file paths in HTML
- Ensure image files are in the same directory

**Styles not applied?**
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Check CSS file path in HTML

**Links not working?**
- Verify anchor IDs match href values
- Check for typos in email/phone links

## 📞 Contact & Support

For questions or suggestions:
- Email: ashishpaikera83@gmail.com
- LinkedIn: https://www.linkedin.com/in/ashish-paikera-44288a2a0

---

**Last Updated**: 2024

Enjoy your new portfolio! 🎉