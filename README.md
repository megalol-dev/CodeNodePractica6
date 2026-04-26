# CodeNodePractica6 - Astro + WordPress REST API

## Descripción

Práctica en la que se conecta una web desarrollada con Astro a la REST API de WordPress.

El objetivo es que la sección de proyectos/comics no use datos hardcodeados, sino datos reales guardados en WordPress y obtenidos mediante `fetch`.

## Tecnologías utilizadas

- Astro
- HTML
- CSS
- JavaScript
- WordPress
- REST API
- ACF

## Funcionalidades

- Web frontend creada con Astro
- Conexión a WordPress mediante `fetch`
- Lectura de datos reales desde la API REST
- Muestra título y descripción de cada comic/manga
- Manejo básico de errores si WordPress está apagado
- Diseño responsive en tarjetas tipo grid

## API utilizada

```bash
http://localhost/wordpresss/wp-json/wp/v2/manga

```

En la carpeta !PROFESOR se incluyen capturas del proyecto funcionando:

página de Astro en local
JSON de la API de WordPress
prueba de conexión entre frontend y backend
Nota

Para ver el proyecto funcionando correctamente es necesario tener WordPress iniciado en local con XAMPP y el CPT manga disponible en la REST API.