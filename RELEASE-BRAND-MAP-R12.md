# Riyadh 2025 identity and interactive reference map

The mobile prototype now uses the original fair and Mayadeen marks, with a navy, blue and gold theme grounded in the supplied 2025 report. Login, navigation, dashboard context and the offline page share this identity.

The new `#fair-map` guide loads same-origin SVG and JSON generated from the public ExpoFP reference. It includes 825 selectable locations, publisher/booth search with Arabic normalization, pan/zoom, selection, parking and transport locations, and an explicit link to the existing operational twin. The 2025 map is labelled as reference data and does not claim live crowd or booth occupancy. No third-party iframe is required.

Archive: `riyadh-book-fair-v2-brand-map-r12.zip`

SHA-256: `708c39fbc4b2d03b992f121e9c9eec0b0ecbb072e1c0796b91dd427a33ac5c52`

Validation: 173 Python tests and 3 Node data/search tests; desktop and 320/390 px browser checks; A-1 publisher selection, pan/zoom/reset, route cleanup, and Parking 9 outside the initial fair viewport. Archive inventory and all 136 file hashes verified. Private report originals, databases and credentials are excluded.

Native iPhone touch gestures and external-link handling remain a separate device check. The app icon is a signed native resource and is not replaced by this web update.

Deployment target: existing mobile prototype service. At packaging time its health/login requests timed out, so a fresh data export could not be verified. This branch is ready for deployment; publication here does not establish that Render is running this release. Retain the previous archive and build configuration for rollback.
