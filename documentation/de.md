<!-- ELUCENIA technical documentation · escala-de-rankin-modificada · de · no clinical/professional/rights approval -->

# Modifizierte Rankin-Skala (mRS)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/escala-de-rankin-modificada)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Aktueller Zustand des Patienten

`mrs`

- `0` — 0 – Keine Symptome
- `1` — 1 – Keine wesentliche Behinderung: führt trotz Symptomen alle üblichen Aktivitäten aus
- `2` — 2 – Leichte Behinderung: nicht alle früheren Aktivitäten möglich, aber selbstständig in der Selbstversorgung
- `3` — 3 – Mäßige Behinderung: benötigt etwas Hilfe, geht aber ohne Hilfe einer anderen Person
- `4` — 4 – Mittelschwere bis schwere Behinderung: kann ohne Hilfe weder gehen noch körperliche Bedürfnisse versorgen
- `5` — 5 – Schwere Behinderung: bettlägerig, inkontinent, benötigt ständige Pflege
- `6` — 6 – Tod

## Fassung der Methode

mRS/NINDS C13230 Version 3: Grade 0–6, keine Summierung; van Swieten 1988: sechs Grade 0–5; Cincura 2009: Referenz zur brasilianischen Anpassung, in dieser Prüfung nicht erneut überprüft

## Dokumentierte Formel

Passendste Kategorie wählen. Keine Addition: das Ergebnis ist der Grad selbst (0 bis 6).

## Grenzen und Population

Ordinale Behinderungsklassifikation bei Schlaganfallpatienten, abhängig von funktioneller Beurteilung und Nachbeobachtungszeit. Bevorzugen Sie strukturierte Anweisungen der verwendeten Ausgabe. Die lokale Variante 0–6 muss von den sechs Kategorien des historischen Abstracts von 1988 unterschieden werden. Bei dieser Dokumentenprüfung wurden die Werte 0 bis 6 im offiziellen NINDS-Datenelement C13230, Version 3, gelesen. Der Abstract von van Swieten (1988) beschreibt sechs Grade von 0 bis 5. Die Übereinstimmung des gewählten Codes validiert weder die funktionelle Beurteilung noch das Interview oder die brasilianische Anpassung.

## Referenzen

- [van Swieten JC et al. Interobserver agreement for the assessment of handicap in stroke patients. Stroke, 1988.](https://doi.org/10.1161/01.STR.19.5.604)

- [Cincura C et al. Validation of the National Institutes of Health Stroke Scale, Modified Rankin Scale and Barthel Index in Brazil: the role of cultural adaptation and structured interviewing. Cerebrovasc Dis, 2009.](https://doi.org/10.1159/000177918)

- [NINDS C13230 version 3. Modified Rankin Scale score: official current permissible values 0–6.](https://cde.nlm.nih.gov/deView?tinyId=1Ff4qmrHH1C)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
