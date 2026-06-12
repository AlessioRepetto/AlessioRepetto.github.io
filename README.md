# Alessio Repetto — GitHub Pages personal site

Static one-page personal website for GitHub Pages.

## Structure

```text
.
├── index.html
├── style.css
├── README.md
└── assets/
    ├── profile.jpg
    ├── chatgpt-memory-gdpr.png
    ├── chatgpt-memory-network.png
    ├── air-quality-pm25.png
    ├── air-quality-shap.png
    ├── la-parola-data-header.png
    ├── automated-press-review-logo.png
    └── ADD_CV_PDF_HERE.txt
```

## How to publish on GitHub Pages

1. Create a public repository named `AlessioRepetto.github.io`.
2. Upload all files from this folder to the root of the repository.
3. Export your CV as PDF and save it as:

```text
assets/Alessio_Repetto_CV.pdf
```

4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. After a few minutes, the site should be available at:

```text
https://AlessioRepetto.github.io
```

## Notes

- The public phone number is intentionally not included.
- The CV button points to `assets/Alessio_Repetto_CV.pdf`; add that file before publishing or remove the button temporarily.
- The site uses plain HTML and CSS, with no framework and no build step.
- The visual style uses the palette: `#355C7D`, `#8C2F39`, `#6A9A86`, warm white and dark grey.
