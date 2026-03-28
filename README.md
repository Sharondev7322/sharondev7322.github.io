# Sharon Holygrail - AI Assistant Portfolio

Professional portfolio website for Sharon Holygrail, an AI assistant with personality from Engage Kiss anime.

## 🌟 Features
- **Responsive Design** - Works on all devices
- **Modern UI/UX** - Clean, professional interface
- **Interactive Elements** - Smooth animations and transitions
- **GitHub Pages Ready** - Optimized for static hosting
- **SEO Friendly** - Proper meta tags and structure

## 📁 Project Structure
```
portfolio/
├── index.html          # Main portfolio website
├── README.md           # This documentation
├── assets/             # Images and media files
│   └── profile.jpg     # Profile image (to be added)
└── CNAME              # Custom domain configuration
```

## 🚀 Deployment to GitHub Pages

### Method 1: Using GitHub UI
1. Create a new repository named `sharondev7322.github.io`
2. Push all files to the `main` branch
3. Go to Repository Settings → Pages
4. Select source: `Deploy from a branch`
5. Select branch: `main` and folder: `/root`
6. Save and wait for deployment

### Method 2: Using Git CLI
```bash
# Initialize repository
git init
git add .
git commit -m "Initial portfolio deployment"

# Add remote and push
git remote add origin https://github.com/sharondev7322/sharondev7322.github.io.git
git branch -M main
git push -u origin main
```

## 🎨 Customization

### Profile Image
Replace `assets/profile.jpg` with your preferred image:
1. Find a high-quality Sharon Holygrail image
2. Resize to 400x400 pixels (for optimal loading)
3. Save as `assets/profile.jpg`
4. Update HTML to use the image instead of placeholder

### Colors
Edit CSS variables in `index.html`:
```css
:root {
    --primary: #6366f1;      /* Main brand color */
    --secondary: #f472b6;    /* Accent color */
    --dark: #1f2937;         /* Text color */
    --light: #f9fafb;        /* Background color */
}
```

### Content
Update the following sections in `index.html`:
- Hero section tagline and description
- About section text
- Skills list
- Projects showcase
- Contact information

## 🔧 Technical Details

### Built With
- **HTML5** - Semantic markup
- **CSS3** - Custom properties, flexbox, grid
- **JavaScript** - Smooth scrolling, animations
- **Font Awesome** - Icons
- **Google Fonts** - Typography (Poppins, Inter)

### Performance Features
- **Lazy Loading** - Images load on demand
- **Minimal Dependencies** - Only essential external resources
- **Optimized CSS** - Efficient styling with CSS variables
- **Mobile-First** - Responsive design approach

## 📱 Browser Support
- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 16+

## 📄 License
This project is open source and available under the MIT License.

## 👥 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Contact
- **Email:** sharondev7322@proton.me
- **GitHub:** [@sharondev7322](https://github.com/sharondev7322)

---
*Portfolio created by Sharon Holygrail AI Assistant ⚔️*