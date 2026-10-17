# Créditos de la música y las imágenes de los videos

## Música de fondo

**Pista en uso** (`img/musica_fondo.mp3`, en bucle y con el volumen cediendo bajo la voz): dos temas
instrumentales de sikus (zampoñas) y bombo.

- «Mula Lunthata» — maqueta ejecutada con pareja de sikus Malta y bombo.
- «29 de setiembre» — maqueta ejecutada con pareja de sikus Malta y bombo.

Autor: **Abel Christian Apaza Amanqui**, proyecto *Sikuri Sumaq Taqi* (Azángaro, Puno).
Licencia **Creative Commons Atribución-CompartirIgual 4.0 (CC BY-SA 4.0)**. Fuente, Wikimedia Commons:

- https://commons.wikimedia.org/wiki/File:Interpretaci%C3%B3n_del_tema_%22Mula_Lunthata%22_-_Maqueta_ejecutada_con_pareja_de_sikus_Malta_y_bombo.wav
- https://commons.wikimedia.org/wiki/File:Interpretaci%C3%B3n_del_tema_%2229_de_setiembre%22_-_Maqueta_ejecutada_con_pareja_de_sikus_Malta_y_bombo.wav

La licencia obliga a **citar al autor** y a **compartir con la misma licencia** cualquier derivado de
la pista. Por eso existe esta página y por eso el video la enlaza.

### Advertencia: esta música no es de Cajamarca

Conviene decirlo con todas sus letras. Los **sikus** son instrumento del altiplano, y esta grabación
es de **Azángaro, Puno**. La música del **carnaval de Cajamarca** es otra: se toca con **clarín**
—trompeta larga de caña— y **caja**, y el *Cilulo* con **pinkullo** y caja.

Se buscó en tres pasadas (Wikimedia Commons, Internet Archive y búsqueda abierta) una grabación de
carnaval cajamarquino con licencia libre y **no se encontró ninguna**. Hay que no confundir dos cosas:

- Las **melodías** tradicionales —*El Cilulo*, *La Carolina*, *La Matarina*, *Cumbe-Cumbe*— están en
  **dominio público** como composición.
- **Cualquier grabación concreta de ellas tiene dueño.** Tomar una de internet y ponerla en una pieza
  de campaña expone a la campaña.

**El camino correcto, y además el más fuerte políticamente:** que un **grupo de Cajamarca grabe el
instrumental**. La melodía es libre, la grabación queda de la campaña, cuesta poco, y la música es de
allá tocada por gente de allá.

**Para cambiarla** basta reemplazar `img/musica_fondo.mp3` y volver a correr
`tools/construir_video_hyper.py`. Si la pista nueva es propia, esta sección se reescribe con su
autoría y desaparece la obligación de CompartirIgual.

## Fotografías

Las fotografías de los candidatos provienen de su **Declaración Jurada de Hoja de Vida** publicada por
el **Jurado Nacional de Elecciones** en la plataforma Voto Informado (https://votoinformado.jne.gob.pe).

## Gráficos

Las doce láminas de datos (`img/graficos/*.png`) se generan con `tools/generar_graficos.py` a partir de
las cifras verificadas del proyecto. **Cada lámina lleva su fuente impresa**, y la tabla completa
—institución, año y enlace— está en la página de Documentos del portal y en `datos/ficha_datos.csv`.

## Narración

La narración de los videos es **voz sintética** (edge-tts, voz `es-PE-AlexNeural` en registro de
locutor). En el video de presentación narra un **narrador en tercera persona**: nadie finge ser el
candidato. El video del discurso, que sí está en primera persona, lo advierte en pantalla de principio
a fin. Cada frase de la narración es un archivo de audio independiente, de modo que la versión
definitiva pueda grabarse con voz real sin rehacer la animación.
