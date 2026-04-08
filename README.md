# Creative Spaces

A modern one-page portfolio website template for an **interior designer + architect studio**.

## What this project includes
- Sticky navigation with mobile menu
- Hero section with CTA buttons
- About, Services, Featured Projects, Process, Testimonials, Contact
- Responsive layout for desktop and mobile
- Ready to publish on GitHub Pages / Netlify / Vercel

## Run locally
Because this is a static website, you can open `index.html` directly in your browser.

If you want a local dev server:

```bash
python3 -m http.server 8080
```

Then open: <http://localhost:8080>

<<<<<<< codex/create-web-project-for-creative-spaces-9o8wbg
## How to add your own images

### 1) Create folders for images
Inside the project root, create:

```text
assets/
  images/
```

### 2) Add your photo files
Example names:

- `assets/images/hero.jpg`
- `assets/images/project-1.jpg`
- `assets/images/project-2.jpg`
- `assets/images/project-3.jpg`

Use web-friendly formats (`.jpg`, `.png`, `.webp`) and optimize images for speed.

### 3) Update image paths in `index.html`
Find and replace the existing `src` values.

Current image tags are in the Hero + Projects sections.

Example replacement:

```html
<img src="assets/images/hero.jpg" alt="Living room interior by Creative Spaces" />
```

### 4) Keep good alt text
Write meaningful `alt` text for accessibility and SEO.

### 5) Commit and publish
After replacing images:

```bash
git add .
git commit -m "Replace demo images with portfolio photos"
git push
```

Then redeploy to GitHub Pages / Netlify / Vercel.

=======
>>>>>>> main
## Customize before publishing
- Replace demo images with your own portfolio images
- Update project descriptions and client testimonials
- Replace contact details with real business details
- Connect the contact form to your backend or form service
