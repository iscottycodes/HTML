# Contributing to SpaceX Demo Website

Thank you for your interest in contributing to this HTML project! This document provides guidelines and information for contributors.

## 📋 Table of Contents
- [Getting Started](#getting-started)
- [Development Setup](#development-setup)
- [Contributing Guidelines](#contributing-guidelines)
- [Code Style](#code-style)
- [Commit Message Format](#commit-message-format)
- [Pull Request Process](#pull-request-process)

## 🚀 Getting Started

### Prerequisites
Before contributing, ensure you have:
- Basic knowledge of HTML5, CSS3, and JavaScript
- Familiarity with Bootstrap framework
- A modern web browser for testing
- Git installed on your system

### Repository Setup
1. Fork the repository on GitHub
2. Clone your fork locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/spacex-html-project.git
   cd spacex-html-project
   ```
3. Add the original repository as upstream:
   ```bash
   git remote add upstream https://github.com/ORIGINAL_OWNER/spacex-html-project.git
   ```

## 🛠️ Development Setup

### Local Development
1. Open the project in your preferred code editor
2. Serve the files using a local server:
   ```bash
   # Python
   python -m http.server 8000
   
   # Node.js
   npx http-server
   
   # PHP
   php -S localhost:8000
   ```
3. Open `http://localhost:8000` in your browser
4. Start making changes!

## 📝 Contributing Guidelines

### Types of Contributions
We welcome various types of contributions:
- **Bug Fixes:** Fix existing issues or bugs
- **Feature Additions:** Add new functionality or sections
- **Design Improvements:** Enhance visual design or UX
- **Documentation:** Improve README, comments, or documentation
- **Performance:** Optimize code or loading times
- **Accessibility:** Improve accessibility features

### Reporting Issues
Before opening an issue, please:
1. Check if the issue already exists
2. Use the appropriate issue template
3. Provide clear description and steps to reproduce
4. Include browser and device information

### Feature Requests
For new features:
1. Describe the feature clearly
2. Explain why it would be valuable
3. Include examples or mockups if possible
4. Consider the impact on existing functionality

## 🎨 Code Style

### HTML Guidelines
- Use semantic HTML5 elements (`<header>`, `<section>`, `<footer>`)
- Include proper indentation (2 spaces)
- Add meaningful comments for complex sections
- Use descriptive class and ID names

```html
<!-- Good example -->
<section id="about-us" class="py-5">
    <div class="container">
        <div class="row">
            <div class="col-lg-6">
                <h2 class="section-title">About Us</h2>
                <p class="lead">Company description...</p>
            </div>
        </div>
    </div>
</section>
```

### CSS Guidelines
- Use consistent naming conventions (kebab-case)
- Group related styles together
- Include comments for section breaks
- Use meaningful variable names

```css
/* Header styles */
.main-header {
    background-size: cover;
    min-height: 100vh;
    position: relative;
}

/* Section spacing */
.py-5 {
    padding: 3rem 0;
}
```

### JavaScript Guidelines
- Use modern ES6+ syntax
- Include error handling
- Add meaningful comments
- Follow camelCase conventions

```javascript
// Smooth scrolling functionality
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
            target.scrollIntoView({
                behavior: 'smooth',
                block: 'start'
            });
        }
    });
});
```

## 📤 Commit Message Format

Use clear, descriptive commit messages:

```
type: brief description

Longer description if needed

Fixes #123
```

### Commit Types
- **feat:** New feature
- **fix:** Bug fix
- **docs:** Documentation changes
- **style:** Code style changes (formatting, etc.)
- **refactor:** Code refactoring
- **test:** Test additions or changes
- **chore:** Maintenance tasks

### Examples
```
feat: add responsive navigation menu

Add mobile-friendly navbar with Bootstrap collapse functionality

fix: resolve image loading issues in Chrome

Docs: update README with installation instructions

style: reformat CSS indentation for consistency
```

## 🔄 Pull Request Process

### Before Submitting PR
1. Create a new branch from main:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. Make your changes
3. Test your changes in multiple browsers
4. Check responsive design on different screen sizes
5. Ensure no console errors or warnings

### PR Requirements
- [ ] Code follows established style guidelines
- [ ] Self-review of code has been completed
- [ ] Code has been tested across browsers
- [ ] Responsive design verified
- [ ] Documentation updated if necessary
- [ ] Commit messages are clear and descriptive

### PR Template
```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Style/design change
- [ ] Performance improvement

## Testing
- [ ] Tested on Chrome
- [ ] Tested on Firefox
- [ ] Tested on Safari
- [ ] Tested on mobile devices

## Screenshots
(If applicable, add screenshots)

## Checklist
- [ ] Code follows style guidelines
- [ ] Self-review completed
- [ ] No console errors
- [ ] Documentation updated
```

## 🤝 Code of Conduct

### Our Standards
- Be respectful and inclusive
- Focus on constructive feedback
- Help others learn and grow
- Maintain a collaborative environment

### Unacceptable Behavior
- Harassment or discrimination
- Personal attacks
- Spam or off-topic discussions
- Copyright violations
	
### Enforcement
Instances of unacceptable behavior may be reported by contacting project maintainers. All complaints will be reviewed and addressed promptly.

## 📞 Support

For questions or support:
- Open an issue on GitHub
- Check existing documentation
- Review previous issues and discussions

Thank you for contributing to this project! 🚀
