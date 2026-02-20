# Personal Website

Minimal personal website showcasing bio, publications, and portfolio.

## Structure

- `index.html` - Main HTML file
- `styles.css` - Stylesheet
- `README.md` - This file

## Adding Content

### Publications

Add publications to the `#publications` section in `index.html` using this format:

```html
<div class="publication-item">
    <h3>Publication Title</h3>
    <p class="authors">Author 1, Author 2, <strong>G. Parra</strong>, Author 3</p>
    <p class="venue">Journal/Conference Name, Year</p>
    <a href="#" class="link">PDF</a> | <a href="#" class="link">DOI</a>
</div>
```

### Portfolio Projects

Add projects to the `#portfolio` section in `index.html` using this format:

```html
<div class="project-card">
    <h3>Project Name</h3>
    <p class="project-description">Brief description of the project.</p>
    <div class="project-links">
        <a href="#" class="link">GitHub</a>
        <a href="#" class="link">Demo</a>
    </div>
</div>
```

### Contact Information

Update the contact links in the `#contact` section with your actual email, LinkedIn profile, and other relevant links.

## Deployment

This repository is set up for GitHub Pages. Simply push your changes to the main branch, and the site will be available at `https://gerardoparra.github.io`.
