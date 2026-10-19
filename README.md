# Portafolio de Rafael González — GitHub Pages (versión ampliada)

Incluye un portafolio estático en HTML/CSS/JavaScript, diseño responsive, tarjetas de habilidades, trayectoria, formación, certificaciones y contacto.

## Vista previa
Descomprime el ZIP y abre `index.html` en un navegador moderno.

## Retrato binario
El código intenta cargar `https://oscidec.com/portafolio/perfil.jpg` y convertir los píxeles del retrato en caracteres 0/1 animados.
- Para convertir píxeles desde un dominio externo, el servidor de la foto debe permitir CORS.
- Si la foto no se transforma correctamente, descarga la imagen de perfil desde tu propio sitio y colócala junto a `index.html` con el nombre `perfil.jpg`. Luego, en el script de `index.html`, cambia `const PHOTO_URL='https://oscidec.com/portafolio/perfil.jpg';` por `const PHOTO_URL='perfil.jpg';`. Esto evita la restricción CORS al publicar todo en el mismo sitio.
- La imagen remota no está empaquetada en este ZIP porque no se pudo descargar desde el entorno de preparación.

## Publicar en GitHub Pages
1. Crea un repositorio llamado exactamente `TU-USUARIO.github.io` (sustituye por tu usuario de GitHub).
2. Sube `index.html` a la raíz del repositorio (y `perfil.jpg` si decides usar la imagen local).
3. Abre **Settings → Pages**. Selecciona **Deploy from a branch**, rama `main` y carpeta `/(root)`.
4. Espera a que termine el despliegue; la web quedará en `https://TU-USUARIO.github.io/`.

## Revisar antes de publicar
- Cambia el enlace genérico de GitHub por tu perfil real.
- Verifica fechas, certificaciones y la redacción de tus conocimientos.
- Los conocimientos indicados como básicos se describen así.
- Se incluye ApacheBench (ab) como interpretación probable de “abenckmark”; confirma si te referías a otra herramienta.
- Las referencias profesionales se señalan como disponibles bajo solicitud para no publicar teléfonos de terceros.
- No publiques informes de auditoría, credenciales, direcciones IP, dominios de clientes ni datos de terceros sin autorización.


## Perfil de GitHub

El portafolio enlaza a https://github.com/rafaelgonzalezm507-byte/ .
