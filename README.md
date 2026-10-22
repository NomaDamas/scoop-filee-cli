# Scoop bucket for filee-cli

[filee-cli](https://github.com/NomaDamas/filee-cli) is an **unofficial** redistribution of the command line of
[Filee](https://github.com/KnifeLemon/Filee): offline file conversion (255 formats) with the engines bundled.
Not made or endorsed by Filee's author.

```powershell
scoop bucket add filee-cli https://github.com/NomaDamas/scoop-filee-cli
scoop install filee-cli
filee-cli formats
filee-cli convert photo.heic --to jpg
```

Windows x64. About 900 MB (engines included); Scoop checks the SHA-256. macOS and Linux: see the
[Homebrew tap](https://github.com/NomaDamas/homebrew-filee-cli).

The manifest updates itself every few hours (`.github/workflows/update.yml`, Scoop's own `checkver`/`autoupdate`).
