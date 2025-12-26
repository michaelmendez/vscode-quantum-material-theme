# Quantum Material Theme

A sleek, modern theme inspired by quantum physics and material design principles

Quantum Material Theme brings the elegance of material design to your coding environment with a sophisticated color palette that reduces eye strain while maintaining excellent readability and syntax highlighting. Available in dark, light, and void variants to match your coding preference.

## Features

- Carefully crafted color palette - Deep quantum-inspired blues and purples with high contrast
- Multiple theme variants - Choose between dark, light, and ultra-dark void themes
- Reduced eye strain - Optimized for long coding sessions
- Enhanced readability - Clear distinction between different code elements
- Semantic highlighting - Consistent color coding across all languages
- True dark themes - Perfect for low-light environments
- Clean light theme - Elegant light variant for bright environments
- Borderless design - Minimalistic interface with seamless UI elements
- Performance optimized - Lightweight and fast loading

## Screenshots

### Dark Theme

![Quantum Material Theme Dark](https://raw.githubusercontent.com/michaelmendez/quantum-material-theme/main/sample-dark.png)

### Void Theme

![Void Material Theme Dark](https://raw.githubusercontent.com/michaelmendez/quantum-material-theme/main/sample-void-dark.png)

### Light Theme

![Quantum Material Theme Light](https://raw.githubusercontent.com/michaelmendez/quantum-material-theme/main/sample-light.png)

## Installation

### Via VS Code Marketplace (Recommended)

1. Open **Extensions** sidebar panel in VS Code (`Ctrl+Shift+X`)
2. Search for `Quantum Material Theme`
3. Click **Install** to install it
4. Go to **File** > **Preferences** > **Theme** > **Color Theme** and select your preferred variant:
   - `Quantum Material Theme (Dark)` - Classic dark theme
   - `Void Material Theme (Dark)` - Ultra-dark minimalistic theme
   - `Quantum Material Theme (Light)` - Clean light theme

### Via Command Palette

1. Open **Command Palette** (`Ctrl+Shift+P`)
2. Type `ext install michaelmendez.quantum-material-theme`
3. Press **Enter**

### Manual Installation

1. Download the latest `.vsix` file from [releases](https://github.com/michaelmendez/quantum-material-theme/releases)
2. Open **Command Palette** (`Ctrl+Shift+P`)
3. Type `Extensions: Install from VSIX...`
4. Select the downloaded `.vsix` file

## Color Palette

The theme uses a carefully selected color palette designed for optimal contrast and readability:

### Dark Theme

| Element      | Hex Code  |
| ------------ | --------- |
| Background   | `#101119` |
| Primary Blue | `#739cf0` |
| Text         | `#EEEEEE` |
| Comments     | `#666666` |

### Void Theme

| Element      | Hex Code  |
| ------------ | --------- |
| Background   | `#0b0a0b` |
| Primary Blue | `#6b8dd6` |
| Text         | `#d0d0d0` |
| Comments     | `#4a4a4a` |

### Light Theme

| Element      | Hex Code  |
| ------------ | --------- |
| Background   | `#fafafa` |
| Primary Blue | `#4b7bdb` |
| Text         | `#263238` |
| Comments     | `#90a4ae` |

## Recommended Setup

For the best experience, pair this theme with the following extensions and settings:

### Font

- [FiraCode Nerd Font](https://www.nerdfonts.com/font-downloads) - A monospaced font with programming ligatures and Nerd Font icons

Add to your VS Code settings:

```json
{
  "editor.fontFamily": "'FiraCode NF', Consolas, 'Courier New', monospace",
  "editor.fontLigatures": true
}
```

### Icon Themes

- [Bearded Icons](https://marketplace.visualstudio.com/items?itemName=BeardedBear.beardedicons) - A sober theme of file icons for VS Code
- [Carbon Product Icons](https://marketplace.visualstudio.com/items?itemName=antfu.icons-carbon) - Carbon Design System icons as product icons for VS Code

Add to your VS Code settings:

```json
{
  "workbench.iconTheme": "bearded-icons",
  "workbench.productIconTheme": "icons-carbon"
}
```

## Customization

You can customize the theme to your liking by modifying your VS Code settings:

```json
{
  "workbench.colorCustomizations": {
    "[Quantum Material Theme]": {
      "editor.background": "#0f0f0f",
      "activityBar.background": "#0f0f0f"
    }
  },
  "editor.tokenColorCustomizations": {
    "[Quantum Material Theme]": {
      "comments": "#888888"
    }
  }
}
```

## Contributing

Contributions are welcome! Please read our [contributing guidelines](CONTRIBUTING.md) before submitting PRs.

### Development Setup

1. Clone this repository
2. Open in VS Code
3. Press `F5` to launch Extension Development Host
4. Make your changes and test them
5. Submit a pull request

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for a detailed history of changes.

## Issues & Feedback

Found a bug or have a suggestion? Please [open an issue](https://github.com/michaelmendez/quantum-material-theme/issues) on GitHub.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Enjoy coding with Quantum Material Theme

Author: [Michael Mendez](https://github.com/michaelmendez)
