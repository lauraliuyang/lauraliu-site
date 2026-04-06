# Yang (Laura) Liu Academic Website

Static personal academic website for GitHub Pages.

## Files

- `index.html` - Home page
- `research.html` - Research page
- `404.html` - Custom not-found page
- `styles.css` - Site styles
- `.nojekyll` - Disables Jekyll processing on GitHub Pages
- `CNAME` - Custom domain configuration for GitHub Pages
- `robots.txt` - Search crawler instructions
- `sitemap.xml` - Search index hints for the custom domain

## Local preview

Open `index.html` in a browser, or run a simple static server from this folder.

## Deployment

1. Push this repository to GitHub.
2. In the repository settings, enable GitHub Pages from the active publishing branch and the root folder.
3. If the repository branch is still `master`, GitHub Pages should be set to `master / root`.
4. The site is configured for the custom domain `lauraliu.net`.
5. Keep the `CNAME` file committed so the custom domain remains attached after future deploys.

## DNS checklist

- Apex domain A records should point to GitHub Pages:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- `www` should be a CNAME to `lauraliuyang.github.io`
- HTTPS in GitHub Pages may remain pending until DNS changes fully propagate

## Notes

- The domain registration can remain with Wix even if the Wix site plan is canceled.
- If the branch is later renamed from `master` to `main`, update the GitHub Pages source in repository settings.
