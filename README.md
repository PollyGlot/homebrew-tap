# homebrew-tap
Homebrew tap for PollyGlot tools, currently hosting gplay (Google Play Developer CLI) as a cask, on macOS and Linux.

```sh
brew install PollyGlot/tap/gplay
```

Installed gplay 1.x as a formula? brew does not switch a formula install to a cask on its own:

```sh
brew uninstall --formula gplay
brew install --cask PollyGlot/tap/gplay
```
