# MarketMaster - Responsive Website

This small site demonstrates a responsive layout implemented with a mobile-first CSS approach and several breakpoints.

Breakpoints implemented

- Mobile: up to 600px — stacked layout, navigation becomes vertical, hero and cards stack.
- Small devices: up to 420px — slight typography and spacing reductions.
- Tablet: 801px to 1024px — moderate adjustments (smaller hero heading, tighter card widths).
- Desktop: 1025px and above — original layout with multi-column sections.

How to test locally

1. Open `index.html` in a browser, or run a local static server (Python):

```bash
# from the project folder
python3 -m http.server 8000
# then visit http://localhost:8000
```

GitHub Pages deployment

1. Make sure your repo has a remote on GitHub (e.g. `origin`).
2. Commit and push the `main` branch or create a `gh-pages` branch.
3. In your GitHub repository settings, enable GitHub Pages from the chosen branch (usually `main` or `gh-pages`).
4. Wait a minute and your site will be available at `https://<your-username>.github.io/<repo-name>/`.

Notes

- I kept a mobile-first approach and added medium and small breakpoints.
- If you want an automatic workflow to build and publish on push, I can add a GitHub Actions workflow to deploy to `gh-pages`.
