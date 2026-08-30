# CV Portfolio

A modern, responsive, and professional CV portfolio website built with HTML, CSS, and JavaScript.

## Features

✨ **Modern Design**
- Clean and professional layout
- Smooth animations and transitions
- Gradient backgrounds and hover effects
- Fully responsive design (mobile, tablet, desktop)

📱 **Responsive Layout**
- Mobile-first approach
- Hamburger menu for mobile devices
- Optimized for all screen sizes

🎯 **Sections**
- **Hero Section**: Eye-catching introduction with call-to-action buttons
- **About**: Personal introduction and key statistics
- **Projects**: Showcase your best work with tags and descriptions
- **Skills**: Organized skill categories
- **Experience**: Timeline-based work experience
- **Contact**: Contact information and message form
- **Navigation**: Fixed navbar with smooth scrolling

⚡ **Interactive Features**
- Smooth scrolling navigation
- Active link highlighting based on scroll position
- Form validation
- Mobile menu toggle
- Keyboard navigation support
- Intersection Observer animations

## Files

- `index.html` - Main HTML structure
- `style.css` - Styling and responsive design
- `script.js` - JavaScript functionality and interactivity
- `README.md` - This file

## How to Use

1. **Open the portfolio** - Simply open `index.html` in your web browser
2. **Customize your information** - Edit the HTML file to add your personal details:
   - Change your name in the hero section
   - Update the about section with your bio
   - Add your projects
   - Update your skills
   - Add your work experience
   - Update contact information
3. **Add your profile picture** - Replace the placeholder image URL in the hero section
4. **Update social links** - Add your GitHub, LinkedIn, and Twitter URLs

## Customization Guide

### Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --primary-color: #667eea;      /* Change primary color */
    --secondary-color: #764ba2;    /* Change secondary color */
    --text-dark: #333;
    --text-light: #666;
    --bg-light: #f7f9fc;
    --bg-white: #ffffff;
}
```

### Sections

#### Hero Section
```html
<h1 class="hero-title">Hi, I'm Your Name</h1>
<p class="hero-subtitle">Your Title | Your Specialty</p>
```

#### Projects
Add new project cards by duplicating the `.project-card` div:
```html
<div class="project-card">
    <div class="project-image" style="background: linear-gradient(...)"></div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Description</p>
        <div class="project-tags">
            <span class="tag">Technology</span>
        </div>
        <a href="#" class="project-link">View Project →</a>
    </div>
</div>
```

#### Skills
Add new skill categories:
```html
<div class="skill-category">
    <h3>Category Name</h3>
    <ul>
        <li>Skill 1</li>
        <li>Skill 2</li>
        <li>Skill 3</li>
    </ul>
</div>
```

#### Experience
Add new timeline items:
```html
<div class="experience-item">
    <div class="experience-marker"></div>
    <div class="experience-content">
        <h3>Job Title</h3>
        <p class="company">Company Name | Date Range</p>
        <p>Description</p>
    </div>
</div>
```

### Fonts
To change fonts, modify the font-family in the `body` selector in `style.css`:
```css
body {
    font-family: 'Your Font Name', sans-serif;
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile, etc.)

## Features in Detail

### Navigation
- Fixed navbar that stays at the top while scrolling
- Active link highlighting based on current section
- Mobile hamburger menu
- Smooth scroll to sections

### Form Validation
- Email format validation
- Required field checking
- User-friendly error messages

### Responsive Design
- Breakpoints at 768px (tablets) and 480px (mobile)
- Flexible grid layouts
- Optimized touch targets for mobile

### Animations
- Fade-in animations on scroll
- Hover effects on cards
- Smooth transitions throughout
- CSS animations for better performance

## Tips for Content

1. **Profile Picture**: Use a high-quality, professional headshot (300x300px recommended)
2. **Project Descriptions**: Keep them concise and highlight the key technologies used
3. **Skills**: Group related skills together for better organization
4. **Experience**: Include dates, company names, and key achievements
5. **Contact Info**: Make it easy for visitors to reach you

## Performance Optimizations

- Minimal external dependencies
- CSS Grid and Flexbox for efficient layouts
- Optimized animations using CSS and Intersection Observer
- No heavy JavaScript libraries
- Lightweight and fast-loading

## Future Enhancements

Consider adding:
- Dark mode toggle
- Blog section
- More interactive filters for projects
- Downloadable resume/CV
- Testimonials section
- Email backend integration
- Analytics tracking

## License

Feel free to use this template for your personal portfolio.

## Support

For customization help or issues, refer to:
- HTML: [MDN Web Docs](https://developer.mozilla.org/)
- CSS: [CSS Tricks](https://css-tricks.com/)
- JavaScript: [JavaScript.info](https://javascript.info/)

---

**Happy coding!** 🚀
