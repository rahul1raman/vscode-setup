# VSCode setup I use

### Theme

I use the default `Visual Studio Dark` theme with the material theme icons. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme)

### Extensions used

`Auto Close Tag` to automatically close HTML tags. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)

`Auto Rename Tag` to automatically change matching HTML tags. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)

`Live Server` to see live changes of a static/dynamic webpage. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

`Paste and Indent` to automatically indent pasted code. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=Rubymaniac.vscode-paste-and-indent)

`Path Intellisense` to autocomplete filenames. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)

`Prettier` to automatically format code. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

`Project Manager`  [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)

### Settings

Go to settings in VSCode, and on the right side, paste this code.

```
{
    "workbench.colorTheme": "Visual Studio Dark",
    "workbench.iconTheme": "eq-material-theme-icons",
    "files.autoSave": "onFocusChange",
    "editor.minimap.enabled": true,
    "workbench.statusBar.visible": true,
    "workbench.activityBar.visible": true,
    "editor.formatOnSave": false,
  
    "workbench.colorCustomizations": {
      "statusBar.background": "#333333",
      "statusBar.noFolderBackground": "#333333",
      "statusBar.debuggingBackground": "#263238"
    },
    "editor.fontSize": 14,
  
    "css.validate": false,
    "scss.validate": false,
    "less.validate": false,
    "editor.wordWrap": "on"
  }
```
