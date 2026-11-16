# Jameel: NAVION blog integration handoff

## Deliverable and confirmed business details

This repository contains 18 complete Markdown article drafts: 13 for NAVION 3D and 5 for the NAVION ROBOTICS companion research project. This is content for integration, not an application or a deployed blog.

- NAVION 3D is based in **Kumbakonam**, serves **Thanjavur**, and ships across **Tamil Nadu**. This owner correction overrides the older Thanjavur-base wording observed on the shop.
- Hosting is cPanel; the underlying shop application and its document root have not been inspected.
- The companion is in research and concept development. There is no companion product for sale. These articles discuss questions and hypothetical scenarios, not tested capabilities.
- Proposed destinations: commercial articles on `shop.navionrobotics.com/blog/`; research articles on `navionrobotics.com/blog/`.

## Live copy conflict rechecked 16 November 2026

The [shop printing page](https://shop.navionrobotics.com/3d-printing) still describes Thanjavur as the base and says project prints are fulfilled by agreed local pickup there. This conflicts with the owner's instructions: Kumbakonam base, service to Thanjavur, and shipping across Tamil Nadu. Align the live location and fulfilment copy with the owner-confirmed arrangements during integration; confirm any project-specific shipping conditions rather than inferring them from the old page. No live copy was edited by the weekly content task.

## Files to use

- `articles/`: article body content, with one H1 per file.
- `metadata.json`: title, description, category, proposed URL and related article slugs. Use the title as the starting SEO title and H1; make any final template changes consistently.
- `metadata.csv`: the same core fields in spreadsheet-friendly format.
- `README.md`: complete article index for review.
- `INITIAL_SITE_AUDIT.md`: observed sitemap issues and original editorial notes.
- `EDITORIAL_GUIDANCE.md`: instructions for future weekly additions.

## Integration sequence

1. Identify both domain document roots and the application serving each. Back up the affected files and relevant database. Use the application's native content/blog feature if available.
2. Add category indexes and reusable article templates matching the existing websites. Markdown is source content; copying these files into public_html alone will not create the intended pages.
3. Import the article bodies and metadata. The proposed paths are not verified live routes; use the final routes in canonical tags, links and the sitemap.
4. Convert relative related-reading links such as `choose-photo-lithophane.md` to the final website route for that article. They currently work for GitHub review. Do not leave `.md` review links in the deployed content.
5. Link the shop articles from the shop blog index, and the research articles from the research blog index. Add a clear blog navigation link on each host. Cross-link between brands only where helpful.
6. Correct old Thanjavur-base wording across shop titles, body text, footer and any structured data. Confirm any physical address and collection terms with the owner; do not invent an address or free-pickup promise.
7. Review current product availability and the article wording before publication. Add real product photos or research sketches where useful, with honest captions and descriptive alt text. No image assets are included.
8. Add accurate author or editorial-team attribution and actual publication dates. Do not attribute these AI-assisted drafts to an individual expert without their review. Do not publish all pages with fabricated historical dates.
9. Use a self-referencing canonical URL, unique description, clear heading structure and crawlable HTML for every article. If adding Article/BlogPosting structured data, match only visible verified facts, the final URL, genuine authorship and actual dates. No invented reviews or ratings.
10. Fix sitemap generation. The shop sitemap returned an empty sitemap index on 14 November 2026. Include indexable canonical routes and update the relevant domain sitemap after integration. Do not overwrite an existing sitemap with a partial blog-only list.
11. Check HTTP 200 responses, mobile rendering, images, related links, canonical URLs, robots directives and sitemap validity. Confirm that adding the blog has not broken existing product, cart or checkout routes.
12. Use the owner's verified Search Console properties to inspect representative published URLs and submit the correct sitemaps. Record live URLs and deployment date in this repository.

## Acceptance criteria

- All articles listed in the current metadata have working public URLs, appropriate host placement, complete body content and correct metadata.
- No article implies a Thanjavur office or an available companion robot.
- Related links resolve to published pages; unpublished articles are not presented as live links.
- Site navigation reaches both blog indexes and the relevant service or survey pages.
- Search Console and sitemap checks are recorded honestly; indexing or a ranking position must not be claimed without evidence.

## Weekly workflow

The owner requested weekly GitHub additions: one article about 3D printing and one about companion research. The scheduled task pushes content to this repository; it does not access cPanel or deploy the website. Review each new pair, integrate it, and update the metadata status and live URLs after deployment. The schedule is managed in Codex, not GitHub Actions.

## Sharing

The repository is public at the owner’s request. Jameel can read and download the content without an invitation. Write access remains separately controlled; no collaborator invitation has been sent by this task.
