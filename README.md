# client-site-example

A live, deployed example of a client site built from
[client-site-starter](https://github.com/sebastiansells13-bot/client-site-starter),
filled in with a fictional client — **Harbor Light Coffee Co.** — so you can see the
whole pipeline working end to end: content → build → GitHub Actions → GitHub Pages.

**Live site:** https://sebastiansells13-bot.github.io/client-site-example/

## What's different from the template

- `src/_data/business.json`, `services.json`, `team.json` filled in with fictional
  content instead of placeholders
- Two sample blog posts, one with a cover image
- `AGENTS.md`/`METHODOLOGY.md`/`INTAKE-WORKSHEET.md` (agency-internal docs) trimmed —
  a real client repo doesn't need those, only `AGENTS.md` for future edits
- `pathPrefix` set to `/client-site-example/` and the sitemap/feed hostnames point at
  `sebastiansells13-bot.github.io/client-site-example` — needed only because this demo
  lives at a GitHub Pages *project* URL rather than a custom domain. A real client site
  on its own domain would use `pathPrefix: "/"` like the template ships with.

## Local development

```bash
npm install
npm start
```

See [client-site-starter](https://github.com/sebastiansells13-bot/client-site-starter)
for the full methodology this repo was generated from.
