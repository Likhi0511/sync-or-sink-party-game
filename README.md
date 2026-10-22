# Sync or Sink

Server-authoritative real-time party game, designed for 3–12 phones. It is dependency-free so it can be deployed as a Cloudflare Worker with Durable Objects.

## Publish

Install Node.js 20+, log into Cloudflare, then run:

```powershell
npx wrangler deploy
```

The command prints the public `workers.dev` URL. Durable Objects are declared in `wrangler.toml`; deploy it from a Cloudflare account that has Workers enabled.

## Quick test

Open the public URL in three browser tabs, create a room in one tab, join from the other two tabs, choose settings, and start. Lock matching answers in all three tabs. Refresh a tab to confirm its saved seat reconnects.
