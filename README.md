# La Barbería Shop · Les Corts

Web de una página para La Barbería Shop, Carrer de Benavent, 2, Les Corts (Barcelona).

## Archivos

- `index.html`: la web lista para publicar. Usa las carpetas `img/` y las librerías GSAP, ScrollTrigger y Lenis desde CDN.
- `entrega/la-barberia-shop.html`: la misma web en un solo archivo, con las imágenes incrustadas. Se abre con doble clic.
- `src.html`: el código fuente. No se edita `index.html` a mano.
- `icons/`: iconos SVG que se convierten en un sprite al construir.
- `build.ps1`: genera `index.html` y el archivo de `entrega/` a partir de `src.html`.

## Construir

```powershell
.\build.ps1
```

## Publicar con GitHub Pages

En Settings → Pages, elige la rama `main` y la carpeta `/ (root)`. La web queda en
`https://jesustiven19-sketch.github.io/Barberia_SHOP_Les-corts/`.
