---
titulo: Mastermind in python
subtitulo: The mastermind board game, also known as Bulls and cows, developed in phyton for fun and study purposes
thumbnail_url: https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/DEC_VT100_terminal.jpg/1200px-DEC_VT100_terminal.jpg
github: https://github.com/GonziTaji/mastermind-game
demo_url:
tags: [python]
---

# README

`portafolio.json` pretende ser la base de datos de las piezas de software a mostrar en /portafolio

## Estructura

```typescript
// interfaz actual simple
interface proyecto {
    titulo: string,
    subtitulo: string,
    resumen: string,
    enlace: string, // enlace a github
}

// full powa
interface proyecto {
    titulo: string,
    subtitulo: string,
    resumen: string,
    tags: string[], // lista de tecnologías, categorías, etc. 
    enlace: string, // enlace a github
    thumbnail: string,
}

```
