# Identidad visual — Cámara Empresaria de Tandil

Este repositorio guarda la **paleta de colores, tipografías y logos** de la CET (y de las instituciones aliadas) para usarlos de forma consistente, a mano o con cualquier inteligencia artificial.

## Cómo usarlo con una IA

1. Copiá el link de este repositorio.
2. Pegalo en tu pedido: *"Leé el DESIGN.md de este repo y armá un flyer para…"*
3. Si la IA no puede abrir links (el repo es privado), descargá el repo con **Code → Download ZIP** y adjuntá el `DESIGN.md` y los logos que necesites.

## Qué hay adentro

```
DESIGN.md              ← manual de marca de la Cámara (colores, tipografías, reglas)
logos/
  cet/                 ← logos de la Cámara (todas las variantes)
aliados/
  fce/                 ← Facultad de Ciencias Económicas: guia.md + logos
  unicen/              ← Universidad Nacional del Centro: logo (guía pendiente)
  (una carpeta por cada institución aliada)
README.md              ← esta guía
```

## Cómo agregar o cambiar un logo de la Cámara (sin saber programar)

1. Entrá al repositorio en GitHub y abrí la carpeta `logos/cet/`.
2. Tocá **Add file → Upload files** y arrastrá el archivo.
3. Usá nombres en minúscula, sin espacios ni tildes: `cet-horizontal-color.png`.
4. Abajo, en **Commit changes**, escribí un mensaje corto (ej.: "Agrego logo vertical") y confirmá.
5. Si es un logo nuevo, sumá una fila en la tabla de `DESIGN.md` (botón del lápiz → editar → **Commit changes**).

## Cómo agregar una institución aliada nueva

1. Creá una carpeta con su nombre corto en minúscula dentro de `aliados/` (ej.: `aliados/came/`). En GitHub: **Add file → Create new file**, escribí `aliados/came/guia.md` en el nombre y confirmá.
2. Subile sus logos a esa carpeta (**Add file → Upload files**), con nombres como `came-horizontal-color.png`.
3. En `guia.md` anotá sus colores, tipografía y reglas de uso, tomadas de su manual de marca. Si no hay manual, dejar escrito que no se definió.
4. Sumá o actualizá su fila en la tabla de la sección 4 de `DESIGN.md`.

## Formatos recomendados

- **SVG** si lo tenés (se ve nítido en cualquier tamaño). Si no, **PNG con fondo transparente**.
- Evitar JPG para logos (no tiene transparencia).
- No subir tipografías pagas (como Gotham) ni fotos pesadas: dejar el link a la fuente oficial.

## Cómo cambiar un color

Abrí `DESIGN.md`, tocá el lápiz de editar, cambiá el código HEX en la tabla de la sección 1 y confirmá.
