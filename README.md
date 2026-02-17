# Nima's Wedding Apology Website 💕

A playful, hand-drawn apology website for missing Nima's wedding. Features whimsical animations, confetti effects, and 12 hilarious marketing-themed reasons.

## Features

- 🎨 Hand-drawn, whimsical wedding-themed design
- 🌸 Watercolor-style backgrounds with soft pastels
- ✨ Scroll-triggered animations for each reason
- 🎊 Interactive confetti effects (click anywhere!)
- 💕 Floating hearts background
- 📱 Fully responsive design
- 🚀 Single HTML file - no build process needed

## Quick Start

1. **View Locally**
   - Simply open `index.html` in your web browser
   - That's it! No server needed.

2. **Deploy to GitHub Pages**

   ### Method 1: Via GitHub Web Interface
   1. Create a new repository on GitHub (e.g., `nima-wedding-apology`)
   2. Upload `index.html` to the repository
   3. Go to Settings → Pages
   4. Under "Source", select `main` branch and `/ (root)` folder
   5. Click Save
   6. Your site will be live at `https://yourusername.github.io/nima-wedding-apology/`

   ### Method 2: Via Command Line
   ```bash
   # Initialize git repository
   git init

   # Add files
   git add index.html README.md

   # Commit
   git commit -m "Initial commit: Nima wedding apology site"

   # Add remote (replace YOUR_USERNAME with your GitHub username)
   git remote add origin https://github.com/YOUR_USERNAME/nima-wedding-apology.git

   # Push to GitHub
   git branch -M main
   git push -u origin main

   # Enable GitHub Pages
   # Go to repository Settings → Pages → select main branch → Save
   ```

3. **Deploy to Netlify** (Alternative)
   1. Go to [Netlify](https://netlify.com)
   2. Drag and drop the project folder
   3. Done! Instant deployment.

4. **Deploy to Vercel** (Alternative)
   1. Install Vercel CLI: `npm i -g vercel`
   2. Run `vercel` in the project directory
   3. Follow the prompts
   4. Done!

## Customization

The website is fully self-contained in `index.html`. You can customize:

- **Reasons**: Edit the reason text in the HTML (lines ~250-300)
- **Colors**: Modify the CSS color variables and gradients
- **Fonts**: Change the Google Fonts imports and CSS font-family
- **Name**: Replace "Nima" with any other name
- **Closing message**: Update the heartfelt message section
- **Signature**: Add your actual name in the signature

## Tech Stack

- Pure HTML5, CSS3, and vanilla JavaScript
- Google Fonts (Caveat, Quicksand)
- Canvas API for confetti effects
- Intersection Observer API for scroll animations
- No frameworks, no dependencies, no build process

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge)

## License

Free to use and modify as you wish!

---

Made with ❤️ and a touch of marketing humor
