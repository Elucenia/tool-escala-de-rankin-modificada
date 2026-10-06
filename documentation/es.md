<!-- ELUCENIA technical documentation · escala-de-rankin-modificada · es · no clinical/professional/rights approval -->

# Escala de Rankin modificada (mRS)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/escala-de-rankin-modificada)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Situación actual del paciente

`mrs`

- `0` — 0 – Sin síntomas
- `1` — 1 – Sin discapacidad significativa: realiza todas las actividades habituales pese a los síntomas
- `2` — 2 – Discapacidad leve: no realiza todas las actividades previas, pero se cuida sin ayuda
- `3` — 3 – Discapacidad moderada: necesita alguna ayuda, pero camina sin ayuda de otra persona
- `4` — 4 – Discapacidad moderadamente grave: no camina ni atiende sus necesidades corporales sin ayuda
- `5` — 5 – Discapacidad grave: encamado, incontinente, necesita cuidados constantes
- `6` — 6 – Fallecimiento

## Edición del método

mRS/NINDS C13230 versión 3: grados 0–6, sin suma; van Swieten 1988: seis grados 0–5; Cincura 2009: referencia de adaptación brasileña, no revisada de nuevo en esta verificación

## Fórmula documentada

Elija la categoría que mejor describe al paciente. No se suma: el resultado es el propio grado (0 a 6).

## Límites y población

Clasificación ordinal de discapacidad en pacientes con ictus, dependiente de la evaluación funcional y del tiempo de seguimiento. Prefiera las instrucciones estructuradas de la edición adoptada. La variante local 0–6 debe distinguirse de las seis categorías descritas en el resumen histórico de 1988. En esta verificación documental, los valores de 0 a 6 se leyeron en el elemento de datos oficial NINDS C13230, versión 3. El resumen de van Swieten (1988) describe seis grados de 0 a 5. La correspondencia del código seleccionado no valida la evaluación funcional, la entrevista ni la adaptación brasileña.

## Referencias

- [van Swieten JC et al. Interobserver agreement for the assessment of handicap in stroke patients. Stroke, 1988.](https://doi.org/10.1161/01.STR.19.5.604)

- [Cincura C et al. Validation of the National Institutes of Health Stroke Scale, Modified Rankin Scale and Barthel Index in Brazil: the role of cultural adaptation and structured interviewing. Cerebrovasc Dis, 2009.](https://doi.org/10.1159/000177918)

- [NINDS C13230 version 3. Modified Rankin Scale score: official current permissible values 0–6.](https://cde.nlm.nih.gov/deView?tinyId=1Ff4qmrHH1C)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Discapacidad leve: independiente

mRS 0 a 2: resultado funcional favorable (independencia).


### 2

Discapacidad moderada: dependencia parcial


### 3

Discapacidad grave: dependencia total

