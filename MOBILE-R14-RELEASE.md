# Mobile r14 — services and measured readiness

Updates the hosted interface used by the existing iOS and Android application. The current mobile origin and app identity remain unchanged. Includes the fair identity and reference map, phase-based service monitoring, zone readiness, spatial links, and evidence-based mission outcomes.

Source archive: `riyadh-book-fair-mobile-r14.zip`

SHA-256: `378ce009dd54810a9703296668d44f5b8a505e9685b4b8b407409d2566e2d488`

Validation: 235 Python tests, 34 JavaScript tests and syntax checks passed. All 167 release-manifest files were verified; the extracted archive passed the Python suite. A private copy of the current demo export was restored without modifying its 84 records or 87 audit events. Repeated initialization made no duplicate changes.

The startup initializer must run before the web server and requires a private, hash-pinned demo export when the database is missing. That export is not included in this repository or release. Existing database contents take priority. This release changes no credentials, roles, native signing, plans, or other services.

The existing free host has temporary storage. Its recovery snapshot preserves the data at this update, not subsequent edits after instance replacement. This remains a prototype with explicitly labeled synthetic readings. See `docs/MOBILE-R14.md` inside the archive.
