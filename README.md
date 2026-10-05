# TrickerBoard
Global stock stats and popular trades. No account needed


# Tickerboard

A no-login website for tracking stocks and popular trades around the world. Star stocks to build your own dashboard, saved in your browser. Bring your own free Alpha Vantage key for live quotes.

It is one static file with no build step and no dependencies.

## Features
- World indices, top movers, a searchable stock table and a most-traded list
- A personal dashboard stored in `localStorage` (no account, no server)
- Optional live quotes for saved stocks using your own [Alpha Vantage key](https://www.alphavantage.co/support/#api-key)
- Light and dark themes, keyboard accessible, works on phones

## Run it
Open `index.html` in a browser, or serve the folder:

    python3 -m http.server 8000

Deploy by uploading the folder to any static host (GitHub Pages, Netlify, Vercel, Cloudflare Pages).

## Live data and privacy
Your API key is stored only in your browser and sent only to alphavantage.co. Nothing else is collected. The free plan allows about 25 requests a day, so quotes load only for saved stocks and are reused for 15 minutes.

Stocks you have not saved show sample data, not real prices. Prices are delayed and are not financial advice.

## Docs
- [Wireframes](docs/wireframes.md)
- [Design process](docs/design-process.md)
- [Design tokens](docs/design-tokens.md)

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md). Good first issues: more exchanges and symbol mappings, a stock detail view, price alerts, CSV export of the dashboard.

## License
MIT. See [LICENSE](LICENSE).
