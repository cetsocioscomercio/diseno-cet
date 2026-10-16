# DESIGN.md — Identidad visual de la Cámara Empresaria de Tandil (CET)

> **Para cualquier IA (Claude, ChatGPT, Gemini, etc.):** leé este archivo completo antes de crear cualquier pieza (informe, flyer, presentación, planilla, mail, post). Usá SOLO los colores, tipografías y logos definidos acá. Los logos están en la carpeta `logos/` de este mismo repositorio. Si falta un dato (marcado como `COMPLETAR`), no lo inventes: avisá y preguntá.

Última actualización: COMPLETAR (fecha)
Responsable: Área de Comercio y Servicios — comercio@camaraempresaria.org.ar

---

## 1. Paleta de colores

> Cargar los valores exactos tomados del logo (se puede usar un cuentagotas en Canva o https://imagecolorpicker.com).

| Rol | Nombre | HEX | RGB | Uso |
|---|---|---|---|---|
| Principal | COMPLETAR | `#______` | COMPLETAR | Títulos, encabezados, botones, elementos de marca |
| Secundario | COMPLETAR | `#______` | COMPLETAR | Subtítulos, detalles, íconos |
| Acento | COMPLETAR | `#______` | COMPLETAR | Destacados, llamados a la acción (usar poco) |
| Fondo claro | COMPLETAR | `#______` | COMPLETAR | Fondos de página, tablas |
| Texto | COMPLETAR | `#______` | COMPLETAR | Texto de párrafo |
| Blanco | Blanco | `#FFFFFF` | 255, 255, 255 | Texto sobre fondo de marca |

**Reglas de color**
- Texto sobre fondo de marca: usar blanco, verificando buen contraste.
- No usar colores fuera de esta paleta, salvo neutros (grises) para detalles menores.
- Gráficos y tablas: tomar los colores de esta paleta, ordenados por prioridad (principal, secundario, acento).

## 2. Tipografías

| Uso | Tipografía | Notas |
|---|---|---|
| Documentos y planillas (Word, Excel, Google Docs) | **Calibri** | Estándar interno |
| Títulos en piezas gráficas | COMPLETAR | Si no hay tipografía institucional, usar Calibri Bold |
| Texto en piezas gráficas | COMPLETAR | |

Tamaños sugeridos para documentos: título 20 pt · subtítulo 14 pt · texto 11 pt.

## 3. Logos de la Cámara

Todos los archivos están en `logos/cet/`. Preferir siempre **SVG** (vectorial); si no hay, usar PNG con fondo transparente.

| Variante | Archivo | Cuándo usarla |
|---|---|---|
| Principal horizontal, color | `logos/cet/cet-horizontal-color.png` | Uso general, encabezados de documentos, fondo claro |
| Vertical, color | `logos/cet/cet-vertical-color.png` | Espacios cuadrados, portadas, redes |
| Solo isotipo / símbolo | `logos/cet/cet-isotipo.png` | Avatares, íconos, sellos, espacios pequeños |
| Blanco (negativo) | `logos/cet/cet-horizontal-blanco.png` | Sobre fondos de color o fotos oscuras |
| Negro / monocromo | `logos/cet/cet-horizontal-negro.png` | Impresiones en blanco y negro, sellos |
| Sello certificación DNV | `logos/cet/sello-dnv.png` | Solo en piezas donde corresponda mencionar la certificación |

> Si algún archivo todavía no existe, subirlo con ese nombre exacto o actualizar la tabla.

**Reglas de uso**
- Dejar espacio libre alrededor del logo igual a la altura de la inicial del nombre (COMPLETAR si hay manual).
- Tamaño mínimo: COMPLETAR (ej.: 30 mm de ancho en impresión / 120 px en pantalla).
- No deformar, rotar, recolorear, agregar sombras ni cambiar la tipografía del logo.
- Sobre fondo oscuro o fotos: usar la versión blanca.
- Sobre fondo claro: usar la versión color.

## 4. Instituciones aliadas

Logos en `logos/aliados/`. Cada institución tiene su propio manual de marca: **respetar sus colores y proporciones y no modificarlos**.

| Institución | Archivo | Notas |
|---|---|---|
| UNICEN — Universidad Nacional del Centro de la Provincia de Buenos Aires | `logos/aliados/unicen.png` | COMPLETAR |
| FCE — Facultad de Ciencias Económicas (UNICEN) | `logos/aliados/fce-unicen.png` | COMPLETAR |
| Municipio de Tandil | `logos/aliados/municipio-tandil.png` | COMPLETAR |
| CAME — Confederación Argentina de la Mediana Empresa | `logos/aliados/came.png` | COMPLETAR |
| FEBA — Federación Empresaria de la Provincia de Buenos Aires | `logos/aliados/feba.png` | COMPLETAR |

**Reglas al combinar con aliados**
- El logo de la CET va primero (a la izquierda o arriba), salvo que la institución organizadora indique otro orden.
- Todos los logos del conjunto con la misma altura visual, separados por espacio parejo.
- Usar una franja o fila de logos al pie de la pieza, sobre fondo blanco.
- Para acciones conjuntas (ej.: CET + Municipio), usar el orden acordado con la contraparte. COMPLETAR si hay convenio que lo defina.
- Agregar un logo aliado nuevo: ver `README.md`.

## 5. Tono y estilo (opcional)

- Idioma: español rioplatense, tono institucional cercano, voseo en comunicaciones a socios.
- Firma institucional: Cámara Empresaria de Tandil · comercio@camaraempresaria.org.ar
- Datos de contacto, redes y web: COMPLETAR.

## 6. Ejemplo de prompt para usar con cualquier IA

> "Leé el DESIGN.md de este repositorio: [LINK AL REPO]. Con esa identidad, armá [una presentación / un informe / un flyer] sobre [tema]. Usá el logo principal en el encabezado y, si corresponde, la fila de aliados al pie."
