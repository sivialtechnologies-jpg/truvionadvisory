# Truvion Advisory Website

A simple static website for Truvion Advisory built with plain HTML and CSS.

## Files

- `index.html` - Home page
- `services.html` - Services overview
- `approach.html` - Approach and methodology
- `about.html` - Mission, vision, values, and global perspective
- `contact.html` - Contact details and engagement information
- `styles.css` - Shared styling for all pages

## Editing

Update page content directly in the HTML files. All pages share the same stylesheet for consistent branding.

## Preview

Open any HTML file in a browser, or host using a local static server:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

## Custom domain setup

A `CNAME` file has been added with the custom domain:

```text
truvionadvisory.com
```

To publish on GitHub Pages:

1. Create a GitHub repository and push these files.
2. In repository settings, enable GitHub Pages from the main branch and root directory.
3. Confirm the custom domain is set in GitHub Pages settings or by the `CNAME` file.
4. Configure DNS for `truvionadvisory.com`:
   - A records to GitHub Pages:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - CNAME record for `www` pointing to your GitHub Pages domain.
