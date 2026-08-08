# Kids Coloring Parent Web Export

Static HTML export for the parent-facing URLs used by `ParentAreaView`.

## Routes

- `https://minmon98.github.io/KidsColoringLegal/privacy/` -> `privacy/index.html`
- `https://minmon98.github.io/KidsColoringLegal/terms/` -> `terms/index.html` (Terms of Use / EULA)
- `https://minmon98.github.io/KidsColoringLegal/support/` -> `support/index.html`

`Refund Help` opens Apple's `https://reportaproblem.apple.com/` directly from the app, so no hosted page is required for that action.

## App Store Metadata

For apps with auto-renewable subscriptions, include these links in the App Description or the subscription review notes:

Terms of Use (EULA): `https://minmon98.github.io/KidsColoringLegal/terms/`

Privacy Policy: `https://minmon98.github.io/KidsColoringLegal/privacy/`

## Hosting Notes

- Copy the full `web-parent-export` folder contents into the root of the hosting repo.
- Keep `assets/styles.css` with the route folders.
- Configure the host to serve extensionless routes from each folder's `index.html`.
- Support contact: `phivanminh10@gmail.com`.
