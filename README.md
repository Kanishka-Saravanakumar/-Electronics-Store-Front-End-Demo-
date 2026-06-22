# Electi 🏷️ — Electronics Store (Front-End Demo)

A single-file, no-framework front-end demo of an e-commerce storefront for electronics and home appliances. Built as a prototype to practice UI/UX, vanilla JS state handling, and responsive layout.

## Features

- 🛒 **Cart** — add/remove items, live quantity + total, slide-out drawer
- ❤️ **Wishlist** — toggle per product, persists across tabs while browsing
- 🔎 **Search** — jumps to a matching product and scrolls into view
- 🗂️ **Category browsing** — dropdown panel + dedicated category section
- 🏷️ **Product tabs** — Featured / Popular / Low Price sorting
- 📄 **Product detail pages** — click any product card to open a full page with image, description, quantity picker, related products, and a working browser back button (via `pushState`)
- 📱 **Responsive layout** — mobile nav, stacked grids, touch-friendly buttons

## Tech

Plain HTML, CSS, and JavaScript — no build step, no dependencies, no backend. Cart and wishlist state live in memory (resets on page refresh) since this is a UI prototype, not a production store.

## Running it locally

Just open `index.html` in a browser — no install needed.

```bash
git clone https://github.com/YOUR_USERNAME/electi-store.git
cd electi-store
open index.html   # or double-click the file
```

## Notes

This is a learning/demo project — there's no real backend, payment processing, or persistent storage. It's meant to showcase front-end UI patterns (cart logic, product routing, responsive grids) in a single self-contained file.

## License

MIT — feel free to fork and build on it.

