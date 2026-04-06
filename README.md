# 🍵 Tea House

A premium, responsive website for a tea and botanical solutions supplier. Built with modern web technologies to provide an elegant user experience and showcase our high-quality tea products.

**🌐 [Live Demo](https://ahammad204.github.io/tea-house/)**

---

## ✨ Features

- **Responsive Design** - Seamlessly adapts to all device sizes (mobile, tablet, desktop)
- **Modern UI/UX** - Built with Tailwind CSS and DaisyUI components for a professional appearance
- **Product Showcase** - Featured tea products with detailed descriptions
- **Client Testimonials** - Carousel-style reviews from satisfied customers
- **Newsletter Signup** - Email subscription form for marketing campaigns
- **Accessibility** - Semantic HTML and inclusive design practices
- **Performance Optimized** - Fast loading with CDN-hosted libraries
- **Interactive Elements** - Smooth animations and intuitive navigation

---

## 🏗️ Project Structure

```
tea-house/
├── index.html              # Main HTML file with all sections
├── tailwind.config.js      # Tailwind CSS configuration
├── README.md               # This file
└── images/                 # Image assets
    ├── banner.png          # Hero banner image
    ├── tea-1.png to tea-4.png
    ├── fresh-1.png & fresh-2.png
    ├── news-1.png to news-3.png
    ├── client.png          # Client testimonial avatar
    ├── circles.png         # Decorative circles
    ├── cup.png             # Cup icon
    ├── arrow.png           # Navigation arrow
    └── bg_cup.png          # Background element
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Semantic markup and page structure |
| **Tailwind CSS** | Utility-first CSS framework for styling |
| **DaisyUI** | Component library built on Tailwind CSS |
| **Font Awesome** | Icon library for UI elements |
| **Manrope Font** | Custom typography from Google Fonts |

---

## 📋 Page Sections

### 1. **Hero Banner**
- Eye-catching headline: "It's good tea time at The Tea House"
- Call-to-action button with "Explore More"
- Trust Pilot ratings display (5.00 stars)
- Responsive layout for mobile and desktop

### 2. **Featured Products**
- Grid display of 4 featured tea products
- Product cards with images and descriptions
- Milk Tea variants highlighting
- Responsive grid (1 column on mobile, 2 on tablet, 4 on desktop)

### 3. **Great Tea Section**
- "Great Tea, Freshly Presented" showcase
- Image gallery layout with text descriptions
- Feature highlights:
  - Unique Taste
  - Premium Quality
- Rich content about the brand story

### 4. **Client Testimonials**
- "Meet Our Super Client" section
- Carousel-style review cards
- Client avatar images
- Rating system integration
- Orange gradient background for visual impact

### 5. **Footer**
- Newsletter subscription form
- Service links (Branding, Design, Marketing, Advertisement)
- Company information
- Legal links (Terms, Privacy, Cookie Policy)
- Copyright information

---

## 🎨 Design Features

### Color Scheme
- **Primary Gradient**: Orange (#FF8938) to Red (#F00)
- **Background Colors**: Light grays and blues for contrast
- **Text Colors**: Professional dark text for readability

### Typography
- **Font Family**: Manrope (400, 500, 600, 700, 800 weights)
- **Headings**: Bold and extra-bold weights for hierarchy
- **Body Text**: Regular weight for readability

### Responsive Breakpoints
- **Mobile**: Full-width, single column layout
- **Tablet**: 2-column grid (md breakpoint)
- **Desktop**: Multi-column optimized layouts (lg breakpoint)

---

## 🖥️ Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools required - ready to use!

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ahammad204/tea-house.git
   cd tea-house
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server for better performance:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

3. **View the site**
   - Local: `http://localhost:8000`
   - Live: [https://ahammad204.github.io/tea-house/](https://ahammad204.github.io/tea-house/)

---

## 📱 Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile Safari (iOS 12+)
- ✅ Chrome Mobile (Android 5+)

---

## 🔧 Customization

### Modify Colors
Edit the Tailwind custom configuration in `index.html`:
```javascript
tailwind.config = {
  theme: {
    extend: {
      colors: {
        'gradiant-start': '#FF8938',  // Change primary
        'gradiant-end': '#F00',       // Change secondary
      }
    }
  }
}
```

### Update Content
- Edit text directly in `index.html`
- Replace images in the `images/` folder
- Maintain the same file names or update image src attributes

### Modify Tailwind Config
Update `tailwind.config.js` for global style changes:
```javascript
module.exports = {
    content: ["./src/**/*.{html,js}"],
    theme: {
      extend: {
        // Add your customizations here
      },
    },
    plugins: [],
}
```

---

## 📊 Performance

- **Lighthouse Score**: Optimized for performance
- **CDN Resources**: Tailwind CSS and DaisyUI served via CDN
- **Image Optimization**: Recommended to compress images
- **Load Time**: < 3 seconds on standard connections

### Performance Tips
1. Optimize images using tools like TinyPNG or ImageOptim
2. Use browser caching for static assets
3. Consider using a CDN for distribution
4. Minify HTML/CSS in production builds

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Contribution Guidelines
- Maintain responsive design compatibility
- Follow existing code style and structure
- Test on multiple devices before submitting
- Update README if adding new features

---

## 📝 Content Information

### Brand Background
The Tea House is a tea and botanical solutions supplier providing:
- Premium tea products
- Exceptional customer service
- Diverse tea selections
- Customized solutions for tea enthusiasts

**Established**: 2006 | **Rating**: 5.00 ⭐ (TrustPilot)

---

## 📄 License

This project is provided as-is for educational and commercial use. 

Copyright © 2023 - All rights reserved by ACME Industries Ltd

---

## 👤 Author

**Ahammad**
- GitHub: [@ahammad204](https://github.com/ahammad204)
- Live Demo: [https://ahammad204.github.io/tea-house/](https://ahammad204.github.io/tea-house/)

---

## 🔗 External Resources

- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [DaisyUI Components](https://daisyui.com/)
- [Font Awesome Icons](https://fontawesome.com/)
- [Google Fonts - Manrope](https://fonts.google.com/specimen/Manrope)

---

## 📞 Support

For questions or issues:
- Open an issue on GitHub
- Check existing documentation
- Review the code comments

---

## 🎯 Future Enhancements

- [ ] Add product filtering functionality
- [ ] Implement shopping cart system
- [ ] Add product detail pages
- [ ] Integrate payment gateway
- [ ] Add blog section
- [ ] Multi-language support
- [ ] Dark mode toggle
- [ ] Backend integration for newsletter


Made with ☕ by kazi Ahammad Ullah
