# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design with smooth animations and interactive elements.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and form validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Loading Animation**: Beautiful loading screen
- **Scroll to Top**: Convenient scroll-to-top button
- **Notification System**: User-friendly notifications for form submissions

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization Guide

### 1. Personal Information

Replace the placeholder content in `index.html` with your information:

#### Hero Section
```html
<!-- Replace "Your Name" with your actual name -->
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>

<!-- Update your title/role -->
<h2 class="hero-subtitle">Full Stack Developer</h2>

<!-- Update your description -->
<p class="hero-description">
    I create beautiful, functional, and user-centered digital experiences. 
    Passionate about clean code and innovative solutions.
</p>
```

#### About Section
```html
<!-- Update your about text -->
<p>
    I'm a passionate developer with a love for creating innovative solutions. 
    With expertise in modern web technologies, I focus on building scalable 
    applications that solve real-world problems.
</p>

<!-- Update your stats -->
<div class="stat">
    <h3>3+</h3>
    <p>Years Experience</p>
</div>
```

#### Contact Information
```html
<!-- Update contact details -->
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
<div class="contact-item">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your City, Country</span>
</div>
```

### 2. Skills Section

Update the skills in the HTML:

```html
<div class="skill-category">
    <h3>Frontend</h3>
    <div class="skill-items">
        <div class="skill-item">
            <i class="fab fa-html5"></i>
            <span>HTML5</span>
        </div>
        <!-- Add more skills as needed -->
    </div>
</div>
```

### 3. Projects Section

Replace the sample projects with your own:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">
            <i class="fas fa-laptop-code"></i>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Description of your project</p>
        <div class="project-tech">
            <span>React</span>
            <span>Node.js</span>
            <span>MongoDB</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="your-live-link" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live
            </a>
        </div>
    </div>
</div>
```

### 4. Social Links

Update the social media links in the contact section:

```html
<div class="social-links">
    <a href="your-github-url" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="your-linkedin-url" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="your-twitter-url" class="social-link">
        <i class="fab fa-twitter"></i>
    </a>
    <a href="your-instagram-url" class="social-link">
        <i class="fab fa-instagram"></i>
    </a>
</div>
```

### 5. Colors and Styling

You can customize the color scheme by modifying the CSS variables in `styles.css`:

```css
/* Primary colors */
--primary-color: #2563eb;
--secondary-color: #7c3aed;
--accent-color: #fbbf24;

/* Background colors */
--bg-light: #f8fafc;
--bg-dark: #1f2937;

/* Text colors */
--text-primary: #1f2937;
--text-secondary: #6b7280;
```

### 6. Adding Your Photo

Replace the placeholder icons with your actual photos:

1. Add your photo to the project folder
2. Replace the placeholder div with an img tag:

```html
<!-- Replace this -->
<div class="profile-placeholder">
    <i class="fas fa-user"></i>
</div>

<!-- With this -->
<img src="your-photo.jpg" alt="Your Name" class="profile-image">
```

Then add CSS for the image:

```css
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid rgba(255, 255, 255, 0.2);
}
```

### 7. Contact Form Setup

The contact form is currently set up to show a success message. To make it functional:

1. **EmailJS**: Use EmailJS service
2. **Formspree**: Use Formspree service
3. **Netlify Forms**: If deploying on Netlify
4. **Custom Backend**: Set up your own backend

Example with EmailJS:

```javascript
// Add EmailJS script to HTML
<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>

// Update form submission in script.js
emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', {
    from_name: name,
    from_email: email,
    subject: subject,
    message: message
});
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Optimized CSS with efficient selectors
- Minimal JavaScript for better performance
- Responsive images and icons
- Smooth animations with hardware acceleration
- Lazy loading for better page load times

## Deployment

### GitHub Pages
1. Push your code to GitHub
2. Go to repository settings
3. Enable GitHub Pages
4. Select source branch

### Netlify
1. Drag and drop your folder to Netlify
2. Or connect your GitHub repository
3. Automatic deployment on push

### Vercel
1. Install Vercel CLI
2. Run `vercel` in your project directory
3. Follow the prompts

## Customization Tips

1. **Keep it simple**: Don't overload with too many animations
2. **Test on mobile**: Always test on different screen sizes
3. **Optimize images**: Compress images for faster loading
4. **Update regularly**: Keep your projects and skills current
5. **Add analytics**: Consider adding Google Analytics
6. **SEO optimization**: Add meta tags and descriptions

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio, feel free to:
- Check the code comments for guidance
- Modify the CSS variables for easy color changes
- Add or remove sections as needed
- Customize the animations and effects

Happy coding! 🚀 