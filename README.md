# Elmwood Community Coalition — website

A basic, static informational website: three files (`index.html`,
`styles.css`, `script.js`), no build step, ready for GitHub Pages.

## Customize it

All the placeholder content — org name, mission text, programs, stats,
address, phone, email — lives in `index.html`. Colors and fonts are set
as CSS variables at the top of `styles.css` (in `:root`), so you can
re-theme the whole site by editing a handful of values there.

## Deploy on GitHub Pages

1. Create a new GitHub repository (or use an existing one).
2. Add these three files to the **root** of the repository (or to a
   `/docs` folder — see step 4).
3. Commit and push them to the `main` branch.
4. In the repository, go to **Settings → Pages**.
   - Under "Build and deployment," set **Source** to "Deploy from a
     branch."
   - Set **Branch** to `main` and the folder to `/ (root)` (or
     `/docs`, if that's where you placed the files).
   - Click **Save**.
5. GitHub will publish the site at:
   `https://<your-username>.github.io/<repository-name>/`
   (it usually takes a minute or two to go live after the first save).

### Using a custom domain (optional)

Add a file named `CNAME` to the same folder as `index.html`, containing
just your domain (e.g. `www.elmwoodcoalition.org`), then point your
domain's DNS at GitHub Pages following
[GitHub's custom domain guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

## Notes

- No dependencies or build tools — just static HTML/CSS/JS, so it
  works as-is with GitHub Pages.
- Fonts (Fraunces, Work Sans) load from Google Fonts via a `<link>` in
  `index.html`.
- The map and hero graphics are hand-drawn inline SVG, not photos, so
  there's nothing extra to host or replace unless you want real
  photography.
