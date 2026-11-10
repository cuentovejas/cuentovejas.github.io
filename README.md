# Cuentovejas · Cuentos para Dormir

Web oficial del canal de YouTube Cuentovejas. Generada con Jekyll y publicada
con GitHub Pages en https://cuentovejas.github.io

## Cómo añadir un cuento nuevo

Crea un archivo nuevo en `_posts/` con el nombre `AAAA-MM-DD-slug-del-cuento.md`
y este formato al principio:

```
---
title: "Título exacto del vídeo en YouTube"
subtitulo: "Frase corta para la tarjeta"
youtube_id: "ID_DEL_VIDEO_DE_YOUTUBE"
carril: "noche | animal | fantasia | ninos | pirata | clasico | recopilacion"
carril_label: "Etiqueta visible, p. ej. Cosas de la noche"
moraleja: "La enseñanza del cuento, en una frase"
excerpt: "Resumen corto para las tarjetas y el buscador"
---
<p>Texto que cuenta de qué trata el cuento (2-3 párrafos).</p>
```

GitHub publica los cambios automáticamente a los pocos minutos de subirlos.
