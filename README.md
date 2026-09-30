# podrodze-data

Nightly place database for the **Po drodze** iOS app, built from OpenStreetMap data for Poland.

The files are published as assets of the [`data-latest`](../../releases/tag/data-latest) release:

| File | Content |
|---|---|
| `manifest.json` | Version, build time, size, SHA-256 and per-category counts |
| `podrodze-pl.sqlite.gz` | Gzip-compressed SQLite database |

This repository holds no code; the files are built and uploaded by an automated job.

## Licence

Contains information from [OpenStreetMap](https://www.openstreetmap.org/copyright), which is made available under the [Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/).
© OpenStreetMap contributors.

The database in the release assets is a derivative database and is likewise available under the ODbL.
