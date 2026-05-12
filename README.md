# Stanford University Website Replica

> A faithful recreation of Stanford University's homepage and main sections, built with vanilla HTML, CSS, and JavaScript. Perfect for learning responsive web design and front-end development practices.

![Stanford Replica](https://img.shields.io/badge/Status-Complete-brightgreen)
![HTML5](https://img.shields.io/badge/HTML-5-E34C26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS-3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-blue)

## 📖 About This Project

This is an educational web development project that replicates the design and structure of Stanford University's official website. It demonstrates modern web design principles, responsive layout techniques, and clean code organization using only vanilla web technologies.

**Note:** This is an independent learning project and is not affiliated with or endorsed by Stanford University.

---

## ✨ Key Features

- 🎨 **Responsive Design** - Mobile-first approach that works seamlessly on all devices
- 🏗️ **Semantic HTML5** - Proper markup structure for accessibility and SEO
- 💅 **Pure CSS3** - No CSS frameworks; custom styling with Flexbox and Grid
- ⚡ **Vanilla JavaScript** - Interactive components without external dependencies
- 📱 **Mobile Optimized** - Touch-friendly navigation and adaptive layouts
- 🎯 **Cross-browser Compatible** - Works on Chrome, Firefox, Safari, and Edge
- 📦 **Zero Dependencies** - Just HTML, CSS, and JavaScript
- 🧹 **Clean Code** - Well-organized, commented, and easy to understand

---

## 🚀 Quick Start

### No Installation Required!

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/stanford-website-replica.git
   cd stanford-website-replica
   ```

2. **Open in your browser:**
   ```bash
   # Option A: Direct file opening
   open index.html
   
   # Option B: Using Python (recommended for better compatibility)
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

3. **That's it!** No build tools, no npm packages, no configuration needed.

---

## 📁 Project Structure

```
stanford-website-replica/
│
├── index.html                 # Main homepage
├── pages/
│   ├── admissions.html       # Admissions section
│   ├── academics.html        # Academics & programs
│   ├── research.html         # Research overview
│   └── about.html            # About Stanford
│
├── css/
│   ├── style.css             # Main stylesheets
│   ├── responsive.css        # Mobile responsiveness
│   └── variables.css         # CSS custom properties
│
├── js/
│   └── script.js             # Interactive components
│
├── assets/
│   ├── images/               # All image files
│   ├── icons/                # SVG icons
│   └── fonts/                # Custom fonts
│
├── README.md                 # This file
└── LICENSE                   # MIT License
```

---

## 💻 Technologies & Tools

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Semantic structure and content |
| **CSS3** | Styling, layouts (Flexbox, Grid), animations |
| **JavaScript (ES6)** | DOM manipulation, interactivity, event handling |
| **Git** | Version control |

**No external libraries or frameworks used!**

---

## 🎯 What You'll Learn

By exploring this project, you'll understand:

- ✅ Responsive web design principles and implementation
- ✅ CSS Flexbox and Grid for modern layouts
- ✅ Semantic HTML best practices
- ✅ JavaScript DOM manipulation and event listeners
- ✅ Mobile-first design methodology
- ✅ CSS animations and transitions
- ✅ File organization and project structure
- ✅ Cross-browser compatibility considerations

---

## 📱 Browser Support

| Browser | Support | Version |
|---------|---------|---------|
| Chrome | ✅ Full | Latest |
| Firefox | ✅ Full | Latest |
| Safari | ✅ Full | Latest |
| Edge | ✅ Full | Latest |
| Internet Explorer | ❌ Not supported | N/A |

---

## 🔧 How to Navigate & Explore

### Desktop View
1. Open `index.html` in your browser
2. Use the navigation menu to explore different sections
3. Click links to navigate between pages
4. Hover over elements to see interactive effects

### Mobile View
1. Open the project in your browser
2. Press `F12` to open Developer Tools
3. Click the device toolbar icon (mobile view)
4. Select different device sizes to test responsiveness

### Inspect the Code
```javascript
// Right-click anywhere on the page → "Inspect" or "Inspect Element"
// Explore:
// - HTML structure in the Elements tab
// - CSS styles in the Styles panel
// - JavaScript in the Console
```

---

## 🎨 Customization Guide

### Easy Modifications

**1. Change Colors & Branding**
```css
/* In css/variables.css */
:root {
  --primary-color: #DAA520;      /* Change Stanford red */
  --secondary-color: #003366;    /* Change secondary color */
  --text-color: #333333;
}
```

**2. Update Content**
- Edit text directly in HTML files
- Replace image files in `assets/images/`
- Update links in navigation menu

**3. Modify Fonts**
```css
/* In css/style.css */
body {
  font-family: 'Your Font', sans-serif;
}
```

**4. Add New Sections**
1. Create new HTML file in `pages/` folder
2. Copy navigation from `index.html`
3. Add link to new page in navigation menu
4. Style with existing CSS

---

## 📂 Featured Sections

### Homepage (`index.html`)
- Hero banner with compelling visuals
- Featured programs and announcements
- About Stanford snapshot
- Quick navigation to main sections
- Footer with links and contact info

### Admissions (`pages/admissions.html`)
- Admissions overview
- Application requirements
- Program details
- Contact information

### Academics (`pages/academics.html`)
- Academic programs listing
- School and department information
- Educational opportunities

### Research (`pages/research.html`)
- Research initiatives
- Faculty research areas
- Innovation highlights

### About (`pages/about.html`)
- Stanford history and mission
- Key facts and statistics
- Notable achievements

---

## ⚡ Performance Tips

The project is optimized for performance:
- No external dependencies = faster load time
- Minimized CSS and JavaScript
- Optimized images
- Efficient DOM queries
- CSS Grid and Flexbox for layout efficiency

**Lighthouse Score Target:** 90+ on all metrics

---

## 🤝 Contributing

This is an educational project. You can:
- Fork the repository for your own learning
- Modify it to practice web development skills
- Create your own university website replica
- Share improvements via pull requests

---

## 📚 Learning Resources

Helpful resources while exploring this project:

- [MDN Web Docs](https://developer.mozilla.org/) - HTML, CSS, JS documentation
- [W3C Standards](https://www.w3.org/) - Web standards and specifications
- [CSS-Tricks](https://css-tricks.com/) - CSS techniques and tutorials
- [JavaScript.info](https://javascript.info/) - JavaScript fundamentals

---

## 🐛 Known Issues & Limitations

- **No Backend:** This is a front-end only project (no server-side functionality)
- **Static Content:** Information is hardcoded (not dynamic)
- **Images:** Placeholder/demo images used for educational purposes
- **Forms:** Not functional (for demonstration only)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, and merge...
```

---

## ⚖️ Disclaimer

**This is an independent educational project.** 

- Not affiliated with Stanford University
- Not an official Stanford University website
- Created for learning and demonstration purposes only
- Stanford University is a trademark of The Board of Trustees of the Leland Stanford Junior University
- Images and branding used for reference only

---

## 📧 Questions or Feedback?

Have questions about the code or the project?

- 📝 Open an [Issue](https://github.com/yourusername/stanford-website-replica/issues)
- 💬 Start a [Discussion](https://github.com/yourusername/stanford-website-replica/discussions)
- 🔗 Check out the [Wiki](https://github.com/yourusername/stanford-website-replica/wiki)

---

## 👨‍💻 Author

**[Your Name]**
- 🔗 [GitHub Profile](https://github.com/yourusername)
- 💼 [LinkedIn](https://linkedin.com/in/yourprofile)
- 🌐 [Portfolio Website](https://yourwebsite.com)

---

## 🎓 About the Creator

This project was created as an educational exercise in modern web development. The goal was to practice:
- Responsive design techniques
- Semantic HTML markup
- CSS layout methods
- Vanilla JavaScript interactivity
- Project organization and structure

---

## 📊 Project Stats

```
Total Lines of Code:     ~2,500+
HTML Files:              5
CSS Files:               3
JavaScript Files:        1
Total Assets:            50+
Responsive Breakpoints:  4 (Mobile, Tablet, Desktop, Large)
Time to Load (avg):      < 2 seconds
```

---

## 🔄 Version History

### v1.0.0 (Latest)
- ✅ Complete homepage
- ✅ Main section pages
- ✅ Responsive design
- ✅ Interactive components
- ✅ Cross-browser tested

---

## 🌟 If You Found This Helpful

⭐ **Star this repository** to show support!  
🔄 **Share** with others learning web development  
🍴 **Fork** to create your own version  

---

**Happy Coding! 🚀**

Last Updated: 2024  
Status: Actively Maintained ✨
