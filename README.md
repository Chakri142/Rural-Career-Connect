# Rural Career Connect

## Open the website
Double-click the root `index.html` in Chrome or Edge. All art, fonts, and demo workflows are included. This is a local-data demonstration: use fictional information only. Each browser stores its own data.

## Publish the demo with GitHub Pages
Extract this ZIP and upload the **contents**, not the ZIP. Put `index.html` at the root of the repository. Commit to `main`. In Settings → Pages choose Deploy from a branch → main → / (root), then save. Open the site URL shown by Pages after deployment. If you only want the demo, uploading the root `index.html` is enough.

## Server edition
`server/` contains the separate Spring Boot/MySQL project. See `server/README.md` for Docker Compose and Maven instructions. To rebuild the executable JAR run `mvn package` inside `server/`. GitHub Pages does not run Java or MySQL.

The generated JAR, private credentials, and build directories are intentionally excluded. Keep your offline administrator sign-in note private.
