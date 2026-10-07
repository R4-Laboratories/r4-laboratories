# R4 Laboratories

A responsive, dependency-free website built with HTML and CSS.

## Preview locally

From the repository root, run:

```sh
python3 -m http.server 8000 --directory site
```

Then open <http://localhost:8000>. Edit `site/index.html` for content and
`site/styles.css` for styling. No package installation or build step is needed.

## Publish on GitHub Pages

1. In the repository's **Settings → Pages**, select **GitHub Actions** as the
   source under **Build and deployment**.
2. Merge the website into `main`. The **Deploy website to GitHub Pages** workflow
   publishes the `site` directory automatically on each push to `main`.
   You can also run it manually from the **Actions** tab, selecting `main`.
3. Once deployment succeeds, visit
   <https://r4-laboratories.github.io/r4-laboratories/>.

The workflow's `github-pages` environment also links to the deployed website.
