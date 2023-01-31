# UMAR

### [TODO Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)

<li>Ingresar a settings.json de vscode</li>

<li>cmd + p 'settings.json'</li>

<li>pegar al final dentro del objeto principal</li>

```json
 "todo-tree.tree.autoRefresh": true,
    "todo-tree.highlights.customHighlight": {
        "WARN": {
            "foreground": "#000000",
            "background": "#F30B0B",
            "iconColour": "#F30B0B",
            "icon": "alert",
            "type": "text"
        },
        "PENDING": {
            "foreground": "#000000",
            "background": "#0bd0f3",
            "iconColour": "#0bd0f3",
            "icon": "history",
            "type": "text"
        },
        "TODO": {
            "foreground": "#000000",
            "background": "#7CFC00", //TODO Green
            "iconColour": "#7CFC00",
            "icon": "check",
            "type": "text"
        },
        "FIXME": {
            "foreground": "#000000",
            "background": "#EFF60B", //FIXME Yellow
            "iconColour": "#EFF60B",
            "icon": "bug"
        },
        "REVIEW": {
            "foreground": "#000000",
            "background": "#00FFFF", //cyan
            "iconColour": "#ADD8E6", //light blue
            "icon": "eye"
        },
        "HACK": {
            "foreground": "#000000",
            "background": "#FFA500",
            "iconColour": "#FFA500",
            "icon": "alert"
        },
        "REF":{ //Reference
            "foreground": "#000000",
            "background": "#FFA500",
            "iconColour": "#FFA500",
            "icon": "link",
            "type":"text"
        },
        "NOTE": {
            "foreground": "#000000",
            "background": "#FF00FF", //magenta
            "iconColour": "#FF00FF",
            "icon": "note",
            "type": "text",
        },
        "CRITICAL": {
            "foreground": "#000000",
            "background": "#ff0d00", //magenta
            "iconColour": "#ff0d00",
            "icon": "flame",
            "type": "text",
        }
    },
    "todo-tree.highlights.defaultHighlight": {
        "type": "text-and-comment"
    },
    "todo-tree.general.tags": [
        "TODO",
        "FIXME",
        "REVIEW",
        "HACK",
        "REF",
        "WARN",
        "NOTE",
        "PENDING",
        "CRITICAL"
    ],
```
suguiero identificar los comentarios
ejemplo: 
```
//NOTE :EM: 'Mi comentario'
//REF :JB: 'Mi otro comentario'
```
EM: Erick Machicado
JB: Jose Bello
EP: Esteban Pavez
