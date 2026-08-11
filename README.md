# xardas.io

Static site for [xardas.io](https://xardas.io), deployed to Cloudflare with Wrangler.

## Deploy

```sh
npm ci
npx wrangler login # opens Cloudflare OAuth in your browser
npm run deploy
```

This publishes `public/` to the `xardas-io` Worker at [xardas.io](https://xardas.io).

## SSH keys

Public keys live in `public/keys/` and are served at `/keys/<name>.pub` (for example, `/keys/neo.pub`).
