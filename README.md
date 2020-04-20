# VS Code Preferences

Here is the list of my personal settings, extensions, themes, icons and fonts for VS Code. The list is bound to grow with the amount of time I spent with VS Code. Asterisks (*) items are currently being used and enabled.



## Themes

- [Monokai Pro](https://marketplace.visualstudio.com/items?itemName=monokai.theme-monokai-pro-vscode&ssr=false) * - Comes with themes and icons.



## Icons

- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) *



## Font

- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) * - Install as system font and see `settings.json` for how to select.



## Extensions

- [IntelliJ IDEA Keybindings](https://marketplace.visualstudio.com/items?itemName=k--kato.intellij-idea-keybindings) * - Being a user of PHPStorm, WebStorm and PyCharm, this extension is a must.
- [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) * - Side by side markdown (*.md) file view and edit.
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) * - Is a must have.
- [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost) * - See imported npm package size.
- [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets) * - Self explanatory.
- [Auto Complete Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-complete-tag) * - Two packages at one.
- [NPM Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) * - Autocompletes npm modules in import statements.
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) * - Autocompletes project directories and filenames.
- [Simple React Snippets](https://marketplace.visualstudio.com/items?itemName=burkeholland.simple-react-snippets) * - Self explanatory.
- [Current File Path](https://marketplace.visualstudio.com/items?itemName=YoshinoriN.current-file-path) * - Show the currently open file location in status bar.



## Settings

Here is the current settings configuration I am using and comfortable with. Update VS Code's `settings.json` with this one. I am using third party terminal [Cmder](https://cmder.net/) that supports autocomplete commands and there is settings for making **Cmder** as default shell in VS Code.

```json
{
    "window.zoomLevel": 0,
    "workbench.startupEditor": "newUntitledFile",
    "workbench.colorTheme": "Monokai Pro",
    "workbench.iconTheme": "material-icon-theme",
    "gitlens.hovers.currentLine.over": "line",
    "files.autoSave": "onWindowChange",
    "editor.tabSize": 2,
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.wordWrap": "on",
    "editor.fontFamily": "'JetBrains Mono Medium', Consolas, 'Courier New', monospace",
    "editor.fontLigatures": true,
    "explorer.confirmDelete": false,
    "editor.formatOnPaste": true,
    "editor.quickSuggestions": {
        "other": true,
        "comments": false,
        "strings": false
    },
    "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\cmd.exe",
    "terminal.integrated.shellArgs.windows": ["/k C:\\Cmder\\vendor\\init.bat"],
    "files.exclude": {
        "**/.idea": true,
        "**/.vscode": true
    },
    "javascript.updateImportsOnFileMove.enabled": "always",
}
```

