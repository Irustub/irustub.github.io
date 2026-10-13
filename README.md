# Tarjeta de contacto digital

Sitio estático para publicar una vCard mediante GitHub Pages. La página principal es `index.html` y funciona sin dependencias ni servidor.

## Personalizar la tarjeta

Los datos de identidad configurados son Cesar Campos Arvelo, Vendedor en Fudo. También se restauraron los campos de contacto y redes sociales que tenía la tarjeta antes. En `index.html`, busca el objeto `profile` para editarlos:

- `firstName` y `lastName`: nombre completo.
- `company` y `role`: empresa y cargo o profesión.
- `email` y `website`: medios de contacto.
- `phone`: número de llamadas.
- `whatsappPhone`: número asociado a WhatsApp, con código de país y entre 8 y 15 dígitos; deja el campo vacío para ocultar el botón hasta configurarlo.
- `whatsappMessage`: texto inicial que se propone al abrir WhatsApp.
- `address`: calle, ciudad, región, código postal y país.
- `note`: descripción o mensaje breve.
- `socialProfiles`: nombre, tipo y URL de cada red social.

El correo, teléfono, WhatsApp, ubicación, nota y perfiles sociales restaurados son los valores de ejemplo de la plantilla, no datos verificados de Cesar. Reemplázalos por los datos correctos antes de publicar; cualquier campo vacío se oculta en la tarjeta.

La tarjeta ofrece enlaces para visitar el sitio web y genera un archivo `.vcf` descargable con los datos disponibles para guardarlo en la agenda del teléfono o computadora. Al configurar un correo, teléfono o WhatsApp, también se muestran sus acciones; el botón de WhatsApp requiere un número con prefijo internacional y entre 8 y 15 dígitos.

## Vista previa al compartir

El banner de la tarjeta usa `fudo-banner.png`, una copia sin modificaciones de la imagen de referencia. `social-preview.png` usa la misma imagen para compartir. Si reemplazas el banner, actualiza ambos archivos si quieres que coincidan.

## Publicar con GitHub Pages

1. Sube `index.html` y este README al repositorio de GitHub.
2. En el repositorio, abre **Settings > Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch** y elige la rama principal y la carpeta raíz (`/`).
4. Guarda y espera a que termine la publicación.
5. Comparte la URL que GitHub Pages muestra en esa misma sección. En este sitio la URL configurada previamente era `https://irustub.github.io/`.
