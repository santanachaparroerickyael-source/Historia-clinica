# Historia Clínica Odontológica - Digital

Este repositorio contiene una página web (HTML + Bootstrap + JS) que funciona como formulario de Historia Clínica Odontológica.

**Contenido**
- `index.html`: formulario completo, interacción del odontograma (nomenclatura FDI), sistemas, antecedentes, consentimiento legal editable y exportación a PDF.
- `/css`, `/js`, `/assets`: carpetas para organización futura.

**Cómo publicar en GitHub Pages**
1. Crear un repositorio en GitHub.
2. Subir los archivos (arrastrar `index.html` y `README.md`).
3. En el repositorio, ir a _Settings → Pages_ y seleccionar:
   - Branch: `main`
   - Folder: `/root`
4. Guardar. Esperar unos minutos. La URL será:
   `https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/`

**Notas**
- El consentimiento informado está redactado en un formato legal estándar. Edítalo antes de usarlo en tu práctica si necesitas adaptar cláusulas locales.
- El odontograma permite marcar estados por diente: Normal → Cariado → Restaurado → Ausente. Las notas por diente se agrupan en el campo de notas del odontograma.
- El botón "Exportar a PDF" genera un PDF de la página usando html2pdf.js.

