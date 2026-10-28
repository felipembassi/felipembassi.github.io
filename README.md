# felipembassi.github.io

The root of the GitHub Pages domain. The app pages live in [felipembassi/apps](https://github.com/felipembassi/apps)
(served at /apps/); this repo only holds what must sit at the domain root:

- `.well-known/assetlinks.json`: Android App Links for Lunido, so invite links
  (https://felipembassi.github.io/apps/lunido/android/join/#CODE) open the app. List every signing key's SHA-256:
  today the debug key; add the upload key and the Play App Signing key (Play Console › Test and release › App
  integrity) before release.
- `.nojekyll`: Jekyll would skip the dot folder.
- `index.html`: sends the bare domain to /apps/.
