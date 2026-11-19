CRYPTO & METALS GBP DASHBOARD

1. Extract the ZIP.
2. Upload index.html to a GitHub Pages repository (root folder).
3. Enable GitHub Pages for the repository's main branch/root.
4. Open the published URL in your browser.

Cryptocurrency prices and history use CoinGecko's public API. They can be rate-limited.

Precious metals and copper/aluminium reference prices require a Metals.Dev API key.
Enter it in the dashboard's Data sources section. The key is saved locally in that browser.
For production use, a backend proxy is safer than exposing an API key in browser requests.

Steel and brass have no single universal market price. These are intentionally marked
Not available until grade-specific data sources are chosen.

IMPORTANT: Metals.Dev response formats, plan permissions and supported symbols can change.
If the feed does not return GBP-per-gram values, the app will show unavailable rather
than substitute invented prices. Check the provider's current API documentation.
