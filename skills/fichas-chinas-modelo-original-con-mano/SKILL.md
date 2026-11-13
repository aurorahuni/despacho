---
name: Fichas chinas — modelo original con mano
description: "Usar al preparar fichas de servicios en chino simplificado con el diseño original de bloques y la mano \U0001F449 delante de cada encabezado, preservando la papelería aprobada."
---
# Fichas chinas: modelo original con mano

## Objetivo
Replicar el estilo visual concreto de la ficha inicial aprobada, no solo su estructura. Contenido en chino simplificado. Usar la papelería aprobada para la organización del encargo y mantener los originales intactos. Este skill no autoriza envíos externos, publicaciones, borrados ni sincronizaciones.

## Recursos de referencia persistentes
Directorio: la carpeta de plantillas aprobada `fichas-chinas-mano-original/`.
- `stationery.png`: fondo exacto aprobado del ejemplo, con logo, marca de agua, encabezado, pie y QR.
- `pointer.png`: mano original recortada (39×33 px); usar esta imagen, NO un emoji dependiente de la fuente.
- `review-updated-2026.png`: referencia visual revisada del modelo de bloques, con la mano delante.
- `texto-chino.txt`: contenido de ejemplo, NO catálogo universal de precios ni requisitos vigentes.
Estos recursos corresponden a la organización del ejemplo. Para otra organización usar sus recursos aprobados, nunca atribuirle este branding. No ejecutar scripts de borradores que puedan copiar automáticamente a base/export; generar un render sin efectos laterales.

## Receta
1. Leer el servicio solicitado y sus fuentes verificadas. Confirmar título aprobado, requisitos, importes, año y alcance. No inventar precios ni plazos, ni reutilizar umbrales viejos del ejemplo como actuales. Lo desconocido se marca pendiente de confirmar.
2. Abrir la referencia visual y el fondo. Conservar exactamente logo, marca de agua, QR, encabezado y pie: no redibujarlos, no reemplazarlos ni recrearlos con generación de imágenes. Si hay una actualización aprobada de papelería, usarla sin cambios ajenos al encargo.
3. Lienzo vertical blanco 1020×1320 px. Título centrado en y=177, Noto Sans CJK SC Bold 29 px, color #7a1f2b. Conservar literalmente el título que el usuario aprobó; no agregar un año ni subtítulo nuevo sin pedirlo. Ajustar solo para que quepa sin invadir logo o cuerpo.
4. Cuerpo desde x=102, y=248, ancho 816 px. Noto Sans CJK SC Regular 19–20 px; texto #1a1a1a; interlineado 28–32 px. Fuentes locales del ejemplo: `/usr/share/fonts/opentype/noto/NotoSansCJK-Regular.ttc` y `NotoSansCJK-Bold.ttc`, índice 2; comprobar disponibilidad antes de usarlas.
5. Mantener estos bloques y su orden cuando correspondan al servicio: `👉服务内容` (servicio), `👉申请条件` (condiciones), `👉所需材料` (documentos), `👉时效` (plazos), `👉服务价格` (honorarios). La MANO DELANTE es obligatoria, igual al modelo inicial: colocar `pointer.png` a 23×20 px, x=102, y=encabezado+4; texto de encabezado x=127, Bold 20 px. Separar bloques 10 px. No sustituir este formato por secciones numeradas genéricas. Preservar cuadros o notas aprobados cuando el encargo los incluya.
6. Honorarios en rojo #7a1f2b. Advertencias económicas en negrita #b3202a. Sin resaltado amarillo; solo conservar el amarillo propio de la mano. Separar claramente honorarios profesionales y derechos oficiales; indicar moneda, año y si están incluidos. No sumar dos representaciones redondeadas de la misma cuota.
7. Fuentes breves al final del cuerpo: 15–17 px, #555555; guardar URLs completas y fecha de consulta en un TXT complementario. El contenido termina antes de y=1120. Franja y=1130–1320 intacta. Si no cabe, añadir otra hoja con la misma papelería, sin recortar texto ni encoger el branding.
8. Renderizar localmente con Pillow o un equivalente tipográfico determinista, nunca con GenerateImage para el texto. Guardar resultado nuevo sin sobrescribir originales salvo instrucción explícita.
9. Revisar imagen completa: mano visible delante de cada bloque, caracteres sin cuadros vacíos, sin recortes ni superposiciones, cifras/citas/monedas correctas, título literal, logo/pie/QR intactos. Comprobar encabezado y pie contra el fondo. Entregar o copiar solo a los destinos pedidos; confirmar un guardado en equipo externo únicamente tras verificarlo.

## Caso de referencia: residencia por solvencia económica
Cuando el encargo sea reutilizar ESTA ficha, mantener el título literal `墨西哥经济能力居留办理（Residencia por solvencia económica）`, el modelo inicial de bloques con mano y los documentos actualizados. Distinguir la solicitud consular del canje INM; no mezclarlos en una lista universal. El ejemplo aprobado separa los honorarios profesionales de los derechos oficiales del año; los importes viven en la lista de precios vigente y en la fuente del encargo, no en esta skill, y solo se reutilizan tras verificar vigencia y alcance. Consultar la fuente oficial vigente suministrada con el encargo, no deducirla de la imagen. No incluir ninguna nota sobre citas en esta ficha mientras siga vigente la instrucción de omitirla. El ejemplo visual no sustituye la fuente documental ni autoriza cambiar contenido que el usuario pidió conservar.
