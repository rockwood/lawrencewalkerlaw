# Lawrence Walker Law - Static Website

Static website for Lawrence Walker, Attorney at Law based in Batavia, Ohio.

## Features

- Clean, professional design
- Fully responsive (mobile, tablet, desktop)
- No dependencies or build process required
- Optimized for GitHub Pages

## Site Structure

- `index.html` - Home page with practice information
- `bio.html` - Biography page
- `style.css` - Main stylesheet
- `profile-final.jpg` - Header image
- `tile.png` - Background texture
- `glow.png` - Background glow effect

## Local Development

Simply open `index.html` in your web browser to view the site locally.

## Deploying to GitHub Pages

### Option 1: Using GitHub UI

1. Create a new repository on GitHub (e.g., `lawrencewalkerlaw`)
2. Push this code to the repository:
   ```bash
   git init
   git add index.html bio.html style.css *.png *.jpg README.md .gitignore
   git commit -m "Initial commit - static site for GitHub Pages"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/lawrencewalkerlaw.git
   git push -u origin main
   ```
3. Go to your repository settings on GitHub
4. Navigate to "Pages" in the left sidebar
5. Under "Source", select "Deploy from a branch"
6. Select "main" branch and "/ (root)" folder
7. Click "Save"
8. Your site will be available at: `https://YOUR-USERNAME.github.io/lawrencewalkerlaw/`

### Option 2: Using Custom Domain

If you want to use `lawrencewalkerlaw.com`:

1. Follow the steps above to deploy to GitHub Pages
2. In your repository settings under "Pages", add your custom domain
3. Update your DNS settings with your domain registrar:
   - Add a CNAME record pointing `www` to `YOUR-USERNAME.github.io`
   - Add A records for the apex domain pointing to GitHub's IP addresses:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
4. Create a `CNAME` file in the repository root with your domain name

## Contact Information

**Lawrence Walker**
Attorney at Law
60 N. Fourth Street
Batavia, Ohio 45103
Telephone: (513) 732-5777
Email: lw@lawrencewalkerlaw.com

## License

Copyright © Lawrence Walker, Attorney at Law. All rights reserved.
