# Lab 01 — Home Page Prototype

A complete, responsive Prabhas fan page using HTML and CSS only. No installation, JavaScript, framework, or build step is required.

## Files

- `index.html`: semantic page structure, navigation, hero, exactly three cards, about section, footer.
- `styles.css`: all styling, CSS Grid, Flexbox, hover/focus states, and mobile breakpoints.
- `assets/prabhas.webp`: supplied photograph, stored locally so deployment does not depend on an image host.

## Test locally

Open `index.html` in your browser. Alternatively, in Codespaces run `python3 -m http.server 8000` in this folder, then open port 8000 using the Ports panel. Resize the browser and check the navigation, hero, and three cards. At phone widths, the cards stack vertically. Navigation and the hero button jump to sections; the card links open relevant Wikipedia pages.

## Publish using GitHub Pages (browser upload)

1. Extract the downloaded ZIP on your computer.
2. Sign in at https://github.com and create a new **public** repository named `lab01-homepage`. Add a README if you want the initial repository ready for uploads.
3. Inside the repository, choose **Add file → Upload files**. Upload `index.html`, `styles.css`, and the `assets` folder from inside the extracted project folder. You can upload this README too. Commit the changes.
4. IMPORTANT: `index.html` must appear at the repository root next to `styles.css`. Do not upload only the ZIP or place everything inside another `lab01-homepage` folder.
5. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Choose **main** and **/(root)**, then **Save**.
6. Wait for deployment. GitHub says publishing can take up to 10 minutes. Open the URL shown in Pages, normally `https://YOUR-USERNAME.github.io/lab01-homepage/`.
7. Submit the live URL and repository URL as required by your instructor.

If Pages shows 404, check that deployment succeeded in Actions and that index.html is at the selected branch root. If the image is missing, check the exact lowercase path `assets/prabhas.webp`.

GitHub guide: https://docs.github.com/en/pages/quickstart

## Using your course's starter repository

This is a standalone implementation because no starter repository or starter HTML/CSS was provided. If the lab requires editing only the supplied CSS, preserve the instructor's HTML, adapt these CSS selectors to its classes, and use the course repository. This project cannot establish compatibility with an unseen starter file.

## Image and content credits

The photograph was supplied by the user as prabhas.webp. The original photographer and license were not supplied; image ownership remains with its respective rights holder. The linked Bing image could not be retrieved; the supplied local image is used instead. The three card graphics are CSS typography, not film posters. This is an unofficial educational fan project and has no affiliation with the actor.

## Personalize and explain your work

Edit the text in index.html and the colors in :root in styles.css. Key concepts: CSS Grid provides the hero and three-card layouts, Flexbox aligns navigation and card contents, object-fit crops the portrait, and media queries adapt the layout to smaller screens. Review these rules before presenting the lab.
