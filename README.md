# tosaint.com

Landing page for tosaint 余致賢. One hand-written HTML file, no build step.

- `index.html` — the page (styles and the theme toggle are inline)
- `favicon.svg`, `og.png` — browser tab icon and link-preview image
- The portfolio lives in its own repository and is served at [/portfolio/](https://tosaint.com/portfolio/)

To change the "Now" line, edit the `.now` cell near the bottom of `index.html`.

The custom domain is set by the `CNAME` file; DNS for tosaint.com lives in Cloudflare (four A records to GitHub Pages and `www` as a CNAME to `tosaint.github.io`, all DNS only).
