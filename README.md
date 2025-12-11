# Panda.DT - Project Website

A modern, responsive website showcasing the Panda.DT project. Built with clean HTML, CSS, and JavaScript.

## Features

- 🎨 Modern and responsive design
- 📱 Mobile-friendly with hamburger menu
- ✨ Smooth scroll animations
- 🎯 Interactive elements and hover effects
- 📊 Animated statistics counter
- 🎭 Section-based navigation
- 💌 Contact form
- 🌐 Cross-browser compatible

## Sections

1. **Home** - Hero section with project introduction
2. **About** - Project overview and key objectives
3. **Problem** - Challenge statement and analysis
4. **Solution** - Detailed solution approach
5. **Features** - Key capabilities and features
6. **Technology** - Technology stack used
7. **Team** - Team members showcase
8. **Contact** - Contact information and form

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- (Optional) A local web server for testing

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000`

## File Structure

```
panda.DT/
│
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Customization

### Updating Content

1. **Team Members**: Edit the team section in `index.html` (lines with class `team-card`)
2. **Contact Info**: Update email, phone, location in the contact section
3. **Statistics**: Modify the `data-target` attribute in stat cards
4. **Colors**: Change CSS variables in `styles.css` under `:root`

### Color Scheme

The website uses CSS variables for easy customization:

```css
--primary-color: #2563eb;
--secondary-color: #10b981;
--dark-color: #1e293b;
--light-color: #f8fafc;
```

### Adding Images

To add team member photos or other images:

1. Create an `images` folder
2. Add your images
3. Replace the icon placeholders in HTML:

```html
<div class="team-image">
    <img src="images/member1.jpg" alt="Team Member">
</div>
```

## Features in Detail

### Responsive Navigation
- Desktop: Horizontal menu
- Mobile: Hamburger menu with slide-in animation

### Smooth Scrolling
- Click navigation links for smooth scroll to sections
- Automatic navbar height adjustment

### Animations
- Fade-in on scroll for cards
- Counter animation for statistics
- Parallax effect on hero section
- Button ripple effects

### Contact Form
- Form validation
- Success message (customize for backend integration)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings > Pages
3. Select branch and save
4. Your site will be available at `https://yourusername.github.io/panda.DT/`

### Netlify

1. Drag and drop your folder to Netlify
2. Or connect your Git repository
3. Site will be deployed automatically

### Vercel

```bash
npm i -g vercel
vercel
```

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- JavaScript (ES6+)
- Font Awesome Icons
- Intersection Observer API

## Performance Optimization

- Minimal dependencies
- Optimized CSS
- Lazy loading support
- Efficient animations
- Mobile-first approach

## Future Enhancements

- [ ] Add blog section
- [ ] Integrate backend for contact form
- [ ] Add project gallery
- [ ] Multi-language support
- [ ] Dark mode toggle
- [ ] Add testimonials section

## Contributing

Feel free to fork this project and customize it for your needs!

## License

This project is open source and available for personal and commercial use.

## Contact

For questions or feedback, please use the contact form on the website or reach out directly.

---

**Made with ❤️ by Team Panda.DT**

## Quick Start Checklist

- [ ] Update team member names and roles
- [ ] Add your contact information
- [ ] Customize project description and objectives
- [ ] Update technology stack
- [ ] Add your social media links
- [ ] Test on mobile devices
- [ ] Deploy to hosting platform

Enjoy your new website! 🎉
