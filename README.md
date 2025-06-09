# TinyCRM Marketing Website

A modern, responsive marketing website for TinyCRM - "The Simplest CRM You'll Ever Use"

## Features

### 🎨 Design & UX
- Clean, modern SaaS-style design
- Mobile-first responsive layout
- Smooth animations and hover effects
- Professional color palette (blue and gray tones)
- Google Fonts (Inter) for typography
- Font Awesome icons

### 📱 Pages Included
- **Home** (`index.html`) - Hero section, features preview, social proof, CTA
- **Features** (`features.html`) - Detailed feature listings with icons
- **Pricing** (`pricing.html`) - 3-tier pricing comparison with FAQ section
- **About** (`about.html`) - Company mission, team bios, statistics
- **Contact** (`contact.html`) - Contact form with company information
- **Login** (`login.html`) - Clean authentication page
- **Signup** (`signup.html`) - Registration form with password strength indicator

### 🚀 Technical Features
- Pure HTML5 and CSS3 (no frameworks)
- Vanilla JavaScript for interactions
- CSS Grid and Flexbox for layouts
- CSS Custom Properties (variables)
- Intersection Observer API for scroll animations
- Form validation with real-time feedback
- Mobile hamburger navigation
- FAQ accordion functionality
- Password strength indicator
- Smooth scrolling and parallax effects

### 📱 Responsive Design
- Mobile-first approach
- Breakpoints at 768px and 480px
- Collapsible navigation for mobile
- Optimized typography scaling
- Touch-friendly interactive elements

### 🎯 Interactive Elements
- Hover effects on cards and buttons
- Animated feature icons
- Dashboard mockup with interactive sidebar
- Form validation with visual feedback
- Loading states for form submissions
- Scroll-triggered animations

## File Structure

```
tinycrm/
├── index.html          # Homepage
├── features.html       # Features page
├── pricing.html        # Pricing page
├── about.html          # About page
├── contact.html        # Contact page
├── login.html          # Login page
├── signup.html         # Signup page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
├── favicon.ico         # Favicon placeholder
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- IE11+ (with graceful degradation)

## Performance Optimizations

- Optimized CSS with minimal redundancy
- Efficient JavaScript with event delegation
- Debounced scroll events
- Lazy loading ready for images
- Minimal external dependencies

## Getting Started

1. Clone or download the files
2. Open `index.html` in your browser
3. All pages are linked and functional
4. Forms are HTML-only (no backend required)

## Customization

### Colors
The color scheme can be easily modified by updating CSS custom properties in `styles.css`:

```css
:root {
    --primary-color: #3b82f6;
    --primary-dark: #2563eb;
    --text-primary: #1e293b;
    --text-secondary: #64748b;
    /* ... other variables */
}
```

### Content
- Update company information in HTML files
- Replace placeholder team bios and contact details
- Modify pricing tiers and features as needed
- Add real social media links

### Branding
- Replace Font Awesome chart-line icon with your logo
- Update favicon.ico with your brand icon
- Modify the tagline and descriptions

## Notes

- All forms use `action="#"` - replace with actual endpoints
- Social media links are placeholders
- Team member avatars use initials - replace with actual photos
- Company logos in social proof section are placeholders
- All external links lead to placeholder pages

## License

This is a demo/template website. Feel free to use and modify as needed. 