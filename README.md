# Tarjeta de contacto digital

Sitio estático para publicar una vCard mediante GitHub Pages. La página principal es `index.html` y funciona sin dependencias ni servidor.

## Personalizar la tarjeta

En `index.html`, busca el objeto `profile` y reemplaza los valores de ejemplo:

- `firstName` y `lastName`: nombre completo.
- `company` y `role`: empresa y cargo o profesión.
- `email`, `phone` y `website`: medios de contacto.
- `address`: calle, ciudad, región, código postal y país.
- `note`: descripción o mensaje breve.
- `socialProfiles`: nombre, tipo y URL de cada red social.

Puedes quitar redes que no uses o agregar otras en `socialProfiles`. No publiques la página hasta cambiar los datos de ejemplo por los tuyos.

La tarjeta ofrece enlaces para escribir y llamar, muestra las redes sociales y genera un archivo `.vcf` descargable con los datos del perfil para guardarlo en la agenda del teléfono o computadora.

## Publicar con GitHub Pages

1. Sube `index.html` y este README al repositorio de GitHub.
2. En el repositorio, abre **Settings > Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch** y elige la rama principal y la carpeta raíz (`/`).
4. Guarda y espera a que termine la publicación.
5. Comparte la URL que GitHub Pages muestra en esa misma sección. En este sitio la URL configurada previamente era `https://irustub.github.io/`.
