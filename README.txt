MUNDO CONECTADO - REALIDAD AUMENTADA

Contenido de la carpeta:
- index.html: experiencia WebAR.
- markers/marcador_mundo_internet.png: marcador para mostrar en pantalla o imprimir.
- markers/marcador_mundo_internet.pdf: marcador listo para imprimir.
- markers/pattern-internet.patt: archivo que usa AR.js para reconocer el marcador.

Como probarlo:
1. Subir toda la carpeta a un sitio con HTTPS, por ejemplo GitHub Pages, Netlify, Vercel o Glitch.
2. Abrir el enlace desde el celular.
3. Permitir el uso de la camara.
4. Apuntar al marcador incluido en la carpeta markers.
5. Deberia aparecer un mundo girando con conexiones activas de internet.

Importante:
- No cambies el nombre de la carpeta markers ni del archivo pattern-internet.patt si no vas a modificar tambien index.html.
- Para mejor deteccion, usar buena luz, mantener el marcador plano y evitar reflejos.
- Si queres usar el marcador clasico HIRO, cambia en index.html la linea del marcador por: <a-marker preset="hiro">
