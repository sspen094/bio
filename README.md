# Sam Spencer Portfolio

A responsive static portfolio site for GitHub Pages. It has no build step and no external dependencies.

## Preview locally

From this directory, run:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a GitHub repository. For a profile site, name it `<your-github-username>.github.io`.
2. Copy the files in this directory to the repository root.
3. Commit and push them to the `main` branch.
4. In the repository, open **Settings > Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**, then choose `main` and `/ (root)`.

GitHub will show the published URL after the deployment finishes.

## Add project links later

When project repositories are public, add an anchor inside the relevant `.project-card` in `index.html`. Use the repository name as the link text and include `target="_blank" rel="noreferrer"` for external links.
