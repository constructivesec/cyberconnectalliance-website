# cyberconnectalliance.org

Static single-page website for CyberConnect Alliance, Inc. (CyCA).

## Structure

- `index.html` - the entire site (HTML and CSS in one file, no build step)
- `logo.png` - header logo and favicon (CyCA logo without tagline)
- `logo-full.png` - full logo with tagline, used for link previews

## Deploying

Hosted on Cloudflare (Workers & Pages), connected to this repository.
Every push to `main` redeploys the site automatically.

Cloudflare settings:
- Framework preset: None
- Build command: (blank)
- Output directory: `/`
- Custom domains: `cyberconnectalliance.org`, `www.cyberconnectalliance.org`

## Editing

Edit `index.html` directly on GitHub or locally, then commit to `main`.
