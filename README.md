# Mark Žnidar - Personal Academic Website

A minimal, clean academic website built with plain HTML and CSS.

## Structure

```
mark-znidar.github.io/
├── index.html          # Main homepage with bio, news, and publications
├── blog.html           # Blog index page
├── style.css           # Stylesheet
├── assets/
│   ├── profile.png     # Profile photo (you need to add this)
│   └── resume.pdf      # Optional CV (you can add this)
└── blog/               # Optional blog posts directory
```

## Setup

### Local Development

1. Clone or download this repository
2. Add your profile photo as `assets/profile.png` (square, ≥512px recommended)
3. (Optional) Add your CV as `assets/resume.pdf`
4. Open `index.html` in your browser to preview

No build process or dependencies required!

### GitHub Pages Deployment

#### Option 1: User Site (Recommended)
1. Rename the repository to `mark-znidar.github.io` (or your GitHub username)
2. Push to GitHub
3. Go to Settings → Pages
4. Select "Deploy from a branch" → `main` → `/ (root)`
5. Your site will be live at `https://mark-znidar.github.io`

#### Option 2: Project Site
1. Keep any repository name
2. Push to GitHub
3. Go to Settings → Pages
4. Select "Deploy from a branch" → `main` → `/ (root)`
5. Your site will be live at `https://yourusername.github.io/repo-name`

## Customization

### Update Content
- **Bio**: Edit the `<p>` tags in `index.html`
- **News**: Modify the `<table>` rows under the "news" section
- **Publications**: Update the `<ul>` lists under "pre-prints" and "publications"
- **Links**: Change URLs in the top navigation

### Add Blog Posts
1. Create HTML files in the `blog/` directory (e.g., `blog/2025-01-15_my-post.html`)
2. Add entries to `blog.html` linking to your posts
3. Use the same `style.css` for consistent styling

### Styling
- Colors and fonts are defined in `style.css`
- Current theme: Green links, Palatino headings, Open Sans body text
- Modify CSS variables to change the look

## Missing Assets

You need to provide:
- **Profile photo**: `assets/profile.png` (square image, ≥512px)
- **Resume** (optional): `assets/resume.pdf`

## Credits

Design inspired by and adapted from [Rishabh Ranjan's website](https://github.com/rishabh-ranjan/rishabh-ranjan.github.io).

## License

Feel free to use this template for your own academic website!

