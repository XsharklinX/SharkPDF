#  SharkPDF - Unificador y Editor de PDF

**SharkPDF** es una herramienta web potente, minimalista y eficiente diseñada para gestionar documentos PDF e imágenes directamente desde el navegador. Sin servidores, sin registros y con total privacidad.

## 🚀 Características Principales

* **Unificación Inteligente:** Combina múltiples archivos PDF e imágenes (JPG, PNG, WebP) en un solo documento de alta calidad.
* **Edición de Páginas:**
    * **Reordenamiento:** Arrastra y suelta (Drag & Drop) o usa controles de flechas para organizar tus páginas.
    * **Rotación Individual:** Corrige la orientación de cualquier página con un clic.
    * **Recorte Preciso:** Ajusta los márgenes superiores, inferiores y laterales de forma independiente.
    * **Duplicación:** Clona páginas existentes instantáneamente.
* **Previsualización Nativa:** Visualiza el resultado final antes de procesar la descarga.
* **Exportación Versátil:**
    * Descarga como un único archivo **PDF**.
    * Exporta como un paquete de **Imágenes (ZIP)** en alta resolución.
* **Privacidad Total:** Todo el procesamiento ocurre de forma local en el navegador del usuario (Client-side). Sus archivos nunca se suben a ningún servidor.

## 🛠️ Tecnologías Utilizadas

Este proyecto fue construido utilizando librerías de vanguardia para garantizar estabilidad y velocidad:

* [PDF-Lib](https://pdf-lib.js.org/) - Creación y modificación de documentos PDF.
* [PDF.js](https://mozilla.github.io/pdf.js/) - Renderizado y generación de miniaturas.
* [Tailwind CSS](https://tailwindcss.com/) - Diseño de interfaz moderno, responsivo y oscuro.
* [SortableJS](https://sortablejs.github.io/Sortable/) - Interactividad avanzada de arrastrar y soltar.
* [JSZip](https://stuk.github.io/jszip/) - Compresión de archivos para exportación de imágenes.

## 📦 Instalación y Uso Local

SharkPDF no requiere dependencias de servidor ni Node.js para ejecutarse. Para probarlo localmente:

1. Clona el repositorio:
   ```bash
   git clone [https://github.com/xsharklinx/SharkPDF.git](https://github.com/xsharklinx/SharkPDF.git)
