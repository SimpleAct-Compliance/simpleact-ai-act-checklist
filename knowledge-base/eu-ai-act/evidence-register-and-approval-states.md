# Nachweise und Freigabezustände

Ein Nachweis ist nicht entweder vorhanden oder nicht vorhanden. Er hat einen Zustand, und die Unterscheidung dieser Zustände ist der Unterschied zwischen einem Nachweisregister und einem Dateiordner.

## Die vier Zustände

| Zustand | Bedeutung | Wer setzt ihn | Trägt in einer Prüfung |
|---|---|---|---|
| **offen** | noch nicht erbracht; Person und Termin eingetragen | Prüfender | als Befund, ja |
| **erbracht** | liegt vor, niemand hat nachgesehen | Umsetzender | nein |
| **geprüft** | eine zweite Person hat inhaltlich nachgesehen | Prüfer | meist |
| **freigegeben** | mit Versionsbezug und Datum bestätigt | Freigebender | ja |

### Der Sprung, der fehlt

Von **erbracht** zu **geprüft**. In vielen Registern gibt es diesen Zustand nicht: Ein Nachweis wird hochgeladen und gilt damit als erledigt. Dann steht im Register ein Dokument, das niemand gelesen hat — und in der Prüfung wird genau dieses eine gelesen.

Was beim Übergang tatsächlich geprüft wird:

- Bezieht sich der Nachweis auf die **Version**, die läuft?
- Belegt er, was er belegen soll — oder etwas Ähnliches?
- Ist er vollständig, oder fehlt die zweite Seite?
- Ist er **auffindbar**, auch für jemanden, der nicht dabei war?

## Warum „offen" ein Zustand und kein Mangel ist

Ein ausdrücklich offener Punkt mit Person und Termin ist ein **Nachweis der Governance**: Er zeigt, dass die Lücke bekannt ist und bearbeitet wird. Ein leeres Feld zeigt dieselbe Lücke ohne den Beleg, dass jemand sie gemerkt hat.

Deshalb ist ein Register mit zwölf freigegebenen und acht offenen Nachweisen in einer Prüfung besser als eines mit zwanzig unklaren.

## Was ein Nachweis mindestens trägt

| Bestandteil | Ohne es |
|---|---|
| **Produktversion oder Systemstand** | belegt er einen Zeitpunkt, nicht einen Zustand |
| Datum | ist nicht feststellbar, was wann galt |
| Fundort | ist er nicht vorlegbar |
| Urheber | gibt es keinen Ansprechpartner für Rückfragen |
| Bezug zur Pflicht | weiß niemand, wofür er liegt |

Die letzte Zeile wird unterschätzt. Ein Ordner mit vierzig Dateien, von denen niemand sagen kann, welche Pflicht welche belegt, ist in einer Prüfung ein Ordner mit vierzig Dateien.

## Welche Nachweisarten taugen

| Art | Taugt für | Fallstrick |
|---|---|---|
| Bildschirmaufnahme | Kennzeichnung, Benutzerführung | ohne Produktversion wertlos |
| Protokollauszug | Aufsicht, Nutzung, Änderungen | Zeitraum und Filter mit angeben |
| Vertrag, AVV | Auftragsverarbeitung, Zusagen | Unterauftragsverarbeiter mitprüfen |
| Teilnahmeliste | Art. 4 Schulung | Datum und **Inhalt**, nicht nur Namen |
| Freigabeprotokoll | Governance | muss eine zweite Person nennen |
| Testsatzergebnis | stiller Modellwechsel | Reihe ist der Nachweis, nicht ein Lauf |
| Kennzahl | ob Aufsicht ausgeübt wird | Erhebungsweg mit angeben |

Zur letzten Zeile: Die Zahl der im letzten Monat geänderten Ausgaben ist der einzige brauchbare Nachweis dafür, dass menschliche Aufsicht nach Art. 14 tatsächlich stattfindet. Alles andere belegt nur, dass sie zugewiesen ist.

## Reihen statt Einzelstücke

Für drei Pflichten ist ein einzelner Nachweis strukturell ungeeignet, weil die Pflicht ein **Fortlaufen** verlangt:

- **Beobachtung nach dem Inverkehrbringen** (Art. 72): die Reihe der Berichte ist der Nachweis
- **Auslöserprüfung**: das Protokoll, einschließlich der Zeilen ohne Ergebnis
- **Testsätze**: die Folge der Durchläufe mit Abweichungen

Ein einzelner aktueller Bericht belegt hier nichts. Er kann auch am Vortag der Prüfung entstanden sein.

## Wer welchen Zustand setzen darf

| Übergang | Durch | Nicht durch |
|---|---|---|
| offen → erbracht | Umsetzender | |
| erbracht → geprüft | **Prüfer** | den Umsetzenden |
| geprüft → freigegeben | Freigebender | den Prüfer allein, bei hohem Risiko |
| zurück auf offen | jeder, mit Begründung | |

Der letzte Übergang muss möglich sein. Ein Register, in dem ein Nachweis nur vorwärts laufen kann, veraltet lautlos: Der Nachweis bleibt freigegeben, während das System, auf das er sich bezieht, drei Versionen weiter ist.

## Wann ein Nachweis ungültig wird

| Ereignis | Folge |
|---|---|
| neue Produktversion | Nachweise mit Versionsbezug prüfen |
| Modellwechsel beim Anbieter | Nachweise zu Genauigkeit und Verhalten neu |
| Einsatzzweck geändert | Prüfung vollständig neu |
| zuständige Person weg | Zuständigkeitsnachweise neu |
| Rechtsänderung | betroffene Nachweise prüfen |

Alte Nachweise werden nicht gelöscht. In einer Prüfung lautet die Frage, was zu einem bestimmten Zeitpunkt belegt war.

## Registertabelle

| Pflicht | Rechtsgrundlage | Nachweis | Version | Zustand | Durch | Datum | Fundort |
|---|---|---|---|---|---|---|---|
| | | | | | | | |

## Weiter

[Mindeststandard](./minimum-review-standard.md) · [Audit-Vorbereitung](https://github.com/SimpleAct-Compliance/simpleact-ai-audit-readiness)
