# Explicación de la Diferencia Entre los Dos Últimos Commits

## Resumen General

Se han analizado los dos últimos commits del repositorio:

1. **Commit más reciente (cee7257)**: "Initial plan" - Realizado por copilot-swe-agent[bot] el 4 de febrero de 2026
2. **Commit anterior (4b4db19)**: "24-4-2025  12:55" - Realizado por Antonio Martín el 24 de abril de 2025

## Diferencias Principales

### Commit 1 (cee7257) - "Initial plan"
- **Autor**: copilot-swe-agent[bot]
- **Fecha**: 4 de febrero de 2026, 20:57:03 UTC
- **Cambios**: Este commit NO contiene cambios de archivos. Es únicamente un commit de planificación.

### Commit 2 (4b4db19) - "24-4-2025  12:55"
- **Autor**: Antonio Martín (amartinsierra)
- **Fecha**: 24 de abril de 2025, 12:54:52 +0200
- **Cambios**: Este commit contiene cambios significativos con **1,927 inserciones** en 34 archivos.

## Archivos Afectados en el Commit 4b4db19

El commit anterior (4b4db19) incluyó una serie importante de archivos nuevos:

### Archivos HTML (ejemplos de JavaScript):
- `01_saludo.html` - `27_reloj.html`: Serie de 27 archivos HTML con ejemplos de código JavaScript
- `28_carrito_basico.html`: Aplicación de carrito de compras básica (65 líneas)
- `29_carrito_basico_fichero.html`: Versión del carrito que lee productos desde un archivo JSON (87 líneas)
- `buscador.html`: Prototipo de buscador (163 líneas)
- `prueba.html`: Archivo de prueba (11 líneas)

### Archivos de Datos:
- `productos.json`: Archivo JSON con 6 productos (alimentación, textil, informática)

### Recursos:
- `papelera.png`: Imagen PNG (16,343 bytes)
- `pizarra.pptx`: Presentación PowerPoint (812,744 bytes)

## Análisis Detallado de los Cambios Principales

### 1. Evolución del Carrito de Compras

#### `28_carrito_basico.html`:
- Implementa un carrito de compras con datos hardcodeados
- Características:
  - Catálogo de productos en una tabla HTML
  - Array de productos en JavaScript con 6 elementos
  - Funcionalidad para agregar productos al carrito
  - Funcionalidad para eliminar productos del carrito
  - Cálculo automático del total usando `map()` y `reduce()`

#### `29_carrito_basico_fichero.html`:
- Versión mejorada que carga productos desde un archivo externo
- Nuevas características:
  - Componente `<input type="file">` para seleccionar archivo JSON
  - Uso de `FileReader` API para leer archivos del sistema
  - Manejo de eventos `onload` y `onerror` para la lectura de archivos
  - Validación de extensión `.json` mediante atributo `accept`
  - Misma funcionalidad de carrito que la versión básica

### 2. Archivo de Datos `productos.json`

Contiene un array JSON con 6 productos:
```json
[
  {"producto":"pan","categoria":"Alimentación","precio":1.2},
  {"producto":"guantes","categoria":"Textil","precio":22.5},
  {"producto":"zapatos","categoria":"Textil","precio":65.0},
  {"producto":"pantalla","categoria":"Informática","precio":200},
  {"producto":"teclado","categoria":"Informática","precio":35.8},
  {"producto":"leche","categoria":"Alimentación","precio":2.0}
]
```

## Conceptos de JavaScript Demostrados

El commit 4b4db19 demuestra varios conceptos importantes de JavaScript:

1. **Manipulación del DOM**: Uso de `document.getElementById()` y `innerHTML`
2. **Event Listeners**: `addEventListener` para eventos `DOMContentLoaded` y `change`
3. **Arrow Functions**: Uso extensivo de funciones flecha `=>`
4. **Array Methods**: 
   - `forEach()` para iterar sobre arrays
   - `map()` para transformar arrays
   - `reduce()` para acumular valores
   - `push()` y `splice()` para modificar arrays
5. **Template Literals**: Uso de backticks para strings con interpolación
6. **File API**: Uso de `FileReader` para leer archivos locales
7. **JSON**: Parsing de datos JSON con `JSON.parse()`

## Conclusión

La diferencia principal entre los dos commits es que:

- **El commit más reciente (cee7257)** es un commit vacío de planificación realizado por un bot.
- **El commit anterior (4b4db19)** contiene todo el contenido real del proyecto: 34 archivos con ejemplos de JavaScript, incluyendo dos implementaciones de un carrito de compras que demuestran la progresión desde datos hardcodeados hasta datos cargados dinámicamente desde archivos JSON.

El trabajo sustancial se encuentra en el commit 4b4db19, que representa una colección completa de ejemplos educativos de JavaScript, progresando desde conceptos básicos hasta aplicaciones más complejas como el sistema de carrito de compras.
