# AI in Law Course - GitHub Pages Implementation

This repository contains a Canvas-style implementation of the "AI in Law Course" for GitHub Pages.

## Project Overview

The course consists of 10 modules covering various aspects of AI in legal education and practice:

1. **Module 1**: The Evolution of AI - Foundations and Fundamentals
2. **Module 2**: The Fundamentals of Prompt Engineering
3. **Module 3**: Legal Chatbots - Understanding, Implementation, and Ethics
4. **Module 4**: Media Creation for Working Professionals
5. **Module 5**: AI Tools in Legal Settings
6. **Module 6**: Advanced Prompting Techniques
7. **Module 7**: AI Ethics & Advanced Prompting Techniques
8. **Module 8**: AI Tools for Working Professionals
9. **Module 9**: AI Learning Tools for Enhancement
10. **Module 10**: How will AGI Impact YOUR Career?

## Repository Structure

```
github-pages-course/
├── index.html               # Simple main landing page
├── canvas-index.html        # Canvas-style main landing page
├── css/
│   ├── styles.css           # Original simple CSS styling
│   ├── simple-styles.css    # Updated simple CSS styling
│   └── canvas-styles.css    # Canvas-style CSS styling
├── modules/                 # Folder for all modules
│   ├── module1/            
│   │   ├── welcome.html     # Simple module welcome page
│   │   ├── canvas-welcome.html # Canvas-style module welcome page
│   │   └── ...
│   ├── module2/
│   │   └── ...
│   └── ...
├── images/
│   ├── utah-logo.png        # University of Utah logo for Canvas style
│   └── module-banners/      # Folder for module banner images
└── README.md                # This file
```

## Using This Repository

### Canvas Style vs. Simple Style

This repository provides two different implementations:

1. **Canvas Style**: Closely mimics the Canvas LMS interface, with red sidebar, left navigation, and Utah branding
   - Main index: `canvas-index.html`
   - Module pages: `modules/moduleX/canvas-welcome.html`
   - CSS: `css/canvas-styles.css`

2. **Simple Style**: A cleaner, simpler layout without the Canvas UI elements
   - Main index: `simple-index.html` or `index.html`
   - Module pages: `modules/moduleX/simple-welcome.html` or `welcome.html`
   - CSS: `css/simple-styles.css` or `css/styles.css`

Choose the style that best fits your needs.

### Required Images

Before deploying to GitHub Pages, you'll need to add:

1. University of Utah logo: `images/utah-logo.png`
2. Module banner images: `images/module-banners/moduleX-banner.jpg`

### Setting Up GitHub Pages

1. Create a new repository on GitHub
2. Upload all files and folders from this project
3. Go to repository Settings > Pages
4. Under "Source", select the branch you want to publish (usually "main")
5. Click "Save"
6. Your site will be published at `https://yourusername.github.io/repository-name/`

## Customization

### Changing Colors and Styles

- Edit `css/canvas-styles.css` to modify the Canvas-style implementation
- Edit `css/simple-styles.css` to modify the simple implementation

### Adding New Content

1. Module Pages:
   - Use `canvas-module-template.html` or `module-template.html` as a starting point
   - Create new HTML files in the appropriate module directory

2. Images:
   - Add new images to the `images` directory
   - Update image paths in HTML files

## Maintenance

- Regularly update links if you add or rename files
- Check for broken links before publishing updates
- Ensure all images are properly referenced and available

## Technical Notes

- This implementation uses Font Awesome for icons in the Canvas-style version
- All styling is done with CSS, no JavaScript is required
- The site is fully responsive and will work on mobile devices
