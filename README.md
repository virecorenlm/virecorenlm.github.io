# Ryan Shorette — GitHub Pages Portfolio

A responsive portfolio showcasing four verified public projects. Plain HTML, CSS, and JavaScript; no build step or dependencies.

## Publish on GitHub Pages

1. Sign in to GitHub as `virecorenlm`.
2. Create a **public** repository named **virecorenlm.github.io**. If that repository already exists, review its contents before replacing anything.
3. Extract this ZIP. Upload the files **inside** the `portfolio` folder to the repository root. `index.html` must be at the root, not inside an extra folder.
4. Open repository **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**. Select **main** and **/(root)**, then save.
6. Wait for the deployment to finish. Your portfolio address is https://virecorenlm.github.io/.

If your account uses different UI labels, consult https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site.

## Preview locally

From the extracted folder:

```bash
cd portfolio
python3 -m http.server 8000
```

Open http://localhost:8000. On Windows use `py -m http.server 8000`.

## Edit

All content and styling are in `index.html`. Update project copy, links, or colors there. Project filters and expandable details work without a backend. Contact links point to your GitHub profile; no email address is published.

The project illustrations are explicitly labeled conceptual architecture flows. They are not screenshots or live system status. Replace them with genuine screenshots when available, with descriptive alternative text. Repository descriptions were checked against public READMEs on October 6, 2026. No private repository contents, credentials, LAN addresses, or household details are included.
