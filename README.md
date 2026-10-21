# Identidad visual — Cámara Empresaria de Tandil

Este repositorio guarda la **paleta de colores, tipografías y logos** de la CET (y de las instituciones aliadas) para usarlos de forma consistente, a mano o con cualquier inteligencia artificial.

## Cómo usarlo con una IA

1. Copiá el link de este repositorio.
2. Pegalo en tu pedido: *"Leé el DESIGN.md de este repo y armá un flyer para…"*
3. Si la IA no puede abrir links (el repo es privado), descargá el repo con **Code → Download ZIP** y adjuntá el `DESIGN.md` y los logos que necesites.

## Qué hay adentro

```
DESIGN.md                ← manual de marca de la Cámara (colores, tipografías, reglas)
README.md                ← esta guía
logos/
  cet/                   ← logos de la Cámara (todas las variantes)
aliados/
  fce/                   ← Facultad de Ciencias Económicas: guia.md + logos
  unicen/                ← Universidad Nacional del Centro
  municipio-tandil/      ← Municipio de Tandil
  came/                  ← Confederación Argentina de la Mediana Empresa
  feba/                  ← Federación Empresaria de la Provincia de Buenos Aires
  apymet/                ← Asociación de la Pequeña y Mediana Empresa de Tandil
```

Las carpetas ya están creadas: solo hay que subir los logos con el nombre que figura abajo.

## Cómo subir un logo (sin saber programar)

1. Entrá al repositorio en GitHub y abrí la carpeta que corresponde (tabla de abajo).
2. Tocá **Add file → Upload files** y arrastrá el archivo.
3. **Antes de subirlo, renombralo** en tu computadora con el nombre de la tabla: minúscula, con guiones, sin espacios, sin paréntesis y sin tildes.
4. Abajo, en **Commit changes**, escribí un mensaje corto (ej.: "Agrego logo de CAME") y confirmá.
5. Si es un logo nuevo que no está en la tabla de `DESIGN.md`, sumá una fila (botón del lápiz → editar → **Commit changes**).

## Mapa de nombres: qué archivo de Drive va a qué carpeta

Los logos se sacan de la carpeta de Drive de logos de la Cámara. Si hay varias copias del mismo archivo ("(1)", "(2)"…), subir una sola.

**Logos de la Cámara → `logos/cet/`** (están en la subcarpeta "Logo 2024" de Drive)

| En Drive | Subirlo como |
|---|---|
| `CET_Logo_Color-Horizontal.png` | `cet-horizontal-color.png` |
| `CET_Logo_1-Color-Horizontal-Blanco.png` | `cet-horizontal-blanco.png` |
| `CET_Logo_1-Color-Horizontal.png` | `cet-horizontal-monocromo.png` |
| `CET_Logo_Color-Vertical.png` | `cet-vertical-color.png` |
| `CET_Logo_Color-Vertical.pdf` | `cet-vertical-color.pdf` |
| `CET_Logo_1-Color-Vertical-Blanco.png` | `cet-vertical-blanco.png` |
| `CET_Logo_1-Color-Vertical.png` | `cet-vertical-monocromo.png` |

**Aliados → `aliados/<nombre>/`**

| En Drive | Carpeta | Subirlo como |
|---|---|---|
| `unicen.png` | `aliados/unicen/` | `unicen-logo.png` |
| `Logo_Municipio_de_Tandil.png` | `aliados/municipio-tandil/` | `municipio-tandil-color.png` |
| `logo_muni_blanco.e3438d9.gif` | `aliados/municipio-tandil/` | `municipio-tandil-blanco.gif` |
| `came1.png` | `aliados/came/` | `came-logo.png` |
| `Logo-FEBA-final.ai` | `aliados/feba/` | `feba-logo.ai` (exportar también un PNG: `feba-logo.png`) |
| `APYMET (1).png` | `aliados/apymet/` | `apymet-sello-azul.png` |
| `APYMET.jpg` | `aliados/apymet/` | `apymet-sello-color.jpg` |

**Regla de nombres:** `institución-variante-color.extensión`. Sin números de versión (GitHub guarda el historial). Si hay un SVG o un PNG con fondo transparente, usar ese antes que un JPG.

## Cómo agregar una institución aliada nueva

1. Creá una carpeta con su nombre corto en minúscula dentro de `aliados/` (ej.: `aliados/usina-tandil/`). En GitHub: **Add file → Create new file**, escribí `aliados/usina-tandil/guia.md` en el nombre y confirmá.
2. Subile sus logos a esa carpeta (**Add file → Upload files**), con nombres como `usina-tandil-logo.png`.
3. En `guia.md` anotá sus colores, tipografía y reglas de uso, tomadas de su manual de marca. Si no hay manual, dejar escrito que no se definió.
4. Sumá o actualizá su fila en la tabla de la sección 4 de `DESIGN.md`.

## Formatos recomendados

- **SVG** si lo tenés (se ve nítido en cualquier tamaño). Si no, **PNG con fondo transparente**.
- Evitar JPG y GIF para logos (no tienen transparencia o tienen poca calidad).
- No subir tipografías pagas (como Gotham) ni fotos pesadas: dejar el link a la fuente oficial.

## Cómo cambiar un color

Abrí `DESIGN.md`, tocá el lápiz de editar, cambiá el código HEX en la tabla de la sección 1 y confirmá.
