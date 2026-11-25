# Scoop bucket for Oriel

[Oriel](https://oriel.charstudio.app/) is a free, open source browser for Windows, an unofficial port of Search, the browser for the Mac. This bucket installs it with [Scoop](https://scoop.sh/).

```powershell
scoop bucket add oriel https://github.com/carpaaaaa/scoop-oriel
scoop install oriel
```

Update and remove it the usual way:

```powershell
scoop update oriel
scoop uninstall oriel
```

- Scoop runs Oriel's own installer for your account, silently. Oriel updates itself afterwards, and `scoop update oriel` does too.
- The installer's SHA-256 is checked by Scoop against the one in this bucket, which comes from `SHA256SUMS.txt` on each [release](https://github.com/carpaaaaa/oriel/releases).
- Oriel isn't code-signed yet, so Windows may ask before it runs ("Windows protected your PC": More info, then Run anyway).
- Oriel is on x64 and ARM64 PCs.

Other ways to install it: [oriel.charstudio.app](https://oriel.charstudio.app/) (installer download), `winget install CharStudio.Oriel` once Microsoft's review is through, and the Microsoft Store.

Manifests here follow Oriel's releases by themselves (a check every few hours). Problems with Oriel go to [carpaaaaa/oriel](https://github.com/carpaaaaa/oriel/issues).
