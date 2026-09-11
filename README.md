# Chicago Abundance PAC

A basic, static informational website for a political action
committee: three files (`index.html`, `styles.css`, `script.js`), no
build step, ready for GitHub Pages.

## Customize it

All the placeholder content — committee name, mission text,
priorities, stats, treasurer, FEC ID, and disclosures — lives in
`index.html`. Colors and fonts are set as CSS variables at the top of
`styles.css` (in `:root`), so you can re-theme the whole site by
editing a handful of values there.

## Before this goes live: legal disclosures

Political committee websites are subject to real, binding rules —
this template is a starting point, not legal advice:

- The **"Paid for by..." disclaimer** and **non-tax-deductible
  statement** in the Disclosures section are placeholders. Confirm the
  exact required wording with the FEC (or your state's election
  authority, if this is a state/local committee) or an election-law
  attorney.
- The **FEC ID** in the Disclosures section is a placeholder
  (`C00000000`) — replace it with your committee's actual registration
  number.
- **Contribution collection**: federal law requires collecting donor
  name, address, occupation, and employer for contributions over $200,
  and enforces contribution limits and source restrictions (e.g., no
  corporate or union treasury funds for many committee types). This
  site has no working donation form or payment processor built in —
  the "Donate" button is a placeholder. You'll need a compliant
  donation processor (e.g., one built for political committees) to
  actually collect contributions.
- Rules differ for connected PACs, non-connected PACs, and Super PACs,
  and for federal vs. state/local committees — make sure the copy
  ("accepts contributions from individuals only," etc.) matches your
  committee's actual type and registration.

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
just your domain (e.g. `www.brightlinepac.org`), then point your
domain's DNS at GitHub Pages following
[GitHub's custom domain guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

## Notes

- No dependencies or build tools — just static HTML/CSS/JS, so it
  works as-is with GitHub Pages.
- Fonts (Spectral, Inter) load from Google Fonts via a `<link>` in
  `index.html`.
- The seal and map-style graphics are hand-drawn inline SVG, not
  photos, so there's nothing extra to host or replace unless you want
  real photography.
