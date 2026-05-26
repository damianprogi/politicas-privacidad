# CeluVentas — Sitio legal y landing

Sitio web estático para la aplicación móvil **CeluVentas**, desarrollada por **Damián Diez**. Su único propósito es publicar la landing informativa y la documentación legal requerida (privacidad y eliminación de cuenta), por ejemplo para **Google Play Console** y **GitHub Pages**.

No incluye backend, frameworks ni lógica de aplicación: solo HTML y CSS.

## Contenido

| Archivo | Descripción |
|---------|-------------|
| `index.html` | Landing principal: presentación de la app, funciones, tecnología y enlaces legales |
| `politicas-privacidad.html` | Política de privacidad completa y sección de eliminación de cuenta (`#eliminacion`) |
| `politicas-privacidad.md` | Copia histórica en Markdown (no se publica; referencia interna) |

## Tecnología

- HTML5 + CSS puro
- Responsive (mobile-first)
- Sin dependencias npm ni proceso de build
- Imágenes decorativas vía Unsplash (carga externa)

## Publicación en GitHub Pages

1. Subí este repositorio a GitHub.
2. En el repositorio: **Settings → Pages**.
3. En **Source**, elegí la rama `main` (o `master`) y la carpeta **/** (raíz del repo).
4. Guardá y esperá unos minutos. La URL será similar a:

   `https://<usuario>.github.io/<nombre-del-repo>/`

Si el repositorio se llama igual que el usuario (`usuario.github.io`), la landing queda en la raíz del dominio.

## URLs útiles

Sustituí `<usuario>` y `<repo>` según tu caso:

| Uso | URL |
|-----|-----|
| Landing | `https://<usuario>.github.io/<repo>/` |
| Política de privacidad (Play Store) | `https://<usuario>.github.io/<repo>/politicas-privacidad.html` |
| Eliminación de cuenta | `https://<usuario>.github.io/<repo>/politicas-privacidad.html#eliminacion` |

Ejemplo publicado: [damianprogi.github.io](https://damianprogi.github.io/)

## Desarrollo local

Abrí `index.html` en el navegador o usá un servidor estático simple:

```bash
# Python 3
python -m http.server 8080
```

Luego visitá `http://localhost:8080`.

## Contacto

- **Desarrollador:** Damián Diez  
- **Email:** [android.endnote767@passinbox.com](mailto:android.endnote767@passinbox.com)

## Licencia

Contenido del sitio © Damián Diez. Reservados todos los derechos sobre textos y marca CeluVentas.
