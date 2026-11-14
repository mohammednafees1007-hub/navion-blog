# NAVION blog publishing notes

Prepared 14 November 2026. Status: draft created; not published. Website administration or repository access has not been established in this chat.

## Proposed placement and metadata

- Site: https://shop.navionrobotics.com/
- Proposed path: /blog/3d-printing-thanjavur-kumbakonam
- SEO title: 3D Printing: Thanjavur & Kumbakonam | NAVION 3D
- Meta description: NAVION 3D offers project printing and personalised gifts from Kumbakonam, serving Thanjavur with shipping across Tamil Nadu. Learn how to order.
- Main heading: 3D Printing for Thanjavur and Kumbakonam: Project Parts and Personalised Gifts
- Primary topics: 3D printing in Thanjavur; 3D printing for Kumbakonam.
- Supporting topics: project printing, personalised gifts, Tamil Nadu shipping, custom name keychains, requesting a 3D printing quotation.
- These are editorial target phrases, not verified search-volume or ranking measurements.
- Canonical URL: use the final published URL. The proposed path above does not yet exist as a verified live page.

Publish the article once on the shop. Link to it from the shop navigation or a blog index and from a relevant section of navionrobotics.com. Avoid publishing identical copies on both hosts. Use the existing site's design and a real author attribution approved by that author. Set publication and modification dates to the actual dates.

Add an original photograph of an actual NAVION print if available, with alt text describing what is pictured. Do not present generated imagery as a photographed customer order. No photos, reviews, order counts or performance claims have been invented for this article.

## cPanel integration

The owner confirmed cPanel hosting and corrected the business location: NAVION 3D is based in Kumbakonam, serves Thanjavur, and ships across Tamil Nadu. Thanjavur is a service area, not a claimed physical branch. The live shop previously described Thanjavur as its base and pickup location; correct that conflicting copy during integration. Collection availability and terms need confirmation, so the article does not promise free pickup.

cPanel is the hosting control panel. The site's application and its document root still need inspection before choosing an installation method. Access has not yet been established.

1. Open cPanel and identify the document root for shop.navionrobotics.com. Do not assume it is the main domain's public_html folder.
2. Identify the shop application and check whether it already supports blog or content pages. Prefer its native publishing feature and layout.
3. Back up affected files and any relevant database before changing the application.
4. Integrate the supplied Markdown content through the application, converting it to the editor's supported format. Uploading a Markdown file alone will not create a styled blog page.
5. Use the proposed route if supported, or update the metadata and links to match the actual published route. Preserve the existing shop routes and checkout.
6. Complete the publishing checks below and verify the live result.

## Observed technical issue

On 14 November 2026, https://shop.navionrobotics.com/sitemap.xml returned HTTP 200 with an empty sitemapindex and no child sitemap entries. The shop's robots.txt points to this URL. Repair sitemap generation to include indexable canonical shop pages and the blog after publication. This observation alone does not establish whether Google has indexed the shop.

The main domain sitemap returned the homepage, terms and privacy URLs. Its robots.txt allows public crawling while blocking several operational directories. No Search Console account was inspected.

## Publishing checks

1. Publish the article with a working HTTP 200 URL, the metadata above and a self-referencing canonical tag.
2. Confirm there is no unintended noindex directive and that the article is readable on mobile.
3. Link to the article from a crawlable blog index or relevant existing page.
4. Repair and validate the shop sitemap, then submit it in the verified Google Search Console property.
5. Inspect the published URL in Search Console and request indexing if appropriate. Indexing and position are not guaranteed.
6. Track relevant search queries, impressions, clicks and enquiries. No baseline ranking or traffic figures have been collected here.

## Next useful articles

- How to prepare your model and requirements for a 3D printing quote.
- Personalised name keychains: spelling, colours and ordering details.
- Choosing a photo for a lithophane gift.

Each should answer a separate customer question and use actual product details and original examples. Avoid repetitive location pages or claims of being the best without evidence.

## Sources checked

- https://shop.navionrobotics.com/ — live shop content, retrieved directly successfully after the web reader could not open it.
- https://navionrobotics.com/ — brand relationship and research-stage companion project.
- https://shop.navionrobotics.com/robots.txt
- https://shop.navionrobotics.com/sitemap.xml
- https://navionrobotics.com/robots.txt
- https://navionrobotics.com/sitemap.xml
- https://developers.google.com/search/docs/fundamentals/seo-starter-guide — useful content, titles, links, discovery and ranking limitations.
