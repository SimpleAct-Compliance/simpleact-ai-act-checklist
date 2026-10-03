# Klasse bestimmen

Schritte 3 bis 5 der Prüfung. Hier steht, was in der Prüfliste als Punkt erscheint — nicht die vollständige Einstufungslehre, die liegt in der [Risikoeinstufung](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu).

## Schritt 3: Art. 5 — die acht verbotenen Praktiken

Anwendbar seit **2.2.2025**. Alle acht durchgehen, Ergebnis je Praktik festhalten.

| # | Praktik | Wo sie in Unternehmen auftaucht |
|---|---|---|
| 1 | unterschwellige oder manipulative Techniken, die zu Schaden führen | Verkaufsoberflächen, Gestaltungsmuster |
| 2 | Ausnutzung von Schwäche wegen Alter, Behinderung, sozialer Lage | Zielgruppenansprache |
| 3 | Sozialbewertung von Personen | Bewertungssysteme über mehrere Zwecke hinweg |
| 4 | Vorhersage von Straftaten allein anhand von Profilen | Sicherheitsanwendungen |
| 5 | **ungezieltes Auslesen von Gesichtsbildern** aus dem Netz oder aus Überwachungsaufnahmen | Werkzeuge zur Personensuche |
| 6 | **Emotionserkennung am Arbeitsplatz und in Bildungseinrichtungen** | Gesprächsanalyse, Bewerbungsgespräche, Lernsoftware |
| 7 | biometrische Kategorisierung zur Ableitung sensibler Merkmale | Analysefunktionen |
| 8 | biometrische Echtzeit-Fernidentifizierung im öffentlichen Raum zu Strafverfolgungszwecken | Behörden, mit engen Ausnahmen |

**Die zwei, die in gekaufter Software vorkommen, sind 5 und 6.** Sie klingen weniger exotisch als die anderen und werden übersehen: Eine Funktion, die Kundengespräche oder Bewerbungsgespräche nach Stimmung auswertet, ist Emotionserkennung — und am Arbeitsplatz verboten, nicht reguliert.

**Prüfpunkt:** nicht „wir machen nichts Verbotenes", sondern je Praktik ein festgehaltenes Ergebnis. Ein Treffer beendet die Prüfung: Die Schritte 4 bis 8 sind gegenstandslos, weil das System nicht betrieben werden darf.

## Schritt 4: Hochrisiko

### Anhang I

Systeme, die Sicherheitsbauteil eines Produkts sind, für das bereits eine Konformitätsbewertung nach anderen Unionsvorschriften verlangt wird — Maschinen, Medizinprodukte, Fahrzeuge, Aufzüge und weitere.

**Prüffrage:** Ist unser System Teil eines Produkts mit CE-Konformitätsbewertung? Bei Ja läuft die KI-Prüfung in dem bestehenden Verfahren mit, und Anwendbarkeit ab **2.8.2028**.

### Anhang III

Acht Bereiche. Anwendbar ab **2.12.2027**.

| # | Bereich | Typische betriebliche Berührung |
|---|---|---|
| 1 | Biometrie | Zugangskontrolle, Identifizierung |
| 2 | kritische Infrastruktur | Steuerung, Netzbetrieb |
| 3 | Bildung | Zulassung, Bewertung, Prüfungsaufsicht |
| 4 | **Beschäftigung** | Bewerberauswahl, Leistungsbewertung, Kündigung, Aufgabenzuweisung |
| 5 | **wesentliche Dienstleistungen** | Kreditwürdigkeit, Versicherungstarifierung, Sozialleistungen |
| 6 | Strafverfolgung | |
| 7 | Migration, Asyl, Grenzkontrolle | |
| 8 | Justiz und demokratische Prozesse | |

Bereiche 4 und 5 sind die, die gewöhnliche Unternehmen treffen. Bereich 4 ist der häufigste und der unauffälligste, weil Personalwerkzeuge selten als KI-Projekt beschafft werden.

### Die Ausnahme nach Art. 6 Abs. 3

Ein System in einem Anhang-III-Bereich ist **nicht** hochriskant, wenn es nur

- eine eng begrenzte Verfahrensaufgabe erfüllt,
- ein zuvor erbrachtes menschliches Ergebnis verbessert,
- Entscheidungsmuster oder Abweichungen davon erkennt, ohne die menschliche Bewertung zu ersetzen, oder
- eine vorbereitende Tätigkeit ausführt.

**Zwei Prüfpunkte, die beide gebraucht werden:**

1. **Ist die Bewertung dokumentiert?** Die Verordnung verlangt sie, nicht eine Selbsteinschätzung. Ein Haken bei „Ausnahme greift" ohne Bewertung ist kein erfüllter Punkt.
2. **Wird profiliert?** Wird Profiling natürlicher Personen vorgenommen, greift die Ausnahme **nicht** — unabhängig von allen vier Spiegelstrichen. Eigener Prüfpunkt, eigene Zeile.

**Die inhaltlich schwierige Frage** steckt im dritten Spiegelstrich: „ohne die menschliche Bewertung zu ersetzen". Wenn ein Vorschlag in 98 von 100 Fällen übernommen wird, ersetzt er sie praktisch. Deshalb gehört die Übernahmequote in die Prüfung.

## Schritt 5: Art. 50 — Transparenz

Anwendbar seit **2.8.2026**. Läuft **unabhängig** vom Ergebnis aus Schritt 4.

| Fall | Pflicht | Prüfpunkt |
|---|---|---|
| direkter Kontakt mit Menschen | Hinweis, dass es KI ist | im laufenden System sichtbar, **vor** der ersten Eingabe |
| erzeugte oder bearbeitete Inhalte | maschinenlesbare Kennzeichnung | technisch umgesetzt, nicht nur in der Richtlinie |
| Emotionserkennung, biometrische Kategorisierung | Information der betroffenen Personen | tatsächlich zugegangen |
| Deepfake | Offenlegung | |

**Nachweis je Punkt:** Bildschirmaufnahme mit **Datum und Produktversion**. Ohne Version belegt sie, dass es einmal so aussah.

## Quer dazu: GPAI

Pflichten für Modelle mit allgemeinem Verwendungszweck liegen beim **Modellanbieter**, anwendbar seit 2.8.2025. Wer ein Modell über eine Schnittstelle nutzt, wird davon nicht zum GPAI-Anbieter.

**Prüfpunkt für Betreiber:** Erfüllt der Anbieter diese Pflichten, und liegen uns die Unterlagen vor, auf die unsere eigene Dokumentation aufbaut? Ein Nein ist ein Befund gegen den Anbieter und gehört in die Beschaffung.

## Und ohne Klasse: Art. 4

KI-Kompetenz, anwendbar seit **2.2.2025**, unabhängig von der Risikoklasse. Der Prüfpunkt ist systembezogen: Wer bedient dieses System, und versteht diese Person, wie es irrt? Eine allgemeine KI-Schulung erfüllt ihn nicht.

## Was das Ergebnis festhalten muss

| Feld | Mindestinhalt |
|---|---|
| Klasse | verboten / Hochrisiko / Transparenzpflicht / minimal |
| Rechtsgrundlage | Artikel oder Anhang samt Nummer |
| Art. 5: alle acht geprüft | ja, mit Datum |
| Art. 6 Abs. 3 | Bewertung, nicht Haken |
| Profiling | ja / nein |
| Art. 50 | je Fall geprüft, auch bei minimaler Klasse |
| Annahmen | was unterstellt wurde |

## Weiter

[Die Abfolge](./checklist-sequence.md) · [Mindeststandard](./minimum-review-standard.md) · [Freigabeprüfung](../../templates/pre-launch-review-checklist.md)
