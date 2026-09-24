# charlee-links

Charlee's link page — the one address that goes in every bio.

Live: https://josefniccum.github.io/charlee-links/

Every product from the videos, newest first, each button going to that product's
Awin tracked link with its own `clickref`, and the customer code under it.

**This repo holds the built page only.** The source of truth is
`commerce/programs/awin/links.json` in the private Affiliate project;
`tools/build_linkpage.py` renders it and `tools/publish_linkpage.command`
rebuilds and pushes here in one double-click. Do not hand-edit `index.html` —
the next publish overwrites it.

Affiliate disclosure is on the page itself.
