# My CBC College Assignment Structure

Hi, I'm Scott Dee from CBC College. Here's how I organized my HTML/CSS assignment files.

## What Files Are Here

```
my-space-website/
├── README.md          # This file explains the project
├── index.html         # The main webpage
├── styles.css         # All my CSS styling
├── images/           # Where local images would go
└── other files...    # License, contributing guide, etc.
```

## What Each File Does

### The Important Ones:
- **`index.html`** - This is the main file with all the HTML code and content
- **`styles.css`** - This has all my custom CSS styling 
- **`images/`** - Empty folder for local images (I used links to internet images)

### Other Files:
- **`README.md`** - Project description and instructions
- **`LICENSE`** - MIT license (this lets people use my code)
- **`CONTRIBUTING.md`** - How others could help improve my code
- **`.gitignore`** - Tells Git to ignore certain files (I mostly copied this from examples)

## How I Built the HTML Structure

My page has these main sections:

```
<html>
<head>
    <!-- Links to Bootstrap and my CSS file -->
</head>
<body>
    <header>
        <!-- Navigation bar -->
        <!-- Hero section with big title -->
    </header>
    
    <section id="about">
        <!-- About information -->
        <!-- Profile image -->
    </section>
    
    <section id="features">
        <!-- Three feature cards -->
        <!-- Table with SpaceX missions -->
    </section>
    
    <section id="contact">
        <!-- Contact form -->
    </section>
    
    <footer>
        <!-- Simple footer -->
    </footer>
</body>
</html>
```

## My CSS Organization

I tried to organize my CSS by sections:

1. **Reset styles** - Remove browser defaults
2. **Header styling** - Big background, navigation, hero text
3. **About section** - Content boxes, profile image styling
4. **Features section** - Cards, table styling
5. **Contact section** - Form styling, background overlay
6. **Responsive stuff** - Makes it work on phones

## How I Made It Work on Mobile

I used Bootstrap classes like:
- `col-md-6` for two columns on tablets
- `col-lg-4` for three columns on computers  
- `d-none d-md-block` to hide things on phones

Plus some CSS media queries for smaller screens:

```css
@media (max-width: 768px) {
    .hero-title {
        font-size: 2.5rem;  /* Smaller on phones */
    }
}
```

## Images I Used

Currently using links to images on the internet:
- Header background: SpaceX Eva Suit image
- Contact background: Same image with darker overlay  
- Profile image: SpaceX Mechazilla robot

The `images/` folder is there if someone wants to download the pictures and use local files instead.

## What I'd Do Differently Next Time

- Maybe split CSS into multiple files (it got pretty long)
- Add more interactive animations
- Better organize the JavaScript code
- Test more on different phones
- Maybe use a CSS framework like Tailwind

## Development Workflow

When I was working on this:
1. Edit HTML/CSS in VS Code
2. Save files
3. Refresh browser to see changes
4. Test on phone by making browser window smaller
5. Fix anything that looked broken

Pretty simple setup. No fancy build tools or anything.

---

*Hope this helps explain how I put things together for my CBC assignment!*
*Scott Dee - CBC College Web Development Student*