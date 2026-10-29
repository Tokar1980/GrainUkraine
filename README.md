# Ukraine Grain Export — sitio demostrativo educativo

Sitio web estático en español (es-AR), preparado para GitHub Pages. Proyecto académico: exportación hipotética de trigo panificable desde Ucrania hacia Argentina.

## Contenido
- `index.html` — inicio
- `productos.html` — ficha de producto y selector de especificación
- `logistica.html` — condiciones FOB/CIF y proceso
- `nosotros.html` — información y carácter educativo
- `contacto.html` — formulario que genera un correo `mailto:`
- `assets/css/style.css` — estilos adaptativos
- `assets/js/main.js` — navegación, animaciones, ficha y formulario

## Publicación en GitHub Pages
1. Crear un repositorio **público** en GitHub.
2. Subir **el contenido de esta carpeta** (no la carpeta contenedora) a la raíz del repositorio; `index.html` debe estar en la raíz.
3. Abrir **Settings → Pages**. Elegir **Deploy from a branch**, `main`, `/ (root)` y guardar.
4. Tras la publicación, visitar `https://USUARIO.github.io/REPOSITORIO/` y probar el sitio en una ventana privada.

## Funcionamiento y límites
- Todos los enlaces a páginas y recursos usan rutas relativas y funcionan bajo subdirectorios de GitHub Pages.
- El formulario **no envía** solicitudes automáticamente: abre la aplicación de correo del visitante mediante `mailto:`. Requiere una aplicación de correo configurada y la confirmación del envío.
- Sin imágenes ni dependencias JavaScript externas. Se utiliza una fuente web de Google Fonts con fuentes alternativas locales.
- La web está únicamente en español, según lo solicitado; no incluye selector de idiomas.
- La compañía es ficticia; no se declaran operaciones, certificaciones ni inventarios reales.

Autor: Володимир Токар, 2026. Contacto: v.tokar@knute.edu.ua.
