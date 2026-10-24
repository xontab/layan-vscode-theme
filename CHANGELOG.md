# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2026-10-24
### Added
- Open VSX publishing, so the theme can be installed in Cursor, Windsurf, VSCodium, Gitpod and Eclipse Theia
- GitHub Actions workflow that publishes to the Visual Studio Marketplace and Open VSX on version tags
- Richer syntax highlighting: functions, types, classes, variables, parameters, constants, control-flow keywords, decorators and regex parts are now coloured, and semantic highlighting is enabled ([#1](https://github.com/xontab/layan-vscode-theme/issues/1))

### Fixed
- `header` scope was navy and unreadable on the dark background
- Visual Studio Marketplace badge in the README (the old badge service is gone)

## [1.0.0] - 2019-12-29
### Added
- Colour Scheme based on Layan GTK Theme