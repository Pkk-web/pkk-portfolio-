# PKK — Personal Developer Portfolio

A responsive, static portfolio website for Paul Kamau Kaigai, built with HTML, CSS and vanilla JavaScript.

## Run locally

No build tools or package installation are required.

1. Extract the project.
2. Open the folder in VS Code.
3. Open `index.html` in your browser, or use the VS Code Live Server extension.

## Project structure

```text
pkk-portfolio/
├── index.html
├── styles.css
├── script.js
├── README.md
├── vercel.json
└── assets/
    ├── docs/
    │   └── .gitkeep
    └── images/
        ├── favicon.svg
        └── social-preview.svg
```

## Before publishing

- Replace `YOUR_EMAIL@example.com` in `index.html` with the professional email address you want to publish.
- Add a reviewed PDF CV to `assets/docs/` and add a visible download link.
- Confirm certificate names, issuers and dates against the original certificates.
- Add direct project repository/demo links only after checking that each is public and ready.
- Consider adding a professional headshot if desired; the current design uses an abstract visual instead.
- Check all content and links on desktop and mobile.

## Deploy to GitHub and Vercel

1. Create a GitHub repository, for example `pkk-portfolio`.
2. Upload/push the contents of this folder to the repository root.
3. In Vercel, choose **Add New → Project**, import the GitHub repository and deploy.
4. Framework preset: **Other**. Build command: leave blank. Output directory: `.`.
5. After deployment, test the live site on mobile and desktop.

This is a static site; it does not require a server or environment variables. The contact action currently opens the visitor's email application using a `mailto:` link. A real form submission workflow can be added later if needed.
