# Mashallah Arts

Website for Mashallah Arts — hand-poured candles, original paintings, and fresh Indian chai by Nargis Salmani Forber-Pratt, a small family business registered in the State of Missouri.

Plain static HTML/CSS site, no build step required. Live at [mashallaharts.com](https://mashallaharts.com).

## Structure

- `index.html` — home page
- `shop.html` — candles, paintings, and chai
- `about.html` — Nargis's story and the family
- `heard-and-seen.html` — "Our Promise" page
- `contact.html` — contact form + phone/email
- `business-info.html` — policies, linked from the footer
- `assets/style.css` — all styling
- `assets/images/` — logo, photos, paintings, product mockups
- `robots.txt`, `sitemap.xml` — SEO basics
- `vercel.json` — `cleanUrls: true`, so every internal link uses extension-less paths (`/shop`, not `/shop.html`)

## Local preview

Serve the folder so absolute paths (`/shop`, `/about`, etc.) resolve correctly:

```
npx serve .
```

Opening `index.html` directly by double-clicking won't resolve those absolute links — use a local server.

## Deploying

Connected to Vercel — pushes to `main` deploy automatically. No build settings needed.

## Still open

- [ ] Nargis's review/approval of her bio on the About page
- [ ] Real candle scents, chai blends, and prices (mockup graphics are standing in for now)
- [ ] Painting titles and prices for the 5 real paintings on the Shop page
- [ ] Social media handles
- [ ] Shipping / pickup / payment / returns specifics on Business Info
- [ ] Confirm Missouri sales tax + cottage food requirements before taking real orders
