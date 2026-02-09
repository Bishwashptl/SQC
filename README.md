# SQC - Science & Technology Club Website

A modern, fully responsive website for the Science & Technology Club (SQC) at NIT Jalandhar, showcasing technology innovations and club activities.

## Features

✨ **Modern Design**
- Gradient backgrounds and smooth animations
- Floating elements and parallax effects
- Smooth transitions on hover
- Professional color scheme

🎨 **Animations & Effects**
- Slide-in animations on page load
- Floating and bouncing elements
- Hover transitions on cards
- Parallax scrolling effects
- Intersection Observer for scroll animations

📱 **Fully Responsive**
- Mobile-first design
- Hamburger menu for mobile devices
- Responsive grid layouts
- Touch-friendly navigation

🎯 **Interactive Features**
- Smooth scrolling navigation
- Image upload capability (click any placeholder image)
- Contact form with validation
- Mobile touch gestures support

## File Structure

```
Chi Chi/
├── index.html      # Main HTML file with all sections
├── styles.css      # Complete styling with animations
├── script.js       # JavaScript for interactivity
└── README.md       # This file
```

## How to Use

### 1. Open the Website
Simply open `index.html` in your web browser. No server or installation needed!

### 2. Add Your Own Photos

**Click on any image placeholder** (the gradient boxes with icons) to upload your own images:
- About section image
- Innovation project images (on the cards)

The website will automatically display your uploaded images.

### 3. Customize Content

Edit `index.html` to update:

#### Navigation Menu
```html
<ul class="nav-links">
    <li><a href="#home">Home</a></li>
    <!-- Add or modify links here -->
</ul>
```

#### Hero Section (Main Title)
```html
<h1 class="hero-title">Science & Technology Club</h1>
<p class="hero-subtitle">Innovating Tomorrow, Today</p>
```

#### About Section
```html
<p>Your club description here</p>
<ul class="about-list">
    <li><i class="fas fa-check-circle"></i> Your achievement here</li>
</ul>
```

#### Innovation Cards
Each innovation card can be customized:
```html
<div class="innovation-card">
    <div class="card-image-placeholder">
        <i class="fas fa-dog"></i>  <!-- Change icon -->
    </div>
    <h3>Your Project Title</h3>
    <p>Your project description</p>
    <div class="card-tags">
        <span>Tag1</span>
        <span>Tag2</span>
    </div>
</div>
```

#### Contact Information
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div>
        <h4>Email</h4>
        <p>your-email@nitj.ac.in</p>
    </div>
</div>
```

#### Team Members
Update team member names and roles:
```html
<div class="team-member">
    <div class="member-image">
        <i class="fas fa-user-circle"></i>
    </div>
    <h3>Member Name</h3>
    <p>Their role in the club</p>
</div>
```

#### Social Links
```html
<div class="social-links">
    <a href="https://facebook.com/yourpage"><i class="fab fa-facebook"></i></a>
    <a href="https://twitter.com/yourpage"><i class="fab fa-twitter"></i></a>
    <a href="https://instagram.com/yourpage"><i class="fab fa-instagram"></i></a>
    <a href="https://linkedin.com/company/yourpage"><i class="fab fa-linkedin"></i></a>
</div>
```

## Colors & Customization

### Change Color Scheme
Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #6366f1;      /* Main color - Indigo */
    --secondary-color: #ec4899;    /* Accent color - Pink */
    --tertiary-color: #8b5cf6;     /* Third color - Purple */
    --dark-bg: #0f172a;            /* Dark background */
    --light-bg: #f8fafc;           /* Light background */
}
```

### Modify Fonts
The website uses 'Segoe UI'. To change:
```css
body {
    font-family: 'Your Font Name', sans-serif;
}
```

## Icons Available

The website uses Font Awesome 6.0 icons. Some useful icons:

- `fa-robot` - Robot
- `fa-dog` - Dog
- `fa-drone` - Drone
- `fa-microchip` - Microchip
- `fa-brain` - Brain
- `fa-sun` - Sun
- `fa-tools` - Tools
- `fa-users` - Users
- `fa-graduation-cap` - Graduation Cap
- `fa-trophy` - Trophy

[View all Font Awesome icons](https://fontawesome.com/icons)

## Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 769px to 1199px
- **Mobile**: 480px to 768px
- **Small Mobile**: Below 480px

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

1. **Optimize Images**: Compress images before uploading for faster loading
2. **Use Modern Formats**: Consider using WebP format for images
3. **Cache**: Modern browsers will cache images automatically

## Troubleshooting

### Images not uploading?
- Check browser console (F12) for errors
- Ensure browser allows file access
- Try a different browser

### Animation not smooth?
- Close other CPU-intensive applications
- Update your browser
- Check hardware acceleration is enabled

### Mobile menu not working?
- Clear browser cache
- Try different browser
- Check if JavaScript is enabled

## Future Enhancements

Consider adding:
- Blog/news section
- Project details with more images
- Newsletter signup
- Gallery section with more photos
- Event calendar
- Member profiles with images
- Video background
- Live project counter

## Credits

- **Framework**: HTML5, CSS3, JavaScript
- **Icons**: Font Awesome 6.0
- **Fonts**: Segoe UI (System Font)
- **Design**: Modern Web Design Principles

## License

Feel free to use and modify this website for your club's needs.

---

**Happy coding! 🚀** 

For more customization help, contact your web developer or refer to the inline comments in the HTML and CSS files.
