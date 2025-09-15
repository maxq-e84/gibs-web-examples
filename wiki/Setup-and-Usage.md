# Setup and Usage

## Running Locally

Clone and install dependencies:

```bash
git clone https://github.com/maxq-e84/gibs-web-examples.git
cd gibs-web-examples
npm install
npm start
```

Navigate your browser to [http://localhost:3001](http://localhost:3001).

For hot-reload development:

```bash
npm install
npm run dev
```

## Displaying Other Layers

Most examples show a single layer.  
To display other layers, refer to the [GIBS Visualization Product Catalog](https://nasa-gibs.github.io/gibs-api-docs/available-visualizations/#visualization-product-catalog) for required parameters.

## WMTS Time Selection

- **WMTS KVP:** Use the `TIME` parameter in `YYYY-MM-DD` format.
- **WMTS REST:** Insert the day in `YYYY-MM-DD` format between style name and the tile matrix set name.

See the "Rolling Seven Day Slider" examples for details.

## API Keys

Some platforms require API keys:
- **Bing Maps:**  
  Insert your key in [`examples/bing/webmercator-epsg3857.js`](./examples/bing/webmercator-epsg3857.js#L25)
- **Google Maps:**  
  Insert your key in [`examples/google/webmercator-epsg3857.html`](./examples/google/webmercator-epsg3857.html#L30)