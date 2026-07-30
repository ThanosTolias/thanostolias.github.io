# Thanos Tolias — Academic Homepage

A minimal, dependency-free academic homepage for GitHub Pages.

## Replace the profile photo

Replace `assets/profile.jpg` with your own square image, keeping the same filename. A resolution of at least 600 × 600 pixels is recommended.

## Preview locally

You can open `index.html` directly in a browser. For a closer approximation of GitHub Pages, run a local server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a GitHub repository. For the shortest URL, name it `<your-github-username>.github.io`.
2. Upload all files in this folder to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then save.

GitHub will display the public URL after deployment.

## Editing the page

- Main content: `index.html`
- Colors, spacing, typography, and mobile layout: `style.css`
- Profile image: `assets/profile.jpg`
- Browser icon: `assets/favicon.svg`

The site uses no JavaScript, framework, package manager, or external font service.
