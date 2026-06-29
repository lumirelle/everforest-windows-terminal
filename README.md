# Everforest for Windows Terminal

Six variants: dark/light × hard/medium/soft.

## Sources

- Colors: [everforest/nvim `palette.md`](https://github.com/everforest/nvim/blob/main/palette.md)
- ANSI mapping: [sainnhe/everforest `colors/everforest.vim`](https://github.com/sainnhe/everforest/blob/master/colors/everforest.vim)

## Mapping

| Key | Dark | Light |
|-----|------|-------|
| background | bg0 | bg0 |
| foreground | fg | fg |
| cursorColor | fg | fg |
| selectionBackground | bg_visual | bg_visual |
| black | bg3 | fg |
| white | fg | bg3 |
| cyan | aqua | aqua |
| tab.background | bg0 | bg0 |
| tabRow.background | bg_dim | bg_dim |

## Usage

Copy the variant you want:

1. Copy the raw content of `variant.jsonc` into `schemes` field of Windows Terminal's configuration file `settings.json`;
2. Copy the raw content of `variantTheme.jsonc` into `themes` field of Windows Terminal's configuration file `settings.json`;
3. Choose the scheme and theme in Windows Terminal's settings;
4. Enjoy!