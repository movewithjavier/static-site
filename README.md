# Static Site Demo

A simple, fast, and secure static website created as a zero-cost alternative to WordPress and Elementor. This project demonstrates how to build a modern, responsive website using only HTML, CSS, and minimal JavaScript.

## Features

- Zero hosting costs (when deployed to GitHub Pages, Netlify, or Vercel)
- Fast loading times
- Mobile responsive design
- Blog functionality
- SEO-friendly structure
- No database or server-side code (improved security)

## Project Structure

```
static-site/
├── index.html              # Homepage
├── css/
│   └── styles.css          # Main stylesheet
├── js/
│   └── main.js             # JavaScript functionality
├── images/                 # Image assets
├── blog/                   # Blog section
│   ├── index.html          # Blog listing page
│   ├── blog.css            # Blog-specific styles
│   └── post1.html          # Sample blog post
└── README.md               # This file
```

## Local Development

To work on this site locally:

1. Clone this repository
2. Open the project in your code editor
3. Use a local development server to preview changes

You can use any of these methods to run a local server:

- Python: `python -m http.server`
- Node.js: Install `http-server` with `npm install -g http-server` and run `http-server`
- VS Code: Use the Live Server extension

## Deployment to GitHub Pages

### 1. Create a GitHub Repository

Create a new repository on GitHub. If you want to create a user or organization site, name your repository `username.github.io`, where "username" is your GitHub username or organization name.

For a project site, you can use any name for your repository.

### 2. Push Your Code to GitHub

```bash
# Initialize a Git repository (if you haven't already)
git init

# Add all files to the repository
git add .

# Commit the changes
git commit -m "Initial commit"

# Add the remote GitHub repository
git remote add origin https://github.com/username/repository-name.git

# Push the code to GitHub
git push -u origin main
```

Replace `username` and `repository-name` with your GitHub username and repository name.

### 3. Configure GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings"
3. Scroll down to the "GitHub Pages" section
4. Under "Source", select the branch you want to deploy (usually "main" or "master")
5. Click "Save"

GitHub will provide you with a URL where your site is published.

### 4. Connect Your Custom Domain (Optional)

If you have a custom domain:

1. In your repository's "Settings", scroll to the "GitHub Pages" section
2. Under "Custom domain", enter your domain name (e.g., `www.example.com`)
3. Click "Save"

Next, configure your domain's DNS settings at your domain registrar:

For an apex domain (example.com):
```
A     @     185.199.108.153
A     @     185.199.109.153
A     @     185.199.110.153
A     @     185.199.111.153
```

For a www subdomain:
```
CNAME     www     username.github.io
```

It may take up to 24 hours for DNS changes to propagate.

### 5. Enable HTTPS (Recommended)

1. In your repository's "Settings", scroll to the "GitHub Pages" section
2. Check the "Enforce HTTPS" option

## Customization

To customize this site for your own use:

1. Update the content in `index.html` and other HTML files
2. Modify the styles in `css/styles.css` to match your brand
3. Replace the placeholder images in the `images` directory
4. Add your own blog posts by creating new HTML files in the `blog` directory

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Google Fonts for the Inter font family
- GitHub Pages for free hosting 