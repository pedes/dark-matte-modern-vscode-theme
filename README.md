# Mate Dim Theme

A modern, matte dark VS Code theme designed to feel dim, calm, and polished.

## Style goals

- Low-glare dark surfaces
- Soft contrast that remains readable
- Muted accent colors (sage, steel blue, dusted amber)
- A more refined look than standard high-contrast dark themes

## Local usage

1. Open this folder in VS Code.
2. Run `Extensions: Install from VSIX...` only if you package it, or use Extension Development Host:
3. Press `F5` in this folder to launch a Development Host.
4. In the new window, run `Preferences: Color Theme` and select **Mate Dim**.

## Package as VSIX (optional)

```bash
npm install -g @vscode/vsce
vsce package
```

Then install the generated `.vsix` file.
