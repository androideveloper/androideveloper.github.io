# Roland Egiazaryan - Personal Portfolio

A minimalistic, Apple-inspired landing page showcasing my professional profile and social presence.

🌐 **Live Site**: [https://androideveloper.github.io](https://androideveloper.github.io)

## ✨ Features

- **🍎 Apple-Style Design**: Modern aesthetics inspired by Apple's latest design principles
- **📱 Fully Responsive**: Seamless experience across all devices and screen sizes
- **🌓 Dark Mode Support**: Automatic theme switching based on system preferences
- **⚡ Performance Optimized**: Fast loading with minimal dependencies
- **♿ Accessible**: WCAG compliant with proper focus management and screen reader support
- **📦 PWA Ready**: Installable as a progressive web app with manifest and service worker support

## 🎨 Design System

### Color Palette
- **Primary**: Apple Blue (#007AFF)
- **Secondary**: Apple Purple (#AF52DE)
- **System Colors**: Dynamic light/dark mode colors
- **Gradients**: Subtle blue-to-purple gradients for accents

### Typography
- **Font Family**: Apple's system font stack (-apple-system, BlinkMacSystemFont, system-ui)
- **Font Weights**: 300 (Light), 400 (Regular), 500 (Medium), 600 (Semibold), 700 (Bold)
- **Responsive Scaling**: Fluid typography using clamp() for optimal readability

### Components
- **Profile Section**: Circular avatar with elegant hover animations
- **Social Cards**: Grid-based layout with platform-specific brand colors
- **Navigation**: Clean, minimalist approach focusing on content

## 🛠️ Tech Stack

- **HTML5**: Semantic markup with proper meta tags
- **CSS3**: Modern features including CSS Grid, Flexbox, and CSS Custom Properties
- **Progressive Enhancement**: Works without JavaScript
- **Modern Favicon**: SVG favicon with PNG fallback
- **Web Manifest**: PWA capabilities for mobile installation

## 📂 Project Structure

```
├── index.html          # Main landing page
├── css/
│   ├── reset.css       # CSS reset for cross-browser consistency
│   └── styles.css      # Main stylesheet with Apple-inspired design
├── images/
│   └── avatar-2025.png # Profile photo
├── favicon.svg         # Modern SVG favicon
├── manifest.json       # PWA manifest file
├── LICENSE            # MIT License
└── README.md          # This file
```

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/androideveloper/androideveloper.github.io.git
   cd androideveloper.github.io
   ```

2. **Open locally**
   ```bash
   # Simple HTTP server
   python -m http.server 8000
   # Or with Node.js
   npx serve .
   ```

3. **Visit** `http://localhost:8000`

## 🎯 Customization

### Update Profile Information
1. Replace `images/avatar-2025.png` with your photo
2. Update social media links in `index.html`
3. Modify the hero content (name, title, description)

### Styling
- **Colors**: Edit CSS custom properties in `:root` selector
- **Typography**: Adjust font sizes in the `clamp()` functions
- **Layout**: Modify grid and flexbox properties for different arrangements

### PWA Configuration
- Update `manifest.json` with your app details
- Add your own icons in various sizes (192x192, 512x512)

## 📱 Browser Support

- **Modern Browsers**: Chrome 88+, Firefox 85+, Safari 14+, Edge 88+
- **Mobile**: iOS 14+, Android 7+
- **Graceful Degradation**: Basic functionality on older browsers

## 🤝 Contributing

Feel free to fork this project and adapt it for your own use! If you make improvements, pull requests are welcome.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Design inspiration from Apple's design system
- Icons from Font Awesome
- Original template inspiration from various open-source portfolio projects

---

**Built with ❤️ by Roland Egiazaryan**

*Software Engineer | Hiker | Traveler | Photographer | Local Guide*
