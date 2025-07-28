# Roblox Developer Portfolio

A modern, responsive portfolio website for Roblox developers. Built with HTML, CSS, and JavaScript, designed to showcase your Roblox development skills and projects.

## Features

- 🎨 Modern, responsive design
- 📱 Mobile-friendly navigation
- ✨ Smooth animations and transitions
- 🎯 Professional sections for projects, skills, and contact
- 🌐 Ready for GitHub Pages deployment

## Sections Included

1. **Hero Section** - Eye-catching introduction with call-to-action buttons
2. **About Me** - Personal introduction and experience highlights
3. **Projects** - Showcase your Roblox games and systems
4. **Skills** - Technical skills and technologies
5. **Goals** - Your aspirations and objectives
6. **Contact** - Ways for potential clients to reach you

## Customization Guide

### Personal Information
1. **Profile Photo**: Replace the placeholder in the About section
   - Look for: `<div class="profile-placeholder">`
   - Replace with your actual photo

2. **Project Screenshots**: Add your game screenshots
   - Look for: `<div class="image-placeholder">` in each project card
   - Replace with actual screenshots of your games

3. **Contact Links**: Update your social media and contact information
   - Look for: `<div class="contact-links">` section
   - Update Discord, Roblox profile, and GitHub links

### Content Updates

#### About Section
- Update the introduction text with your personal story
- Modify the experience highlights to match your specialties

#### Projects Section
- Replace project titles with your actual game names
- Update descriptions with your specific implementations
- Add relevant tags for each project

#### Skills Section
- Add or remove skills based on your expertise
- Update the categories as needed

#### Contact Section
- Update the benefits list to reflect your strengths
- Add your actual contact information

## Deployment to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [GitHub](https://github.com)
2. Click "New repository"
3. Name it `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
4. Make it public
5. Don't initialize with README (we already have one)

### Step 2: Upload Your Files
1. Clone the repository to your local machine
2. Copy all the files from this portfolio folder into the repository
3. Commit and push the changes:

```bash
git add .
git commit -m "Initial portfolio website"
git push origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings"
3. Scroll down to "GitHub Pages" section
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch
6. Click "Save"

Your portfolio will be available at `https://yourusername.github.io`

## File Structure

```
roblox-portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization Tips

### Colors
The website uses a purple gradient theme. To change colors:
- Primary gradient: `#667eea` to `#764ba2`
- Accent color: `#ffd700` (gold)
- Update these values in `styles.css`

### Fonts
The website uses Inter font from Google Fonts. To change:
- Update the Google Fonts link in `index.html`
- Modify the font-family in `styles.css`

### Adding New Sections
1. Add the HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Update navigation if needed

### Adding Animations
The website includes scroll animations. To add more:
- Use CSS animations in `styles.css`
- Add JavaScript triggers in `script.js`

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Performance

- Optimized images recommended
- Minified CSS/JS for production
- Fast loading times
- SEO-friendly structure

## License

This portfolio template is free to use and modify for personal and commercial projects.

## Support

If you need help customizing or deploying your portfolio, feel free to reach out!

---

**Note**: Remember to replace all placeholder content with your actual information before deploying. The website is designed to be easily customizable while maintaining a professional appearance. 