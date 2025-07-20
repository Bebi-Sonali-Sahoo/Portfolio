# Bebi Sonali Sahoo - Professional Portfolio

A modern, responsive portfolio website showcasing skills, experience, and projects in Data Science and Python Full-Stack Development.

## 🌟 Features

### ✨ Professional Design
- Modern, clean interface with smooth animations
- Responsive design that works on all devices
- Professional color scheme with gradient backgrounds
- Interactive hover effects and transitions

### 📱 Responsive Navigation
- Fixed header with smooth scrolling navigation
- Mobile-friendly hamburger menu
- Active section highlighting
- Smooth scroll-to-section functionality

### 🖼️ Dynamic Content Management
- **Profile Image Upload**: Click the camera icon to upload and change your profile photo
- **CV Upload & Download**: Upload your CV and provide download functionality for visitors
- **Local Storage**: Uploaded files persist between browser sessions

### 📧 Interactive Contact Form
- Form validation with error handling
- Success/error notifications
- Email format validation
- Responsive design

### 🎨 Animated Sections
- Fade-in animations on scroll
- Typing effect for hero text
- Bouncing skill tags
- Parallax effects
- Timeline animations for experience section

### 🔗 Social Integration
- Direct links to GitHub and LinkedIn profiles
- Social media icons in header and footer
- Professional contact information display

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS/JavaScript for customization

### Installation
1. Download or clone this repository
2. Open `index.html` in your web browser
3. The portfolio is ready to use!

### File Structure
```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── assets/             # Images and media files
│   ├── profile-photo.jpg
│   ├── project1.jpg
│   ├── project2.jpg
│   └── project3.jpg
└── README.md           # This file
```

## 🎯 Customization Guide

### Personal Information
Edit the following sections in `index.html`:

1. **Hero Section** (Lines 48-66):
   - Update name, title, and description
   - Modify social media links

2. **About Section** (Lines 84-110):
   - Update personal description
   - Modify background information

3. **Skills Section** (Lines 113-159):
   - Add/remove skill categories
   - Update technology lists

4. **Experience Section** (Lines 162-194):
   - Update education and work experience
   - Modify dates and descriptions

5. **Projects Section** (Lines 197-255):
   - Replace project information
   - Update project links and technologies

6. **Contact Section** (Lines 258-315):
   - Update contact information
   - Modify email and phone number

### Images
Replace the following placeholder images in the `assets/` folder:
- `profile-photo.jpg` - Your professional headshot
- `project1.jpg` - Screenshot of your first project
- `project2.jpg` - Screenshot of your second project
- `project3.jpg` - Screenshot of your third project

### Colors and Styling
Modify colors in `styles.css`:
- Primary color: `#3498db` (blue)
- Secondary color: `#f39c12` (orange)
- Background gradient: `#667eea` to `#764ba2`
- Text color: `#2c3e50` (dark blue)

### Social Media Links
Update social media URLs in:
- Hero section social links
- Contact section social links
- Footer social links

## 📱 Mobile Responsiveness

The portfolio is fully responsive and includes:
- Mobile navigation menu
- Responsive grid layouts
- Touch-friendly buttons
- Optimized typography for mobile
- Responsive images and media

## 🔧 Technical Features

### JavaScript Functionality
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Navigation links scroll smoothly to sections
- **Image Upload**: Profile picture upload with local storage
- **CV Management**: Upload and download CV functionality
- **Form Handling**: Contact form with validation
- **Animations**: Scroll-triggered animations and effects

### CSS Features
- **Flexbox & Grid**: Modern layout techniques
- **Custom Properties**: CSS variables for easy theming
- **Animations**: Keyframe animations and transitions
- **Media Queries**: Responsive breakpoints
- **Modern Effects**: Backdrop filters, gradients, shadows

### Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Customization Examples

### Changing the Color Scheme
```css
/* In styles.css, update these variables */
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    --accent-color: #your-color;
}
```

### Adding New Projects
```html
<!-- Add this structure in the projects section -->
<div class="project-card">
    <div class="project-image">
        <img src="assets/your-project.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="#" class="btn btn-small">Live Demo</a>
            <a href="#" class="btn btn-outline btn-small">GitHub</a>
        </div>
    </div>
</div>
```

### Adding New Skills
```html
<!-- Add skills in the appropriate category -->
<div class="skill-items">
    <span class="skill-item">New Skill</span>
    <!-- Add more skills as needed -->
</div>
```

## 📧 Contact Form Setup

The contact form currently simulates submission. To make it functional:

1. **Using Formspree** (Recommended):
   ```html
   <form action="https://formspree.io/f/your-form-id" method="POST">
   ```

2. **Using Netlify Forms**:
   ```html
   <form netlify>
   ```

3. **Custom Backend**: Implement your own form handler

## 🚀 Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Go to Settings > Pages
3. Select source branch
4. Your portfolio will be available at `username.github.io/repository-name`

### Netlify
1. Connect your GitHub repository
2. Deploy automatically on push
3. Custom domain available

### Vercel
1. Import GitHub repository
2. Automatic deployments
3. Custom domain support

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements, consider sharing them back with the community!

## 📞 Support

If you need help customizing this portfolio:
- Check the code comments for guidance
- Review this README for common customizations
- Create an issue in the repository

---

**Built with ❤️ for Bebi Sonali Sahoo**

*A modern portfolio showcasing expertise in Data Science and Python Full-Stack Development*
