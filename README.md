# Pro Joinery & Renovation — Vercel-ready website

## Before publishing
1. Replace the dummy phone number in `index.html`.
2. Replace the dummy email address.
3. Confirm the service-area wording.
4. Replace gallery placeholders with your real project photos.
5. If you have your logo, replace the PJR text mark later.

## Gallery photos
Create an `images` folder. Add compressed JPG/WebP files, ideally under about 500 KB each.

Replace:
`<div class="placeholder">Project photo 1</div>`

with:
`<img src="/images/renovation-1.webp" alt="Renovation project by Pro Joinery & Renovation">`

## Fastest Vercel deployment
1. Sign in to Vercel.
2. Open `vercel.com/drop`.
3. Drag the website folder or ZIP onto the page.
4. Choose the project name and deploy.
5. Check the generated `*.vercel.app` site.
6. Open the project → **Settings → Domains**.
7. Add `projoineryandrenovation.co.uk`.
8. Vercel will display the exact DNS records required at your domain registrar.
9. Add those DNS records at the registrar.
10. Add `www.projoineryandrenovation.co.uk` too, and redirect one version to the other.
11. Wait until Vercel shows **Valid Configuration**.

## Better long-term setup
Use GitHub:
1. Create a repository, for example `projoineryandrenovation`.
2. Upload these files.
3. Vercel → **Add New → Project** → import that repository.
4. Deploy.
5. Every future GitHub update automatically triggers a new Vercel deployment.

## After launch
- Add the website to Google Business Profile.
- Add real job photos.
- Ask previous customers for Google reviews.
- Set up Google Search Console.
- Later create location/service pages for searches such as `joiner Peebles`, `property maintenance Scottish Borders`, etc.
