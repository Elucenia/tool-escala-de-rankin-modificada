<!-- ELUCENIA technical documentation · escala-de-rankin-modificada · pt-BR · no clinical/professional/rights approval -->

# Escala de Rankin modificada (mRS)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/escala-de-rankin-modificada)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Situação atual do paciente

`mrs`

- `0` — 0 – Sem sintomas
- `1` — 1 – Sem incapacidade significativa: faz todas as atividades habituais, apesar dos sintomas
- `2` — 2 – Incapacidade leve: não faz todas as atividades prévias, mas cuida de si sem ajuda
- `3` — 3 – Incapacidade moderada: precisa de alguma ajuda, mas anda sem auxílio de outra pessoa
- `4` — 4 – Incapacidade moderadamente grave: não anda nem cuida do corpo sem ajuda
- `5` — 5 – Incapacidade grave: acamado, incontinente, precisa de cuidado constante
- `6` — 6 – Óbito

## Edição do método

mRS/NINDS C13230 versão 3: graus 0–6, sem soma; van Swieten 1988: seis graus 0–5; Cincura 2009: referência de adaptação brasileira, não reconferida nesta verificação

## Fórmula documentada

Escolha a categoria que melhor descreve o paciente. Não há soma: o resultado é o próprio grau (0 a 6).

## Limites e população

Classificação ordinal de incapacidade em pacientes com AVC, dependente de avaliação funcional e do tempo de seguimento. Prefira instruções estruturadas da edição adotada. A variante local 0–6 precisa ser distinguida das seis categorias descritas no resumo histórico de 1988. Nesta verificação documental, os valores de 0 a 6 foram lidos no elemento de dados oficial NINDS C13230, versão 3. O resumo de van Swieten (1988) descreve seis graus de 0 a 5. A correspondência do código selecionado não valida a avaliação funcional, a entrevista ou a adaptação brasileira.

## Referências

- [van Swieten JC et al. Interobserver agreement for the assessment of handicap in stroke patients. Stroke, 1988.](https://doi.org/10.1161/01.STR.19.5.604)

- [Cincura C et al. Validation of the National Institutes of Health Stroke Scale, Modified Rankin Scale and Barthel Index in Brazil: the role of cultural adaptation and structured interviewing. Cerebrovasc Dis, 2009.](https://doi.org/10.1159/000177918)

- [NINDS C13230 version 3. Modified Rankin Scale score: official current permissible values 0–6.](https://cde.nlm.nih.gov/deView?tinyId=1Ff4qmrHH1C)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
