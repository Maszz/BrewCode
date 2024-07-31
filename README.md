# BrewCode Theme

BrewCode is a unique coding editor theme that combines the rich, dark aesthetics of the Catppuccin theme with the professional, clean design of Xcode. This theme offers three variants to suit different preferences and enhance your coding experience.

This theme not have an light mode because I don't use light mode, but if you want to create a light mode, you can fork this repository and create a new variant. I will be happy to accept your pull request.

This is my personal theme that I use for coding. I have combined the Catppuccin theme with the Xcode theme to create a unique and visually appealing coding environment. I hope you enjoy using it as much as I do!

> [!NOTE]
> BrewCode is currently only available for Zed Editor.

## Variants

- **BrewCode Macchiato**

  - Combines the rich, dark tones of Macchiato with the professional look of Xcode. It features dark backgrounds with a variety of accent colors, providing a balanced and visually appealing experience for extended coding sessions.

- **BrewCode Frappe**

  - Integrates the light, refreshing shades of Frappe with the sleek, modern aesthetics of Xcode. This variant offers a mix of light and dark elements, creating a unique and comfortable coding environment.

- **BrewCode Mocha**
  - Blends the warm, inviting hues of Mocha with the clean, refined design of Xcode. This variant focuses on deep, warm colors that are easy on the eyes, perfect for long hours of coding.

## Installation

### Zed Editor

Download the theme JSON files

```bash
git clone https://github.com/Maszz/BrewCode
```

Place the JSON files in the following directory `~/.config/zed/themes`:

```bash
cp <dowloaded-dir>/brewcode-zed.json ~/.config/zed/themes/brewcode-zed.json
```

Change the theme in Zed settings JSON: ~/.config/zed/settings.json or press cmd + , to open settings.json

```json
{
  "theme": {
    "mode": "system",
    "dark": "BrewCode Macchiato"
  }
}
```

> If you prefer not to modify settings.json manually, you can use the Theme Selector by typing cmd+k, cmd+t.

## License

This project is licensed under the MIT License. See the [LICENCE](./LICENCE) file for details.

## Acknowledgements

- [Catppuccin](https://github.com/catppuccin/zed/tree/main)
- [Xcode Theme](https://github.com/MateoCerquetella/xcode-theme)

## Contribute

Contributions are welcome! If you have suggestions for improvements, feel free to create an issue or submit a pull request.
