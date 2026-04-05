# Cloesce VS Code Extension

Syntax highlighting for `.cloesce` and `.clo` schema files.

## Features

- Full syntax highlighting for the Cloesce schema language
- SQL highlighting inside `sql` blocks
- Bracket matching and auto-closing
- Region folding (`//#region` / `//#endregion`)

## Install from source

```bash
npm install -g @vscode/vsce
cd cloesce-vscode
vsce package
code --install-extension cloesce-0.1.0.vsix
```
