# Gaia Bianciotto — Research Website

Personal academic website built with Quarto.

## Local preview

1. Install Quarto: https://quarto.org/docs/get-started/
2. Open a terminal in this folder.
3. Run:

```bash
quarto preview
```

## Publish to GitHub Pages

Recommended first-time workflow:

```bash
git init
git add .
git commit -m "Initial research website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
git push -u origin main
quarto publish gh-pages
```

For a root personal site, create the repository as `YOUR_USERNAME.github.io`.

After the first publish, check GitHub repository Settings → Pages and ensure the `gh-pages` branch is selected if GitHub has not selected it automatically.

## Before publishing

- Do **not** add the unpublished manuscript or supplementary PDF.
- Do **not** add unpublished benchmark tables or figures.
- Create a public CV PDF without a phone number before adding it to `assets/`.
- Confirm the manuscript title with coauthors before making the working title public.
- Replace the M2 project placeholder when a strong project is ready.


## Add your profile photo

Place your portrait at:

```
assets/profile.jpg
```

A square or nearly-square head-and-shoulders image works best. The homepage crops it into a circle automatically.

The homepage and navigation already include:

- LinkedIn: https://www.linkedin.com/in/gaia-bianciotto-269056312/
- GitHub: https://github.com/gaiabianciotto
