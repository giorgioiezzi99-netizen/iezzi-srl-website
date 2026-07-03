# Iezzi Srl Website

Static website for `iezzisrl.com`.

## Workflow

1. Edit the website files in this local folder.
2. Preview locally when needed:

   ```bash
   python3 -m http.server 4173
   ```

   Then open `http://127.0.0.1:4173`.

3. Commit and push changes:

   ```bash
   git add .
   git commit -m "Describe the website change"
   git push
   ```

4. Vercel is connected to the GitHub repository and deploys pushed changes.

## Hosting

- GitHub repository: `giorgioiezzi99-netizen/iezzi-srl-website`
- Vercel project: `iezzi-srl-website`
- Current Vercel URL: `https://iezzi-srl-website.vercel.app`

## Domain

The custom domain `iezzisrl.com` is still managed through Aruba DNS until DNS changes are explicitly approved.

Preserve Aruba email records when changing website records.
