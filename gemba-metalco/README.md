# GembaMetalCo Updates

This folder is the stable update channel for the GembaMetalCo desktop application.

- `latest.json` is read by installed GembaMetalCo clients.
- Versioned update ZIP files are published as GitHub Release assets using tags such as `gemba-v1.0.0.2`.
- Release notes are stored under `release-notes/` when an update is published.
- Customer configuration, database files, credentials, logs, license files, and private build assets must never be included in an update package.

Publishing is intentionally manual from the private `asapamit/GembaMetalCo` repository using the self-hosted Windows runner.
