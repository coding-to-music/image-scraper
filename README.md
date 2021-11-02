# Serverless Image URL Scraper

This is a lightweight api deployed to [Cloudflare Workers](https://workers.cloudflare.com/) which leverages the [HTMLRewriter runtime API](https://developers.cloudflare.com/workers/runtime-apis/html-rewriter) to quickly scrape image URLs from a webpage. A huge inspiration for this was [Adam Schwartz's workers web-scraper](https://workers.cloudflare.com/built-with/projects/web-scraper)

[Website →](https://web.coding-to-music.workers.dev)

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/coding-to-music/image-scraper.workers.dev)

## Usage
```
curl https://scraper.coding-to-music.workers.dev?url=https://developers.google.com/speed/webp/gallery
```
