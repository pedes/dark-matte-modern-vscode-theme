# Mate Dim Theme

![VS Code](https://img.shields.io/badge/VS%20Code-Theme-2F80ED?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Dark](https://img.shields.io/badge/Style-Dark%20Dim-111827?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-0.0.1-22C55E?style=for-the-badge)

**A calm, matte, low-glare VS Code theme built for long coding sessions.**  
Mate Dim blends soft contrast, refined syntax accents, and balanced UI depth so your editor feels focused, not noisy.

## Why Developers Like It

- 🌙 `Dark-dim` surfaces that reduce visual fatigue
- 🎯 Semantic-first syntax colors for better code scanning
- 🧠 Clear diagnostics and git diff signals
- 🧩 Improved coverage for modern language tokenization
- 🧪 Tuned for real development workflows, not just screenshots

## Color Character

| Role | Color |
| --- | --- |
| Background | `#08090B` |
| Foreground | `#C7CCD6` |
| Keyword | `#8EA4CF` |
| Function | `#7FCB9E` |
| String | `#D1AF7E` |
| Number | `#E09B8A` |
| Comment | `#667083` |
| Added / Success | `#7FA98C` |
| Warning | `#D2AF74` |
| Error / Deleted | `#C97888` |

## Install and Use

### Option 1: Run in Extension Development Host (recommended while building)

1. Open this folder in VS Code.
2. Press `F5` to launch a new Extension Development Host window.
3. In the new window, open Command Palette.
4. Run `Preferences: Color Theme`.
5. Select **Mate Dim**.

### Option 2: Package and Install as VSIX

```bash
npm install -g @vscode/vsce
vsce package
```

Then in VS Code:

1. Open Command Palette.
2. Run `Extensions: Install from VSIX...`.
3. Select the generated `.vsix`.
4. Switch theme to **Mate Dim**.

## Best Experience Setup

- Use semantic highlighting: `Editor: Semantic Highlighting` -> `configuredByTheme` or `true`
- Use a programming ligature font if preferred (JetBrains Mono, Fira Code, Cascadia Code)
- Keep editor contrast at default first, then adjust workbench UI density

## Contributing

Ideas, tweaks, and language-specific token improvements are welcome.  
If a language looks off, open an issue with:

- file type / language
- screenshot
- token scope (if known)
- expected color behavior

---

Built for developers who want focus, clarity, and a modern dark matte aesthetic.
