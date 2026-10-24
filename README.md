# Hooman Operations website (draft)

Plain HTML and CSS, no build step. Hosting: Cloudflare Pages, connected to a GitHub repository.

## Files
- index.html: homepage (copy as written on the current site, minus the Loocy section)
- services.html: three tiers; Advanced+ left out
- about.html: copy as written on the current site
- contact.html: form (needs an endpoint before launch)
- styles.css: brand tokens from the brand record (Figtree, five colors, spacing, radii)
- assets/hooman-mark.svg: the bridge mark in brand colors

## Open items before launch
1. Contact form endpoint: replace REPLACE_WITH_FORM_ENDPOINT in contact.html with a form service's address, or the form will fail.
2. Case study: the homepage shows a "coming soon" line in place of the full case study.
3. Claims on the homepage and services page (savings ranges, zero layoffs, 2.3 FTE) are as written. They need sources before launch.
4. About page copy is the current generic text. Needs your words.
5. Services prices are shown without "Starting at" on the services page; the note under the cards says they are starting prices.
6. Social links removed; add your own accounts if you want them.
7. Mobile layout has only basic responsive rules. Not yet reviewed.
8. Logo wordmark is live text in Figtree; the mark is the SVG in assets/.

## Email
Google Workspace DNS (MX, DKIM, SPF, DMARC) is handled at the domain registrar and must be kept during the site move.
