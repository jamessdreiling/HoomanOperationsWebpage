# Hooman Operations website (draft)

Plain HTML and CSS, no build step. Hosting: Cloudflare Pages, connected to a GitHub repository.

## Files
- index.html: homepage (copy as written on the current site, minus the Loocy section)
- services.html: four tiers (Back Office Checkup, Fix One Workflow, Back Office Setup, Keep It Running)
- about.html: copy as written on the current site
- contact.html: form (needs an endpoint before launch)
- styles.css: brand tokens from the brand record (Figtree, five colors, spacing, radii)
- assets/hooman-mark.svg: the bridge mark in brand colors

## Open items before launch
1. Contact form endpoint: replace REPLACE_WITH_FORM_ENDPOINT in contact.html with a form service's address, or the form will fail.
2. Case study: the homepage shows a "coming soon" line in place of the full case study.
3. Claims on the homepage and About page (78 to 37 minutes per request, 53% faster, more than $820,000 a year saved, $2,900 invested) come from the NGOsource project. Keep documentation on hand to back them up before launch.
4. About page copy is the current generic text. Needs your words.
5. Services prices: Back Office Checkup is a flat $500; the other tiers show "Starting at." The note under the cards also says they are starting prices and mentions the nonprofit discount (no amount given).
6. Social links removed; add your own accounts if you want them.
7. Mobile layout has only basic responsive rules. Not yet reviewed.
8. Logo wordmark is live text in Figtree; the mark is the SVG in assets/.

## Email
Google Workspace DNS (MX, DKIM, SPF, DMARC) is handled at the domain registrar and must be kept during the site move.
