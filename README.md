# BrightSmile Dental Website

A modern, accessible, and fully responsive dental clinic website built with HTML, CSS, and JavaScript.

## Features

### ✨ Modern Design
- Clean and professional dental clinic branding
- Teal/turquoise primary color (#0e7490)
- Professional typography with Playfair Display and Inter fonts
- Smooth animations and transitions

### ♿ Accessibility
- **WCAG 2.1 Compliant**: Full compliance with Web Content Accessibility Guidelines
- **Semantic HTML**: Proper use of semantic tags (nav, section, article, footer)
- **ARIA Labels**: Screen reader support with appropriate ARIA attributes
- **Keyboard Navigation**: Full keyboard accessibility throughout
- **Color Contrast**: High contrast text for readability
- **Focus Indicators**: Clear visual focus states for keyboard users
- **Skip Links**: Quick navigation options
- **Form Accessibility**: Proper labels and error handling

### 📱 Responsive Design
- Mobile-first approach
- Works seamlessly from 320px to 4K+ displays
- Flexible grid layouts using CSS Grid and Flexbox
- Mobile navigation menu with hamburger toggle
- Responsive images with proper scaling
- Touch-friendly buttons and interactive elements

### 🎯 Features
- **Hero Section**: Compelling introduction with call-to-action buttons
- **Treatments Gallery**: 6 dental treatment cards with images and descriptions
- **Transparent Pricing**: Three pricing tiers with clear feature lists
- **Contact Form**: Fully functional contact form with validation
- **Contact Information**: Multiple ways to reach the clinic
- **Footer**: Comprehensive footer with links and information
- **Scroll-to-Top**: Easy navigation for long pages
- **Smooth Scrolling**: Smooth anchor link navigation

## Structure

```
brightsmile-dental/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Sections

### 1. Navigation Bar
- Sticky navigation with logo
- Mobile-responsive hamburger menu
- Smooth navigation to all sections
- Book Now button

### 2. Hero Section
- Compelling headline with highlight color
- Description of services
- Call-to-action buttons (Book Appointment, Our Treatments)
- Hero image

### 3. Treatments Section
- 6 treatment cards in responsive grid
- Each card includes:
  - Professional image from Unsplash
  - Service title
  - Service description
  - Hover effects

### 4. Pricing Section
- 3 pricing tiers:
  1. **Essential Care** (£65) - Basic dental health
  2. **Cosmetic & Restorative** (£295) - Most popular plan
  3. **Advanced Treatments** (£1,500) - Specialist procedures
- Transparent pricing note
- Finance information

### 5. Contact Section
- Contact form with fields:
  - Full Name
  - Email
  - Phone
  - Service Selection
  - Message
- Contact information:
  - Physical address
  - Phone number
  - Email
  - Opening hours

### 6. Footer
- Multiple link sections
- Copyright information
- Scroll-to-top button

## Design System

### Colors
```css
--primary-color: #0e7490 (Teal)
--text-dark: #1a202c (Charcoal)
--text-light: #666 (Gray)
--bg-white: #ffffff (White)
--bg-light: #f0fdfa (Light Teal)
--border-color: #e2e8f0 (Light Gray)
--success-color: #10b981 (Green)
```

### Typography
- **Headings**: Playfair Display (serif)
- **Body Text**: Inter (sans-serif)
- **Font Sizing**: Responsive using CSS clamp()

### Spacing
Using CSS custom properties for consistent spacing:
- xs: 0.5rem
- sm: 1rem
- md: 1.5rem
- lg: 2rem
- xl: 3rem
- 2xl: 4rem

## JavaScript Features

### Mobile Navigation
- Toggle menu on mobile devices
- Close menu when link is clicked
- Auto-close on window resize

### Smooth Scrolling
- Smooth scroll to sections via anchor links

### Scroll-to-Top Button
- Appears after scrolling 300px
- Smooth scroll to top

### Form Handling
- Form validation
- Success message on submission
- Form reset after submission

### Animation on Scroll
- Intersection Observer API for scroll animations
- Treatment and pricing cards fade in as they enter viewport

### Keyboard Navigation
- Arrow key navigation through treatment cards
- Tab through all interactive elements

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Optimizations

- Lazy loading for images
- Optimized images from Unsplash (w=480&q=80)
- Minimal CSS and JavaScript
- CSS variables for easy theming
- Smooth transitions with hardware acceleration
- No external dependencies

## Accessibility Features

### Semantic HTML
```html
<nav role="navigation" aria-label="Main navigation">
<section id="home" aria-labelledby="hero-title">
<article aria-labelledby="treatment-1-title">
<footer role="contentinfo">
```

### ARIA Labels
- Button labels for screen readers
- Form field labels
- Section descriptions
- Navigation landmarks

### Keyboard Navigation
- All buttons and links are tab-accessible
- Visible focus indicators
- Arrow key navigation for treatment cards

### Color Accessibility
- Text contrast ratio > 4.5:1
- No reliance on color alone for information
- Color-blind friendly palette

## Getting Started

1. Clone this repository
2. Open `index.html` in a web browser
3. No build process required!

## Customization

You can easily customize the website by editing:

### Colors
Modify CSS variables in `styles.css`:
```css
:root {
    --primary-color: #0e7490;
    /* ... other colors ... */
}
```

### Content
Edit text and images directly in `index.html`

### Fonts
Modify the Google Fonts link in the `<head>` section

## License

This project is open source and available under the MIT License.

## Contact

For questions or support, contact BrightSmile Dental:
- Phone: +44 (0)20 7494 5531
- Email: hello@brightsmile.co.uk
- Address: 42 Harley Street, London, England
