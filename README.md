# Cary Suneja, PhD — Personal Website

A professional, responsive GitHub Pages site built in plain HTML and CSS.

## Files
- `index.html`: homepage and headshot placeholder
- `about.html`: personal and professional background
- `projects.html`: featured projects, publications, volunteer work
- `education.html`: academic credentials and teaching experience
- `contact.html`: email and phone
- `style.css`: sitewide Calibri-first typography, green palette, navigation, and responsive layout

## Publishing
In GitHub, open **Settings → Pages** and select **Deploy from a branch**, branch `main`, folder `/ (root)`. The site should then be available at https://carysuneja.github.io/ .

## Adding a headshot
The homepage deliberately contains a headshot placeholder. To add a photo:
1. Upload a photo to `assets/headshot.jpg` (create the folder if needed).
2. In `index.html`, replace the inner `<div class="portrait-placeholder">…</div>` with:
   `<img src="assets/headshot.jpg" alt="Cary Suneja portrait">`
3. Commit the change.

The source DOCX contains a photo; it may be reused for the headshot if desired. Consider cropping for a professional portrait.

## Content
Based on the supplied career biography and project descriptions. The 2027 FSG rollout and publications are described as planned rather than completed. Contact information is public on the Contact page; remove it if you prefer privacy.

## Typography
The first-choice font is **Calibri**. Browsers without Calibri installed will use Carlito, Segoe UI, or Arial.