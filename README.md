# DorkBrown — a tan + jungle-green dark brown theme for VS Code

DorkBrown is a cozy, high-contrast dark brown theme with tan foregrounds and subtle jungle-green accents. It’s designed to be easy on the eyes while keeping code structure clear.

## Features

- Tan text on a deep brown canvas for comfortable reading
- Jungle-green accents for selection, cursor, strings, functions, and keywords
- Thoughtful contrast for comments and punctuation

## Palette

- Editor background: `#2A211C`
- Foreground (tan): `#D7C29E`
- Selection: `#3B463D`
- Cursor: `#A3D9A5`
- Strings: `#9EC78A`
- Functions: `#7DBF9B`
- Keywords: `#6FAF7A`
- Operators/regex/escapes: `#74B3A5`

## Install (local dev)

1. Open this folder in VS Code.
2. Press `F5` to launch an Extension Development Host.
3. In the new window, press `Cmd+K Cmd+T` and choose `DorkBrown`.
4. Edit `themes/DorkBrown-color-theme.json`, save, then press `Cmd+R` in the dev host to reload.

## Packaging (optional)

To package a `.vsix`, install `vsce` and run:

```bash
npm install -g @vscode/vsce
vsce package
```

Then install it via VS Code’s Extensions view overflow menu: “Install from VSIX…”.

## Contributing

Issues and tweaks welcome. If you prefer different contrast for comments, strings, or numbers, open an issue or PR with screenshots of problem areas and suggestions.

## License

MIT
