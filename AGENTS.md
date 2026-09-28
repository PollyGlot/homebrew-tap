# AGENTS.md : homebrew-tap

Tap Homebrew PollyGlot : casks dans `Casks/`, actuellement `gplay`
(Google Play Developer CLI), pour macOS et Linux.

- `Casks/gplay.rb` est écrit par GoReleaser (`homebrew_casks`) à chaque release
  du repo [google-play-cli](https://github.com/PollyGlot/google-play-cli), en
  push direct sur `main` : ne jamais exiger de PR ici, la release casserait.
  Ne pas éditer le cask à la main, il serait écrasé à la release suivante.
- `tap_migrations.json` renvoie l'ancienne formule `gplay` (jusqu'à 1.7.1) vers
  le cask ; le garder tant que des installations en formule peuvent exister.
- Valider le cask publié : `brew audit --cask --strict pollyglot/tap/gplay`.
