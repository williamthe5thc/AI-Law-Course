# Canvas to GitHub Pages Conversion Guide

This guide will help you convert your Canvas modules to GitHub Pages format.

## Step 1: Extract Content from Canvas

For each module:

1. Go to the module page in Canvas
2. View the page source (right-click > View Page Source)
3. Find the content within the HTML (usually in a `<div id="wiki_page_show">` section)
4. Copy the relevant HTML content (headings, paragraphs, lists, etc.)

## Step 2: Create Module Folders

For each module:

1. Create a folder `modules/moduleX/` (where X is the module number)
2. Create three files in each folder:
   - `welcome.html`
   - `assignments.html`
   - `activities.html`

## Step 3: Adapt the HTML Template

Use the Module 9 files as templates:

1. Copy the existing HTML structure from Module 9
2. Replace the content with your extracted Canvas content
3. Update titles, headings, and navigation links
4. Make sure to keep the overall structure consistent

## Step 4: Add Images

1. Extract images from Canvas:
   - Right-click on images in Canvas > Save Image As
   - Or find image URLs in the HTML source
2. Save images to the `images/` folder
3. Update image paths in your HTML files

## Step 5: Update Navigation

1. Add links to your new modules in `index.html`
2. Update navigation in each module page to link correctly

## Step 6: Test Locally

1. Open your HTML files in a browser
2. Check all links and images
3. Make adjustments as needed

## Step 7: Deploy to GitHub Pages

Follow the instructions in README.md to deploy to GitHub Pages.

## Prompting Claude for Help

If you need assistance converting specific modules, you can use Claude with a prompt like this:

```
I need help converting my Canvas module to GitHub Pages format.
Here's the HTML content from Canvas:

[Paste your Canvas HTML here]

Please create a well-structured HTML file for GitHub Pages following the template in my repository.
```
