# Hotel Savoy Website

A responsive, static 5-page website built for GitHub Pages / Cloudflare Pages.

## Pages
- `index.html` — Home
- `about.html` — About Us
- `menu.html` — Searchable, category-based menu with dish details, representative photos and WhatsApp enquiry
- `privacy-policy.html` — Privacy Policy starter copy
- `contact.html` — Contact details and email-app contact form

## Deploy to Cloudflare Pages
1. Extract this ZIP.
2. Push the contents of this folder to a GitHub repository (keep `index.html` in the repository root).
3. In Cloudflare Dashboard, open Workers & Pages → Create → Pages → Connect to Git.
4. Select the repository. Framework preset: **None**. Build command: leave blank. Build output directory: `/` (or `.` depending on the UI).
5. Deploy.

## Before going live
- Confirm all menu prices and spellings against the original PDF. Some entries in the PDF are image-only and OCR can be imperfect.
- Confirm business address, opening hours, ordering/delivery options and contact details.
- The website uses externally hosted Unsplash food photos; an internet connection is needed to load them.
- Contact form opens the visitor's email app; it is not a server-side form.
- Review the privacy policy for the actual tools and legal requirements applicable to the business.
