# Giants, Gods and Pyramids — Lead Magnet Landing Page

A single-page landing site for Adam J. Hanrahan's new book **Giants, Gods and Pyramids**. The free sample (Hook, Introduction, and Chapter 1) is email-gated: a visitor enters their email, the address is emailed to Faithful Books, and the visitor is sent straight to the sample PDF.

**Live URL (once Pages is on):** https://faithfulbooks316.github.io/giants-gods-pyramids/

## Files

| File | What it is |
|---|---|
| `index.html` | The whole landing page (CSS inline, no build step) |
| `giants-gods-pyramids-free-sample.pdf` | The free sample — Hook, Introduction, Chapter 1 (8 pages) |
| `banner.png` | The FaithfulBook Shop banner (blue/green acid-drip logo) |
| `book-description-seo.md` | The SEO book description, standalone, for reuse on store listings |
| `README.md` | This file |

## How to push it (Adam's hand)

1. On GitHub, signed in as **faithfulbooks316**, create a new public repository named **`giants-gods-pyramids`**.
2. Upload all five files to the repo's `main` branch (GitHub web: Add file → Upload files — or `git push` from a local clone).
3. Enable GitHub Pages: repo **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main, /(root) → Save**.
4. Wait a minute or two, then open https://faithfulbooks316.github.io/giants-gods-pyramids/ — the page should be live.

## Email-gate activation (do this FIRST, before sharing the link)

The form posts to **FormSubmit** (https://formsubmit.co/faithfulbooks.shop@gmail.com). FormSubmit needs one activation click before it forwards anything:

1. After the page is live, submit the form once yourself with your own email.
2. FormSubmit sends an **activation email to faithfulbooks.shop@gmail.com** — open it and click **Activate**.
3. From then on, every signup lands in that inbox (subject: "New Giants lead magnet signup") and the visitor is redirected straight to the PDF.

Until that activation click, signups go nowhere. Test it once and confirm the email arrives.

## The one-line gate swap

If the repo name ever changes, update **one line** in `index.html` — the `_next` hidden field in the form (it is marked with an HTML comment `UPDATE THIS IF THE REPO NAME CHANGES`):

```html
<input type="hidden" name="_next" value="https://faithfulbooks316.github.io/giants-gods-pyramids/giants-gods-pyramids-free-sample.pdf">
```

Change the URL to the new Pages address of the PDF and re-push. Nothing else needs to move.

## Brand

Navy `#0d1526` background, gold `#c9a227` accents, acid-drip blue/green theme, FaithfulBook Shop banner on top. Masthead: "Truth to power. Knowledge to the vulnerable." Contact everywhere is faithfulbooks.shop@gmail.com — no home address, no photo of Adam, no GED reference anywhere on the page.

© 2026 Faithful Books Publishing — Adam J. Hanrahan
