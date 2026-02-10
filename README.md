# My Portfolio

**🌐 Live Demo:** [https://amish-cv.netlify.app/](https://amish-cv.netlify.app/)

A beginner-friendly portfolio website built with HTML, CSS, and JavaScript.

## Features

- Clean, modern design
- Fully responsive (mobile-friendly)
- Smooth scrolling navigation
- Multiple sections: Home, About, Skills, Projects, Contact
- Easy to customize

## Customization

1. **Edit Your Information**
   - Update the hero section with your name and tagline
   - Modify the About section to describe yourself
   - Add your actual projects to the Projects section
   - Update contact links with your email, LinkedIn, and GitHub

2. **Change Colors**
   - Open `style.css`
   - Modify the CSS variables at the top:
     ```css
     --primary-color: #3498db;
     --secondary-color: #2c3e50;
     ```

3. **Add Your Profile Image**
   - Add image files to `/assets/images/`
   - Reference them in the HTML

## Local Testing

Simply open `index.html` in your browser to preview the portfolio.

## Deployment to Netlify

### Method 1: GitHub (Recommended)
1. Create a GitHub repository and push this folder
2. Go to [netlify.com](https://netlify.com)
3. Click "New site from Git"
4. Connect your GitHub account
5. Select your repository
6. Netlify will auto-detect the settings and deploy!

### Method 2: Drag & Drop
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the entire portfolio folder
3. Your site will be live instantly!

### Method 3: Command Line (using Netlify CLI)
```bash
npm install -g netlify-cli
cd portfolio
netlify deploy
```

## File Structure

```
portfolio/
├── index.html      (Main HTML file)
├── style.css       (Styling)
├── script.js       (JavaScript functionality)
├── assets/
│   └── images/     (Place your images here)
├── README.md       (This file)
└── .gitignore      (Git ignore file)
```

## Tips for Beginners

- Keep your About section concise but interesting
- Showcase 3-5 of your best projects
- Add links to live demos and GitHub repositories
- Use real contact information (email, LinkedIn, GitHub)
- Test on different screen sizes before deploying
- Keep the design simple and user-friendly

## Next Steps

- [ ] Customize your information
- [ ] Add project details with links
- [ ] Add a profile image
- [ ] Deploy to Netlify
- [ ] Share your portfolio!

Good luck! 🚀
