# Resume Web Page Deployment

This folder is a static website for the resume page.

## Files

- `index.html`: self-contained resume webpage. Images and PDF data are embedded.
- `.nojekyll`: tells GitHub Pages to serve files directly.

## GitHub Pages

1. Create a public GitHub repository, for example `ike-guo-resume`.
2. Upload `index.html` and `.nojekyll` to the repository root.
3. Open repository `Settings` -> `Pages`.
4. Choose `Deploy from a branch`.
5. Select branch `main` and folder `/root`.
6. The long-term URL will be:

```text
https://<your-github-username>.github.io/ike-guo-resume/
```

If the repository is named `<your-github-username>.github.io`, the URL will be:

```text
https://<your-github-username>.github.io/
```

## Netlify

1. Log in to Netlify.
2. Drag this folder, or upload `resume-pages-site.zip`.
3. Netlify will generate a public URL.
4. Rename the site in Netlify settings if needed.

## Vercel

1. Log in to Vercel.
2. Create a new project from this folder or from a GitHub repo.
3. Use default static site settings.
