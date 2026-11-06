# James Lennox — Web Design & Development Portfolio

A multi-page responsive portfolio for INFO1005 Website Design, based on the supplied Marge Simpson starter template and customised for James Lennox.

## Pages

- `index.html` — Home and introduction
- `about.html` — About and design approach
- `resume.html` — Education, employment, developing skills and PDF download
- `portfolio.html` — Academic/concept project gallery with Bootstrap modal lightbox
- `contact.html` — Contact details and client-side demonstration form

## Technology

- Semantic HTML5
- Bootstrap 5.3.3 and Bootstrap Icons (CDN)
- Custom CSS and responsive breakpoints
- Google Fonts: Space Grotesk and DM Sans
- JavaScript: theme switch, typewriter heading, portfolio lightbox and form validation

## Run locally

Open `index.html` in a browser. For best results, run a local static server from this folder (for example, `python -m http.server 8000`) and visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a new public GitHub repository, for example `james-lennox-portfolio`.
2. Upload the **contents** of this folder to the repository root (so `index.html` is at the root, not inside another folder).
3. Commit the files to the `main` branch.
4. In the repository, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source.
5. The included `.github/workflows/deploy.yml` deploys the site after a push to `main` (or when manually triggered from Actions).
6. Wait for the Pages deployment to complete. Copy the published URL and test every page and download link.

## Before submitting

- Confirm James's exact job title and duties at Silverwood Industries; currently only the employer and three-year duration are stated.
- Confirm the Diploma of Social Science wording and current enrolment details.
- Replace the illustrative project concept images with screenshots of James's own work where available. The existing images are labelled as concepts and must not be presented as client projects.
- Complete HTML and CSS validation using the W3C validators.
- Test the published site in current Chrome and Firefox at phone, tablet and desktop sizes.
- Complete two genuine peer reviews and the reflection form. Do not fabricate feedback.
- Submit the ZIP and live URL through vUWS.

See `QA-TESTING.txt` for the checks completed and remaining manual steps.
