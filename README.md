# Athlete Mastersheet — GitHub Pages website

This folder contains a **self-contained static website** based on the supplied Athlete Mastersheet Overview HTML export. It requires no server, database, build step, or external dependencies.

## Publish on GitHub Pages

1. On GitHub, create a new repository named `athlete-mastersheet` (or another preferred name).
2. Upload `index.html` and `.nojekyll` into the top level of the default (`main`) branch. `README.md` can also be uploaded.
3. Open **Settings → Pages → Build and deployment**.
4. Choose **Deploy from a branch**, set **Branch: main** and **Folder: /(root)**, then save.
5. When publishing finishes, visit `https://YOUR-USERNAME.github.io/athlete-mastersheet/` (adjust the repository name if different). If the repository belongs to an organization, replace `YOUR-USERNAME` with the organization name.

Your website will stay online while you keep the repository and Pages enabled, subject to GitHub's hosting policies. GitHub Pages provides HTTPS and can also use a custom domain.

## Important: privacy and content

**The page contains athlete names, contract and commercial terms, campaign performance details and social links. GitHub Pages websites are public to internet visitors, including when the source repository is private on supported plans.** Do not publish the supplied content without authorization from the relevant data owners. A private or password-protected portal is a safer choice if this data is confidential.

## Updating the dashboard

This is a static snapshot. To refresh the data or layout, generate a new self-contained HTML export, rename it to `index.html`, commit the file to the `main` branch, and GitHub Pages will redeploy automatically. The page does not sync with a spreadsheet and does not save edits to a backend.

## Website files

- `index.html` — full website, including embedded fonts, scripts, and dashboard data.
- `.nojekyll` — skip Jekyll processing for a plain static-site deployment.
- `README.md` — publishing and maintenance instructions.

Source export: `Athlete Mastersheet Overview (standalone).html`. Dashboard data as of **23 October 2026**.
