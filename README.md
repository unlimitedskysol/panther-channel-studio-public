# Panther Channel Studio Public

Standalone static download/update site.

Upload every file and the `assets` folder directly to the repository root.
Do not create a `public` folder and do not upload the ZIP itself.

Planned production domain:
`https://studio.panthergame.app`

Update manifests:
- `/update-v2.json`
- `/version.json`

The JSON manifests are configured with no-store/no-cache headers in `vercel.json`.

Important:
V7.0.14 is included only to test the new standalone hosting. Before public release,
build the next application version so its internal update checker uses:
`https://studio.panthergame.app/update-v2.json`
