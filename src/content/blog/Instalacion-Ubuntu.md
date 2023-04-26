---
title: "Nuevo entorno Linux"
description: "Registro de la configuración de las aplicación que uso"
pubDate: "Apr 25 2023"
heroImage: '/tux.jpeg'
---
## VScode

A continuación voy a dejar el JSON del User setting que a mi me gusta
```javascript
{
    "workbench.colorTheme": "Ayu Mirage Bordered",
    "workbench.iconTheme": "vscode-icons",
    "editor.fontFamily": "'Cascadia Code PL','Droid Sans Mono', 'monospace', monospace",
    "terminal.integrated.fontFamily": "'Hack Nerd Font'",
    "editor.fontLigatures": true,
    "editor.cursorBlinking": "expand"
}
```
- Fuente del editor:  [Cascadia Code PL](https://github.com/microsoft/cascadia-code)
- Fuente de la terminal: [Hack Nerd Font](https://www.nerdfonts.com/font-downloads)


## Terminal

Se utiliza un zsh como shell y como tema se utiliza [powerlevel10k](https://github.com/romkatv/powerlevel10k)

Para que la terminar funciona correctamente se debe añadir lo siguiente en el archivo .zshrc
```bash
bindkey "^[[1;5C" forward-word
bindkey "^[[1;5D" backward-word
```

