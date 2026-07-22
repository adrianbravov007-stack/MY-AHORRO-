=========================================
      MI AHORRO - APLICACIÓN WEB PWA
=========================================

Contenido del paquete:
-----------------------
- index.html         : Código principal optimizado de la aplicación.
- manifest.webmanifest : Configuración para instalación como App PWA en móvil/PC.
- service-worker.js  : Cache para soporte offline.
- README.txt         : Este archivo con las instrucciones.

Mejoras y correcciones incluidas:
----------------------------------
1. Corrección del foco en inputs: Ya no se cierra el teclado táctil ni se pierde el cursor al escribir valores en vivo.
2. Accesibilidad: Etiquetas `<label>` correctamente enlazadas con sus respetivos campos (`id` y `for`).
3. Confirmación de eliminación: Se solicita confirmación antes de eliminar depósitos del historial.
4. Manejo correcto de fechas: Parseo local de fechas para evitar problemas de zonas horarias.
5. Mejoras de diseño y UX: Animaciones más suaves en barras de progreso y botones con estado responsivo.

Instrucciones de uso:
---------------------
1. Para probar en local: Basta con hacer doble clic sobre `index.html` para abrirlo en cualquier navegador.
2. Para desplegar online (Servidor/GitHub Pages/Vercel/Netlify): Sube todos los archivos a la raíz de tu hosting.
3. Para instalar como app (PWA): Al visitar el sitio en Safari (iOS) o Chrome (Android), selecciona "Agregar a la pantalla de inicio".
