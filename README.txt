NEBULA — Idle Clicker PWA (v1.1)

Mejoras incluidas:
- PWA instalable: manifest correctamente enlazado, theme-color, apple-touch-icons, service worker actualizado.
- Botón «Instalar» cuando el navegador lo permite (beforeinstallprompt).
- Iconos propios (icons/).
- Navegación por pestañas inferiores en móvil (Núcleo / Tienda / Ciclo) para reducir scroll.
- Sin cuadros azules al pulsar en móvil (-webkit-tap-highlight-color: transparent + estilos de foco).
- Safe-area para notch e home indicator.
- Stats sticky, animaciones suaves, mejor feedback táctil.
- Caché offline incluye ambient.mp3 (si está presente).

PUBLICAR EN GITHUB PAGES:
1. Sube todos los archivos y la carpeta icons al repositorio (raíz o subcarpeta).
2. En Settings > Pages, publica la rama/carpeta deseada.
3. Abre la URL HTTPS en móvil. Aparecerá el botón Instalar o usa el menú del navegador «Añadir a pantalla de inicio».
4. Tras la primera carga, los archivos principales quedan en caché para jugar sin conexión.

PWA requiere HTTPS (GitHub Pages lo proporciona) o localhost.
El progreso y los ajustes se guardan en el navegador de cada dispositivo.
El audio puede requerir una primera interacción por las restricciones del navegador.
