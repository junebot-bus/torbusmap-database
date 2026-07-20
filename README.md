# torbusmap-database

Over-the-air Core Data store for **TOR Next Bus** (Toronto / TTC).

- `dcbusmap.sqlite` — the shared-model Core Data store (subway + surface stops, routes, paths).
- `dcbusmap_version.txt` — current DB version; the app compares it against its bundled version and downloads when newer.

File names are `dcbusmap.*` for every city because the shared Core Data model is named `dcbusmap` (see `City.databaseName`). Do not rename.
