# Birthday Surprise ❤️

A simple, mobile-friendly interactive birthday mini-website.

## Run locally
Use VS Code with the Live Server extension, or run a small static server from this folder:

```sh
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Customize
Open `birthday-config.json` and edit:
- `recipientName`
- `birthdayMessage`
- The three mystery card icons, titles, and descriptions

The site stores the chosen card in the browser after selection. After the other surprises are revealed, there is no reset button and the closed-card view will not return on that same browser.

Open `index.html` and edit only if you want to change:
- Colors and fonts in the `<style>` section

## Publish with GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` (and this README).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. GitHub will provide the public website URL.

Tip: Send only the GitHub Pages URL to your wife. ❤️
