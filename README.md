# Bioinformatics Basics - Test Site

Simple educational article about bioinformatics for SEO indexing test.

## Purpose

Test site to check if educational content in bioinformatics niche gets indexed by Google/Bing.

## Quick Deployment to GitHub Pages

1. **Create repository on GitHub:**
   - Go to: https://github.com/new
   - Repository name: `bioinfo-basics-test`
   - Make it **Public**
   - Click "Create repository"

2. **Push files to GitHub:**
   ```bash
   cd C:\dev\bioinfo-basics-test
   git init
   git add .
   git commit -m "Initial commit - SEO test site"
   git branch -M main
   git remote add origin https://github.com/gorelikspb/bioinfo-basics-test.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to repository Settings → Pages
   - Source: "Deploy from a branch"
   - Branch: `main` / folder: `/ (root)`
   - Click Save

4. **Site will be available at:**
   `https://gorelikspb.github.io/bioinfo-basics-test/`

## Testing Indexing

1. **Google Search Console:**
   - Add property: `https://gorelikspb.github.io/bioinfo-basics-test/`
   - Verify ownership
   - Submit sitemap: `sitemap.xml`
   - Request indexing via URL Inspection

2. **Bing Webmaster Tools:**
   - Add site: `https://gorelikspb.github.io/bioinfo-basics-test/`
   - Verify ownership
   - Submit sitemap: `sitemap.xml`

3. **Check in 3-5 days:**
   - Search: `site:gorelikspb.github.io/bioinfo-basics-test`
   - Compare with main site behavior

## Notes

- This is a diagnostic tool, not a production site
- Educational content (article), not a tool (doesn't duplicate main site)
- Simple structure to test indexing capabilities

