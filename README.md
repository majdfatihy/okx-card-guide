# OKX Card Guide | دليل شروحات أوكي إكس

A static, responsive, bilingual (Arabic / English) OKX educational guide for GitHub Pages. Unaffiliated with OKX.

## Repository and URLs

- Repository: `majdfatihy/okx-card-guide`
- Proposed URL: `https://dev.majdfatihy.com/okx-card-guide/`
- English: `https://dev.majdfatihy.com/okx-card-guide/en/`
- GitHub repository URL after creation: `https://github.com/majdfatihy/okx-card-guide`

The canonical URL assumes the GitHub Pages custom-domain configuration already in use by the main site. Verify GitHub Pages routing after deployment.

## Features

- 12 verified PUBLIC long-form tutorials and 11 PUBLIC Shorts, separately presented with search and category filters.
- 4 private Shorts deliberately excluded. The Excel export dated 2026-10-16 contained 11 older OKX tutorials; the latest YouTube/vidIQ connection was checked on 2026-11-23.
- Arabic index and SEO-indexable English version at `/en/`, each with server-rendered video links and visible original titles/translated descriptions.
- Clear OKX referral code `HST7MIOD` and signup link `https://okx.com/join/HST7MIOD` with disclosure and copy action.
- 5 official OKX documentation links, clearly marked as date/region-dependent.
- 5 related guide cards: Grey, nsave, Bybit, Binance registration, and International Payment Guide.
- Centralized legal and contact links to `https://dev.majdfatihy.com/`; no duplicate about/contact/privacy/terms/disclaimer files.
- Canonical, hreflang, OG/Twitter meta tags, structured data, a verified public YouTube thumbnail URL for visual and social previews.
- No local `robots.txt` or `sitemap.xml`: those belong to the main site; once deployed, optionally update the central sitemap in the main repository after approval.
- The owner-provided Google Tag Manager loader (`GTM-P2PDLCWJ`) is included on both language pages. Google Fonts are loaded from CSS, and YouTube embeds are loaded only after a click.

## Deployment

1. Use the public repository `okx-card-guide`.
2. The source has been uploaded to the repository root; keep `en/index.html`, `videos.json`, and `assets/` in their paths.
3. Enable Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
4. Verify both language URLs, remote YouTube preview image, referral link, footer links, and social preview.
5. After publication, decide whether to add the two URLs to the CENTRAL sitemap of `majdfatihy.github.io`; this package does not modify the main repo.

## Upload note

The original ZIP contains large custom PNG assets which were not transferred by the connected text-file GitHub write interface. The published HTML instead uses the **verified public YouTube thumbnail** for the featured image and Open Graph preview, so there are no broken image references. This is a documented difference from the preview ZIP; the original custom images are still available in that archive for subsequent manual replacement if desired.

## Source audit

- YouTube channel via connected vidIQ, checked 2026-11-23: `https://www.youtube.com/@MajdFatihy`
- Attached `Majd Fatihy - ماجد فتحي_2274_Videos(1).xlsx`: 2,274 records, embedded export timestamp 2026-10-16T22:15:54Z.
- Canonical full tutorial: https://www.youtube.com/watch?v=Xyp0NekCmoM
- The earlier conversational link X2bGojeivW4 was not returned by the connected vidIQ video lookup, so this page uses the verified canonical video.
- Individual video IDs, dates and titles are in `videos.json`. Do not re-publish private videos without changing their privacy settings first.
- Official OKX references:
  - Card overview & eligibility: https://www.okx.com/en-gb/help/whats-okx-card
  - Card fees: https://www.okx.com/help/what-fees-apply-when-im-using-my-okx-card
  - Funding OKX Pay: https://www.okx.com/help/how-to-add-funds-into-my-pay-balance
  - Regular cashback rules: https://www.okx.com/help/okx-card-cashback-program-faq
  - Subscription cashback terms: https://www.okx.com/help/whats-the-okx-card-subscription-cashback

## Change discipline

Do not edit already approved versions unless the site owner explicitly specifies the section to change. Current files are a pre-publication candidate for review.