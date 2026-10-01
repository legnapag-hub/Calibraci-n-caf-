AFINA – Calibración de café: app instalable (PWA) para Android y Windows

CONTENIDO
index.html (la app) · manifest.webmanifest · sw.js (modo sin internet) · iconos

1) PROBAR EN TU PC
   En esta carpeta ejecuta:  python -m http.server 8080
   Abre http://localhost:8080 en Chrome o Edge.

2) PUBLICAR (necesario HTTPS para instalar en el teléfono)
   - Netlify: entra a app.netlify.com/drop y arrastra la carpeta descomprimida.
   - GitHub Pages: sube los 6 archivos a un repositorio y activa Pages.
   - Cloudflare Pages / Vercel: también sirven; es un sitio estático sin build.

3) INSTALAR
   - Android: abre la URL en Chrome > menú ⋮ > "Instalar app".
   - Windows: abre la URL en Edge o Chrome > icono de instalar en la barra
     de direcciones (o botón "Instalar" dentro de la app).
   Una vez instalada funciona sin internet.

4) APK / INSTALADOR NATIVO (opcional)
   Entra a pwabuilder.com, pega tu URL y descarga el paquete Android (APK/AAB)
   o Windows (MSIX). Para Play Store o Microsoft Store necesitas cuenta de
   desarrollador en cada tienda.

5) DATOS
   Se guardan en cada dispositivo (no se sincronizan entre ellos).
   Usa "Respaldar (JSON)" en Registro para copiar o mover tus datos, e
   "Importar respaldo" para restaurarlos. "Exportar CSV" abre en Excel.

6) ACTUALIZAR
   Reemplaza los archivos en tu hosting; la app se actualiza sola al abrirla
   con internet.
