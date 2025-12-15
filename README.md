# AI Agency Website

A modern, responsive website for an AI agency built with HTML, CSS, and JavaScript.

## Features

- Fully responsive design (mobile, tablet, desktop)
- Smooth scroll navigation
- Animated sections on scroll
- Mobile hamburger menu
- Modern gradient design
- Contact form
- Service showcase
- Portfolio section

## Folder Structure

```
ai-agency-website/
├── index.html              # Main HTML file
├── css/
│   ├── style.css          # Main styles
│   └── responsive.css     # Responsive/mobile styles
├── js/
│   └── main.js            # JavaScript functionality
├── images/                # Place your images here
├── assets/                # Place other assets (fonts, icons)
└── README.md              # This file
```

## Getting Started

### 1. Open the Website

Simply open `index.html` in your web browser. No build tools or server required!

### 2. Customize Content

Edit `index.html` to update:
- Company name and tagline
- Services offered
- About section text
- Portfolio items
- Contact information

### 3. Add Your Images

- Replace the placeholder boxes with your actual images
- Place images in the `images/` folder
- Update the HTML image references

### 4. Customize Colors

Open `css/style.css` and modify the CSS variables at the top:

```css
:root {
    --primary-color: #6366f1;      /* Main brand color */
    --secondary-color: #8b5cf6;    /* Secondary brand color */
    --dark-color: #1f2937;         /* Dark text */
    --light-color: #f9fafb;        /* Background */
}
```

## Customization Guide

### Change the Gradient Colors

In `css/style.css`, find the `--gradient` variable and modify it:

```css
--gradient: linear-gradient(135deg, #YOUR_COLOR_1 0%, #YOUR_COLOR_2 100%);
```

### Add More Services

Copy a service card in `index.html`:

```html
<div class="service-card">
    <div class="service-icon">🎯</div>
    <h3>Your Service Name</h3>
    <p>Service description here</p>
</div>
```

### Add Portfolio Projects

Copy a portfolio item in `index.html`:

```html
<div class="portfolio-item">
    <div class="portfolio-image">
        <img src="images/your-image.jpg" alt="Project name">
    </div>
    <h3>Project Name</h3>
    <p>Project description</p>
</div>
```

### Set Up Contact Form Backend

The contact form currently shows an alert. To make it functional:

1. Use a service like Formspree, EmailJS, or Web3Forms
2. Or set up your own backend server
3. Update the form submission handler in `js/main.js`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Next Steps

### Add More Features

- Blog section
- Team member profiles
- Client testimonials
- Pricing tables
- FAQ section

### Improve Performance

- Optimize images (use WebP format)
- Add lazy loading for images
- Minify CSS and JavaScript

### Deploy Your Website

Choose a hosting option:

1. **GitHub Pages** (Free)
   - Push to GitHub
   - Enable GitHub Pages in repository settings

2. **Netlify** (Free)
   - Drag and drop your folder
   - Or connect to GitHub

3. **Vercel** (Free)
   - Import from GitHub
   - Auto-deploy on push

4. **Traditional Hosting**
   - Upload files via FTP
   - Works with any web host

## Tips for Success

1. Replace all placeholder text with your actual content
2. Add real images to make it professional
3. Update contact information
4. Test on mobile devices
5. Get feedback from others
6. Keep it simple and focused

## Need Help?

If you want to add advanced features:
- Analytics (Google Analytics, Plausible)
- SEO optimization
- Blog with CMS
- Database integration
- User authentication

Consider using a framework like Next.js, React, or hiring a developer.

## License

Free to use for your AI agency. Customize as needed!
