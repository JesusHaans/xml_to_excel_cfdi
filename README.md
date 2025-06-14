# xml_to_excel_cfdi

Herramienta en Python para extraer automáticamente datos clave desde archivos CFDI (XML) emitidos por el SAT y organizarlos en hojas de cálculo Excel para facilitar la contabilidad de personas físicas con actividad empresarial o asimilados a salarios.

## 🚀 Funcionalidades

- Parseo de archivos CFDI 4.0 (XML).
- Extracción de datos: RFC emisor/receptor, conceptos, montos, fechas, UUID, formas de pago, IVA, etc.
- Exportación estructurada a Excel (.xlsx) con hojas para:
  - Facturas emitidas
  - Facturas recibidas
  - Estados de cuenta (conciliación bancaria no soportada en este momento)
  - Resumen mensual
- Compatible con requerimientos comunes de contadores en México.

## 🧰 Tecnologías usadas

- Python 3.9+
- `pandas`
- `openpyxl`
- `lxml` (o `xml.etree.ElementTree`)
- `fpdf` (para generar guías de uso)

## 📦 Objetivo

Automatizar tareas contables recurrentes, reducir errores manuales y brindar mayor visibilidad sobre la información fiscal contenida en los XML del SAT. Este proyecto es especialmente útil para automatizar la captura de datos fiscales de las facturas descargadas desde el portal del SAT que vienen en formato XML.

## 📑 Licencia

MIT – Libre de usar, modificar y compartir.

## 📌 Nota

Este proyecto es una herramienta que ayuda a la captura de facturas emitidas y recibidas en un formato de excel.