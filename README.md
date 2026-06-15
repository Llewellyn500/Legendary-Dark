<div align="center">

<img src="images/Logo.png" alt="Legendary Dark logo" width="120">

# Legendary Dark

A dark editor theme for VS Code and Zed, combining Andromeda's deep UI feel with vivid SynthWave '84-inspired syntax colors.

[![GitHub release](https://img.shields.io/github/v/release/Llewellyn500/Legendary-Dark?style=for-the-badge&logo=github&color=0b8eed)](https://github.com/Llewellyn500/Legendary-Dark/releases/latest)
[![Visual Studio Marketplace](https://img.shields.io/visual-studio-marketplace/v/LlewellynPaintsil.legendary-dark?style=for-the-badge&logo=visualstudiocode&color=007acc)](https://marketplace.visualstudio.com/items?itemName=LlewellynPaintsil.legendary-dark)
[![Downloads](https://img.shields.io/visual-studio-marketplace/d/LlewellynPaintsil.legendary-dark?style=for-the-badge&color=4cbe6c)](https://marketplace.visualstudio.com/items?itemName=LlewellynPaintsil.legendary-dark)
[![Rating](https://img.shields.io/visual-studio-marketplace/stars/LlewellynPaintsil.legendary-dark?style=for-the-badge&color=f6c343)](https://marketplace.visualstudio.com/items?itemName=LlewellynPaintsil.legendary-dark)

</div>

![Legendary Dark screenshot](images/dark.jpg)

## VS Code

Install Legendary Dark from the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=LlewellynPaintsil.legendary-dark), or install it from the command line:

```sh
code --install-extension LlewellynPaintsil.legendary-dark
```

Then open the theme picker and select `Legendary Dark`.

VS Code's built-in bracket pair colorization and indentation guides pair well with this theme.

## Zed

Zed support lives in the [`zed/`](zed/) folder. The Zed extension ID is `legendary-dark-theme`.

Until the Zed Extension Gallery submission is merged, install it as a dev extension:

1. Open Zed.
2. Open the command palette.
3. Run `zed: install dev extension`.
4. Select this repository's `zed/` folder, not the repository root.
5. Open the theme selector and choose `Legendary Dark`.

You can also install the theme file manually by copying [`zed/themes/legendary-dark.json`](zed/themes/legendary-dark.json) to your Zed themes directory:

- Windows: `%USERPROFILE%\AppData\Roaming\Zed\themes\`
- macOS/Linux: `~/.config/zed/themes/`

Restart Zed if the theme does not appear immediately.

## Repository Layout

```text
zed/                                           Zed theme extension
zed/extension.toml                             Zed extension manifest
zed/themes/legendary-dark.json                 Zed theme
vscode/themes/Legendary Dark-color-theme.json  VS Code theme
images/                                        Logo and screenshot
```

## Publishing

Zed registry submission details are in [`ZED_PUBLISHING.md`](ZED_PUBLISHING.md).

## License

[MIT](LICENSE.md)
