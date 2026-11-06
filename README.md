# Damimus

Web personal de Damimus con juegos musicales, vídeos y actividades. La web está publicada con GitHub Pages.

## Añadir recursos

Edita la lista `resources` al final de `index.html`. Cada elemento puede usar esta estructura:

```js
{
  title: "Nombre del recurso",
  description: "Breve descripción.",
  category: "game", // Usa "game" o "web".
  categoryLabel: "Juego musical",
  icon: "🎵",
  url: "https://ejemplo.com",
  action: "Explorar"
}
```

Los vídeos destacados se editan en la sección `#video` de `index.html`.

## Publicación

Cada cambio en `main` inicia automáticamente el despliegue de GitHub Pages mediante `.github/workflows/pages.yml`.
