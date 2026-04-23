# Yuli Creation

Sitio web estático para la marca **Yuli Creation**, enfocado en mostrar un catálogo visual de piezas en crochet y facilitar el contacto directo para pedidos por **WhatsApp**, **Instagram** y **email**.

## Descripción

La web presenta:

- portada con identidad de marca
- sección informativa breve sobre la propuesta
- catálogo con fotografías reales de productos
- acceso a publicaciones de Instagram
- sección de contacto y pedidos

El proyecto está construido como una sola página HTML y no requiere framework ni proceso de compilación.

## Estructura del proyecto

```text
Web_Yuli/
├── index.html
├── README.md
└── img/
    ├── yuli-logo.png
    └── WhatsApp Image ....jpeg
```

## Archivos principales

- `index.html`: contiene toda la estructura, estilos y contenido del sitio.
- `img/`: almacena el logo y las fotografías usadas en el catálogo.

## Cómo abrir el proyecto

Como es un sitio estático, basta con abrir `index.html` en el navegador.

También puedes usar un servidor local simple si deseas probarlo con más comodidad.

Ejemplo con PowerShell:

```powershell
start index.html
```

## Cómo actualizar el catálogo

Para cambiar o agregar productos:

1. coloca las nuevas imágenes dentro de la carpeta `img/`
2. abre `index.html`
3. busca la sección `id="colecciones"`
4. duplica o edita una tarjeta con clase `catalog-card`
5. actualiza:
   - la imagen en `src`
   - el texto visible
   - el enlace a Instagram
   - el enlace de WhatsApp

## Cómo actualizar datos de contacto

En `index.html` puedes modificar fácilmente:

- número de WhatsApp
- correo electrónico
- enlace de Instagram
- textos comerciales

Busca los enlaces que contienen:

- `https://wa.me/`
- `mailto:`
- `https://www.instagram.com/yuli_creation/`

## Diseño y responsividad

La web ya incluye estilos responsive para:

- escritorio
- tablet
- móvil

Los estilos están escritos directamente dentro de `index.html` en una etiqueta `<style>`.

## Publicación

Este proyecto puede publicarse fácilmente en cualquier hosting de archivos estáticos, por ejemplo:

- GitHub Pages
- Netlify
- Vercel
- servidor compartido tradicional

Solo necesitas subir `index.html` y la carpeta `img/`.

## Recomendaciones

- comprimir imágenes antes de subir nuevas fotos para mejorar la velocidad de carga
- mantener nombres de archivo simples si se agregan nuevas imágenes
- revisar siempre los enlaces de WhatsApp e Instagram después de cada cambio
- probar la web en móvil y escritorio antes de publicar

## Estado actual

Actualmente la web incluye:

- catálogo con fotos reales del proyecto
- enlaces a publicaciones de Instagram
- tono comercial orientado al cliente
- estructura responsive

