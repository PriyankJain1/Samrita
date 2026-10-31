# For Samrita ♡
A dreamy, romantic static website made with HTML, CSS, and JavaScript. No build tools required.

## Publish on GitHub Pages
1. Sign in at https://github.com and create a **public** repository named `for-samrita`.
2. Upload `index.html`, `style.css`, `script.js`, and the `photos` folder to the **root** of the repository (not a nested `for-samrita` folder). Commit the files.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**. Select branch `main` and folder `/ (root)` and click **Save**.
5. Once GitHub finishes publishing, visit `https://YOUR-USERNAME.github.io/for-samrita/` (replace `YOUR-USERNAME`). Publishing can take a few minutes.

## Personalize
- **Photos:** Place four JPG files in `photos/`, named `1.jpg`, `2.jpg`, `3.jpg`, `4.jpg`. Until then, the site displays illustrated placeholders.
- **Love letter:** Edit the text inside `<div class="letter-paper">` in `index.html`. Change the signature to your own name.
- **Timeline:** Edit the headings and descriptions in `<section id="story">` in `index.html`. Replace generic chapters with real dates and moments.
- **Surprise:** Edit the text in `<div id="surprise-reveal">`.
- **Colors:** Adjust CSS variables at the beginning of `style.css`.

## Notes
- The website is public to anyone with its URL; do not upload photos or private details without consent.
- Google Fonts requires internet access. The site otherwise works without external libraries.
- Photo filenames are case-sensitive on GitHub Pages. Use exactly `1.jpg`, etc.
