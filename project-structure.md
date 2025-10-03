# Project Structure

This document outlines the file structure and organization of the SpaceX Demo Website HTML project.

```
spacex-html-project/
├── README.md                 # Main project documentation
├── CONTRIBUTING.md           # Contribution guidelines
├── LICENSE                   # MIT License file
├── .gitignore               # Git ignore rules
├── project-structure.md     # This file - project organization
├── index.html               # Main HTML file
├── styles.css               # Custom CSS styles
└── images/                  # Images directory
    └── README.txt           # Images folder documentation
```

## File Descriptions

### Core Files
- **`index.html`** - Main webpage containing all HTML structure, navigation, content sections, and JavaScript functionality
- **`styles.css`** - Custom CSS featuring responsive design, animations, Bootstrap customizations, and mobile optimization

### Documentation Files
- **`README.md`** - Comprehensive project documentation including setup, usage, features, and contribution guidelines
- **`CONTRIBUTING.md`** - Detailed guidelines for contributors including code style, commit formats, and pull request process
- **`LICENSE`** - MIT License providing open-source usage permissions
- **`project-structure.md`** - This file explaining project organization and file purposes

### Configuration Files
- **`.gitignore`** - Specifies files and directories to ignore in Git version control
- **`images/README.txt`** - Documentation for images folder usage and external image source information

## Directory Organization

### `/images/`
- **Purpose:** Directory for local image files (currently uses external URLs)
- **Usage:** Replace external image URLs with uploaded local files
- **Formats:** .jpg, .png, .svg supported
- **Documentation:** Contains README.txt with usage instructions

### External Dependencies
- **Bootstrap 5:** Loaded via CDN from unpkg.js
- **Background Images:** SpaceX Eva Suit image from Azure CDN
- **Profile Image:** SpaceX Mechazilla image from shop.spacex.com
- **No local dependencies:** All frameworks loaded via CDN

## HTML Structure Overview

```
<!DOCTYPE html>
<html>
<head>
    <!-- Meta tags, title, Bootstrap CDN, custom CSS -->
</head>
<body>
    <header>
        <!-- Navigation bar -->
        <!-- Hero section with background image -->
    </header>
    
    <section id="about">
        <!-- About us content with profile image -->
    </section>
    
    <section id="features">
        <!-- Feature cards and mission data table -->
    </section>
    
    <section id="contact">
        <!-- Contact form with background image -->
    </section>
    
    <footer>
        <!-- Footer information -->
    </footer>
    
    <!-- Bootstrap JS and custom JavaScript -->
</body>
</html>
```

## CSS Organization

### Style Sections
1. **Base Styles** - Reset, typography, general layout
2. **Header Styles** - Hero section, navigation, background images
3. **About Section** - Content boxes, bio sections, profile images
4. **Features Section** - Feature cards, table styling, grid layouts
5. **Contact Section** - Form styling, background overlays, validation
6. **Footer Styles** - Footer layout and typography
7. **Responsive Design** - Mobile breakpoints and adaptive layouts

### Responsive Breakpoints
- **Desktop:** 1200px and above
- **Tablet:** 768px - 1199px
- **Mobile:** 576px - 767px
- **Small Mobile:** Below 576px

## JavaScript Functionality

### Core Features
- **Smooth Scrolling:** Navigation link scroll behavior
- **Form Validation:** Client-side form validation and error handling
- **Responsive Menu:** Bootstrap navbar toggle functionality
- **Interactive Elements:** Button hover effects and transitions

## Development Workflow

### Local Development
1. Clone repository to local machine
2. Open index.html in browser or serve via local server
3. Make changes to HTML, CSS, or JavaScript files
4. Test changes across different browsers and devices
5. Commit changes with descriptive messages

### Version Control
- Git repository with main branch
- Feature branches for new development
- Descriptive commit messages following conventional format
- Pull request process for code review

### Testing Strategy
- **Cross-browser testing:** Chrome, Firefox, Safari, Edge
- **Responsive testing:** Various screen sizes and devices
- **Performance testing:** Page load times and optimization
- **Accessibility testing:** Screen reader compatibility and keyboard navigation

## Deployment Options

### Static Hosting
- GitHub Pages (free, integrated with repository)
- Netlify (free tier with continuous deployment)
- Vercel (frontend-focused deployment platform)
- Traditional web hosting (Apache/Nginx servers)

### CDN Considerations
- Bootstrap loaded via CDN for reliability
- Images can be converted to local for better control
- External dependencies minimize bundle size
