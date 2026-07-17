# Herdeno.sg Executive Digital Profile

Production source for Herdeno.sg, deployed to Cloudflare Workers from `main`.

## Required before the first Git deployment

Upload your official TAQWA logo as:

`public/assets/taqwa-official.jpg`

The executive portrait and all other V5 files are already included.

## Cloudflare deployment

Deploy command: `npx wrangler deploy`

Wrangler publishes `public/` using Workers Static Assets.
