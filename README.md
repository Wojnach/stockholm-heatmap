# Stockholm appreciation heatmap

Interactive map of apartment price appreciation (CAGR) across Stockholm,
built from public sold-price records. 20,247 buildings, 255,818 sales.

Colour = compound annual growth rate over the selected window (1y–10y).
Hollow rings = no sales of their own; value inferred from street/neighbourhood.

Basemap © CARTO, © OpenStreetMap contributors.

## Third-party code
deck.gl 9.0.0 (MIT) and maplibre-gl 3.6.2 (BSD-3-Clause) are vendored inline
rather than loaded from a CDN. SHA-256 of the vendored bytes:
  deck.gl     3047558 08b8e6bca...
  maplibre-gl c46084df69bbaa99...
  maplibre css 731181d400d65a8b...
A meta Content-Security-Policy restricts all network access to CARTO basemap
endpoints only.
