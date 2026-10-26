# Nebula Quest

Nebula Quest is a browser-playable arcade game. The game source remains in
[`Thenebulaquest.html`](./Thenebulaquest.html); the GitHub Pages workflow
publishes it as the website's root page (`index.html`).

## Play on GitHub Pages

1. In the repository settings, open **Pages** and set the build and deployment
   source to **GitHub Actions**.
2. Push a commit to `main`, or run **Deploy game to GitHub Pages** from the
   Actions tab.
3. Open the Pages URL shown in the workflow's deployment summary.

The game uses Tailwind CSS and Google Fonts from their public CDNs, so those
visual assets require an internet connection. Gameplay itself runs in the
browser and does not require a server or backend.
