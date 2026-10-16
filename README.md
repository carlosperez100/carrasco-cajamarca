# Edison Carrasco Olivera · Gobernador Regional de Cajamarca

Portal informativo de campaña. **Segunda Elección Regional: domingo 6 de diciembre de 2026.**

Candidato del **Partido Democrático Somos Perú**, lista 38403, expediente **ERM.2026021166**, fórmula INSCRITA ante el Jurado Nacional de Elecciones. Vicegobernadora Regional: Amparo Leocadia Ramírez Triveños.

## Qué hay acá

- `index.html` — inicio: quién es el candidato, los cinco números de Cajamarca y el balance de la gestión dicho de frente.
- `discurso.html` — el discurso de plaza.
- `ejes.html` — las propuestas: seis ejes con la meta, la línea de base y la competencia legal.
- `mapa.html` — mapa interactivo de las 13 provincias con las brechas del Censo 2025, el ranking y las demandas prioritarias por el método GEMSES.
- `documentos.html` — Plan de Gobierno, hoja de vida ante el Jurado Nacional de Elecciones y la fuente de cada cifra.

## Cómo se genera

Sitio estático, sin dependencias. Se genera con `python tools/construir_sitio.py` desde el proyecto `p35_CAJAMARCA_CARRASCO`. Los datos del mapa salen de `tools/construir_provincias.py`.

**Todas las cifras tienen fuente oficial citada** (Instituto Nacional de Estadística e Informática, Oficina Nacional de Procesos Electorales, Jurado Nacional de Elecciones y el propio Plan de Gobierno). Nada de material interno de campaña se publica acá.
