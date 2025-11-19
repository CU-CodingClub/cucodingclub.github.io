# Coding Club Chandigarh University - Website

A professional, formal, and college-friendly website for the Coding Club at Chandigarh University. Built with clean, semantic HTML, modern CSS, and vanilla JavaScript.

## 📋 Project Overview

This website showcases the Coding Club's mission, events, projects, and team. It features a professional academic design with light colors, minimal animations, and excellent responsiveness across all devices.

## ✨ Features

- **Clean Academic Design**: Professional layout inspired by university websites
- **Fully Responsive**: Mobile-first approach with breakpoints for all devices
- **Light Color Palette**: 
  - Primary: #0A4D9C (Professional Blue)
  - Secondary: #0066CC (Bright Blue)
  - Background: #FFFFFF (Clean White)
  - Light Gray: #F5F7FA (Subtle backgrounds)
- **Minimal Animations**: Subtle fade-in effects on scroll
- **Accessibility**: Keyboard navigation, ARIA labels, semantic HTML
- **Fast Performance**: No heavy frameworks, optimized CSS and JavaScript

## 📁 Folder Structure

```
coding_clubCU/
├── index.html              # Homepage
├── about.html              # Club information, mission, activities
├── events.html             # Upcoming events and workshops
├── team.html               # Team members and leadership
├── projects.html           # Showcase of club projects
├── assets/
│   ├── css/
│   │   ├── style.css       # Main styles
│   │   └── responsive.css  # Mobile & tablet styles
│   ├── js/
│   │   └── script.js       # JavaScript functionality
│   └── images/             # Image assets (for future use)
└── README.md               # This file
```

## 🎯 Pages

### 1. **Home (index.html)**
   - Eye-catching hero section with club mission
   - Quick preview of club activities
   - Statistics showcase (members, events, projects, etc.)
   - Call-to-action buttons

### 2. **About (about.html)**
   - Club vision and mission statements
   - List of core activities
   - Values section
   - Detailed information about workshops, competitions, and initiatives

### 3. **Events (events.html)**
   - Card-based event layout
   - Event date, time, and location information
   - Event categories (workshops, competitions, hackathons, talks)
   - Registration and "Learn More" buttons

### 4. **Projects (projects.html)**
   - Showcase of completed and ongoing projects
   - Technology stack badges
   - Project leads and descriptions
   - Different project categories (Web App, Tool, Mobile App, etc.)

### 5. **Team (team.html)**
   - Leadership section
   - Coordinators and committee members
   - Member roles and contact information
   - "Join Us" call-to-action

## 🎨 Design System

### Colors
- **Primary Blue**: #0A4D9C - Main branding color
- **Secondary Blue**: #0066CC - Hover states and accents
- **White**: #FFFFFF - Clean backgrounds
- **Light Gray**: #F5F7FA - Subtle backgrounds for cards
- **Dark**: #333333 - Text color
- **Text Light**: #666666 - Secondary text

### Typography
- **Font Family**: Poppins (from Google Fonts)
- **Weights Used**: 300, 400, 500, 600, 700
- **Hierarchy**: 
  - H1: 2.5rem (bold)
  - H2: 2rem (bold)
  - H3: 1.5rem (semi-bold)
  - Body: 1rem (regular)

### Spacing System
- XS: 0.5rem
- SM: 1rem
- MD: 1.5rem
- LG: 2rem
- XL: 3rem
- 2XL: 4rem

### Shadows
- Light: `0 2px 8px rgba(0, 0, 0, 0.08)`
- Heavy: `0 4px 16px rgba(0, 0, 0, 0.12)`

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required

### Installation

1. Clone or download the project
   ```bash
   git clone https://github.com/yourusername/coding_clubCU.git
   cd coding_clubCU
   ```

2. Open in a web server (required for full functionality)
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   
   # Or use any other local server
   ```

3. Open your browser and navigate to `http://localhost:8000`

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and up
- **Tablet**: 769px to 1199px
- **Mobile**: 481px to 768px
- **Small Mobile**: 360px to 480px
- **Extra Small**: 360px and below

## 🔧 JavaScript Features

- **Mobile Menu Toggle**: Hamburger menu for tablets and mobile
- **Smooth Scrolling**: Smooth page scrolling for anchor links
- **Fade-in Animations**: Cards fade in when scrolled into view
- **Active Navigation**: Current page indicator in navigation
- **Keyboard Navigation**: Escape key closes mobile menu
- **Accessibility**: ARIA labels and semantic HTML

## 🎭 Animations

All animations are minimal and professional:
- **Fade-in**: Elements fade in when scrolled into view (0.6s)
- **Hover Effects**: Subtle shadow and translation on hover
- **Transitions**: 0.3s ease timing for all interactive elements

## 📝 Customization

### Colors

```css
:root {
    --primary: #0A4D9C;
    --secondary: #0066CC;
    --background: #FFFFFF;
    --light-gray: #F5F7FA;
    --dark: #333333;
}
```

### Content
- Club name and branding
- Event information
- Team members
- Project descriptions

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## ♿ Accessibility

- Semantic HTML5 structure
- ARIA labels for interactive elements
- Keyboard navigation support
- Color contrast compliant (WCAG AA)
- Focus indicators for keyboard navigation
- Alt text support for images

## ⚡ Performance

- Zero external dependencies
- Optimized CSS (no unused styles)
- Vanilla JavaScript (no framework overhead)
- Fast page load times
- Mobile-optimized images (recommended)

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Report bugs
- Suggest improvements
- Submit pull requests
- Improve documentation

## 📞 Contact

**Coding Club Chandigarh University**
- Email: codingclub@chandigarh.edu.in
- Campus: Chandigarh University, India

## 🙏 Credits

- Design inspired by modern university websites
- Built with HTML5, CSS3, and Vanilla JavaScript
- Font: Poppins from Google Fonts

---

**Last Updated**: 18 November 2025
**Version**: 1.0.0

Made with ❤️ by Coding Club CU

