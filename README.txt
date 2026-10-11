CASEYCO.CA — NETLIFY MIGRATION

Snapshot: October 11, 2026. Source commit: 909d49be4456ecb3198e7a649e71ca66014f6bae.

1. Extract this ZIP. Keep the extracted folder as your independent backup.
2. For a manual Netlify deployment, upload the website folder. index.html must be at the upload root.
3. Test the Netlify preview URL before changing domain settings.
4. Check Home, Benefits, Retirement, About Us, Community and Let's talk on desktop and mobile. Check video, images, email and telephone links, Google Calendar booking and The Beacon.
5. Keep caseyco.ca on its current host until the preview works. Domain connection is a later step; preserve email DNS records.

GitHub option: create a private repository containing this package's extracted contents. Netlify publish directory: website. No build command required.

Included: all six pages, images, logo video, robots.txt and sitemap.xml. Source HTML is also the deployable website; no build dependencies are needed.
External dependencies: Google Fonts, Google Analytics, Google Calendar booking, mail/telephone apps, and The Beacon on destinybenefits.ca. No ChatGPT runtime calls were found in the HTML. The Beacon is currently an external link; this export preserves that behavior.

This is the current caseyco.ca project, which currently displays Destiny Benefits branding and content. This package preserves that version without redesigning it.

Canonical URLs and sitemap retain the current domain. Retirement currently has the home-page canonical URL. Review SEO settings before the final domain cutover. Analytics currently retains the existing measurement ID.

Manual deployments do not sync future edits automatically. GitHub-connected Netlify deployments can provide version history and automatic updates.
