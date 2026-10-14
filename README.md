# Blanca Asensio — Personal Portfolio

A responsive static portfolio, written in plain HTML, CSS and a few lines of JavaScript. No build tools, subscriptions or frameworks required.

## Preview

Open `index.html` in a browser. The project cards link to two separate case-study pages. The CV button downloads the PDF included in `assets/`.

For a local web server, run `python3 -m http.server 8000` from this folder and visit http://localhost:8000.

## Files

- `index.html`: home page
- `document-automation.html`: document automation case study
- `mortgage-refinancing.html`: refinancing case study
- `styles.css`: all styling and responsive layouts
- `script.js`: mobile menu
- `assets/Blanca_Asensio_CV.pdf`: existing exported CV

## Publish on GitHub Pages

1. Create a public GitHub repository (for example `portfolio`).
2. Upload the contents of this folder to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**, `main`, and `/ (root)`.
4. Once deployed, GitHub shows the published URL. You can later attach a custom domain.

## Publish on Vercel

Import a GitHub repository containing these files into Vercel as a static project. No framework or build command is needed.

## Before publishing

- Review project descriptions and metrics for employer confidentiality. Some information in the portfolio may not be appropriate to publish without approval.
- Replace `assets/Blanca_Asensio_CV.pdf` when you have a final CV. The included PDF is the existing three-page export.
- Add your GitHub profile URL if you want a GitHub button; none has been guessed.
- Confirm the LinkedIn URL and email address are correct.
- All content and styling can be edited directly in the HTML and CSS files.


## Rediseño editorial

La portada ahora incluye la fotografía corporativa `assets/blanca-portrait.png`, una sección de fotografía con enlace a Instagram (@byblancaat), nueva tipografía y una paleta verde salvia/crema. El sitio no depende de frameworks. Las fuentes web requieren conexión; hay fuentes alternativas locales.

## Public confidentiality check

Project cards and case studies intentionally do not identify ING as the client/employer. The experience timeline still names ING as a past/current employer. Before publication, review the project descriptions, metrics and domain details for confidentiality; removing the employer name alone does not ensure anonymity. The downloadable CV also names ING.
