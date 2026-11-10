# ZA CMA Learning Hub

An independent digital learning workspace for CMA students. The project is provided as a **single-page, self-contained HTML application** and can be hosted with GitHub Pages.

## Features

- Student learning workspace and course navigation
- Study resources and practice tools
- Progress tracking saved in the browser
- Theme preference support
- AI teacher integration that requires the student to configure their own supported API credentials in the app settings
- Browser-based storage using IndexedDB, with localStorage/memory fallback where supported

> **Important:** This repository contains the website front end. Browser-stored data (such as a student's progress and locally saved content) is not automatically shared between devices or users and is not included in GitHub. AI features may require a separately configured API key and may incur charges from the provider.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. For the most reliable experience, serve the folder through a local web server rather than opening the file directly.

Example using Python:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy with GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html` and `README.md` to the repository's root folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the site. Your website URL will appear in the Pages settings.

## Updating the website

Replace the repository's `index.html` with your latest version and commit the change. GitHub Pages will publish the update automatically after the deployment completes.

## Security and privacy notes

- Do not commit private API keys, passwords, student records, or other secrets to a public repository.
- Anyone can view the source code of a public GitHub Pages website. A password screen in a browser-only HTML app should not be treated as server-side security.
- User data stored in the browser remains in that browser unless the application provides a separate export or sync feature.

## Project details

- **Project:** ZA CMA Learning Hub
- **Format:** Single-file HTML application
- **Main entry point:** `index.html`
- **Author credit in application:** Zaid Alam

## Disclaimer

This is an independent educational project and is not an official website of ICMA or any other professional accounting body. Course names, marks, and third-party services remain the property of their respective owners.
