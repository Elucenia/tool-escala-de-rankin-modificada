<!-- ELUCENIA technical documentation · escala-de-rankin-modificada · it · no clinical/professional/rights approval -->

# Scala di Rankin modificata (mRS)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/escala-de-rankin-modificada)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Situazione attuale del paziente

`mrs`

- `0` — 0 – Nessun sintomo
- `1` — 1 – Nessuna disabilità significativa: svolge tutte le attività abituali nonostante i sintomi
- `2` — 2 – Disabilità lieve: non svolge tutte le attività precedenti, ma si prende cura di sé senza aiuto
- `3` — 3 – Disabilità moderata: necessita di qualche aiuto, ma cammina senza l’aiuto di un’altra persona
- `4` — 4 – Disabilità moderatamente grave: non cammina né soddisfa i bisogni corporei senza aiuto
- `5` — 5 – Disabilità grave: allettato, incontinente, necessita di assistenza costante
- `6` — 6 – Decesso

## Edizione del metodo

mRS/NINDS C13230 versione 3: gradi 0–6, senza somma; van Swieten 1988: sei gradi 0–5; Cincura 2009: riferimento dell’adattamento brasiliano, non ricontrollato in questa verifica

## Formula documentata

Scegliere la categoria più adatta. Nessuna somma: il risultato è il grado stesso (0 a 6).

## Limiti e popolazione

Classificazione ordinale della disabilità nei pazienti con ictus, dipendente dalla valutazione funzionale e dal tempo di follow-up. Preferire le istruzioni strutturate dell’edizione adottata. La variante locale 0–6 va distinta dalle sei categorie descritte nell’abstract storico del 1988. In questa verifica documentale, i valori da 0 a 6 sono stati letti nell’elemento di dati ufficiale NINDS C13230, versione 3. L’abstract di van Swieten (1988) descrive sei gradi da 0 a 5. La corrispondenza del codice selezionato non valida la valutazione funzionale, l’intervista o l’adattamento brasiliano.

## Riferimenti

- [van Swieten JC et al. Interobserver agreement for the assessment of handicap in stroke patients. Stroke, 1988.](https://doi.org/10.1161/01.STR.19.5.604)

- [Cincura C et al. Validation of the National Institutes of Health Stroke Scale, Modified Rankin Scale and Barthel Index in Brazil: the role of cultural adaptation and structured interviewing. Cerebrovasc Dis, 2009.](https://doi.org/10.1159/000177918)

- [NINDS C13230 version 3. Modified Rankin Scale score: official current permissible values 0–6.](https://cde.nlm.nih.gov/deView?tinyId=1Ff4qmrHH1C)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Disabilità lieve: indipendente

mRS 0 a 2: esito funzionale favorevole (indipendenza).


### 2

Disabilità moderata: dipendenza parziale


### 3

Disabilità grave: dipendenza totale

