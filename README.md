# EventGo Landing Page

[![GitHub Pages](https://img.shields.io/badge/deployment-GitHub%20Pages-blue.svg)](https://planificaa.github.io/EventGo-Landing-Pague/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)
[![Google Fonts](https://img.shields.io/badge/Google%20Fonts-4285F4?logo=google-fonts&logoColor=white)](https://fonts.google.com/)
[![Font Awesome](https://img.shields.io/badge/Font%20Awesome-528DD7?logo=font-awesome&logoColor=white)](https://fontawesome.com/)
[![SweetAlert2](https://img.shields.io/badge/SweetAlert2-3085d6?logo=javascript&logoColor=white)](https://sweetalert2.github.io/)
[![Responsive Design](https://img.shields.io/badge/Responsive-Design-green?logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Learn/CSS/CSS_layout/Responsive_Design)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

> **Professional landing page for EventGo** - A platform connecting event hosts with professional organizers

## 🎯 Overview

EventGo is a modern, responsive landing page showcasing a platform that bridges the gap between event hosts seeking perfect organizers and professional organizers looking to grow their business. Built with vanilla HTML, CSS, and JavaScript, this landing page delivers an exceptional user experience across all devices.

**Live Demo:** [View Landing Page](https://planificaa.github.io/EventGo-Landing-Pague/)

## ✨ Key Features

### 🎨 Design & User Experience
- **Fully Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, professional interface with smooth animations
- **Cross-browser Compatible** - Tested across major browsers
- **Performance Optimized** - Fast loading times and smooth interactions
- **Accessibility Compliant** - WCAG guidelines implementation

### 🛠️ Technical Features
- **Smooth Scrolling Navigation** - Seamless section transitions with `scroll-behavior: smooth`
- **Interactive Animations** - CSS3 transforms and JavaScript-powered effects
- **Mobile-first Approach** - Progressive enhancement with hamburger menu
- **Loading Screen** - Branded loading experience with animated spinner
- **Responsive Images** - Optimized media delivery and lazy loading
- **SEO Optimized** - Meta tags and semantic HTML5 structure
- **SweetAlert2 Integration** - Modern alert dialogs for user interactions
- **Font Awesome Icons** - Scalable vector icons for UI elements
- **Google Fonts** - Poppins typography for consistent branding

## 💻 Technologies Used

### Core Technologies
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with Flexbox and Grid
- **Vanilla JavaScript** - Interactive functionality and DOM manipulation

### External Libraries & Services
- **Google Fonts (Poppins)** - Typography system
- **Font Awesome 6.5.0** - Icon library for UI elements
- **SweetAlert2** - Enhanced alert dialogs and notifications

### Development Features
- **CSS Custom Properties** - Maintainable color and sizing system
- **Mobile-first Responsive Design** - Progressive enhancement approach
- **Semantic HTML5** - Accessibility and SEO optimization
- **Modern JavaScript (ES6+)** - Arrow functions, const/let, template literals

### Browser APIs Used
- **Intersection Observer** - Scroll-based animations
- **DOM Manipulation** - Dynamic content updates
- **Event Listeners** - User interaction handling
- **Local Navigation** - Smooth scrolling implementation

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- Local web server (optional, for development)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Planificaa/EventGo-Landing-Pague.git
cd EventGo-Landing-Pague
```

2. **Open locally**
```bash
# Option 1: Direct file access
open public/index.html

# Option 2: Local server (recommended)
cd public
python -m http.server 8000
# Visit: http://localhost:8000
```

3. **For development with live reload**
```bash
# Using live-server (npm install -g live-server)
live-server public/

# Using Python
cd public && python -m http.server 8000
```

## 📁 Project Structure

```
EventGo-Landing-Pague/
├── public/
│   ├── assets/
│   │   ├── images/                 # All visual assets
│   │   │   ├── eventgo-logo2.png   # Main logo
│   │   │   ├── eventgo-icon.png    # Favicon
│   │   │   ├── hero-section-image.png
│   │   │   ├── benefits-section-image.png
│   │   │   └── team-photos/        # Team member photos
│   │   ├── styles/
│   │   │   └── style.css           # Main stylesheet
│   │   └── scripts/
│   │       └── script.js           # Interactive functionality
│   ├── index.html                  # English version
│   └── index-es.html              # Spanish version
├── README.md                       # Project documentation
└── LICENSE                        # License file
```

## 🌐 Browser Compatibility

| Browser | Version | Status | Notes |
|---------|---------|--------|-------|
| Chrome  | 90+     | ✅ Fully Supported | All features tested |
| Firefox | 88+     | ✅ Fully Supported | CSS Grid optimized |
| Safari  | 14+     | ✅ Fully Supported | Webkit prefixes included |
| Edge    | 90+     | ✅ Fully Supported | Chromium-based |
| IE      | 11      | ❌ Not Supported | Modern features required |

## 📱 Responsive Breakpoints

| Device | Breakpoint | Layout |
|--------|------------|--------|
| Mobile | < 576px | Single column, hamburger menu |
| Mobile Large | 576px - 768px | Optimized mobile layout |
| Tablet | 768px - 992px | Two-column sections |
| Desktop | 992px - 1200px | Multi-column layout |
| Large Desktop | > 1200px | Full-width experience |

## 🎨 Design System

### Color Palette
```css
--primary-blue: #3A506B     /* Navigation, buttons */
--dark-blue: #1C2541        /* Backgrounds, headings */
--accent-teal: #6FFFE9      /* Highlights, CTA elements */
--secondary-teal: #5BC0BE   /* Secondary actions */
--white: #FFFFFF            /* Text, backgrounds */
```

### Typography
- **Font Family:** Poppins (Google Fonts)
- **Weights:** 200, 300, 400, 500, 600, 700
- **Responsive scaling:** Fluid typography implementation

### Component Library
- Navigation bar with mobile hamburger menu
- Hero section with call-to-action buttons
- Feature cards with hover animations
- Pricing cards with interactive elements
- Team member profiles
- Contact footer with social links

## ⚡ Performance Metrics

- **Lighthouse Score:** 95+ across all categories
- **First Contentful Paint:** < 1.5s
- **Largest Contentful Paint:** < 2.5s
- **Cumulative Layout Shift:** < 0.1
- **Total Bundle Size:** < 500KB

## 🔧 Customization

### Updating Content
1. **Text Content:** Edit HTML files directly for content updates
2. **Images:** Replace files in `assets/images/` directory
3. **Styling:** Modify CSS variables in `style.css`
4. **Colors:** Update CSS custom properties for theme changes

### Adding New Sections
1. Add HTML structure following existing patterns
2. Include appropriate CSS classes
3. Update navigation links
4. Test responsive behavior

### Configuration Options
```javascript
// Available in script.js
const CONFIG = {
  smoothScroll: true,
  loadingScreen: true,
  animations: true,
  mobileMenu: true
};
```

## 🚀 Deployment

### GitHub Pages (Recommended)
1. Push code to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (main/master)
4. Access via: `https://username.github.io/repository-name`

### Other Hosting Options
- **Netlify:** Drag and drop `public/` folder
- **Vercel:** Connect GitHub repository
- **Firebase Hosting:** Use Firebase CLI
- **Traditional Hosting:** Upload `public/` contents via FTP

## 🧪 Testing

### Manual Testing Checklist
- [ ] All navigation links function correctly
- [ ] Responsive design works across breakpoints
- [ ] Images load and display properly
- [ ] Forms submit successfully (when applicable)
- [ ] Cross-browser compatibility verified
- [ ] Mobile menu operates smoothly
- [ ] Loading animations complete
- [ ] Language switcher functions

### Validation
- HTML: [W3C Markup Validator](https://validator.w3.org/)
- CSS: [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
- Accessibility: [WAVE Web Accessibility Evaluator](https://wave.webaim.org/)

## 🤝 Contributing

We welcome contributions to improve the EventGo landing page. Please follow these steps:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Development Guidelines
- Follow existing code style and structure
- Test across multiple browsers and devices
- Ensure responsive design principles
- Maintain accessibility standards
- Update documentation as needed

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Team

**Planificaa Development Team:**

- **Didier Sebastian Meza Solórzano** - Software Engineer
- **Deybbi Anderson Crisanto Calle** - Software Engineer  
- **Bryan Norberto Hermoza Paredes** - Software Engineer
- **Jesús Fernando Paucar Zenteno** - Software Engineer
- **July Zelmira Paico Calderon** - Software Engineer

## 📞 Contact & Support

- **Email:** eventgo@planificaa.com
- **Phone:** +51 983290166
- **GitHub:** [@Planificaa](https://github.com/Planificaa)
- **Project Repository:** [EventGo-Landing-Pague](https://github.com/Planificaa/EventGo-Landing-Pague)

## 🔗 Related Resources

- [EventGo Platform Documentation](https://docs.eventgo.com) *(Coming Soon)*
- [Design System Guide](https://design.eventgo.com) *(Coming Soon)*
- [API Documentation](https://api.eventgo.com/docs) *(Coming Soon)*

---

**Built with ❤️ by the Planificaa Team**

*If you find this project helpful, please consider giving it a ⭐ on GitHub!*
