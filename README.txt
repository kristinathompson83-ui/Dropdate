DROPDATE — GitHub Pages installation (12 October 2026)

The website files are in this folder. Upload the files themselves into your GitHub repository, not this ZIP file.

1. Sign in at https://github.com (or create an account).
2. Open https://github.com/new
3. Repository name: dropdate
4. Visibility: Public (free GitHub Pages).
5. Create repository.
6. In the repository, select Add file > Upload files.
7. Upload the 6 website files from this folder directly into the repository root:
   index.html
   manifest.webmanifest
   sw.js
   icon-192.png
   icon-512.png
   .nojekyll (optional, hidden file)
   Do not upload a surrounding folder; index.html must be at the top level.
8. Commit changes.
9. Repository Settings > Pages > Build and deployment > Source: Deploy from a branch.
10. Branch: main; folder: /(root); Save.
11. Your site address will be:
    https://YOUR-GITHUB-USERNAME.github.io/dropdate/
    Replace YOUR-GITHUB-USERNAME with your own username.
12. Wait a few minutes for the site to appear. GitHub Pages Settings will show the live address.
13. On RAWG's API-key application page, enter this published https://... URL in the Website URL field.
14. Open the live Dropdate site > Set up > paste the API key > Save & refresh.

Note: The RAWG API key must NOT be placed in your public GitHub repository. The supplied files do not include your key. Dropdate saves the key in browser storage on your own device.
Note: Existing wishlists from a different file/URL will not automatically transfer to this published site. Re-add the saved titles there.
Note: Data refresh happens at most once per day while the app is opened; there are no background notifications while it is closed.
Note: A RAWG link is included in the app for attribution.

For help, see: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
