# Setup Instructions for Mark Žnidar's Website

## ✅ What's Been Created

Your minimal academic website is ready! Here's what was built:

### Files Created
- `index.html` - Main homepage with your bio, news, and publications
- `blog.html` - Blog page (currently a placeholder)
- `style.css` - Styling (same clean look as the original)
- `README.md` - Documentation for the site
- `assets/` - Directory for your images and files

### Content Included
- **Name**: Mark Žnidar
- **Navigation**: scholar | LinkedIn | email | blog
- **Bio**: First-person academic bio mentioning:
  - MSc at Oxford (co-advised by Bronstein & Leskovec)
  - Visiting Researcher at Stanford
  - ASEF Fellow
  - BSc from Ljubljana
  - Industry experience at Teads
- **News**: 4 recent updates
- **Publications**: Relational Transformer preprint + 2 papers from your Google Scholar

## 🎯 Next Steps - What You Need to Do

### 1. Add Your Profile Photo (REQUIRED)
- Place a square photo (≥512px) at: `assets/profile.png`
- Without this, the site will show a broken image

### 2. Optional: Add Your CV
- If you want a resume link, add: `assets/resume.pdf`
- Or remove the resume link from the navigation if you don't want it

### 3. Test Locally
```bash
cd mark-znidar.github.io
open index.html  # On Mac
# or just double-click index.html in your file browser
```

### 4. Deploy to GitHub Pages

#### Create a new GitHub repository:
```bash
cd mark-znidar.github.io
git init
git add .
git commit -m "Initial commit: Mark Žnidar academic website"
```

#### Push to GitHub:
1. Create a new repository on GitHub named `mark-znidar.github.io` (or your username)
2. Run:
```bash
git remote add origin https://github.com/YOUR-USERNAME/mark-znidar.github.io.git
git branch -M main
git push -u origin main
```

#### Enable GitHub Pages:
1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select **Deploy from a branch**
4. Select branch: **main** and folder: **/ (root)**
5. Click **Save**
6. Your site will be live at: `https://YOUR-USERNAME.github.io`

## 🎨 Customization

### Update Links
If you want to add GitHub or other links, edit the navigation in `index.html`:
```html
<h3>
<a href="https://scholar.google.com/citations?user=zsmIHq8AAAAJ&hl=en">scholar</a>
| <a href="https://github.com/YOUR-USERNAME">GitHub</a>  <!-- Add this -->
| <a href="https://www.linkedin.com/in/mark-znidar/">LinkedIn</a>
| <a href="mailto:znidar.mark@gmail.com">email</a>
| <a href="blog.html">blog</a>
</h3>
```

### Add More News Items
Edit the `<table>` section in `index.html`:
```html
<tr>
	<th>Date</th>
	<td>Your news item here.</td>
</tr>
```

### Change Colors
Edit `style.css` - current link color is green. To change:
```css
a {
	color: blue;  /* or any color you prefer */
}
```

## 📝 Content Sources Used
- LinkedIn: https://www.linkedin.com/in/mark-znidar/
- Google Scholar: https://scholar.google.com/citations?user=zsmIHq8AAAAJ&hl=en
- Design adapted from: https://github.com/rishabh-ranjan/rishabh-ranjan.github.io

## ❓ Questions?

The site is fully functional and ready to go once you add your profile photo. Everything else is optional!

