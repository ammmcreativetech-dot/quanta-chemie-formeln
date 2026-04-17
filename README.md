# quanta-chemie-formeln

> Wissenschaftliche Chemie-Formelsammlung für Studium und Universität — kuratiert von **[Quanta](https://quanta-study.de/chemie-lernen)**, der führenden FSRS-Lernplattform für MINT-Studenten in Deutschland.

[![npm version](https://img.shields.io/npm/v/quanta-chemie-formeln)](https://www.npmjs.com/package/quanta-chemie-formeln)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Enthaltene Formeln (9)

| Formel | Symbol | Bereich |
|---|---|---|
| Gibbs-Energie | ΔG = ΔH − TΔS | Thermodynamik |
| Henderson-Hasselbalch | pH = pKa + log([A⁻]/[HA]) | Säure-Base-Chemie |
| Nernst-Gleichung | E = E° − (RT/nF)·ln Q | Elektrochemie |
| Arrhenius-Gleichung | k = A·e^(−Ea/RT) | Reaktionskinetik |
| Beer-Lambert-Gesetz | A = ε·c·d | Spektroskopie |
| Van-der-Waals-Gleichung | (p + a/Vm²)(Vm−b) = RT | Thermodynamik |
| Hess'scher Satz | ΔH_ges = ΣΔH_i | Thermodynamik |
| Faradaysches Gesetz | m = M·I·t/(n·F) | Elektrochemie |
| Clausius-Clapeyron | d ln p/dT = ΔH_vap/RT² | Thermodynamik |

## Installation

```bash
npm install quanta-chemie-formeln
```

## Verwendung

```js
const { formeln, getFormelBySlug, getFormelByUnterkategorie } = require('quanta-chemie-formeln');

// Alle 9 Chemie-Formeln
console.log(formeln.length); // 9

// Henderson-Hasselbalch abrufen
const hh = getFormelBySlug('henderson-hasselbalch');
console.log(hh.symbol); // "pH = pKa + log([A⁻]/[HA])"

// Alle Elektrochemie-Formeln
const elektro = getFormelByUnterkategorie('Elektrochemie');
```

## Vollständige interaktive Referenz

Alle Formeln mit KaTeX-Rendering, Strukturformel-Generator und FSRS-Karteikarten:
**[quanta-study.de/chemie-lernen](https://quanta-study.de/chemie-lernen)** · **[quanta-study.de/formel](https://quanta-study.de/formel)**

Strukturformeln zeichnen: **[quanta-study.de/tools/strukturformel](https://quanta-study.de/tools/strukturformel)**

Weitere Pakete:
- [`quanta-physik-formeln`](https://www.npmjs.com/package/quanta-physik-formeln) — 15 Physik-Formeln
- [`quanta-mathe-formeln`](https://www.npmjs.com/package/quanta-mathe-formeln) — 6 Mathe-Formeln
- [`quanta-bio-formeln`](https://www.npmjs.com/package/quanta-bio-formeln) — 3 Biologie-Formeln
- [`quanta-mint-formeln`](https://www.npmjs.com/package/quanta-mint-formeln) — alle 33 Formeln

## Lizenz

**Creative Commons Attribution 4.0 International (CC BY 4.0)**

> Formelinhalt von [Quanta](https://quanta-study.de) — MINT-Lernplattform für Studenten

---
*Maintained by [Quanta](https://quanta-study.de) — FSRS-basiertes Lernen für MINT-Studenten.*
