# QR Regalo — prueba con Ordinary

Este proyecto contiene una página romántica para celular y un generador de QR.

## Archivos

- `index.html` — página que verá la persona al escanear el QR.
- `assets/foto.jpg` — foto utilizada como fondo/imagen.
- `qr.html` — generador de QR a partir de la URL pública.
- `README.txt` — estas instrucciones.

## Cómo probarlo en tu PC

Abrí `index.html` en un navegador. La página funciona como diseño local, pero el botón de Spotify necesita conexión a Internet.

## Cómo hacer que el QR funcione en otro celular

El QR necesita apuntar a una URL pública. La opción gratuita más simple es GitHub Pages.

1. Crear una cuenta en GitHub.
2. Crear un repositorio nuevo, por ejemplo `qr-regalo`.
3. Subir `index.html` y la carpeta `assets`.
4. Activar GitHub Pages desde Settings > Pages.
5. GitHub dará una URL parecida a:
   `https://TUUSUARIO.github.io/qr-regalo/`
6. Abrir `qr.html`.
7. Pegar esa URL.
8. Generar y descargar el QR.

## Importante sobre Spotify

Esta versión NO copia ni aloja el audio de "Ordinary". El botón abre la pista oficial en Spotify.

En un teléfono con Spotify Premium, después de iniciar la canción podés volver a esta página y, si el sistema mantiene Spotify reproduciendo en segundo plano, continuar viendo el mensaje mientras suena.

La reproducción automática de una canción de Spotify dentro de una página web no está garantizada por los navegadores ni por Spotify. Esta primera versión está pensada como prueba personal.

## Cambiar el mensaje

En `index.html`, buscá:

eres única y<br><span>especial,</span><br>te amo por<br><span>toda la eternidad</span>

y reemplazalo por el mensaje deseado.

## Cambiar la canción

En `index.html`, reemplazá la URL de Spotify en las dos apariciones de:

https://open.spotify.com/track/7vC6GPyWuKptLe8vuYDgNQ

por la URL de la nueva canción.

