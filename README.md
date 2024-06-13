# Atom-One-Dracula Theme

A custom Visual Studio Code theme that combines the Atom One Dark theme with Dracula Soft syntax highlighting, created by [Austin Spraggins](https://github.com/spragginsdesigns).

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Atom-One-Dracula is a Visual Studio Code theme that blends the sleek, dark aesthetics of the Atom One Dark theme with the vibrant, high-contrast syntax highlighting of the Dracula Soft theme. This theme aims to provide a visually appealing and easy-to-read coding environment.

## Installation

To install the Atom-One-Dracula theme in Visual Studio Code, follow these steps:

1. **Download the Theme Files**: Download the `one-dark-dracula.json` and `package.json` files from this repository.

2. **Create the Theme Directory**: Navigate to your VS Code extensions folder:
   ```
   C:\Users\Owner\.vscode\extensions
   ```

3. **Add the Theme Files**: Create a new folder named `one-dark-dracula-theme` and place the downloaded `one-dark-dracula.json` and `package.json` files inside this folder.

4. **Reload VS Code**: Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS) to open the Command Palette and type `Developer: Reload Window` to reload VS Code.

## Usage

After reloading VS Code, you can activate the Atom-One-Dracula theme:

1. **Open the Command Palette**: Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS) to open the Command Palette.
2. **Select Color Theme**: Type `Preferences: Color Theme` and press Enter.
3. **Choose One Dark Dracula**: Select `One Dark Dracula` from the list of available themes.

## Customization

You can further customize the theme by editing the `one-dark-dracula.json` file. This file defines the color scheme and styles for various UI elements and syntax highlighting.

### Example Customization

To change the background color of the editor, modify the `editor.background` property in `one-dark-dracula.json`:

```json
{
  "colors": {
    "editor.background": "#1e1e1e",
    ...
  },
  ...
}
```

After making changes, reload VS Code to apply the new settings.

## Contributing

We welcome contributions to improve the Atom-One-Dracula theme! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them with clear, descriptive messages.
4. Push your changes to your fork and create a pull request.

Please ensure your code adheres to the project's coding standards and includes appropriate documentation.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
