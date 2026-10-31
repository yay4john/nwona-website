# NWONA website preview

This repository hosts a free static website prototype for the Northwest Olympia Neighborhood Association.

## Hosting with Cloudflare Pages
1. Open Cloudflare Dashboard > Workers & Pages > Create > Pages > Connect to Git.
2. Choose GitHub and `yay4john/nwona-website`.
3. Select production branch `main`, framework preset **None**, leave build command blank, and set output directory `/`.
4. Deploy and review the resulting `*.pages.dev` URL before connecting the association's domain.
5. Keep existing WordPress hosting running until content, payment links, and newsletter signup are migrated and tested.

## Editing
This initial version is a single self-contained `index.html`. Edit copy and presentation there. An `events` array near the bottom controls dated announcements; events no longer show after their end date.

## Migration checklist
- Confirm association contact details, board roster, and event dates.
- Migrate legally authoritative bylaws, downloadable PDFs, news archives, and photos from the original website.
- Replace temporary links to the existing website with verified PayPal donation and newsletter subscription URLs.
- Verify mobile and keyboard accessibility; check all links.
- Add redirects for old URLs if necessary.
- Set up organizational ownership/succession documentation.

**Do not cancel WordPress or move the production domain yet.** This is a preview, not a complete archived copy of the original website.