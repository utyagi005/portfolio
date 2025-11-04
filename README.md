# Uday Tyagi — CS Co-op Portfolio

A lightweight single-page portfolio (HTML/CSS/JS) with smooth reveal animations to showcase my projects, learning journey, and contact info. Deployed on GitHub Pages.

**Live site:** https://utyagi005.github.io/portfolio  
**Resume:** (add link later)

## Features
- Sticky nav + smooth scrolling
- Reveal-on-scroll animations (IntersectionObserver)
- Responsive grid and timeline
- Easy “Projects” data model (JS array → cards)

## Tech Stack
- HTML5, CSS3 (no framework)
- Vanilla JavaScript (no build step)
- GitHub Pages (hosting)


## Local Development
1. Clone repo  
2. Open `index.html` in any browser (no server needed)

## Deployment (GitHub Pages)
- Settings → Pages → Source: **Deploy from a branch**, Branch: `main`, Folder: `/ (root)`
- Site will be available at `https://<username>.github.io/portfolio/`

## Add / Edit Projects
Open `index.html`, find the `// Projects data` block (see “Make it more modular” below).  
Add a new object to the `projects` array and it will render automatically.

## Roadmap
- Light/Dark mode toggle  
- Real project links (GitHub, demos)  
- Contact form via Formspree  
- SEO/OpenGraph metadata & favicon

## License
MIT

