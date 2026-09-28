# Recall — Incident Response Copilot

A self-contained hackathon frontend prototype. Describe an incident, load a sample scenario, and view simulated matches against incident history and runbooks.

## Run locally

No build step or dependencies are required. Open `index.html` in a browser, or serve this folder with any static file server. For example:

```sh
python -m http.server 8000
```

Then open http://localhost:8000.

## Project structure

- `index.html` — app shell and interface markup
- `src/styles.css` — responsive styling
- `src/main.js` — sample knowledge base and demo interactions

## Prototype notes

The investigation logic uses local sample data in `src/main.js`; it does not connect to production systems or execute actions. Replace the sample knowledge base and investigation handler with an API call to connect a backend.
