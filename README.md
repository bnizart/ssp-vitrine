# SSP Website

**SSP** (Surveillance Sécurité Privée) is a private security company based in France.

## Technos

- **[Astro.js](https://astro.build/)** — Static site generator focused on performance.
- **[Cloudflare Workers](https://workers.cloudflare.com/)** — Hosts and serves the static build.
- **[TailwindCSS](https://tailwindcss.com/)** — Advanced CSS framework.

## Deploy

On push to `main`, CI runs `astro check`, Lighthouse CI, then deploys via `wrangler deploy` to Cloudflare Workers.
