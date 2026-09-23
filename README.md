# Villa Miyabi — Cloudflare Workers

This package is configured for Cloudflare Workers Static Assets.

## Deploy

1. Install Node.js.
2. Open a terminal in this folder.
3. Run `npm install`.
4. Run `npx wrangler login` and complete the Cloudflare login.
5. Run `npm run deploy`.

Wrangler uploads the files in `public/` as Worker static assets.

## Local preview

Run `npm install`, then `npm run dev`.

## Custom domain

After deployment, attach your domain from the Worker dashboard under Domains & Routes / Custom Domains. The domain must be managed through Cloudflare for the custom-domain setup.

## Project structure

- `public/index.html` — website
- `wrangler.jsonc` — Workers configuration
- `package.json` — Wrangler scripts/dependency
