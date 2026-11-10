# ZA CMA Learning Hub

A standalone, single-file HTML learning platform for CMA students.

## Files
- `index.html` — the complete web application. The app is bundled into this file; no build step is required.
- `.nojekyll` — tells GitHub Pages not to process the site with Jekyll.

## Publish with GitHub Pages
1. Create a new repository on GitHub, for example `za-cma-learning-hub`.
2. Upload `index.html`, `README.md`, and `.nojekyll` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. Wait for GitHub Pages to finish publishing. The public website URL will appear in the Pages settings.

## Important notes
- This is a standalone client-side HTML app. Student progress and settings that use browser storage remain on that browser/device unless a separate sync/backend service is implemented.
- AI features require a supported provider API key and internet access unless configured otherwise in the app.
- Do not put a private API key directly into a public GitHub repository. Anyone who can view the source can retrieve it. Each user should enter their own key, or use a properly secured server-side AI gateway.
- The app includes developer contact information in its About section. Review that information before publishing the repository publicly.
- Student password/feature controls implemented only in front-end HTML should not be treated as tamper-proof security. Strong authentication, authorization, shared accounts, and centralized student data require a secure backend.
- This is an independent educational project and is not an official ICMAP/ICMA International website or an endorsed platform.
