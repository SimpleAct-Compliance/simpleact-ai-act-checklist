# Das Netz der Repositories

Dieses Repository deckt den **Prüfschritt** ab. Es setzt ein Inventar und eine Einstufung voraus und erzeugt Befunde und Nachweise.

## Der Weg

```
  Inventar -> Einstufung -> [Prüfung] -> Dokumentation -> Audit -> Betrieb
```

| Richtung | Repository | Beantwortet |
|---|---|---|
| vorher | [KI-Inventar](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory) | Welche Einsatzzwecke sind überhaupt zu prüfen? |
| vorher | [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu) | Welche Klasse, und damit welche Punkte? |
| danach | [Dokumentationsvorlage](https://github.com/SimpleAct-Compliance/simpleact-ai-act-documentation-template) | Anhang IV im Einzelnen |
| danach | [Vorlagensammlung](https://github.com/SimpleAct-Compliance/simpleact-ai-act-templates) | welche Vorlage für welchen Nachweis |
| danach | [Audit-Vorbereitung](https://github.com/SimpleAct-Compliance/simpleact-ai-audit-readiness) | wenn eine Prüfung von außen ansteht |

Ohne das Inventar ist der **Nenner** unbekannt: Dann lautet das Ergebnis „acht von acht Punkten erfüllt" bei unbekannter Grundmenge. Das ist der häufigste Weg, mit einer Prüfliste nichts zu erfahren.

## Abgrenzung zur Audit-Vorbereitung

Die beiden werden verwechselt:

| | Diese Prüfliste | Audit-Vorbereitung |
|---|---|---|
| Frage | Ist der Zustand erreicht? | Ist er vorzeigbar? |
| Anlass | vor Inbetriebnahme, im Turnus | eine Prüfung steht an |
| Ergebnis | Befunde | Nachweispaket, Lückenliste |

Wer mit der Audit-Vorbereitung beginnt, weil ein Termin ansteht, dokumentiert Systeme, deren Prüfung nicht steht.

## Übergreifend

| Repository | Wofür |
|---|---|
| [Governance-Rahmenwerk](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework) | wie alle Teile zusammenhängen |
| [Governance-Playbook](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-playbook) | wer prüft, wer freigibt, wer eskaliert |
| [Vorfallmanagement](https://github.com/SimpleAct-Compliance/simpleact-incident-management) | Art. 72 und 73 |
| [AI Act für SaaS](https://github.com/SimpleAct-Compliance/simpleact-ai-act-for-saas) | wenn die Rollenfrage offen ist |
| [KI-Kompetenz](https://github.com/SimpleAct-Compliance/elearning) | Art. 4, seit 2.2.2025 |
| [Anbieterregister](https://github.com/SimpleAct-Compliance/simpleact-model-vendor-register) | für Befunde, die gegen den Anbieter gehen |

Das Governance-Playbook beantwortet die Frage, die der [Mindeststandard](../knowledge-base/eu-ai-act/minimum-review-standard.md) aufwirft: Wer darf feststellen, wenn es nur drei Leute gibt?

## Datenschutzseite

Die Datenschutzpunkte sind in dieser Prüfliste **enthalten** und nicht nachgelagert — in der Praxis prüfen Datenschutzaufsichten seit Jahren, KI-Marktüberwachung ist neu.

| Repository | Für |
|---|---|
| [DSGVO-Grundlagen](https://github.com/SimpleAct-Compliance/simpleact-gdpr-compliance-workspace) | Art. 30, Rechtsgrundlage, Betroffenenrechte |
| [DSFA und FRIA](https://github.com/SimpleAct-Compliance/simpleact-dpia-dsfa-workflow) | Art. 35 DSGVO und Art. 27 AI Act, getrennt geführt |
| [Datenschutzverletzungen](https://github.com/SimpleAct-Compliance/simpleact-gdpr-data-breach-management) | Art. 33 und 34 |

## Tarifgenaue Anbieterangaben

Für die Prüfpunkte zu Trainingsnutzung, Verarbeitungsort und Unterauftragsverarbeitern: ein öffentliches Register mit tarifgenauen Angaben, jede mit Quelle und Prüfdatum — **[actcomp.de](https://actcomp.de)**

Das erspart die Recherche, nicht die Feststellung: Der Nachweis bleibt die Fundstelle in den eigenen Vertragsunterlagen.
