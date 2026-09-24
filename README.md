# TIS Admin

A static site with no build step, laid out for GitHub Pages.

Open `index.html` in a browser to preview it. From this folder you can also run:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Publish on GitHub Pages

1. Push `main` to GitHub.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then save.

GitHub will publish the site at:

`https://dchavarria-tisadmin.github.io/tisadmin_website_static/`

Keep links and asset paths relative (for example `css/styles.css`, not `/css/styles.css`) so they resolve on that project URL. `.nojekyll` tells Pages to serve the files as-is and skip Jekyll.

Replace the placeholder copy and `hello@example.com` in `index.html` before you share the site.
