# Personal Website

A personal and research portfolio site, built for **GitHub Pages**.

## What’s included

- **Hero** — Name, tagline, short bio  
- **About** — Background and interests  
- **Research** — Papers, projects, links  
- **Projects** — Side projects and “cool stuff”  
- **Contact** — GitHub, Twitter, LinkedIn, email  

Edit `index.html` to add your content, then publish with GitHub Pages.

## Publish with GitHub Pages

1. **Push this repo to GitHub**  
   Create a new repository and push your code (or use an existing repo).

2. **Turn on GitHub Pages**  
   - Open the repo on GitHub → **Settings** → **Pages**  
   - Under **Source**, choose **Deploy from a branch**  
   - Branch: **main** (or **master**), folder: **/ (root)**  
   - Save  

3. **View your site**  
   After a minute or two it will be at:  
   `https://<your-username>.github.io/<repo-name>/`  

   If the repo is named **`<username>.github.io`**, the URL is:  
   `https://<your-username>.github.io/`

## Local preview

Open `index.html` in a browser, or run a simple server:

```bash
# Python 3
python -m http.server 8000
# Then visit http://localhost:8000
```

## Customization

- **Content**: Edit text, links, and section order in `index.html`.
- **Styling**: Colors and fonts are in `styles.css` (CSS variables at the top).
- **Add pages**: Create more `.html` files and link to them from the nav.

No build step required — plain HTML and CSS.
