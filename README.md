# AI in Law Course - GitHub Pages Implementation

This repository contains the GitHub Pages implementation of the "AI in Law" course, converted from Canvas LMS format.

## Project Status

### Completed
- Project structure established with proper CSS styling
- Canvas-style layout implemented 
- Module 1 and Module 2 content structures implemented:
  - Welcome pages
  - Learning activity pages (placeholder)
  - Quiz pages (placeholder)
  - Discussion pages (placeholder)
- Basic navigation between pages implemented
- Placeholder for Utah logo created
- Placeholder for module banners created

### Pending
- Add actual content to all pages
- Complete modules 3-10 with full page structure
- Add real images for module banners
- Finalize navigation between all pages
- Add responsive design tweaks for mobile
- Test all pages and fix any issues

## Project Structure

```
github-pages-course/
├── css/
│   ├── styles.css               # Original simple styling
│   ├── simple-styles.css        # Updated simple styling
│   └── canvas-styles.css        # Canvas-style styling that matches Canvas UI
│
├── modules/                     # All course modules
│   ├── module1/
│   │   ├── welcome.html         # Module 1 welcome page
│   │   ├── learning/            # Learning activities
│   │   │   ├── evolution-of-ai.html
│   │   │   └── understanding-ai-development.html
│   │   ├── practice/            # Practice activities
│   │   │   └── history-quiz.html
│   │   └── discussions/         # Discussion pages
│   │       └── historical-patterns.html
│   ├── module2/
│   │   ├── welcome.html         # Module 2 welcome page
│   │   ├── learning/            # Learning activities
│   │   │   ├── prompt-elements.html
│   │   │   ├── zero-shot-prompting.html
│   │   │   └── one-shot-prompting.html
│   │   ├── practice/            # Practice activities
│   │   │   └── basic-prompting-quiz.html
│   │   └── discussions/         # Discussion pages
│   │       └── module2-discussion.html
│   └── [module3-10]/            # Placeholder modules
│
├── images/
│   ├── module-banners/          # Module banner images
│   │   └── placeholder.svg      # Placeholder banner
│   └── utah-logo.svg            # Utah "U" logo placeholder
│
├── index.html                   # Main landing page
├── canvas-index.html            # Canvas-style course home
├── templates/                   # Template files for different content types
│   ├── learning-template.html   # Template for learning pages
│   ├── quiz-template.html       # Template for quiz pages
│   ├── discussion-template.html # Template for discussion pages
│   └── assignment-template.html # Template for assignment pages
└── README.md                    # Project documentation
```

## How to Use

1. Navigate to the `index.html` file to see the main course page
2. Click on "View Canvas-Style Version" to see the Canvas-style interface
3. Navigate through modules using the links and navigation buttons
4. Each module has a welcome page and associated learning activities, quizzes, and discussions

## Implementation Notes

- All pages follow the Canvas LMS styling and layout
- The sidebar and navigation panels are consistent across all pages
- Placeholder content is used where actual content will be added later
- Navigation buttons allow for easy movement between pages
- The file structure follows a logical organization by module and content type

## Next Steps

1. Add actual content to Module 1 and 2 pages
2. Create full page structure for Modules 3-10
3. Add real images and replace placeholders
4. Test navigation and fix any issues
5. Deploy to GitHub Pages

## Credits

University of Utah AI in Law Course
