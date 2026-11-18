# Días de Topología No Conmutativa — página web

Página estática (HTML + CSS, sin dependencias) para GitHub Pages.

## Archivos

- `index.html` — contenido de la página (programa, ponentes, sede, registro).
- `style.css` — diseño; los colores están al inicio, en `:root`.

## Dos versiones (ramas de git)

- `main` — **versión provisional**, la que se publica: sin programa y con el
  registro como "próximamente".
- `completa` — versión con programa, donde se sigue trabajando.

Cuando la completa esté lista, se pasa a `main` y deja de haber versión provisional.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub, `dias-topologia-nc` (público), en la cuenta `analisisnc`.
2. Sube `index.html`, `style.css`, la carpeta `img/` y este `README.md` a la rama `main`.
3. En el repositorio: **Settings → Pages → Build and deployment**:
   - Source: *Deploy from a branch*
   - Branch: `main`, carpeta `/ (root)` → **Save**.
4. En uno o dos minutos la página queda en
   `https://analisisnc.github.io/dias-topologia-nc/`.

## Pendientes en `index.html`

Busca los comentarios `<!-- ... -->`:

- Enlace al registro de Fernando (dos lugares: botón del encabezado y sección Registro).
- Lunes 15:30: Helena Lizárraga por confirmar (poner su nombre en el programa y en Ponentes).
- Títulos de las charlas de María de los Ángeles Sandoval, Cristina Villanueva, Kohei Miyazaki y Raúl Rodríguez.
- Correo de contacto (opcional).

Para dar acceso a Felipe y Francisco: **Settings → Collaborators → Add people**.
