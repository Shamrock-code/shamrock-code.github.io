# Shamrock Website

A modern, responsive website for the Shamrock scientific computing framework built with HTML, CSS, and JavaScript.

## 🚀 Features

- **Modern Design**: Clean, professional design with viridis-inspired color palette
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth animations, copy-to-clipboard functionality, and mobile navigation
- **Fast Loading**: Optimized static files for quick loading times
- **Accessibility**: Built with accessibility best practices

## 📁 Project Structure

```
website-testing/
├── index.html          # Main HTML file
├── styles.css          # CSS styles with modern design
├── script.js           # JavaScript for interactivity
├── _static/            # Static assets
│   ├── logo.png        # Shamrock logo
│   └── no_background_nocolor.png  # Shamrock banner
├── .github/workflows/  # CI/CD configuration
│   └── upload-page.yml # GitHub Pages deployment
└── README.md           # This file
```

## 🎨 Design Features

### Color Palette
- **Primary Purple**: `#440154` - Main brand color
- **Secondary Purple**: `#482475` - Secondary brand color
- **Blue**: `#355f8d` - Accent color
- **Teal**: `#22a884` - Success/positive color
- **Green**: `#7ad151` - Highlight color

### Typography
- **Font Family**: Inter (Google Fonts)
- **Responsive**: Scales appropriately across devices
- **Hierarchy**: Clear typographic hierarchy with proper contrast

### Components
- **Navigation**: Fixed header with mobile hamburger menu
- **Hero Section**: Eye-catching introduction with call-to-action buttons
- **Quick Links**: Grid of important links and resources
- **Features**: Highlighted feature cards with icons
- **Installation**: Code examples with copy functionality
- **Documentation**: Links to various documentation resources
- **Community**: Community links and contribution call-to-action
- **Footer**: Comprehensive footer with links and social media

## 🛠️ Development

### Local Development
1. Clone the repository
2. Open `index.html` in your browser
3. Make changes to HTML, CSS, or JavaScript files
4. Refresh browser to see changes

### File Structure
- **HTML**: Semantic structure with proper accessibility
- **CSS**: Modern CSS with CSS Grid, Flexbox, and CSS Variables
- **JavaScript**: Vanilla JS with modern ES6+ features

### Key JavaScript Features
- Mobile navigation toggle
- Copy-to-clipboard functionality
- Smooth scrolling for anchor links
- Intersection Observer for animations
- Form validation utilities

## 🚀 Deployment

The website is automatically deployed to GitHub Pages via GitHub Actions.

### CI/CD Pipeline
1. **Trigger**: Push to main branch or pull request
2. **Build**: Copy static files to build directory
3. **Deploy**: Upload to GitHub Pages
4. **Result**: Website available at `https://shamrock-code.github.io/website-testing`

### Manual Deployment
If you need to deploy manually:
1. Run the build script locally
2. Upload files to your web server
3. Ensure all assets are accessible

## 📱 Responsive Design

The website is fully responsive with breakpoints at:
- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px

### Mobile Features
- Hamburger menu navigation
- Touch-friendly buttons and links
- Optimized typography for small screens
- Proper spacing and padding

## 🎯 Performance

### Optimizations
- **Minimal Dependencies**: Only Font Awesome for icons
- **Efficient CSS**: CSS Grid and Flexbox for layout
- **Fast Loading**: Optimized images and minimal JavaScript
- **Caching**: Static assets can be cached effectively

### Best Practices
- Semantic HTML structure
- CSS custom properties for maintainability
- Progressive enhancement
- Accessibility compliance

## 🔧 Customization

### Colors
Update the CSS variables in `styles.css`:
```css
:root {
    --primary-purple: #440154;
    --secondary-purple: #482475;
    /* ... other colors */
}
```

### Content
- Update `index.html` for content changes
- Modify `styles.css` for styling changes
- Edit `script.js` for functionality changes

### Adding New Sections
1. Add HTML structure to `index.html`
2. Add corresponding CSS to `styles.css`
3. Add any JavaScript functionality to `script.js`

## 📄 License

This website is part of the Shamrock project. See the main project repository for license information.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Submit a pull request

## 📞 Support

For questions or issues:
- Create an issue in the GitHub repository
- Check the main Shamrock documentation
- Join the community discussions

---

Built with ❤️ for the Shamrock community 