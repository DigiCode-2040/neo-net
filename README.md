# neo-net

NEO-NET is a self-contained, browser-based security operations dashboard. It
simulates network telemetry, incident response, and a spatial digital twin for
demonstration purposes. It does not connect to real infrastructure or perform
real security actions.

## Run locally

Open `index.html` in a modern browser, or serve the project with a local web
server:

```sh
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Features

- Interactive operations dashboard, network topology, and spatial digital twin
- Simulated incident scenarios with investigation, containment, and recovery
- Local command terminal, event journal, and CSV export
- Responsive layout, visualization modes, and dashboard customization

The project uses embedded HTML, CSS, and JavaScript and has no external runtime
dependencies. All displayed telemetry and security events are simulated in the
browser.
