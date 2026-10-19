# Brentley Dorsainvil, personal site

Plain static HTML and CSS. No build step and no dependencies.

## Files
- `index.html`: home page (hero, Meet the Creator, Projects, Experience, Contact)
- `notify.html`, `pooh.html`, `sentinel.html`: project detail pages
- `assets/headshot.jpg`: hero photo
- `assets/Brentley_Dorsainvil_Resume.pdf`: resume opened by the Resume buttons

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

## Host it
- **Vercel:** `npx vercel` in this folder, or import the GitHub repo at vercel.com/new (framework: Other).
- **Netlify:** drag this folder onto app.netlify.com/drop.
- **GitHub Pages:** push to a repo, then Settings > Pages > deploy from the main branch.

## Common edits
- Swap the photo: replace `assets/headshot.jpg` (4:5 ratio works best).
- Update the resume: replace `assets/Brentley_Dorsainvil_Resume.pdf` with the same file name.
- Colors: yellow `#FFD84D`, pink `#FF8FB1`, blue `#7CC8FF`, ink `#111`.
- Fonts load from Google Fonts: Anton, Lilita One, Nunito, Space Mono.
