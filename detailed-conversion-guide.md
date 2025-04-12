# Detailed Canvas to GitHub Pages Conversion Guide

This comprehensive guide will walk you through the process of converting your Canvas course content to a GitHub Pages website.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Repository Structure](#repository-structure)
3. [Converting Canvas Content](#converting-canvas-content)
   - [Extracting Content from Canvas](#extracting-content-from-canvas)
   - [Adapting Content for GitHub Pages](#adapting-content-for-github-pages)
   - [Handling Images and Media](#handling-images-and-media)
4. [Module Conversion Process](#module-conversion-process)
5. [Using Templates](#using-templates)
6. [Customizing the Site](#customizing-the-site)
7. [Testing and Deployment](#testing-and-deployment)
8. [Additional Resources](#additional-resources)

## Project Overview

This project converts your Canvas "AI in Law" course into a static website hosted on GitHub Pages. The benefits include:

- **Public Access**: Make your course materials available to a wider audience
- **Persistent Access**: Materials remain available even after the Canvas course ends
- **Easy Updates**: Simple process for updating content
- **No Cost**: GitHub Pages hosting is free
- **Version Control**: Track changes to your content over time

## Repository Structure

```
github-pages-course/
├── index.html               # Main landing page
├── css/
│   └── styles.css           # Custom styling
├── modules/                 # Folder for all modules
│   ├── module1/             # Each module gets its own folder
│   │   ├── welcome.html     # Module welcome page
│   │   ├── assignments.html # Module assignments
│   │   └── activities.html  # Learning activities
│   ├── module2/
│   │   └── ...
│   └── ...
├── images/                  # Folder for images
├── resources/               # Folder for downloadable resources
│   └── index.html           # Resources landing page
├── module-template.html     # Template for new modules
└── README.md                # Repository documentation
```

## Converting Canvas Content

### Extracting Content from Canvas

1. **Access Your Canvas Page**:
   - Navigate to the specific module/page in Canvas
   - Right-click and select "View Page Source" (or press Ctrl+U)

2. **Find the Content**:
   - Search for sections containing your actual content (usually within a div with class "content-wrapper" or similar)
   - For module listings, you'll want the section with class "context_module"

3. **Copy the HTML Content**:
   - Copy just the relevant HTML content (not the entire page source)
   - Be careful to get complete tags - look for matching opening and closing tags

### Adapting Content for GitHub Pages

1. **Use the Templates**:
   - Start with one of the provided templates (module-template.html, etc.)
   - Replace placeholder content with your Canvas content

2. **HTML Cleanup**:
   - Remove Canvas-specific attributes and classes
   - Remove any interactive Canvas elements (like quiz previews)
   - Replace Canvas-specific elements with standard HTML

3. **Navigation Updates**:
   - Update navigation links to point to the correct files
   - Ensure "Back to Module" and other navigation works properly

### Handling Images and Media

1. **Extracting Images**:
   - Right-click on images in Canvas and save them
   - Alternatively, find image URLs in the HTML source and download them

2. **Organizing Media**:
   - Place images in the "images" directory
   - Place downloadable files in the "resources" directory

3. **Updating References**:
   - Update all image src attributes to use relative paths (e.g., "../../images/banner.jpg")
   - Update links to resources to use relative paths

4. **YouTube Video Embedding**:
   - For videos, identify the YouTube video ID and use the embedded player format:
   ```html
   <iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" 
   title="Title" frameborder="0" allow="accelerometer; autoplay; clipboard-write; 
   encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
   ```

## Module Conversion Process

Follow this step-by-step process for each module:

1. **Create Module Directory**:
   ```
   modules/moduleX/
   ```

2. **Create Base Files**:
   - welcome.html
   - activities.html
   - assignments.html

3. **Create Activity-Specific Files** (as needed):
   - learning-activities/
   - quizzes/
   - discussions/

4. **Update Index Page**:
   - Add a link to the new module on index.html

5. **Update Resources Page**:
   - Add any downloadable resources for the module

## Using Templates

We've created several templates to make the conversion process easier:

1. **module-template.html**: Use this as a starting point for any new module page
2. **Module 9 files**: Use these as examples for different types of content

For each new page:

1. Copy the appropriate template
2. Replace placeholder content with your actual content
3. Update navigation links
4. Test the page

## Customizing the Site

You can customize the look and feel of your site by:

1. **Modifying CSS**:
   - Edit css/styles.css to change colors, fonts, spacing, etc.
   - Add page-specific styles in the `<style>` section of individual pages

2. **Adding New Features**:
   - Create new HTML components as needed
   - Add JavaScript for interactive elements

3. **Updating Structure**:
   - Modify navigation
   - Add new sections to pages

## Testing and Deployment

1. **Local Testing**:
   - Open HTML files directly in your browser to preview
   - Check that all links work correctly
   - Verify images and media display properly

2. **GitHub Repository Setup**:
   - Create a new repository on GitHub
   - Upload all files maintaining the directory structure

3. **Enable GitHub Pages**:
   - Go to repository Settings > Pages
   - Select the branch to publish (usually "main")
   - Save and wait for the site to build

4. **Final Testing**:
   - Test the live site thoroughly
   - Check all links and media again

## Additional Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [HTML/CSS Tutorial on W3Schools](https://www.w3schools.com/)
- [Markdown Guide](https://www.markdownguide.org/)
- [Free Image Optimization Tools](https://tinypng.com/)

## Getting Help

If you encounter issues while converting your content:

1. Check the examples in Module 9 and Module 1
2. Use the module-template.html as a reference
3. Consult GitHub Pages documentation
4. Use Claude or another AI assistant for HTML/CSS help

Remember that converting a full course is a significant undertaking. Consider converting one module at a time, starting with the most important content.
