# Prüfliste EU AI Act

**Ein Haken ist kein Nachweis.** Eine Prüfliste taugt nur, wenn zu jedem Punkt feststeht, *woran* man erkennt, dass er erfüllt ist, und *wer* das festgestellt hat. Dieses Repository beschreibt die Prüfung als Abfolge mit Mindeststandard — nicht als Liste zum Abhaken.

*The review layer: obligations per risk class in the order they have to be established, with a minimum standard for what counts as checked.*

---

## Das Problem mit Prüflisten

Sie erzeugen das Gefühl von Erfüllung. Vierzig Haken sehen aus wie vierzig erledigte Pflichten, und in einer Prüfung stellt sich heraus:

- Der Haken bezieht sich auf einen **Plan**, nicht auf einen Zustand.
- Er bezieht sich auf eine **Version**, die es nicht mehr gibt.
- Ihn hat die Person gesetzt, die auch die Arbeit gemacht hat.
- Niemand kann sagen, **wann** er gesetzt wurde.

Vier Lücken, und keine davon ist eine Wissenslücke. Deshalb steht hier vor jeder Liste ein [Mindeststandard](./knowledge-base/eu-ai-act/minimum-review-standard.md): Was muss vorliegen, damit ein Punkt als geprüft gilt.

## Die Reihenfolge

Eine Prüfung hat eine Ordnung, und sie wird häufig umgekehrt begangen:

```
  1 Gegenstand abgrenzen    (welcher Einsatzzweck, nicht welches Werkzeug)
  2 Rolle bestimmen         (Anbieter oder Betreiber — Art. 25 prüfen)
  3 Art. 5 prüfen           (ein Treffer beendet alles)
  4 Klasse bestimmen        (Anhang I, Anhang III, Art. 6 Abs. 3)
  5 Art. 50 prüfen          (unabhängig von Schritt 4)
  6 Pflichten je Klasse     (zuweisen, mit Person und Termin)
  7 Nachweise               (Version, Freigabestand, Fundort)
  8 Fortschreibung          (Auslöser, Turnus, Protokoll)
```

Wer bei Schritt 6 anfängt — weil die Pflichten die eigentliche Arbeit sind — weist Pflichten zu, deren Grundlage nicht steht. Ausführlich: [checklist-sequence.md](./knowledge-base/eu-ai-act/checklist-sequence.md)

## Zwei Fristen, die verwechselt werden

Nach dem **Digital Omnibus** (Verordnung (EU) 2026/1744, in Kraft seit 27.7.2026):

- **Art. 50 Transparenz: seit 2.8.2026 anwendbar** — nicht verschoben
- **Anhang III Hochrisiko: erst ab 2.12.2027** — um 16 Monate verschoben

Für eine Prüfliste heißt das: Die Art.-50-Punkte sind heute fällig, die Anhang-III-Punkte sind Vorarbeit. Wer beides gleich behandelt, prüft entweder zu viel oder das Falsche. Vollständige Fristen in [overview.md](./knowledge-base/eu-ai-act/overview.md).

## Die vier Zustände eines Nachweises

Ein Nachweis ist nicht entweder da oder nicht da. Er hat einen Zustand, und nur einer davon trägt:

| Zustand | Bedeutung | Trägt in einer Prüfung |
|---|---|---|
| **offen** | noch nicht erbracht, mit Person und Termin | als Befund, ja |
| **erbracht** | liegt vor, niemand hat nachgesehen | nein |
| **geprüft** | eine zweite Person hat nachgesehen | meist |
| **freigegeben** | mit Versionsbezug und Datum bestätigt | ja |

Der Sprung von **erbracht** zu **geprüft** ist der, der am häufigsten fehlt. Ausführlich: [evidence-register-and-approval-states.md](./knowledge-base/eu-ai-act/evidence-register-and-approval-states.md)

## Inhalt

| Dokument | Inhalt |
|---|---|
| [Was wann gilt](./knowledge-base/eu-ai-act/overview.md) | Fristen, und was welche Prüfung heute schon braucht |
| [Begriffe](./knowledge-base/eu-ai-act/definitions.md) | die Begriffe, an denen Prüfpunkte hängen |
| [Rolle bestimmen](./knowledge-base/eu-ai-act/scope-and-actors.md) | Anbieter oder Betreiber, und Art. 25 |
| [Klasse bestimmen](./knowledge-base/eu-ai-act/risk-logic.md) | Art. 5, Anhang I/III, Art. 6 Abs. 3, Art. 50 |
| [Die Abfolge](./knowledge-base/eu-ai-act/checklist-sequence.md) | acht Schritte, und was jeder voraussetzt |
| [Mindeststandard](./knowledge-base/eu-ai-act/minimum-review-standard.md) | wann ein Punkt als geprüft gilt |
| [Nachweise und Freigabezustände](./knowledge-base/eu-ai-act/evidence-register-and-approval-states.md) | die vier Zustände, und wer welchen setzen darf |
| [Was das Inventar liefern muss](./knowledge-base/eu-ai-act/inventory-and-governance.md) | die Voraussetzungen einer Prüfung |

### Vorlagen

| Vorlage | Wann |
|---|---|
| [Freigabeprüfung](./templates/pre-launch-review-checklist.md) | vor Inbetriebnahme, einmal je Einsatzzweck |
| [Turnusprüfung](./templates/periodic-review-checklist.md) | wiederkehrend, verkürzt |

Maschinenlesbar: [framework/simpleact-framework.json](./framework/simpleact-framework.json) · [llms.txt](./llms.txt)

## Davor und danach

- vorher: [KI-Inventar](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory) — ohne Inventar prüft man Stichproben
- vorher: [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu) — die Klasse bestimmt die Punkte
- danach: [Dokumentationsvorlage](https://github.com/SimpleAct-Compliance/simpleact-ai-act-documentation-template) — Anhang IV im Einzelnen
- danach: [Audit-Vorbereitung](https://github.com/SimpleAct-Compliance/simpleact-ai-audit-readiness) — wenn eine Prüfung ansteht

## In Software umsetzen

[SimpleAct](https://simpleact.de) führt risikobezogene Prüflisten mit Nachweisregister, Freigabezuständen und Prüfprotokoll: **[AI Act Software](https://simpleact.de/ai-act-software)**

## Stand und Lizenz

Zuletzt aktualisiert: 2026-10-03 · MIT — frei nutzbar, auch kommerziell. Keine Rechtsberatung.
