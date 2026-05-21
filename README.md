# Academic Website

This is a simple academic website designed to work with GitHub Pages.

## Edit your details

Update `index.html` with your:

- Name and role
- Research interests
- Publications
- Teaching
- Email and academic links

Update `styles.css` if you want to change colors, spacing, or typography.

## Add public files

Put public files in the `assets` folder:

- `assets/cv/` for your CV
- `assets/papers/` for papers and preprints
- `assets/teaching/` for syllabi, slides, notes, and other course materials

Then link to them from `index.html`. For example:

```html
<a href="assets/cv/Resume.pdf">Download CV</a>
```

GitHub Pages will publish these files at URLs like:

```text
https://Anand-Dube.github.io/assets/cv/Resume.pdf
```

## Publish with GitHub Pages

1. Create a new GitHub repository named either:
   - `yourusername.github.io` for a personal site at `https://yourusername.github.io`
   - Any repository name, such as `academic-site`, for a project site
2. Push these files to GitHub.
3. In GitHub, open the repository settings.
4. Go to **Pages**.
5. Set the source to the `main` branch and root folder.
6. Save. GitHub will show the public site URL after it builds.

## Local preview

Open `index.html` in a browser to preview the site locally.
