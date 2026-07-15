# site

Official website for ArchAsCode

Built with [Astro](https://astro.build), deployed to Cloudflare via
[Wrangler](https://developers.cloudflare.com/workers/wrangler/) as a
static-assets Worker (config in `wrangler.jsonc`).

## Commands

| Command           | Action                                                |
| :---------------- | :---------------------------------------------------- |
| `npm install`     | Install dependencies                                  |
| `npm run dev`     | Local dev server with hot reload at `localhost:4321`  |
| `npm run build`   | Build the production site to `./dist/`                |
| `npm run preview` | Build, then serve `./dist/` locally in the Workers runtime |
| `npm run deploy`  | Build, then deploy to Cloudflare                      |

First deploy: run `npx wrangler login` once to authenticate, then `npm run deploy`.
