VSCodium Customization

This repository contains my personalized settings for VSCodium, including a list of extensions that enhance my development experience, and some useful keyboard shortcuts for VSCodium.

## 🛠 VS Code Settings
```bash
  {
  // Editor Settings
  "editor.fontSize": 18,                         // Font size for the editor
  "editor.fontFamily": "Operator Mono, Fira Code", // Font family for the editor
  "editor.fontLigatures": true,                   // Enable font ligatures
  "editor.wordWrap": "on",                       // Enable word wrapping
  "editor.minimap.enabled": false,               // Disable minimap
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "comment",
        "settings": {
          "fontStyle": "italic"                   // Italicize comments
        }
      }
    ]
  },
  "editor.cursorSmoothCaretAnimation": "on",     // Enable smooth caret animation
  "editor.cursorBlinking": "expand",             // Set cursor blinking style
  "editor.defaultFormatter": "HookyQR.beautify", // Default code formatter
  "editor.formatOnSave": true,                   // Format code on save
  "[javascript]": {
    "editor.formatOnSave": false,
    "editor.defaultFormatter": null
  },
  "[javascriptreact]": {
    "editor.formatOnSave": false,
    "editor.defaultFormatter": null
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit",          // Configure ESLint on save
    "source.fixAll.tslint": "explicit",          // Configure TSLint on save
    "source.organizeImports": "explicit"         // Organize imports on save
  },
  "eslint.alwaysShowStatus": true,               // Always show ESLint status

  // Terminal Settings
  "terminal.integrated.fontSize": 16,           // Terminal font size
  "terminal.integrated.fontWeight": "normal",   // Terminal font weight
  "terminal.integrated.fontFamily": "Fira Code, Operator Mono", // Terminal font family

  // Workbench Settings
  "workbench.colorTheme": "Community Material Theme Ocean High Contrast", // Color theme for the workbench
  "workbench.iconTheme": "material-icon-theme", // Icon theme for the workbench
  "workbench.colorCustomizations": {
    "terminal.background": "#1D2021",           // Terminal background color
    "terminal.foreground": "#A89984",           // Terminal text color
    "terminalCursor.background": "#A89984",     // Terminal cursor background color
    "terminalCursor.foreground": "#A89984",     // Terminal cursor text color
    // ... Additional color customizations for the terminal
  },

  // Other Settings
  "files.autoSave": "afterDelay",               // Auto-save files after a delay
  "workbench.productIconTheme": "Tabler"        // Product icon theme for the workbench
}


```

## ⚙️ VS Code Extension & Themes
- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) by formulahendry: Automatically closes HTML and XML tags.
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) by formulahendry: Automatically renames paired HTML and XML tags.
- [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify) by HookyQR: Beautifies and formats code for various languages.
- [Community Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-community-material-theme) by Equinusocio: A visually pleasing material theme for the VS Codium workbench.
- [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css) by ecmel: Adds autocompletion and syntax support for HTML and CSS.
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) by ritwickdey: Launches a local development server with live reloading for web development.
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) by PKief: Adds Material Design icons to your files in the VS Codium explorer.
- [Tabler Product Icons](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme) by zguolee: A set of high-quality product icons for VS Codium.


## 🔑 VS Code Keyboard Shortcuts 

| Keyboard Shortcuts | Linux / Windows     | Mac   |
| :-------- | :------- | :-------------------------------- |
|  HTML boilerplate  |  ! + TAB | ! + TAB |
|  Open the palette to search for a file  | Ctrl + P | cmd + P |
|  Add cursors to all matching selections  | Ctrl + Shift + L  | cmd + Shift + L |
|  Undo  |  Ctrl + U | cmd + U |
|  Select Current Line  | Ctrl + L | cmd + L |
|  Zen Mode  | Ctrl + K Z | cmd + K Z |
|  Toggle Sidebar  | Ctrl + B | cmd + B |
|  Search Global Files  | Ctrl + Shift + F | Ctrl + Shift + F |
|  Search on file  | Ctrl + F | cmd + F |
|  Find and Replace  | Ctrl + H | cmd + H |
|  Delete the previous Word  | Ctrl + Backspace | cmd + Backspace |
|  Move line up/Down  | Alt + up/down arrow | option + up/down arrow |
|  Add multiple cursors  | Ctrl + Alt +up/down arrow | cmd + option + up/down arrow |
|  Comment Line  | Ctrl + / | cmd + / |
|  Comment Line  | Ctrl + K + Ctrl + C | cmd + K + cmd + C |
|  Split View  | Ctrl + \  | cmd + \ |
|  Switch Between views |  Ctrl +1, Ctrl + 2 .. | cmd + 1, cmd + 2 |
|  Duplicate Line  | Alt + Shift + up/down | option + Shift + up/down |
|  Navigate to a specific line  | Ctrl + g | cmd + G |
|  Open Terminal | Ctrl + ` | cmd + ` |
|  To Show suggestion | Ctrl + Space | cmd + space |
|  To Close a TAB | Ctrl + W | cmd + W |
|  To Close all TAB | Ctrl + Shift + W | cmd + Shift + W |


## ✒ Font Info
- [Fira Code](https://fonts.google.com/specimen/Fira+Code)
- [Operator Mono](https://github.com/keyding/Operator-Mono)
