# Website Setup Instructions

This guide will help you complete your personal website by adding images and updating all placeholder links.

## Step 1: Add Images

### Create the images folder
1. Create a new folder called `images` in the same directory as `first.html`

### Required Images

Add these images to the `images` folder:

#### Profile & Education
- **headshot.jpg** - Your circular headshot (recommended: 600x600px square)
- **profile.jpg** - Photo for About Me section (recommended: 600x600px)
- **cornell-logo.png** - Cornell University logo (120x120px recommended)
- **band-photo.jpg** - Night Espresso band photo (recommended: 800x600px)

#### Project Images (at top of each project card)
- **project-tcam.jpg** - TCAM project image
- **project-gesturehome.jpg** - GestureHome project image
- **project-pilooper.jpg** - PiLooper project image
- **project-intelliglove.jpg** - IntelliGlove project image
- **project-mazebot.jpg** - MazeBot project image

Recommended size: 700x400px (16:9 aspect ratio)

#### Publication Thumbnails (next to each publication)
- **pub-openrobocare.jpg** - OpenRoboCare paper figure
- **pub-collisions.jpg** - Collision adaptation paper figure
- **pub-cushsense.jpg** - CushSense paper figure

Recommended size: 400x300px

### Folder Structure
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
├── SETUP_INSTRUCTIONS.md
└── IMAGE_GUIDE.md
```

## Step 2: Update Links in first.html

Open `first.html` in a text editor and search for `href="#"` to find all placeholder links. Replace them with your actual URLs.

### Hero Section (Lines ~1015-1028)

**LinkedIn:**
```html
<a href="https://linkedin.com/in/YOUR-PROFILE" class="social-link" target="_blank" title="LinkedIn">
```

**CV Download:**
```html
<a href="files/YOUR_CV.pdf" class="social-link" target="_blank" title="Download CV">
```
*Note: Create a `files` folder and add your CV PDF there*

### Publications Section (Lines ~1092-1168)

For each publication, find the placeholder links and update:

**OpenRoboCare:**
```html
<a href="https://arxiv.org/abs/YOUR-PAPER-ID" target="_blank">PDF</a>
<a href="https://your-project-website.com" target="_blank">Website</a>
<a href="https://your-dataset-link.com" target="_blank">Dataset</a>
```

**Collision Adaptation:**
```html
<a href="https://arxiv.org/abs/YOUR-PAPER-ID" target="_blank">PDF</a>
<a href="https://your-project-website.com" target="_blank">Website</a>
<a href="https://youtu.be/VIDEO-ID" target="_blank">Video</a>
```

**CushSense:**
```html
<a href="https://arxiv.org/abs/YOUR-PAPER-ID" target="_blank">PDF</a>
<a href="https://your-project-website.com" target="_blank">Website</a>
<a href="https://github.com/your-username/repo" target="_blank">Code</a>
```

### Projects Section (Lines ~1118-1229)

Each project card is now clickable. Find and update the main project link:

**TCAM:**
```html
<a href="https://your-project-page.com" class="project-card fade-in" target="_blank">
```

**GestureHome:**
```html
<a href="https://your-project-page.com" class="project-card fade-in" target="_blank">
```

**PiLooper:**
```html
<a href="https://your-project-page.com" class="project-card fade-in" target="_blank">
```

**IntelliGlove:**
```html
<a href="https://your-project-page.com" class="project-card fade-in" target="_blank">
```

**MazeBot:**
```html
<a href="https://your-project-page.com" class="project-card fade-in" target="_blank">
```

### Interests Section (Lines ~1307-1313)

**Band Website:**
```html
<a href="https://nightespresso.com" class="interest-link" target="_blank">
```

**Instagram:**
```html
<a href="https://instagram.com/nightespresso" class="interest-link" target="_blank">
```

### Footer (Lines ~1330-1334)

**LinkedIn:**
```html
<a href="https://linkedin.com/in/YOUR-PROFILE">LinkedIn</a>
```

**GitHub:**
```html
<a href="https://github.com/YOUR-USERNAME">GitHub</a>
```

**Google Scholar:**
```html
<a href="https://scholar.google.com/citations?user=YOUR-ID">Google Scholar</a>
```

## Step 3: Tips for Images

- **File format**: Use `.jpg` for photos, `.png` for logos with transparency
- **Optimization**: Compress images for web to reduce file size (use tools like TinyPNG or ImageOptim)
- **File names**: Make sure they match exactly (case-sensitive!)
- **Aspect ratios**:
  - Headshot: Square (1:1)
  - Project images: Wide (16:9)
  - Publication thumbnails: Landscape (4:3)

## Step 4: Testing

1. Open `first.html` in your web browser
2. Check that all images load correctly
3. Click all links to verify they work
4. Test on both desktop and mobile views

## Quick Checklist

- [ ] Created `images/` folder
- [ ] Added all 13 required images
- [ ] Updated LinkedIn link (hero section)
- [ ] Updated CV download link
- [ ] Updated all 3 publication links (PDF, Website, etc.)
- [ ] Updated all 5 project card links
- [ ] Updated band website and Instagram links
- [ ] Updated footer links (LinkedIn, GitHub, Google Scholar)
- [ ] Tested website in browser
- [ ] Verified all images display correctly
- [ ] Verified all links work

## Need Help?

- Make sure file names in HTML match your actual image files exactly
- Check that all images are in the `images/` folder
- Verify URLs start with `https://` or `http://`
- For local files (like CV), use relative paths: `files/filename.pdf`

---

Your website should now be fully functional with all images and links working!
