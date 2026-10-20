# lucaschantelou.com

Personal website. Plain HTML, no build step.

Every push to `main` deploys to https://lucaschantelou.com through Cloudflare Pages.

- `index.html`: the whole page, styles included
- `fonts/`: Atkinson Hyperlegible Next, self-hosted so visitors' IP addresses are not sent to Google (SIL Open Font License, see `fonts/OFL.txt`)
- `_headers`: security headers that Cloudflare Pages adds to every response
