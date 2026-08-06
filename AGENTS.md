# CLAUDE.md

Tap Homebrew PollyGlot — formules dans `Formula/`, actuellement `gplay`
(Google Play Developer CLI).

- Bump de version = mettre à jour `url` + `sha256` dans la formule ; les
  binaires et release notes viennent du repo
  [google-play-cli](https://github.com/PollyGlot/google-play-cli).
- Valider une formule modifiée :
  `brew install --build-from-source ./Formula/gplay.rb && brew audit --strict gplay`.
