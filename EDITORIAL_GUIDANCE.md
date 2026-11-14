# Weekly NAVION editorial guidance

## Scope

Add two complete articles each week: one for NAVION 3D and one for the NAVION ROBOTICS companion research project. Write for actual customers and research participants, with a distinct question, practical examples and a useful next step. There is no minimum word count for SEO; complete the chosen topic without padding.

Keep NAVION 3D's location accurate: Kumbakonam base, service to Thanjavur, shipping across Tamil Nadu. Avoid separate near-identical articles for every town. Companion articles must preserve research-stage status unless fresh owner-approved evidence establishes a change.

## Before writing

Read the current article index, metadata and any updated owner instructions. Check recent commits so that a retry does not create duplicate weekly posts. Select topics not already covered; do not simply reword an existing article. Review current website service/product information, but flag any conflict with explicit owner-confirmed details instead of silently overwriting them.

Research technical or current claims using primary sources such as manufacturer documentation, original papers or official project documentation. Cite the exact supporting pages in the article. Do not invent test results, customer stories, business statistics, discounts, product launches, privacy implementations or delivery promises. Label hypothetical examples as examples.

## Useful future angles

These are candidates, not ready-to-publish claims. Research and adapt each before use.

- 3D printing: a measured enclosure planning example; choosing which dimensions to mark on a drawing; how print orientation affects a specific part; reading a material datasheet; a photographed owner-supplied project walkthrough; designing a useful display stand; organising revisions for a repeat order; explaining visible layer lines with original photographs.
- Companion research: when a reminder becomes an interruption; how to communicate a paused state; designing for a shared study room; physical controls versus voice commands; what a useful concept interview asks; how to evaluate a reminder concept without claiming productivity gains; accessibility questions for early prototypes; what evidence should separate a demo from a dependable product.

## Deliverables and checks

1. Add each article under its correct category using a unique descriptive slug.
2. Include a clear title, focused introduction, useful sections, an appropriate next step and relevant source links when technical claims are made.
3. Add metadata entries to JSON and CSV with proposed URLs and `draft` status. Keep metadata schema consistent. Add related-reading links only to existing articles or the new pair where appropriate.
4. Update the README article counts and links. Add a dated changelog entry identifying both new articles and what was checked.
5. Validate metadata parsing, unique slugs and URLs, heading structure, relative link targets and factual consistency. Review wording before committing.
6. Fetch the latest remote changes, preserve other contributors' work and push a descriptive commit to the repository's default branch. Never force push or overwrite Jameel's edits.
7. Report the two article links and the commit. Clearly distinguish a GitHub content update from website publication. If authentication, permissions or a conflict blocks the push, report the blocker without claiming success.

## Source basis for the initial collection

- The live NAVION shop and robotics homepage were inspected on 14 November 2026 for catalogue and research-stage details.
- The owner explicitly corrected the business base to Kumbakonam and confirmed Thanjavur service and Tamil Nadu shipping.
- Initial articles are practical ordering guides and clearly labelled concept discussions; they do not present invented engineering measurements or experimental results.
- Google recommends helpful content intended for people rather than producing many pages simply to attract search traffic: https://developers.google.com/search/docs/fundamentals/creating-helpful-content
- Search fundamentals and ranking limitations: https://developers.google.com/search/docs/fundamentals/seo-starter-guide
