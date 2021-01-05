<h1 align="center">Visual Studio Code settings 📐</h1>

- 🌑 Theme: [Omni (Rocketseat)](https://marketplace.visualstudio.com/items?itemName=rocketseat.theme-omni)
- 🖋 Font: [JetBrains Mono](https://www.jetbrains.com/lp/mono/)

```json
{
    // Terminal
    "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
    
    // Theme 🖤
    "workbench.colorTheme": "Omni",
    "workbench.iconTheme": "material-icon-theme",
    
    // Font 
    "editor.fontFamily": "JetBrains Mono",
    "editor.fontSize": 13,
    "editor.fontLigatures": true,

    // Window zoom 🔎
    "window.zoomLevel": 1.5,

    "npm-intellisense.importES6": true,
    "npm-intellisense.importQuotes": "'",
    "npm-intellisense.importLinebreak": ";\r\n",
    "npm-intellisense.importDeclarationType": "const",
    
    // Nunjucks Template
    "files.associations": {
        "html": "njk"
    },

    "vsicons.associations.files": [
        {
            "icon": "nunjucks",
            "extensions": [
                "njk"
            ],
            "format": "svg"
        }
    ],
    
    // Emmet config
    "emmet.syntaxProfiles": {
        "javascript": "jsx"
    },
    
    "emmet.includeLanguages": {
        "njk": "html",
        "javascript": "javascriptreact"
    },
    
    // Auto imports
    "javascript.suggest.autoImports": true,
    "typescript.suggest.autoImports": true,
    
    // Others
    "breadcrumbs.enabled": true,
    "editor.parameterHints.enabled": false,
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
    "editor.minimap.enabled": false
}
```