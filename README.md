# felipembassi.github.io

The root of the GitHub Pages domain. The app pages live in [felipembassi/apps](https://github.com/felipembassi/apps)
(served at /apps/); this repo only holds what must sit at the domain root:

- `.well-known/assetlinks.json`: Android App Links for Lunido, so invite links
  (https://felipembassi.github.io/apps/lunido/android/join/#CODE) open the app. List every signing key's SHA-256:
  the debug key, the upload key (scripts/bundle.sh builds) and the Play App Signing key (installs from Play;
  Play Console › Test and release › App integrity).
- `.nojekyll`: Jekyll would skip the dot folder.
- `index.html`: sends the bare domain to /apps/.
