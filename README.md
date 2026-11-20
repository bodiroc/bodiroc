# bodiroc.com

Website for Bodi Roc Personal Fitness Training (Shelly Shubert), a Total Fitness Concept since 1981.

- Preview layout while the family chooses a design:
  - `/` cover page linking to both versions
  - `/a/` Version A, one long page
  - `/b/` Version B, separate Home / About / Testimonials / Contact pages (`/b/style.css`)
- Images are shared in `/img/`. Hosted free on Cloudflare Pages; any change saved to `main` republishes automatically.
- At launch: move the chosen version to the site root, delete the other and the cover page, remove the "PREVIEW-ONLY" Compare-designs button and every `noindex` tag, and set up `_redirects` for the old Wix links.
