# my-vs-code-customization

## 🛠 VS Code Settings

```json
{
    "editor.mouseWheelZoom": true,
    "code-runner.runInTerminal": true,
    "code-runner.saveAllFilesBeforeRun": true,
    "code-runner.saveFileBeforeRun": true,
    "workbench.editorAssociations": {
        "*.lnk": "default",
        "*.pdf": "pdf.view"
    },
    "[c]": {
        "editor.defaultFormatter": "ms-vscode.cpptools"
    },
    "explorer.confirmDelete": false,
    "editor.fontSize": 20,
    "editor.fontLigatures": true,
    "security.workspace.trust.untrustedFiles": "open",
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "liveServer.settings.donotShowInfoMsg": true,
    "explorer.confirmDragAndDrop": false,
    "[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
    },
    "files.exclude": {
        "**/.classpath": true,
        "**/.project": true,
        "**/.settings": true,
        "**/.factorypath": true
    },
    "java.help.firstView": "gettingStarted",
    "files.autoSave": "afterDelay",
    "[python]": {
        "editor.defaultFormatter": "ms-python.python"
    },
    "[css]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "liveServer.settings.donotVerifyTags": true,
    "workbench.startupEditor": "none",
    "vsicons.dontShowNewVersionMessage": true,
    "workbench.editor.splitInGroupLayout": "vertical",
    "[jsonc]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "kite.showWelcomeNotificationOnStartup": false,
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "git.ignoreMissingGitWarning": true,
    "open-php-html-js-in-browser.selectedBrowser": "Chrome",
    "editor.wordWrap": "on",
    "editor.fontFamily": "Operator Mono",
    
    "workbench.colorCustomizations": {
        "terminal.background": "#1D2021",
        "terminal.foreground": "#A89984",
        "terminalCursor.background": "#A89984",
        "terminalCursor.foreground": "#A89984",
        "terminal.ansiBlack": "#1D2021",
        "terminal.ansiBlue": "#0D6678",
        "terminal.ansiBrightBlack": "#665C54",
        "terminal.ansiBrightBlue": "#0D6678",
        "terminal.ansiBrightCyan": "#8BA59B",
        "terminal.ansiBrightGreen": "#95C085",
        "terminal.ansiBrightMagenta": "#8F4673",
        "terminal.ansiBrightRed": "#FB543F",
        "terminal.ansiBrightWhite": "#FDF4C1",
        "terminal.ansiBrightYellow": "#FAC03B",
        "terminal.ansiCyan": "#8BA59B",
        "terminal.ansiGreen": "#95C085",
        "terminal.ansiMagenta": "#8F4673",
        "terminal.ansiRed": "#FB543F",
        "terminal.ansiWhite": "#A89984",
        "terminal.ansiYellow": "#FAC03B"
    },
    "terminal.integrated.fontSize": 16,
    "editor.cursorSmoothCaretAnimation": true,
    "editor.cursorBlinking": "expand",
    "workbench.iconTheme": "vscode-icons",
    "[java]": {
        "editor.defaultFormatter": "mwpb.java-prettier-formatter"
    },
    "editor.linkedEditing": true,
    "settingsSync.ignoredExtensions": [
    
    ],
    "workbench.colorTheme": "Dracula",
    "php.validate.executablePath": "",
    "php.suggest.basic": false,
    "php.validate.enable": false,
    "emmet.excludeLanguages": [
        "markdown",
        "php"
    ],
    "git.autofetch": true,
    "git.enableSmartCommit": true,
    "git.confirmSync": false,
    "editor.unicodeHighlight.invisibleCharacters": false,
    "remote.SSH.defaultExtensions": [
        "gitpod.gitpod-remote-ssh"
    ],
    "editor.accessibilitySupport": "off",
    "[php]": {
        "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
    },
}
```

## ⚙️ VS Code Extension
### Must
1. Code Runner : `formulahendry.code-runner`
2. Dracula Official : `dracula-theme.theme-dracula`
3. Auto Close Tag : `formulahendry.auto-close-tag`
4. Auto Rename Tag : `formulahendry.auto-rename-tag`

### Web Developmet
1. Live Server : `ritwickdey.LiveServer`
2. Bracket Pair Colorizer 2 : `CoenraadS.bracket-pair-colorizer-2`

### Java
1. Java Pack : `vscjava.vscode-java-pack`


## 🎨 VS Code Themes
1. [Dracula](https://draculatheme.com/)

## 🔑 VS Code Keyboard Shortcuts 
```json
[
    {
        "key": "ctrl+r",
        "command": "code-runner.run"
    },
    {
        "key": "ctrl+alt+n",
        "command": "-code-runner.run"
    },
    {
        "key": "ctrl+n",
        "command": "welcome.showNewFileEntries"
    },
    {
        "key": "ctrl+alt+win+n",
        "command": "-welcome.showNewFileEntries"
    },
    {
        "key": "ctrl+r ctrl+j",
        "command": "java.debug.runJavaFile"
    }
]
```

## ✒ Font Info
1. [Operator Mono](fonts)

