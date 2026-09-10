# The Well Chiropractic — landing page review preview

Static **preview** of the restructured `/google-ads/` and `/facebook/` landing pages for
The Well Chiropractic (Dr. Hojin Seo), Los Angeles CA. Built 2026-09-10.

🔴 **These are NOT the live pages.** The live pages are on the client's own WordPress host at
`thewellchiro.com` and are unchanged. This repo is a frozen render for client review only.

- The lead form is **stubbed** — a submit here posts nothing and creates no contact.
- The Meta pixel base code is present on `facebook.html` because it is part of the page being
  reviewed; no Lead event can fire, because the form never completes.
- All pages `noindex, nofollow`; `robots.txt` disallows all.
- Video thumbnails are local copies in `thumbs/`; the live page hotlinks `i.ytimg.com`.

Source and the apply procedure: `the-well/lp-redesign-2026-09-10/` in the localember repo
(`build.py`, `PATCH.md`).
