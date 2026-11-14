PROGAME ARCADE
==============
Abrir en tu PC: doble clic en index.html (funciona sin internet, salvo el multijugador).
Publicar: arrastra esta carpeta (progame-arcade) a Netlify, o sube su contenido a un repositorio de GitHub.

Estructura
- index.html                  Portada con todos los juegos
- sobre-nosotros.html, privacidad.html, contacto.html   Páginas informativas (el formulario de contacto funciona en Netlify)
- juego/<nombre>/index.html   Página de cada juego (portada, descripción y juego en ventana flotante)
- games/<nombre>/index.html   El juego en sí
- assets/img/                 Capturas (portada y secundaria) de cada juego
- assets/video/               Clips cortos de gameplay para el carrusel de la portada (webm y mp4)
- sitemap.xml, robots.txt     Para buscadores (usa la dirección progame-arcade.netlify.app)
- manifest.webmanifest, sw.js  Permiten instalar PROGAME como app en el celular y que cargue más rápido
