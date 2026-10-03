# ZE2 / CE2 – Kontaktmatrix
**Zielgrundträger:** 357 937 039  
**Dokumentstand:** 03.10.2026  
**Freigabe:** Unvollständige Rekonstruktion; nicht als Verdrahtungs- oder Brückenplan verwenden.

## 1. Geltungsbereich

Erfasst werden sollen ausschließlich feste Verbindungen im Grundträger:
- rückseitige Anschlusskontakte,
- physische Relaissockelkontakte,
- beide Kontakte jedes Sicherungshalters,
- Einzelanschlüsse und Einspeisungen.

Untersuchungszustand: ohne Kabelbaum, Relais, Sicherungen und herausnehmbare Brücken.
Teilenummernindex, Hersteller und mögliche interne Varianten sind nicht verifiziert.
T4-Quellen werden nicht automatisch auf den Zielgrundträger übertragen.

## 2. Bedeutung der Matrixwerte

| Wert | Bedeutung |
|---|---|
| 1 | Direkte feste Verbindung für den konkreten Grundträger nachgewiesen |
| 0 | Keine direkte feste Verbindung für den konkreten Grundträger nachgewiesen |
| Q1 / Q2 | Explizite interne Kontaktreferenz einer Quelle; Zielteil noch nicht verifiziert |
| ? | Unbekannt; weder Verbindung noch Trennung nachgewiesen |
| — | Selbstbezug; keine Aussage zum Vorhandensein eines Kontakts |

Aktuell werden keine Paarbeziehungen mit 1 oder 0 freigegeben.
Insbesondere darf ein Fragezeichen nicht als offener Stromkreis interpretiert werden.

## 3. Teilmatrix der ausdrücklich referenzierten Kontaktpaare

Diese Teilmatrix umfasst nur die vier benannten Endpunkte der zwei internen Quellenreferenzen.
Sie ist kein vollständiges Kontaktinventar.

| Kontakt | E/02 | U2/01 | F/02 | G1/01 |
|---|---|---|---|---|
| E/02 | — | Q1 | ? | ? |
| U2/01 | Q1 | — | ? | ? |
| F/02 | ? | ? | — | Q2 |
| G1/01 | ? | ? | Q2 | — |

Die symmetrische Darstellung beschreibt die behauptete elektrische Beziehung.
Sie bedeutet nicht, dass bei Q1 beide Tabellenrichtungen gelesen wurden.

### Belegregister

| ID | Kontaktpaar | Quellenangabe | Prüfgrenze |
|---|---|---|---|
| Q1 | E/02 ↔ U2/01 | A2Resource, E/02, Inside Fusebox: „U2/1“ | Gegenzeile U2/01 nicht geprüft; Grundträger nicht gemessen |
| Q2 | F/02 ↔ G1/01 | Bisheriger Recherchestand: F/02 → „G1/1“ und G1/01 → „F/2“ | Im letzten verkürzten Abruf nicht erneut sichtbar; keine physische Verifizierung |

Quelle: https://www.a2resource.com/electrical/CE2.html

## 4. Externe Verbindungen – NICHT Teil der internen Matrix

| ID | Endpunkt A | Endpunkt B | Einordnung |
|---|---|---|---|
| X01 | -30 | -30B | Außenverbindung laut A2Resource |
| X02 | B/01 | B/02 | Außenverbindung laut A2Resource |
| X03 | B/03 | D/04 | Alternativ direkte Leitung zum Lichtschalter |
| X04 | B/04 | C/03 | Alternativ direkter Masseanschluss |
| X05 | B/05 | Y/02 | Außenverbindung zur Batterieversorgung |
| X06 | E/02 | D/11 | Ausführungsabhängige Instrumentenversorgung |
| X07 | E/02 | D/08 | Alternative Instrumentenversorgung; D/08 nennt A3 |

X06 und X07 nicht ohne Variantenbeleg gleichzeitig einsetzen.
Daraus insbesondere keine interne Verbindung D/08 ↔ D/11 erzeugen.
Die sieben Zeilen sind keine sieben gleichzeitig vorhandenen Brücken.

## 5. Kraftstoffpumpenrelais / Steckplatz 12

| Anschluss oder Bezeichnung | Belegte Aussage | Physische Sockelkammer am Zielgrundträger |
|---|---|---|
| -30B | A2Resource: Fuel Pump Relay Input | ? |
| -Z1 | A2Resource: Fuel Pump/Glow Plug Relay Output | ? |
| G1/03 | Bisheriger Recherchestand: u. a. ECU-Ansteuerung, Benzin | ? |
| J17 | T4-Wiki: Relais auf Steckplatz 12 rechts unten | Keine Kammerzuordnung |
| Kontakt 2 | Im bisherigen T4-Prüfbericht erwähnt | Blickrichtung und Gegenkontakt fehlen |
| Kontakt 4 | Im bisherigen T4-Prüfbericht erwähnt | Blickrichtung und Gegenkontakt fehlen |
| Kontakt 6 | Im bisherigen T4-Prüfbericht erwähnt | Blickrichtung und Gegenkontakt fehlen |
| „pin 3“ | Separate VWVortex-Nummerierungsangabe | Nicht mit obigen Nummern abgeglichen |

**Nicht freigegeben:**
- eine Kammerzuordnung für -30B, -Z1 oder G1/03;
- eine feste Verbindung zwischen diesen drei Anschlüssen;
- eine interne Verbindung -30 ↔ -30B;
- die Gleichsetzung von DIN-Klemme, Sockelkammer und Steckplatznummer.

Das J17/G23-Schaltbild wurde lokalisiert, aber nicht visuell ausgewertet.
Ein gemeldeter abgeschnittener Base64-Abruf liefert keinen zusätzlichen Beleg.

## 6. Relaisplatzregister – ausschließlich T4-Quellenkontext

Diese Tabelle erfasst Bestückungsfunktionen, keine internen Leiterkanten.

| Platz | T4-Wiki: ausstattungsabhängige Bestückung |
|---|---|
| 1 | Frischluftgebläse / Klimaanlage / Climatronic |
| 2 | Heckscheibenwischer |
| 3 | Spannungsversorgung Digifant / Klemme 30 / Simos |
| 4 | X-Kontakt-Entlastungsrelais |
| 5 | CAN-Bus-Verteiler in entsprechender Ausführung |
| 6 | Blinker |
| 7 | Scheinwerferreinigung |
| 8 | Scheibenwischer |
| 9 | Lichtwarnsummer |
| 10 | Nebelscheinwerfer |
| 11 | Doppeltonhorn |
| 12 | Kraftstoffpumpe / Glühkerzen |

Die Quelle nummeriert die Plätze von oben links nach unten rechts.
Daraus folgt keine Nummerierung der einzelnen Sockelkammern.

Quelle: https://www.t4-wiki.de/wiki/Relaisplatte

## 7. Sicherungskontakte

| Erfassungsumfang | Stand |
|---|---|
| Vorgesehenes Register S01 bis S22 | Noch nicht vollständig physisch inventarisiert |
| Jeweils zwei getrennte Halterkontakte | Erforderlich |
| Zuordnung Eingangs-/Ausgangsseite | Offen |
| Interne Gegenkontakte | Offen |
| Verbindung durch eingesetzte Sicherung | Separates Bauteil, keine feste Leiterkante |

Eine Angabe wie „Headlight, Left, Fuse 1“ identifiziert allein keine physische Halterseite.
S01–S22 ist hier eine Arbeitsnotation, kein zusätzlicher Hardwarebeleg.

## 8. Inventar- und Variantenkorrekturen

- Die früher genannten 65 Positionen waren vollständig erfasste Tabellenzeilen,
  keine physische Vollzählung der ZE.
- F/10 wurde im bisherigen Recherchestand als „no pin“ erfasst.
- Ein „-“ in einer Funktionsspalte beweist keine fehlende Kontaktbestückung.
- Die frühere Erfassung reichte bis G1/04; der jüngste Abruf brach bereits in E/05 ab.
- U2/01 und Y/02 sind bislang Gegenreferenzen ohne vollständig geprüfte eigene Zeile.
- Eine behauptete interne Brückenänderung bleibt als Variantenhinweis erhalten.
  Teilenummer, Index und konkrete Endpunkte fehlen.
- Gleich benannte Funktionen werden nicht automatisch zu internen Netzen vereinigt.
- Wiederholte Abrufe derselben Seite zählen nicht als unabhängige Bestätigung.

## 9. Voraussetzungen für die vollständige Freigabe

| Erforderlicher Nachweis | Status |
|---|---|
| Identifikation des konkreten Grundträgers einschließlich Index | Offen |
| Vollständiges Kontaktinventar mit eindeutiger Blickrichtung | Offen |
| Alle Relaissockelkammern eindeutig nummeriert | Offen |
| Beide Seiten sämtlicher Sicherungshalter zugeordnet | Offen |
| Alle festen Netze durch passende Pläne oder Messung belegt | Offen |
| Bauteilpfade und äußere Brücken getrennt | Methodisch festgelegt |
| Varianten voneinander getrennt | Begonnen, nicht abgeschlossen |
| Vollständige Matrix elektrisch geprüft | Nein |

## 10. Ergebnis

- Zwei interne Quellenreferenzen dokumentiert.
- Sieben externe Verbindungsdatensätze getrennt geführt.
- Kein vollständiges internes Netz für das konkrete Zielteil freigegeben.
- Keine physische Relaissockelverbindung für das konkrete Zielteil freigegeben.
- Keine vollständige Sicherungskontaktmatrix vorhanden.

**Dokumentstatus: konsolidierter Arbeitsstand, keine abgeschlossene Kontaktrekonstruktion.**