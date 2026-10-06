<!-- ELUCENIA technical documentation · escala-de-rankin-modificada · fr · no clinical/professional/rights approval -->

# Échelle de Rankin modifiée (mRS)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/escala-de-rankin-modificada)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Situation actuelle du patient

`mrs`

- `0` — 0 – Aucun symptôme
- `1` — 1 – Aucun handicap significatif : effectue toutes les activités habituelles malgré les symptômes
- `2` — 2 – Handicap léger : ne réalise pas toutes les activités antérieures, mais se prend en charge sans aide
- `3` — 3 – Handicap modéré : nécessite une certaine aide, mais marche sans l’aide d’une autre personne
- `4` — 4 – Handicap modérément sévère : ne marche pas et ne satisfait pas ses besoins corporels sans aide
- `5` — 5 – Handicap sévère : alité, incontinent, nécessite des soins constants
- `6` — 6 – Décès

## Édition de la méthode

mRS/NINDS C13230 version 3 : grades 0–6, sans somme ; van Swieten 1988 : six grades 0–5 ; Cincura 2009 : référence d’adaptation brésilienne, non revérifiée dans cette vérification

## Formule documentée

Choisissez la catégorie décrivant le mieux le patient. Pas de somme : le résultat est le degré lui-même (0 à 6).

## Limites et population

Classification ordinale du handicap chez les patients ayant subi un AVC, dépendant de l’évaluation fonctionnelle et du temps de suivi. Privilégiez les instructions structurées de l’édition adoptée. La variante locale 0–6 doit être distinguée des six catégories décrites dans le résumé historique de 1988. Dans cette vérification documentaire, les valeurs de 0 à 6 ont été lues dans l’élément de données officiel NINDS C13230, version 3. Le résumé de van Swieten (1988) décrit six grades de 0 à 5. La correspondance du code sélectionné ne valide ni l’évaluation fonctionnelle, ni l’entretien, ni l’adaptation brésilienne.

## Références

- [van Swieten JC et al. Interobserver agreement for the assessment of handicap in stroke patients. Stroke, 1988.](https://doi.org/10.1161/01.STR.19.5.604)

- [Cincura C et al. Validation of the National Institutes of Health Stroke Scale, Modified Rankin Scale and Barthel Index in Brazil: the role of cultural adaptation and structured interviewing. Cerebrovasc Dis, 2009.](https://doi.org/10.1159/000177918)

- [NINDS C13230 version 3. Modified Rankin Scale score: official current permissible values 0–6.](https://cde.nlm.nih.gov/deView?tinyId=1Ff4qmrHH1C)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Handicap léger : indépendant

mRS 0 à 2 : issue fonctionnelle favorable (indépendance).


### 2

Invalidité modérée : dépendance partielle


### 3

Invalidité sévère : dépendance totale

