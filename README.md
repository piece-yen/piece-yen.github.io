# Research Profile Website

A clean, professional research profile website designed for academics and researchers. Built with simple HTML and CSS for easy deployment on GitHub Pages.

## Features

- Clean, minimalist design inspired by professional academic websites
- Fully responsive layout (mobile-friendly)
- Multiple pages: Home, About, Research, Publications, CV, Contact
- Easy to customize with your own content
- Ready for GitHub Pages deployment

## Deployment on GitHub Pages

### Option 1: Deploy from Main Branch

1. **Create a new GitHub repository**
   - Go to [GitHub](https://github.com) and create a new repository
   - Name it `yourname.github.io` (replace `yourname` with your GitHub username)
   - Make it public

2. **Upload your files**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourname.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository Settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click Save

4. **Access your site**
   - Your site will be live at `https://yourusername.github.io`
   - It may take a few minutes for the site to go live

### Option 2: Deploy from a Custom Repository Name

If you want to use a different repository name (e.g., `research-profile`):

1. Create a repository with any name you like
2. Follow the same steps above
3. Your site will be available at `https://yourusername.github.io/repository-name`

## Customization Guide

### 1. Update Your Information

Edit each HTML file to replace placeholder text:
- Replace `[Your Name]` with your actual name
- Update `your.email@institution.edu` with your email
- Add your social media links (Twitter, LinkedIn, GitHub)
- Fill in your research interests, publications, and CV details

### 2. Customize Colors and Fonts

Edit `style.css` to change:
- Colors: Search for hex color codes (e.g., `#000`, `#333`, `#0066cc`)
- Fonts: Modify the `font-family` properties
- Spacing: Adjust `padding` and `margin` values

### 3. Add Your CV PDF

1. Create an `assets` folder in your project
2. Add your CV PDF file (e.g., `YourName_CV.pdf`)
3. Update the link in `cv.html` to point to your PDF

### 4. Add Photos (Optional)

To add a profile photo or research images:
1. Add images to the `assets` folder
2. Insert `<img>` tags in your HTML files:
   ```html
   <img src="assets/profile-photo.jpg" alt="Your Name" style="max-width: 300px; border-radius: 50%;">
   ```

## File Structure

```
ResearchProfile/
├── index.html          # Home page
├── about.html          # About page
├── research.html       # Research page
├── publications.html   # Publications page
├── cv.html            # CV page
├── contact.html       # Contact page
├── style.css          # Stylesheet
├── assets/            # Folder for images, PDFs, etc.
└── README.md          # This file
```

## Tips for Academic Websites

1. **Keep it updated**: Regularly update your publications and research projects
2. **Be concise**: Researchers are busy; make your content scannable
3. **Add links**: Link to your papers, code repositories, and collaborator sites
4. **Google Scholar**: Include a link to your Google Scholar profile
5. **ORCID**: Add your ORCID ID for academic identity verification
6. **SEO**: Use descriptive titles and meta descriptions for better visibility

## Browser Compatibility

This website works on all modern browsers:
- Chrome, Firefox, Safari, Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

Feel free to use this template for your own research profile website. No attribution required.

## Need Help?

If you encounter issues with deployment or customization, check out:
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [HTML/CSS Tutorials](https://developer.mozilla.org/en-US/docs/Web)

---

**Built in 2026** - A simple, effective solution for academic web presence.
