# MD to PDF

A simple web app to convert Markdown files (`.md`) into PDF directly in the browser.

## English

### What it does

- Lets you drag and drop or choose a Markdown file.
- Shows a live preview of parsed Markdown content.
- Generates and downloads a PDF using the original file name.
- Displays inline error messages when something goes wrong.

### How to use

1. Open `index.html` in your browser.
2. Drag a `.md` file into the drop zone, or click to select one.
3. Review the preview content.
4. Click **Download PDF**.

### Technologies

- [Marked](https://marked.js.org/) to parse Markdown for preview.
- [jsPDF](https://github.com/parallax/jsPDF) to generate the PDF.

### Important notes

- This version prioritizes stable PDF export.
- The PDF is generated from Markdown content processed as text.
- Some advanced Markdown styling (complex tables, embedded HTML, etc.) may not match the preview exactly.

### Project structure

- `index.html`: UI, file handling, preview, and PDF generation.
- `.gitignore`: ignored local/editor files.

### Suggested improvements

- Improve PDF formatting (heading hierarchy, indented lists, styled code blocks).
- Better support for tables and images.
- Add style presets (light/dark theme, fonts, margins).

---

## Espanol

Aplicacion web simple para convertir archivos Markdown (`.md`) a PDF desde el navegador.

### Que hace

- Permite arrastrar o seleccionar un archivo Markdown.
- Muestra una previsualizacion del contenido parseado.
- Genera y descarga un PDF con el nombre del archivo original.
- Muestra mensajes de error en pantalla cuando algo falla.

### Como usarla

1. Abre `index.html` en tu navegador.
2. Arrastra un archivo `.md` en la zona de carga, o haz clic para seleccionarlo.
3. Revisa la previsualizacion del contenido.
4. Haz clic en **Descargar PDF**.

### Tecnologias

- [Marked](https://marked.js.org/) para parsear Markdown a HTML (previsualizacion).
- [jsPDF](https://github.com/parallax/jsPDF) para generar el PDF.

### Notas importantes

- Esta version prioriza estabilidad en la exportacion a PDF.
- El PDF se genera a partir del contenido Markdown procesado como texto.
- Algunos estilos avanzados de Markdown (tablas complejas, HTML embebido, etc.) pueden no conservarse igual que en la previsualizacion.

### Estructura del proyecto

- `index.html`: interfaz, carga de archivo, preview y generacion de PDF.
- `.gitignore`: archivos/carpetas locales ignorados por Git.

### Mejoras sugeridas

- Mejorar el formato del PDF (jerarquia de titulos, listas con sangria, bloques de codigo).
- Soporte mas fiel para tablas e imagenes.
- Exportacion con plantillas de estilo (tema claro/oscuro, tipografias, margenes).
