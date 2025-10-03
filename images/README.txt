Images Folder Documentation
============================

This folder is for local images used in the SpaceX Demo project by Scott Dee (CBC College assignment).

## Adding a Website Screenshot for GitHub

### Step 1: Take a Screenshot of Your Website
1. Open your website in a web browser
2. Resize browser window to about 1200px wide (or use browser developer tools)
3. Take a screenshot of the full webpage:
   - Windows: Use Snipping Tool or Windows+Shift+S
   - Mac: Command+Shift+4, then select area
   - Save the image as "website-screenshot.png"

### Step 2: Add Screenshot to Project
1. Save the screenshot in this images folder
2. Name it exactly: "website-screenshot.png"
3. Update README.md to reference it at the top:
   ```markdown
   <img src="images/website-screenshot.png" alt="Screenshot of my website" width="800">
   ```

### Screenshot Tips:
- Show the full webpage (header to footer)
- Make sure it looks good on desktop view
- Keep file size under 1MB
- Use PNG format for best quality
- 1200px width is ideal for GitHub display

## Current External Images Used

The project currently uses images from external sources:

1. **Header Background Image**
   - URL: https://sxcontent9668.azureedge.us/cms-assets/assets/Eva_Suit_Desktop_alternate_1cf9bae18e.jpg
   - Usage: Hero section background

2. **Contact Section Background**
   - URL: Same as header
   - Usage: Contact form background

3. **Profile Image**
   - URL: https://shop.spacex.com/cdn/shop/files/Mechazilla_wall_decal_250x.png
   - Usage: About section profile image

## Converting to Local Images

To use local images instead:

1. Download images to this folder
2. Rename them clearly (e.g., "spacex-background.jpg")
3. Update index.html to reference local files:
   ```html
   <!-- Change from: -->
   background-image: url('https://external-url.com/image.jpg');
   
   <!-- To: -->
   background-image: url('images/spacex-background.jpg');
   ```

## Image Guidelines for Academic Projects:
- Keep images under 500KB each
- Use descriptive filenames
- Include alt text for accessibility
- Test that images load after moving to local files