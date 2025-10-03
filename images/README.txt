Images Folder Documentation
============================

This folder is designated for local image files to replace external URLs in the project.

## Current External Image Usage

The project currently uses images from external sources:

1. **Header Background Image**
   - URL: https://sxcontent9668.azureedge.us/cms-assets/assets/Eva_Suit_Desktop_alternate_1cf9bae18e.jpg
   - Usage: Hero section background
   - Dimensions: 1920x1080 (recommended)

2. **Contact Section Background**
   - URL: Same as header (SpaceX Eva Suit image)
   - Usage: Contact form background with overlay

3. **Profile Image**
   - URL: https://shop.spacex.com/cdn/shop/files/Mechazilla_wall_decal_250x.png
   - Usage: About section profile display
   - Dimensions: 250x250 (square format recommended)

## Using Local Images

To use local images instead of external URLs:

1. **Download and place images in this folder**
   - Use descriptive filenames (e.g., spacex-background.jpg, mechazilla-profile.png)

2. **Update HTML references**
   - Edit index.html to point to local files:
   ```html
   <!-- Change from: -->
   background-image: url('https://external-url.com/image.jpg');
   
   <!-- To: -->
   background-image: url('images/spacex-background.jpg');
   ```

3. **Recommended image formats and sizes**
   - **Background images:** JPG or PNG, 1920x1080 pixels, <500KB
   - **Profile images:** PNG or JPG, 250x250 pixels, <100KB
   - **Icon images:** SVG or PNG, 64x64 pixels, <50KB

4. **Optimization guidelines**
   - Compress images for web (reduce file size)
   - Use appropriate formats (JPG for photos, PNG for graphics)
   - Include alt text for accessibility

## File Naming Conventions

Recommended naming structure:
- `spacex-background-main.jpg` - Main hero background
- `spacex-background-contact.jpg` - Contact section background  
- `spacex-profile-image.png` - Profile/about section image
- `spacex-icon-rocket.png` - Feature icons
- `spacex-logo.png` - Brand/logo images

## Image Optimization

Before adding images:
1. **Compress** using online tools (TinyPNG, CompressJPEG)
2. **Resize** to appropriate dimensions for web use
3. **Format** - Use JPG for photos, PNG for graphics with transparency
4. **Filename** - Use descriptive, lowercase names with hyphens

## Project Integration

When submitting the project:
- Include all image files in this folder
- Maintain folder structure in zip submission
- Update all HTML references to local paths
- Test that images load correctly offline

Note: External URLs are used in current version for convenience and demonstration purposes. Local images provide better control and offline functionality.