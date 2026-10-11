# Teoría de la información

Libro en español escrito con [Quarto](https://quarto.org), publicado en HTML (con versión PDF descargable) mediante GitHub Pages.

## Requisitos

- Quarto 1.10 o superior.
- Una distribución TeX con LuaLaTeX y las fuentes `newcomputermodern` (para el PDF y las figuras).
- Poppler (`pdftocairo`) para convertir las figuras a SVG.
- Node.js (solo para los ganchos de git y las versiones).

## Uso

```sh
npm install           # instala lefthook y commitlint, y activa los ganchos
npm run preview       # vista previa con recarga en vivo
npm run figuras       # recompila las figuras TikZ desactualizadas
npm run render        # figuras + HTML + PDF en _book/
npm run release       # nueva versión y CHANGELOG (Conventional Commits)
```

Las convenciones de escritura están en [AGENTS.md](AGENTS.md).

## Licencia

El contenido se distribuye bajo [CC BY-SA 4.0](LICENSE).
