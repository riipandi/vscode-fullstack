# VSCode Extension Pack for Fullstack Developer

Collection of many extensions to get started with various app development and deployment in Visual Studio Code.

## Prerequisites

In Microsoft Windows you will need:

1. [Git for Windows](https://git-scm.com/download/win)
2. [NodeJS](https://nodejs.org/en/download/)
3. [Yarn](https://yarnpkg.com/lang/en/docs/install/#windows-stable)
4. [Laragon](https://github.com/leokhoa/laragon/releases) or another stack
5. [Hyper Terminal](https://hyper.is/) (optional)
## Recomended Configuration

```json
{
  "telemetry.enableTelemetry": false,
  "telemetry.enableCrashReporter": false,
  "workbench.colorTheme": "One Dark Pro Vivid",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.activityBar.visible": true,
  "workbench.editor.showIcons": true,
  "workbench.editor.tabCloseButton": "right",
  "workbench.startupEditor": "none",
  "workbench.statusBar.feedback.visible": false,
  "workbench.enableExperiments": false,
  "workbench.tree.horizontalScrolling": false,
  "workbench.tips.enabled": false,
  "workbench.settings.editor": "json",
  "workbench.settings.enableNaturalLanguageSearch": false,
  "typescript.surveys.enabled": false,
  "editor.insertSpaces": true,
  "editor.detectIndentation": true,
  "editor.formatOnType": false,
  "editor.renderControlCharacters": true,
  "editor.multiCursorModifier": "alt",
  "editor.snippetSuggestions": "top",
  "editor.formatOnPaste": false,
  "editor.fontSize": 14,
  "editor.wordWrap": "off",
  "editor.autoIndent": false,
  "editor.find.autoFindInSelection": false,
  "editor.autoClosingBrackets": "always",
  "editor.links": false,
  "editor.fontFamily": "'Fira Code', 'Droid Sans Mono', 'monospace', 'Droid Sans Fallback'",
  "editor.fontLigatures": true,
  "editor.formatOnSave": false,
  "window.menuBarVisibility": "default",
  "window.newWindowDimensions": "maximized",
  "window.titleBarStyle": "custom",
  "window.title": "${dirty}${activeEditorMedium}${separator}${rootName}${separator}${appName}",
  "files.trimTrailingWhitespace": true,
  "files.encoding": "utf8",
  "files.eol": "\n",
  "extensions.showRecommendationsOnlyOnDemand": false,
  "update.enableWindowsBackgroundUpdates": false,
  "update.showReleaseNotes": false,
  "extensions.autoCheckUpdates": true,
  "extensions.autoUpdate": true,
  "extensions.ignoreRecommendations": true,
  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,
  "explorer.autoReveal": false,
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.cursorStyle": "underline",
  "terminal.integrated.fontSize": 12,
  "terminal.explorerKind": "integrated",
  "terminal.external.windowsExec": "C:\\Program Files\\Git\\bin\\bash.exe",
  "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
  "material-icon-theme.showWelcomeMessage": false,
  "material-icon-theme.showUpdateMessage": false,
  "markdown.extension.toc.githubCompatibility": true,
  "eslint.packageManager": "yarn",
  "php.suggest.basic": false,
  "php.validate.enable": false,
  "git.autofetch": false,
  "html.autoClosingTags": true,
  "html.format.endWithNewline": true,
  "html.format.indentHandlebars": true,
  "emmet.triggerExpansionOnTab": true,
  "auto-close-tag.enableAutoCloseTag": true,
  "auto-close-tag.enableAutoCloseSelfClosingTag": true,
  "auto-rename-tag.activationOnLanguage": ["html", "xml", "php", "javascript", "vue"],
  "[markdown]": {"editor.wordWrap": "off", "editor.quickSuggestions": false},
  "fileHeaderComment.parameter": {
    "*":{
      "commentbegin": "/*",
      "commentprefix": " *",
      "commentend": " */",
      "author": "Aris Ripandi",
      "company": "Ruhay Creative Studio"
    }
  },
  "fileHeaderComment.template": {
    "*":[
      "${commentbegin}",
      "${commentprefix} Created on ${datetime24h}",
      "${commentprefix}",
      "${commentprefix} Copyright (c) ${year} ${author}",
      "${commentend}"
    ]
  }
}
```

## Contact

Please file any [issues](https://github.com/riipandi/vscode-fullstack/issues) or
have a suggestion please tweet me [@riipandi](https://twitter.com/riipandi).

## License

This project is open-sourced software licensed under the [MIT license](./LICENSE).
