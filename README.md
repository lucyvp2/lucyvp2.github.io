# lucy-berry.github.io

Static portfolio site for Lucy Berry. Plain HTML and CSS, no JavaScript. No build step, no frameworks, no third-party requests (fonts are self-hosted).

## Deploy to GitHub Pages

1. Create a public repository named exactly `<github-username>.github.io` (for example `lucyberry.github.io`). This makes it a user site served at the root URL.
2. Upload the contents of this folder to the repository root, including the hidden `.nojekyll` file.
3. In the repository, go to Settings > Pages. Under "Build and deployment", set Source to "Deploy from a branch", Branch to `main`, folder `/ (root)`, and save.
4. The site will be live at `https://<github-username>.github.io/` within a few minutes. Tick "Enforce HTTPS" once it is available.
5. Update the `og:url` meta tag in `index.html` to the live URL.

If you use a different repository name (a project site at `username.github.io/repo/`), the main page works as is, but edit the root-relative paths in `404.html` to start with `/repo/`.

## Editing content

All content lives in `index.html`. Colors are defined once at the top of `assets/css/style.css`.

## Before publishing

- Remove anything that identifies a client, engagement, or internal tool, including in linked write-ups and screenshots.
- The résumé button links to `resume.pdf`. Upload a web version without the phone number, or delete the button.
- Strip metadata from the résumé PDF (author, company, file paths) before uploading.
- Consider a dedicated contact address rather than a personal or work email, since anything on a public page will be scraped.

## Files

- `index.html` main page
- `404.html` not-found page
- `assets/css/style.css` all styling, and the color palette
- `assets/fonts/` Schibsted Grotesk and JetBrains Mono, both under the SIL Open Font License
- `assets/img/favicon.svg` site icon
