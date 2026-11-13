# cyberconnectalliance.org

Static single-page website for CyberConnect Alliance, Inc. (CyCA).

## Structure

- `index.html` - the entire site (HTML and CSS in one file, no build step)
- `logo.png` - add the board-approved logo here, then swap it into the header (see comment in `index.html`)

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
