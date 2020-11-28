# VS Code Preferences

Here is the list of my personal settings, extensions, themes, icons and fonts for VS Code. The list is bound to grow with the amount of time I spent with VS Code. Asterisks (*) items are currently being used and enabled in my workspace.



## Themes

- [Monokai Pro](https://marketplace.visualstudio.com/items?itemName=monokai.theme-monokai-pro-vscode&ssr=false) * - Comes with themes and icons.
- [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme) - A good dark theme.



## File Icon Themes

- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) * - Theme for vscode sidebar icons.



## Font

- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) * - Install as system font and see `settings.json` for how to select.



## Extensions

### Universal

- [IntelliJ IDEA Keybindings](https://marketplace.visualstudio.com/items?itemName=k--kato.intellij-idea-keybindings) * - Being a user of PHPStorm, WebStorm and PyCharm, this extension is a must.
- [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) * - Side by side markdown (*.md) file view and edit.
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) * - Is a must have.
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) * - Autocompletes project directories and filenames.
- [File Utils](https://marketplace.visualstudio.com/items?itemName=sleistner.vscode-fileutils) * - Great for copy/pasting file with renaming.
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)* - Checks typing errors and suggests fix.
- [Highlight Matching Tag](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag) * - Highlights opening and closing tags on select.
- [Indented Block Highlighting](https://marketplace.visualstudio.com/items?itemName=byi8220.indented-block-highlighting) * - Highlights code block area.
- [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) * - Highlights color code block.
- [Current File Path](https://marketplace.visualstudio.com/items?itemName=YoshinoriN.current-file-path) - Show the currently open file location in status bar.



### JavaScript & React

- [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost) * - See imported npm package size.
- [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets) * - Self explanatory.
- [NPM Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) * - Autocompletes npm modules in import statements.
- [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets) * - All in one useful snippets.
- [Simple React Snippets](https://marketplace.visualstudio.com/items?itemName=burkeholland.simple-react-snippets) - Some easy to remember snippets for files.



### PHP & Laravel & HTML & CSS

- [PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client) * - PHP and HTML autocomplete and format mix support.
- [Laravel Artisan](https://marketplace.visualstudio.com/items?itemName=ryannaddy.laravel-artisan) - Easily access artisan commands from vscode command.
- [Auto Complete Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-complete-tag) * - Two packages in one.
- [Laravel Goto View](https://marketplace.visualstudio.com/items?itemName=codingyu.laravel-goto-view) * - Go to blade view from controllers.
- [Laravel Goto Controller](https://marketplace.visualstudio.com/items?itemName=stef-k.laravel-goto-controller) * - Go to controller from routes file.
- [Laravel Extra Intellisense](https://marketplace.visualstudio.com/items?itemName=amiralizadeh9480.laravel-extra-intellisense) * - Better intellisense for laravel projects.
- [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv) * - Laravel .env file support.
- [Laravel Blade](https://marketplace.visualstudio.com/items?itemName=amirmarmul.laravel-blade-vscode) * - Blade Snippets, Syntax Highlighting and Formatting for VS Code.
- [Laravel Blade Spacer](https://marketplace.visualstudio.com/items?itemName=austenc.laravel-blade-spacer) * - Automatically add spaces in Laravel Blade template tags.



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
    "window.openFoldersInNewWindow": "on",
    "window.openFilesInNewWindow": "default",
    "files.trimTrailingWhitespace": true,
    "files.trimFinalNewlines": true,
    "files.insertFinalNewline": true,
    "path-intellisense.showHiddenFiles": true,
}
```

