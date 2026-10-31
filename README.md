# MEBA Planner: horizon scan prototype

Single-file mobile web app (`index.html`). Open over HTTPS on a phone, tap Start, allow motion + camera, sweep 360°, export a NINA `.hrz`, JSON or CSV.
Serve locally: `python3 -m http.server` (localhost counts as secure; phones need HTTPS, e.g. a tunnel).
NINA: Options > General > Astrometry > Custom Horizon.
