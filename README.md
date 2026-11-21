# GeoAkses API Documentation

OpenAPI 3.0.3 contract and Swagger UI static site for GitHub Pages.

- `openapi.yaml` documents the read API, validation behavior, schemas, and examples.
- `index.html` loads Swagger UI from jsDelivr and the spec relative to the page, so it works at a GitHub Pages project path.

To preview, serve this directory over HTTP (for example `python -m http.server 8000`) and open `http://localhost:8000`. Opening `index.html` as a `file://` URL may prevent Swagger UI from fetching the YAML due to browser origin restrictions.

The production API host in the spec is a planned placeholder and must be verified before launch. The backend supports `http://localhost:8080` for local use. Demo examples are explicitly labeled; confirm source and freshness before representing transit information as official or live.
