HOJA DE PERSONAJE D&D 5.5e · VERSIÓN COMPLETA

CONTENIDO
- index.html: hoja interactiva.
- manifest.webmanifest e iconos: instalación desde la pantalla de inicio.
- sw.js: caché offline para usar la hoja sin internet tras la primera visita.

CÓMO PROBARLA EN TU PC
Abre index.html en tu navegador. Para instalarla como aplicación móvil, necesitas publicarla desde HTTPS (o localhost para desarrollo).

CÓMO COMPARTIRLA O INSTALARLA
1. Descomprime este ZIP y sube TODOS los archivos de esta carpeta a GitHub Pages, Netlify, Cloudflare Pages u otro hosting estático HTTPS. NO subas solo el ZIP a Pages.
2. Abre la URL que ofrece el hosting y envíala a tu amigo.
3. Android con Chrome: menú ⋮ → Instalar aplicación o Añadir a la pantalla de inicio.
4. iPhone con Safari: Compartir → Añadir a pantalla de inicio.

GUARDADO Y COPIAS
Los cambios se guardan automáticamente SOLO en el navegador o instalación actual (localStorage). Cada dispositivo mantiene sus propios personajes, sin sincronización con el otro. Usa Exportar e Importar para mover una copia JSON entre dispositivos. No borres los datos del navegador sin antes exportarlos.

USO DE CONJUROS
Marca el conjuro como Seleccionado / preparado y presiona Lanzar para gastar un espacio disponible. Puedes elegir ranura de nivel superior si existe. Los trucos y los rituales válidos no gastan espacios. Para brujo se incluyen los arcanos místicos de nivel 6–9, con recuperación en descanso largo. Usa Deshacer último lanzamiento para corregir un error. Esto no verifica automáticamente componentes, alcance o acciones: la decisión corresponde a los jugadores y al DM.

FUENTES Y LIMITACIONES
El catálogo original contiene 319 conjuros (texto extraído del archivo HTML proporcionado, con posibles errores tipográficos). Los resúmenes de habilidades oficiales en esta app no son transcripciones completas del manual y no incluyen todas las subclases. La clase The Pugilist de Benjamin Huffman es contenido de terceros; la pestaña Moxie solo aparece al elegir Pugilista. Las cinco situaciones por conjuro o rasgo son sugerencias contextuales editables, NO una validación universal de las reglas.
El SRD 5.2.1 de Wizards of the Coast es referencia CC BY 4.0: https://www.dndbeyond.com/srd

PRUEBAS
- Sintaxis JavaScript validada con Node.js.
- Interacción real verificada con Chromium y Playwright a 360, 390, 768 y 1280 px: navegación, responsive, hechizos (preparar, lanzar, deshacer, límites de ranuras), edición, inventario, Moxie, descanso y clase.
- No se ha verificado en hardware Android/iPhone ni se ha auditado contra cada suplemento o subclase.
