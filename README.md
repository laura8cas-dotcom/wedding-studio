# Wedding Studio

Organizador de boda privado en un único archivo HTML (`index.html`), sin dependencias ni proceso de build.

Incluye planificación (lista y Kanban), presupuesto, invitados, proveedores con calendario de pagos, calendario, inspiración, mesas, día de la boda con cronología, documentación y buscador global.

## Uso en local

Abre `index.html` en el navegador.

## Publicar con GitHub Pages

1. Crea un repositorio y sube estos archivos a la rama `main`.
2. En **Settings → Pages**, elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. Tras un minuto, la web estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Datos y privacidad

- Los datos se guardan en el `localStorage` del navegador de cada persona. No hay servidor ni sincronización: el repositorio contiene solo el código.
- Para pasar los datos entre dispositivos o hacer copia: **Configuración → Exportar / Importar**.
- Los nombres y la fecha por defecto están en el código (busca `Carlos` en `index.html`). Si el repositorio es público, cámbialos o hazlo privado.

## Tipografías

IM Fell English SC se carga desde Google Fonts; sin conexión se usa Georgia.
