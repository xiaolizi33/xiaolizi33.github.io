# Shiyi Li — Academic Homepage

A responsive, buildless academic homepage based on the supplied CV. Edit `index.html` for content and `style.css` for appearance. No package installation is required.

## Preview

Run `python3 -m http.server 8000` from this directory and open http://localhost:8000.

## Publish to GitHub Pages

1. Create a repository named `<your-github-username>.github.io` on GitHub.
2. Push this directory to the repository's `main` branch.
3. Open **Settings → Pages → Build and deployment**, and select **GitHub Actions** as the source.
4. Run the **Deploy GitHub Pages** workflow, or push a new commit. The site will be available at `https://<your-github-username>.github.io/` after deployment.

The workflow uploads `index.html`, `style.css`, and the selected publication image. The original CV is not included in the deployed website. Do not upload the original CV to a public repository unless you intend to expose its personal information.

Paper status and dates reproduce the supplied CV; update them when they change. The name is romanized as “Shiyi Li”. No unverified publication links or social profiles are included.
