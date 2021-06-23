<p align="center">
  <img alt="KomoRebi Dark Logo" src="https://github.com/ChubsB/KomoRebi-Dark/blob/master/images/logo.png" width="500" />
</p>
<h1 align="center">
  KomoRebi Dark Theme for VS Code
</h1>
<p align="center">
  A minimal dark theme for <a href="https://halcyon-theme.netlify.com/">VS Code, Atom, Sublime Text, and more</a>.
</p>
<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=brittanychiang.halcyon-vscode">
    <img alt="Version" src="https://vsmarketplacebadge.apphb.com/version/brittanychiang.halcyon-vscode.svg" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=brittanychiang.halcyon-vscode">
    <img alt="Downloads" src="https://vsmarketplacebadge.apphb.com/downloads/brittanychiang.halcyon-vscode.svg" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=brittanychiang.halcyon-vscode">
    <img alt="Installs" src="https://vsmarketplacebadge.apphb.com/installs/brittanychiang.halcyon-vscode.svg" />
  </a>
</p>

![demo](https://github.com/ChubsB/KomoRebi-Dark/blob/master/images/Demo.png)

## Installation via VS Code

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `KomoRebi Dark`
3. Click **Install** to install it
4. Click **Reload** to reload the editor
5. Code > Preferences > Color Theme > **KomoRebi Dark**

## Manual Installation

Read the [VSC Extension Quickstart Guide](https://github.com/ChubsB/KomoRebi-Dark/blob/master/vsc-extension-quickstart.md)

## Icon Theme

The file icon theme seen in the screenshot above is [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) with these settings:

```json
  "material-icon-theme.folders.color": "#8695b7",
  "material-icon-theme.folders.theme": "specific",
  "material-icon-theme.hidesExplorerArrows": true,
```

## Color Reference

### Syntax Colors

|                               Color                                | Usage                                           |
| :----------------------------------------------------------------: | ----------------------------------------------- |
| ![#C286FF](https://via.placeholder.com/10/c3a6ff?text=+) `#c3a6ff` | Keywords, constants, template literals          |
| ![#FFD564](https://via.placeholder.com/10/ffd580?text=+) `#ffd580` | Functions, classes, object literal keys         |
| ![#D99623](https://via.placeholder.com/10/ffae57?text=+) `#ffae57` | Constants, operators                            |
| ![#BDE86B](https://via.placeholder.com/10/bae67e?text=+) `#bae67e` | Strings, markdown headings                      |
| ![#5ccfe6](https://via.placeholder.com/10/5ccfe6?text=+) `#5ccfe6` | Special keywords, classes, markdown code blocks |
| ![#a2aabc](https://via.placeholder.com/10/a2aabc?text=+) `#a2aabc` | Variables, property names, tags                 |

### UI Colors

|                               Color                                | Usage                                      |
| :----------------------------------------------------------------: | ------------------------------------------ |
| ![#10141A](https://via.placeholder.com/10/171c28?text=+) `#171c28` | Workbench background                       |
| ![#171e26](https://via.placeholder.com/10/1d2433?text=+) `#1d2433` | Editor background                          |
| ![#222C38](https://via.placeholder.com/10/2f3b54?text=+) `#2f3b54` | Highlight, widgets, panels                 |
| ![#65799C](https://via.placeholder.com/10/6679a4?text=+) `#6679a4` | Dividers, subtle UI elements               |
| ![#65799C](https://via.placeholder.com/10/8695b7?text=+) `#8695b7` | Status bar text, buttons, etc              |
| ![#d7dce2](https://via.placeholder.com/10/d7dce2?text=+) `#d7dce2` | Active text, anything that should be white |
| ![#EDBE47](https://via.placeholder.com/10/ffcc66?text=+) `#ffcc66` | Accent, list tree titles, badges, etc      |
| ![#BDE86B](https://via.placeholder.com/10/bae67e?text=+) `#bae67e` | Addition highlights                        |
| ![#E85D72](https://via.placeholder.com/10/ef6b73?text=+) `#ef6b73` | Deletion highlights, errors, warnings      |
| ![#5ccfe6](https://via.placeholder.com/10/5ccfe6?text=+) `#5ccfe6` | Modified highlights                        |

## Theming Reference

[VS Code Theme Color Reference](https://code.visualstudio.com/docs/getstarted/theme-color-reference)

[VS Code Theme Documentation](https://code.visualstudio.com/docs/extensions/themes-snippets-colorizers)

[VS Code Publishing Extensions](https://code.visualstudio.com/docs/extensions/publish-extension)

Heavily inspired by [Halcyon Theme](https://github.com/bchiang7/halcyon-vscode)

```bash
vsce publish patch/minor/major
```

## Dont use VS Code?

KomoRebi Dark is also available for [Sublime Text, Atom, iTerm, and more!](https://halcyon-theme.netlify.com/).
