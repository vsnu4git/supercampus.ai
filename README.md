# Supercampus Image Host (React)

This repo is a tiny **React** website that also acts like an **image host**.

Any file you put in `images/` becomes a direct URL on your deployed domain, for example:

- `https://your-domain.com/images/sample.svg`

## Add / replace your image

1. Put your image file in `images/` (examples: `logo.png`, `avatar.jpg`, `banner.webp`).
2. Commit + push to GitHub.

If you keep the same filename, the URL stays the same forever.

### Recommended filename for your banner

Save your provided banner image as:

- `images/supercampus.png`

Then your URL will be:

- `https://<your-domain>/images/supercampus.png`

## Deploy on Vercel

1. Import this GitHub repo in Vercel.
2. Framework preset: **Other** (or “Static”).
3. Build command: **None**
4. Output directory: **.** (project root)
5. Deploy.

Then add your custom domain in Vercel → Project → Settings → Domains.

### If Vercel CLI says “Failed to locate package.json”

This repo includes `package.json` + `vercel.json` so the CLI can deploy it as a static site with **no install** and **no build**.

## Deploy on Netlify

1. Import this GitHub repo in Netlify.
2. Build command: **None**
3. Publish directory: **.** (project root)
4. Deploy.

Then add your custom domain in Netlify → Domain management.

## Your direct image URL

Once deployed, your direct image URL is:

`https://<your-domain>/images/<your-file>`

Examples:

- `https://example.com/images/logo.png`
- `https://example.com/images/avatar.jpg`
