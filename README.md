# Personal Portfolio Website

A modern, responsive portfolio website with a beautiful pink theme. This portfolio includes Home, About, Contact Info, and Photos pages.

## Features

- 🎨 Modern pink gradient design
- 📱 Fully responsive layout
- ✨ Smooth animations and transitions
- 🌟 Unique visual effects
- 📄 Four main pages: Home, About, Contact Info, and Photos

## Pages

- **Home** (`index.html`) - Landing page with hero section
- **About** (`about.html`) - Personal information and skills
- **Contact Info** (`contact.html`) - Contact details and contact form
- **Photos** (`photos.html`) - Photo gallery

## How to Push to GitHub and Deploy

### Step 1: Create a GitHub Account (if you don't have one)
1. Go to [github.com](https://github.com)
2. Sign up for a free account

### Step 2: Install Git (if not already installed)
1. Download Git from [git-scm.com](https://git-scm.com/downloads)
2. Install it following the installation wizard
3. Open your terminal/command prompt and verify installation:
   ```bash
   git --version
   ```

### Step 3: Initialize Git in Your Project
1. Open your terminal/command prompt
2. Navigate to your project folder:
   ```bash
   cd C:\Users\rosal\OneDrive\Desktop\maryrose
   ```
3. Initialize Git:
   ```bash
   git init
   ```

### Step 4: Create a .gitignore File (Optional but Recommended)
Create a `.gitignore` file to exclude unnecessary files:
```
.DS_Store
Thumbs.db
*.log
```

### Step 5: Add and Commit Your Files
1. Add all files to Git:
   ```bash
   git add .
   ```
2. Commit your files:
   ```bash
   git commit -m "Initial commit: Portfolio website"
   ```

### Step 6: Create a New Repository on GitHub
1. Go to GitHub.com and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository (e.g., "portfolio" or "my-portfolio")
5. **Important:** Make it **Public** (required for free GitHub Pages)
6. **Don't** initialize with README, .gitignore, or license (you already have files)
7. Click "Create repository"

### Step 7: Connect Your Local Repository to GitHub
1. After creating the repository, GitHub will show you commands
2. Copy the repository URL (it will look like: `https://github.com/yourusername/portfolio.git`)
3. In your terminal, run:
   ```bash
   git remote add origin https://github.com/yourusername/portfolio.git
   ```
   (Replace `yourusername` and `portfolio` with your actual username and repository name)

### Step 8: Push Your Code to GitHub
```bash
git branch -M main
git push -u origin main
```

You'll be prompted to enter your GitHub username and password (or personal access token).

### Step 9: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on "Settings" (top menu)
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"
7. Wait a few minutes, then your site will be live at:
   `https://yourusername.github.io/portfolio/`

## Customizing Your Portfolio

### Update Your Information
1. **Name**: Replace "Your Name" in all HTML files with your actual name
2. **Contact Info**: Update the contact details in `contact.html`
3. **About Section**: Edit the content in `about.html` to reflect your information
4. **Photos**: Replace the photo placeholders in `photos.html` with your actual images

### Adding Your Photo
1. Add your photo to the project folder
2. In `index.html`, replace the image placeholder with:
   ```html
   <img src="your-photo.jpg" alt="Your Name" class="profile-image">
   ```
3. Add CSS for `.profile-image` in `styles.css` if needed

### Adding Real Photos to Gallery
1. Add your photos to a folder (e.g., `images/`)
2. In `photos.html`, replace placeholders with:
   ```html
   <img src="images/photo1.jpg" alt="Description">
   ```

## Local Development

To view your website locally:
1. You can simply open `index.html` in your browser
2. Or use a local server:
   - **VS Code**: Install "Live Server" extension and click "Go Live"
   - **Python**: Run `python -m http.server 8000` and visit `http://localhost:8000`
   - **Node.js**: Install `http-server` and run `npx http-server`

## File Structure

```
maryrose/
│
├── index.html          # Home page
├── about.html          # About page
├── contact.html        # Contact page
├── photos.html         # Photos page
├── styles.css          # All styling
└── README.md           # This file
```

## Tips

- **Update regularly**: Keep your portfolio updated with your latest work
- **Customize colors**: Edit the CSS variables in `styles.css` to change the color scheme
- **Add more pages**: You can add more HTML files and link them in the navigation
- **Mobile-friendly**: The design is responsive and works on all devices

## Troubleshooting

### Git Push Issues
- If you get authentication errors, you may need to use a Personal Access Token instead of a password
- Generate one at: GitHub → Settings → Developer settings → Personal access tokens

### GitHub Pages Not Updating
- Wait 5-10 minutes after pushing changes
- Clear your browser cache
- Check the "Actions" tab in your GitHub repository for deployment status

## Need Help?

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Guides](https://guides.github.com/)

---

**Happy coding! 🎉**

