# HK Software Hub - Corporate Website

A modern, professional corporate website for HK Software Hub showcasing IT professionals, portfolios, and custom software solutions.

## Features

### 🏠 Home Page
- Modern hero section with animated code elements
- Responsive navigation with mobile hamburger menu
- Call-to-action buttons for portfolio and contact

### 📋 About Section
- Company mission and values
- Feature highlights with icons
- Animated statistics counters
- Professional layout with gradient backgrounds

### 👥 Team Profiles
- Professional team member cards
- Skills showcase with tags
- Social media links (LinkedIn, GitHub)
- Hover animations and effects

### 💼 Portfolio
- Filterable project showcase
- Categories: Web Apps, Mobile Apps, Enterprise Solutions
- Project overlays with technology stacks
- Responsive grid layout

### 📞 Contact Form
- Comprehensive contact form with validation
- Service type and budget selection
- Project timeline options
- Real-time form validation
- Success/error notifications

### 🎨 Design Features
- Modern gradient backgrounds
- Smooth scrolling navigation
- Intersection Observer animations
- Mobile-responsive design
- Professional color scheme (Blues and purples)
- Font Awesome icons
- Google Fonts (Inter)

## File Structure

```
hksoftwarehub/
├── index.html          # Main HTML file
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript functionality and interactions
└── README.md           # Project documentation
```

## Technology Stack

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with Flexbox/Grid, animations, gradients
- **JavaScript (ES6+)** - Interactive functionality and form handling
- **Font Awesome** - Professional icons
- **Google Fonts** - Typography (Inter font family)

## Features in Detail

### Navigation
- Fixed header with backdrop blur effect
- Smooth scroll to sections
- Mobile-responsive hamburger menu
- Active link highlighting

### Hero Section
- Animated code blocks simulation
- Gradient background with geometric patterns
- Responsive call-to-action buttons

### Team Section
- 4 professional team members
- Skills displayed as tags
- Social media integration ready
- Hover effects and animations

### Portfolio Filtering
- JavaScript-powered filtering system
- Categories: All, Web Apps, Mobile Apps, Enterprise
- Smooth fade animations
- Technology stack displays

### Contact Form
- Full validation (email, phone, required fields)
- Service type dropdown
- Budget range selection
- Project timeline options
- Success/error notification system

### Responsive Design
- Mobile-first approach
- Breakpoints at 768px and 480px
- Collapsible navigation
- Flexible grid layouts
- Touch-friendly buttons

## Customization

### Adding Team Members
Edit the team section in `index.html`:
```html
<div class="team-member">
    <!-- Update member information -->
    <h3>Name</h3>
    <p class="member-role">Role</p>
    <p class="member-bio">Bio</p>
    <!-- Add skills -->
    <div class="member-skills">
        <span class="skill">Skill</span>
    </div>
</div>
```

### Adding Portfolio Items
Add new portfolio items in the portfolio section:
```html
<div class="portfolio-item" data-category="web">
    <!-- Portfolio content -->
</div>
```

### Updating Contact Information
Modify the contact details in the contact section and footer.

### Color Scheme
Primary colors are defined in CSS variables. Key colors:
- Primary Blue: `#2563eb`
- Dark Text: `#1e293b`
- Light Text: `#64748b`
- Background: `#f8fafc`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- Optimized CSS with efficient selectors
- Minimal JavaScript bundle
- Lazy loading animations
- Efficient DOM manipulation
- Mobile-optimized touch interactions

## Setup Instructions

1. Clone or download the files
2. Open `index.html` in a web browser
3. For development, use a local server for best performance
4. Customize content, images, and contact information as needed

## Form Integration

The contact form currently shows success messages. To integrate with a backend:

1. Update the form action in `index.html`
2. Modify the form submission handler in `script.js`
3. Replace the setTimeout simulation with actual API calls

## Future Enhancements

- Blog/news section
- Client testimonials
- Service detail pages
- Online chat integration
- Analytics tracking
- SEO optimization
- Content Management System integration

## License

This project is designed for HK Software Hub. Customize as needed for your organization.

---

Built with modern web technologies for a professional corporate presence.
