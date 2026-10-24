# Layan Theme [![Visual Studio Marketplace][MarketplaceBadge]][Marketplace] [![Open VSX][OpenVSXBadge]][OpenVSX]

[Marketplace]: https://marketplace.visualstudio.com/items?itemName=xonTAB.layan-theme
[MarketplaceBadge]: https://vsmarketplacebadges.dev/version-short/xonTAB.layan-theme.svg
[OpenVSX]: https://open-vsx.org/extension/xonTAB/layan-theme
[OpenVSXBadge]: https://img.shields.io/open-vsx/v/xonTAB/layan-theme?label=Open%20VSX

Layan theme is based on the popular [Layan GTK theme](https://github.com/vinceliuice/Layan-gtk-theme) 

## Install

The theme is published to both the [Visual Studio Marketplace][Marketplace] and [Open VSX][OpenVSX], so it works in VS Code and the editors built on it.

| Editor | Registry |
| --- | --- |
| VS Code | Visual Studio Marketplace |
| Cursor | Open VSX |
| Windsurf | Open VSX |
| VSCodium | Open VSX |
| Gitpod / Eclipse Theia / code-server | Open VSX |

In any of them, open the Extensions view (`CTRL`/`Command` + `Shift` + `x`), search for **Layan Theme** and install it. Or press `CTRL`/`Command` + `p` and run

```
ext install xonTAB.layan-theme
```

Then select it with **Preferences: Color Theme** → **Layan (Dark)**.

### Manual install

Download the `.vsix` from the [releases page](https://github.com/xontab/layan-vscode-theme/releases) (or build it with `npm run package`), then run **Extensions: Install from VSIX...** from the command palette.

## Screenshot

![Dark Theme Screenshot](https://github.com/xontab/layan-vscode-theme/raw/master/screenshot.png)

## Colour Theme Based on

* VS Code Dark Theme
* [Layan GTK theme](https://github.com/vinceliuice/Layan-gtk-theme) 

## Publishing

Pushing a `v*` tag runs the [publish workflow](.github/workflows/publish.yml), which packages the extension and publishes it to the Visual Studio Marketplace (`VSCE_PAT` secret) and Open VSX (`OVSX_PAT` secret). To publish by hand, run `npm run publish` with those tokens in your environment.

## Contributors

**Would you like to contribute?** - Open a [new issue](https://github.com/xontab/layan-vscode-theme/issues) or [pull request](https://github.com/xontab/layan-vscode-theme/pulls) on GitHub.
