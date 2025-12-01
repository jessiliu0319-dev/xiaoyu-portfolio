# Image Setup Guide

This guide will help you add images to your personal website.

## Required Images

Create an `images` folder in your website directory and add the following images:

### Profile & Education
- `images/headshot.jpg` - Your headshot photo for the hero section (recommended: 600x600px, square, will be displayed as a circle)
- `images/profile.jpg` - Another photo for the About Me section (recommended: 600x600px, square or rectangular)
- `images/cornell-logo.png` - Cornell University logo (120x120px recommended)
- `images/band-photo.jpg` - Night Espresso band photo for Interests section (recommended: 800x600px)

### Project Images
These appear at the top of each project card:
- `images/project-tcam.jpg` - TCAM project image
- `images/project-gesturehome.jpg` - GestureHome project image
- `images/project-pilooper.jpg` - PiLooper project image
- `images/project-intelliglove.jpg` - IntelliGlove project image
- `images/project-mazebot.jpg` - MazeBot project image

Recommended size: 700x400px (16:9 aspect ratio works well)

### Publication Thumbnails
These appear as thumbnails next to each publication:
- `images/pub-openrobocare.jpg` - OpenRoboCare paper figure
- `images/pub-collisions.jpg` - Collision adaptation paper figure
- `images/pub-cushsense.jpg` - CushSense paper figure

Recommended size: 400x300px

## How to Add External Links

Replace the `#` placeholder links in your HTML with actual URLs:

### Projects Section
Each project card is now a clickable link. Update the `href="#"` in the `<a class="project-card">` tags:
```html
<!-- Example: -->
<a href="https://your-project-page.com" class="project-card fade-in" target="_blank">
```

### Publications Section
Look for `<a href="#" target="_blank">` tags and update them:
```html
<!-- Example: -->
<a href="https://arxiv.org/abs/your-paper-id" target="_blank">PDF</a>
<a href="https://your-project-site.com" target="_blank">Website</a>
<a href="https://github.com/your-username/dataset" target="_blank">Dataset</a>
```

## Tips
- Use `.jpg` for photos and complex images
- Use `.png` for logos and images with transparency
- Optimize images for web (compress them to reduce file size)
- Make sure image file names match exactly what's in the HTML (case-sensitive)
- Test your website locally after adding images

### Interests Section
Look for `<a href="#" class="interest-link">` tags and update them:
```html
<!-- Example: -->
<a href="https://nightespresso.com" class="interest-link" target="_blank">Band Website</a>
<a href="https://instagram.com/nightespresso" class="interest-link" target="_blank">Instagram</a>
<a href="https://open.spotify.com/artist/..." class="interest-link" target="_blank">Listen on Spotify</a>
```

## Folder Structure
```
XY personal web/
├── first.html
├── images/
│   ├── headshot.jpg
│   ├── profile.jpg
│   ├── cornell-logo.png
│   ├── band-photo.jpg
│   ├── project-tcam.jpg
│   ├── project-gesturehome.jpg
│   ├── project-pilooper.jpg
│   ├── project-intelliglove.jpg
│   ├── project-mazebot.jpg
│   ├── pub-openrobocare.jpg
│   ├── pub-collisions.jpg
│   └── pub-cushsense.jpg
└── IMAGE_GUIDE.md
```

## Theme Colors

The website now uses a blue color theme:
- Primary accent: Blue (#3b82f6)
- Secondary accent: Darker blue (#2563eb)
- Tertiary accent: Cyan (#06b6d4)
