# Design a Loop

A content site about **loop engineering** — the discipline of designing the iterative perceive, reason, decide, act, verify, recover cycle an AI agent runs on every turn.

**Live site:** https://designaloop.com
**Repository:** https://github.com/3IVIS/designaloop

This is a sister content site to [buildaharness.com](https://buildaharness.com). It doesn't ship a product of its own — it teaches the discipline and points to **Build A Harness**, the open-source tool ([github.com/3IVIS/buildaharness](https://github.com/3IVIS/buildaharness)) that implements it.

## Pages

- `index.html` — homepage: what a loop is, the seven stages, loop vs. prompt engineering, the tool
- `loop-engineering.html` — the long-form pillar page: full definition, comparisons, stage-by-stage anatomy, FAQ (served at `/loop-engineering`)
- `privacy.html`, `impressum.html` — legal
- `404.html` — not found page

## Local preview

This repo is a static site. Open `index.html` in a browser or serve the root with any static server.

```sh
# Python 3
python3 -m http.server 8080
# or Node
npx serve .
```

## Before going live

- Replace the placeholder Google Analytics ID (`G-XXXXXXXXXX`) in `index.html`, `loop-engineering.html`, and `privacy.html` with a real GA4 measurement ID (or remove the gtag block entirely if analytics aren't wanted yet).
- Point `designaloop.com` DNS at GitHub Pages and confirm the `CNAME` file matches.

## License

Site content: © 3IVIS. The tool it describes, Build A Harness, is Apache 2.0.
