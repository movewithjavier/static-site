# Static Site Instructions

## Technology Stack
- HTML5
- CSS3 (with Flexbox/Grid for layouts)
- Vanilla JavaScript
- No build tools required

## File Structure 

/
├── index.html # Main landing page
├── about.html # About page
├── contact.html # Contact page
├── css/
│ ├── styles.css # Main stylesheet
│ ├── normalize.css # CSS reset/normalize
│ └── components/ # Component-specific styles
│ ├── header.css # Header styles
│ ├── footer.css # Footer styles
│ ├── buttons.css # Button styles
│ └── cards.css # Card component styles
├── js/
│ ├── main.js # Main JavaScript file
│ └── components/ # Component-specific scripts
│ ├── navigation.js # Navigation functionality
│ ├── carousel.js # Image carousel
│ └── form-validation.js # Form validation
├── assets/
│ ├── images/ # Image files
│ │ ├── logo.svg # Site logo
│ │ ├── hero.jpg # Hero image
│ │ └── icons/ # Icon files
│ ├── fonts/ # Web fonts
│ └── videos/ # Video files (if any)
├── blog/
│ ├── index.html # Blog listing page
│ └── posts/ # Individual blog posts
│ ├── post-1.html # First blog post
│ └── post-2.html # Second blog post
├── .github/
│ └── workflows/
│ └── deploy.yml # GitHub Actions workflow
├── requirements/ # Project documentation
│ ├── site_instructions.md # This file
│ ├── design_guidelines.md # Design guidelines
│ └── deployment_instructions.md # Deployment instructions
├── .gitignore # Git ignore file
├── CNAME # Custom domain for GitHub Pages
└── README.md # Project README


## Development Workflow

1. **Local Development**:
   - Use a local server (like Live Server VS Code extension)
   - Make changes to HTML, CSS, and JavaScript files
   - Test in multiple browsers

2. **Version Control**:
   - Commit changes regularly with descriptive messages
   - Use feature branches for major changes
   - Merge to main branch when ready to deploy

3. **Testing**:
   - Test on multiple devices and browsers
   - Validate HTML with W3C Validator
   - Check for accessibility with tools like WAVE or Lighthouse

4. **Deployment**:
   - Push changes to GitHub
   - GitHub Actions will automatically deploy to GitHub Pages
   - Verify deployment on live site

## Best Practices

- Use semantic HTML elements
- Keep CSS organized with BEM naming convention
- Minimize JavaScript dependencies
- Optimize all images and assets
- Ensure responsive design works on all screen sizes
- Follow accessibility guidelines (WCAG 2.1 AA)