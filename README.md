# VS-Code-Customization
---

## Table of Contents
1. [VS Code Setting](#VS-Code-Setting)
2. [VS Code Theme](#VS-Code-Theme)
3. [VS Code Extensions](#VS-Code-Extensions)
4. [VS Code Extension For Python](#VS-Code-Extension-For-Python)
   
---

## 🛠️ VS Code Setting
```python

// TODO: Workbench customization
{
  "workbench.colorTheme": "Palenight (Mild Contrast)",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.activityBar.location": "default",
  "workbench.editor.showTabs": "multiple",
  "workbench.statusBar.visible": true,
  "workbench.startupEditor": "none",
  "workbench.tips.enabled": false,
  "editor.minimap.enabled": true,
  "breadcrumbs.enabled": false,
  "workbench.sideBar.location": "left",
  "material-icon-theme.hidesExplorerArrows": true,
  "workbench.tree.enableStickyScroll": false,
  "workbench.tree.renderIndentGuides": "none",
  "workbench.tree.indent": 20,
  "explorer.compactFolders": false,
  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,
  "explorer.decorations.badges": false,
  "git.decorations.enabled": false,
  "window.zoomLevel": 1,
  "extensions.ignoreRecommendations": true,


  // TODO: Titlebar customization 
  "window.customTitleBarVisibility": "never",
  "window.titleBarStyle": "native",
  "custom-ui-style.electron": {
    "titleBarStyle": "hiddenInset",
    "trafficLightPosition": {
      "x": 20,
      "y": 16
    }
  },


  // TODO: Code Formatter
  // "editor.formatOnSave": true,
  // "editor.defaultFormatter": "esbenp.prettier-vscode",
  // "[javascript]": {
  //   "editor.defaultFormatter": "esbenp.prettier-vscode"
  // },
  "editor.defaultFormatter": "charliermarsh.ruff",
  "[python]": {
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "charliermarsh.ruff"
  },

  // TODO: cursor customization
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.overtypeCursorStyle": "line",
  "editor.cursorBlinking": "expand",
  "editor.wordWrap": "on",
  "files.autoSave": "afterDelay",


  // TODO: font customization
  "editor.fontSize": 20,
  // "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true,
  // "editor.lineHeight": 1.5,


  //TODO: Workbench color customization
"workbench.colorCustomizations": {
    "editorCursor.foreground": "#bfe20d" 
},


  //TODO: Comment color customization
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "comment",
        "settings": {
          "foreground": "#00FF00",
          "fontStyle": "italic"
        }
      }
    ]
  },


  // TODO: Material folder icons 
  "material-icon-theme.folders.associations": {
    "pipelines": "pipe",
    "prompts": "content",
    "workflows": "context",
    "celery": "queue",
    "venv": "environment",
    "collections": "interface",
    "1lm": "core",
    "references":"docs",
    "modeling": "generator"
},


  // TODO: Interactive Jupyter 
  "jupyter.interactiveWindow.textEditor.executeSelection": true,
  
}

```


## VS Code Theme
1. Palenight Theme  (Olaolu Olawuyi)<br>
2. Aura Split Dracula theme<br>
3. Atom One dark theme



## VS Code Extensions
1. Code Runner<br>
2. Tabnine<br>
3. Todo highlights<br>
4. materia icon<br>
5. material folder icon<br>
6. polacode<br>
7. Spell checker<br>
8. Prettier/ruff<br>
9. indent-rainbow<br>
10. Path intellisence


## VS Code Extension For Python
1. Python<br>
2. Python Extension Pack<br>
3. Jupyter




















