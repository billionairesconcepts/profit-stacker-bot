# Profit Stacker Bot landing page — GitHub Pages package

This folder is ready for free static hosting on GitHub Pages.

## Files

- `index.html` — the full landing page.
- `CNAME.example` — optional custom-domain helper. Rename to `CNAME` only when your DNS is ready.

## Fast GitHub Pages setup

1. Create a new GitHub repository, for example:
   `profit-stacker-ea`
2. Upload the contents of this folder into the repository root:
   - `index.html`
   - optionally `CNAME` later
3. Go to the repository:
   `Settings → Pages`
4. Under `Build and deployment`, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save.

GitHub will publish the site at a URL like:

`https://your-github-username.github.io/profit-stacker-ea/`

## Optional custom subdomain

If you want:

`olivervelez-inspiredbot.myotherdomain.com`

then:

1. Create a DNS `CNAME` record at your domain provider:
   - Name/Host: `olivervelez-inspiredbot`
   - Target: `your-github-username.github.io`
2. Rename `CNAME.example` to `CNAME`
3. Keep only this inside the `CNAME` file:

`olivervelez-inspiredbot.myotherdomain.com`

4. Upload/commit the `CNAME` file to GitHub.
5. In GitHub repository `Settings → Pages`, set the custom domain.

## Notes before publishing

- Replace the MT5 Marketplace button placeholder with your actual MQL5 product URL once approved.
- Keep the risk warning visible.
- Do not use Oliver Velez’s face, thumbnails, videos, or logo unless you have permission.
- The page may reference Oliver Velez as inspiration, but it should not claim official endorsement unless he grants one.
