<!-- ELUCENIA technical documentation · escala-de-rankin-modificada · en · no clinical/professional/rights approval -->

# Modified Rankin Scale (mRS)

[conditions, sources and permissions](https://elucenia.org/en/tools/escala-de-rankin-modificada)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Patient’s current status

`mrs`

- `0` — 0 – No symptoms
- `1` — 1 – No significant disability: performs all usual activities despite symptoms
- `2` — 2 – Slight disability: cannot perform all previous activities but looks after self without help
- `3` — 3 – Moderate disability: needs some help but walks without another person’s assistance
- `4` — 4 – Moderately severe disability: cannot walk or attend to bodily needs without help
- `5` — 5 – Severe disability: bedridden, incontinent, needs constant care
- `6` — 6 – Death

## Method edition

mRS/NINDS C13230 version 3: grades 0–6, no sum; van Swieten 1988: six grades 0–5; Cincura 2009: Brazilian adaptation reference, not rechecked in this review

## Documented formula

Select the category best describing the patient. There is no sum: the result is the grade itself (0 to 6).

## Limits and population

An ordinal classification of disability in patients with stroke, dependent on functional assessment and follow-up time. Prefer structured instructions from the adopted edition. The local 0–6 variant must be distinguished from the six categories described in the historical 1988 abstract. In this documentary review, values 0 to 6 were read in the official NINDS C13230 data element, version 3. The van Swieten (1988) abstract describes six grades from 0 to 5. Matching the selected code does not validate functional assessment, the interview or the Brazilian adaptation.

## References

- [van Swieten JC et al. Interobserver agreement for the assessment of handicap in stroke patients. Stroke, 1988.](https://doi.org/10.1161/01.STR.19.5.604)

- [Cincura C et al. Validation of the National Institutes of Health Stroke Scale, Modified Rankin Scale and Barthel Index in Brazil: the role of cultural adaptation and structured interviewing. Cerebrovasc Dis, 2009.](https://doi.org/10.1159/000177918)

- [NINDS C13230 version 3. Modified Rankin Scale score: official current permissible values 0–6.](https://cde.nlm.nih.gov/deView?tinyId=1Ff4qmrHH1C)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
