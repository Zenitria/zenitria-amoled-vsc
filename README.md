# Zenitria AMOLED Visual Studio Code

Best AMOLED theme for Visual Studio Code.

## Screenshots

<p align="center">
    <img src="https://raw.githubusercontent.com/Zenitria/zenitria-amoled-vsc/master/screenshots/1.png" width="600"/>
    <img src="https://raw.githubusercontent.com/Zenitria/zenitria-amoled-vsc/master/screenshots/2.png" width="600"/>
    <img src="https://raw.githubusercontent.com/Zenitria/zenitria-amoled-vsc/master/screenshots/3.png" width="600"/>
    <img src="https://raw.githubusercontent.com/Zenitria/zenitria-amoled-vsc/master/screenshots/4.png" width="600"/>
</p>

## Build and install

1. Install vsce

```bash
npm i -g @vscode/vsce
```

2. Build theme

```bash
vsce package
```

3. Install theme

```bash
code --install-extension zenitria-amoled-x.x.x.vsix
```

## Recommended settings

This is my recommended settings. Open your `settings.json` by clicking `CTRL + SHIFT + P` or `CMD + SHIFT + P` and choice `Preferences: Open User Settings (JSON)` then change your settings to this.

```json
"editor.fontFamily": "'JetBrains Mono', monospace",
"editor.fontSize": 12,
"editor.fontWeight": "300",
"editor.lineHeight": 20,
"editor.letterSpacing": 0.5,
"editor.fontLigatures": true,
"editor.cursorBlinking": "smooth",
```
