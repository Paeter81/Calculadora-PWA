# Calculadora de aceptacion de menus — PWA

## Subir a GitHub Pages

1. En GitHub, crea un repositorio nuevo (por ejemplo `calculadora-menus`).
2. Descomprime este ZIP en tu ordenador.
3. Sube **todos los archivos y carpetas que contiene** directamente a la raíz del repositorio. `index.html` debe quedar en la raíz, no dentro de otra carpeta.
4. En el repositorio entra en **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**; rama `main` y carpeta `/(root)`. Pulsa **Save**.
6. Espera a que GitHub Pages publique la web y abre la URL que te indique, normalmente `https://TU-USUARIO.github.io/NOMBRE-REPOSITORIO/`.
7. Para instalarla, abre esa URL en Chrome o Edge. Busca el icono de instalación en la barra de direcciones o usa el menú del navegador → **Instalar aplicación** / **Instalar Calculadora de aceptacion de menus**. En móvil, puede aparecer **Añadir a pantalla de inicio**.

## Importante
- La PWA necesita servirse por HTTPS; GitHub Pages lo proporciona. No la abras haciendo doble clic en el archivo para probar la instalación.
- El historial se guarda en el almacenamiento local del navegador y dispositivo. No se sincroniza automáticamente entre dispositivos; no borres los datos del sitio si quieres conservarlo.
- El archivo conserva dependencias de diseño cargadas desde CDN (Tailwind, Font Awesome y Google Fonts), por lo que la apariencia completa puede necesitar conexión a Internet. El service worker guarda la estructura principal de la app para ofrecer una experiencia básica si se pierde la conexión después de haberla abierto.
- Para publicar cambios, vuelve a subir los archivos modificados al mismo repositorio.
