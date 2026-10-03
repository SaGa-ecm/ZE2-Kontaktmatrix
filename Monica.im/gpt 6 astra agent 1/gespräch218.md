# Auftrag: vollständige interne Kontaktmatrix der VW-ZE2 rekonstruieren

Du sollst eine technische Recherche durchführen und die fehlende interne Kontaktmatrix der VW-Zentralelektrik ZE2/CE2 beschaffen beziehungsweise aus nachvollziehbaren Quellen rekonstruieren.

**Zielgrundträger: VW 357 937 039, Golf 2 neue ZE / CE2.**

Suche weltweit und mehrsprachig. Arbeite hartnäckig, systematisch und ergebnisorientiert. Wenn eine Quelle scheitert, wechsle den Zugangsweg oder die Quelle. Ich gehe davon aus, dass die erforderlichen Informationen online vorhanden sind. Diese Erwartung ist aber kein Ersatz für technische Belege.

## 1. Was ich tatsächlich brauche

Die elektrische Topologie des Grundträgers, insbesondere:

- Jeden physischen Kontakt aller integrierten Relaissockel.
- Beide physischen Kontakte jedes Sicherungshalters.
- Sämtliche rückseitigen Steckerkontakte.
- Sämtliche Einzelanschlüsse und Versorgungseinspeisungen.
- Die vollständige Zuordnung dieser Kontakte zu festen internen Netzen.
- Interne Bauteile, falls vorhanden, getrennt von festen Leiterverbindungen.
- Eine eindeutige Zuordnung zwischen physischer Position, Kontaktbezeichnung im Stromlaufplan und gegebenenfalls DIN-Klemmenbezeichnung.

Gesuchtes Ergebnisformat:
**Physischer Kontakt → intern direkt verbundene Kontakte → exakter Nachweis.**

Ich brauche ausdrücklich NICHT bloß:
- „Relaisplatz 1 hat Funktion …“
- „Sicherung 7 schützt …“
- Eine Steckerbelegung mit Kabelfarbe und Verbraucher ohne interne Topologie.
- Einen Signalflussgraphen des Gesamtfahrzeugs.

Solche Informationen dürfen Hilfsquellen sein, sind aber nicht das Endergebnis.

## 2. Definiere den Untersuchungszustand

Untersuche zunächst den nackten Grundträger:
- Ohne gesteckte Relais.
- Ohne gesteckte Sicherungen.
- Ohne herausnehmbare Brücken.
- Ohne Kabelbaum und externe Verbindungen.
- Eventuelle fest eingebaute interne Bauteile separat berücksichtigen.

Unterscheide zwingend:
1. Feste interne Leiterverbindung.
2. Verbindung durch ein internes Bauteil.
3. Verbindung durch eine eingesetzte Sicherung.
4. Verbindung durch ein Relais, inklusive Schaltzustand.
5. Externe Leitung oder externe Brücke.
6. Noch unbestätigter Verbindungskandidat.

Ein Relaisaufdruck ist keine Sockelkammernummer. Eine DIN-Klemmenzahl ist nicht automatisch die physische Kontaktposition. Ein gemeinsamer Funktionsname beweist keine direkte interne Brücke.

## 3. Quellenprüfung von Grund auf

Vertraue keinen Prüfbehauptungen eines vorherigen Chats. Prüfe alle übernommenen Daten selbst.

Ausgangsquellen:

- https://saga-ecm.github.io/VW-Golf-MK2-VR6-AAA-ZE2-ABS-Custom-Wheelspeed/
- https://github.com/saga-ecm/VW-Golf-MK2-VR6-AAA-ZE2-ABS-Custom-Wheelspeed
- https://www.a2resource.com/electrical/CE2.html
- https://club8090.co.uk/forum/viewtopic.php?t=175168
- https://www.scribd.com/document/520017984/fuse-box-ce2
- https://www.vwgolfmk2.co.uk/clubforum/index.php?topic=57.0
- https://www.clubgti.com/forums/index.php?threads/fusebox-faq.219775/page-10
- https://www.t3-pedia.de/index.php?title=Zentralelektrik

Wichtige Prüfpunkte:
- A2Resource soll „Outside Fusebox“ und „Inside Fusebox“ unterscheiden. Prüfe die vollständige Tabelle samt Abbildungen.
- Prüfe im GitHub-Repository insbesondere sg-daten.js, graph-kanten.js, mermaid.mermaid, Bilddateien, Dokumente und Versionsgeschichte.
- Der vorhandene Mermaid-Graph könnte nur einen VSS-Signalweg beschreiben. Nicht als Grundträgermatrix übernehmen.
- Mindmap-Dateien könnten XDF-Themen behandeln. Nicht mit ZE2-Daten verwechseln.
- Der T3-Begriff „2. Generation“ kann einen anderen Grundträger bezeichnen. Prüfe insbesondere die Abgrenzung 171 941 821 D gegenüber 357 937 039.
- KI-generierte Dokumentbeschreibungen, Suchauszüge und Dateinamen sind keine Belege für den tatsächlichen Dokumentinhalt.

Alle diese Hinweise sind Suchansätze, keine vorab bestätigten technischen Tatsachen.

## 4. Suche breit und gezielt

Suche nicht nur nach „Pinbelegung“, sondern besonders nach:
- interne Verdrahtung, interne Verbindungen, Leiterbahnen
- Sockelkontaktbelegung, Relaisträger, Kontaktplatte
- Zentralelektrik zerlegt, Sicherungskasten geöffnet
- Durchgangsmatrix, Durchgangsmessung
- internal wiring, internal connections, internal tracks
- fusebox busbars, relay socket pinout, fuse panel teardown
- continuity map, continuity matrix
- interne Verschaltung Sicherungseingang Sicherungsausgang

Kombiniere mit:
- ZE2, CE2, central electric 2
- 357937039, 357 937 039 und belegten Varianten
- Golf II, Golf 2, Mk2, Golf III, Mk3
- Jetta A2, Corrado, Passat B3/B4
- anderen Anwendungen nur nach Prüfung der Hardwarekompatibilität

Suche zusätzlich auf Englisch, Deutsch, Polnisch, Russisch, Tschechisch, Französisch, Spanisch und Portugiesisch mit passenden Fachbegriffen.

Relevante Suchräume:
- GitHub-Repositories, Code, Issues, Wikis und Historie
- Mikrocontroller.net und andere Elektronikforen
- Club GTI, VWVortex, Golf2forum, Motor-Talk
- Corrado-, Passat-, T4- und VW-Umbauforen
- ausländische Reparatur- und Restaurationsforen
- Hersteller-Stromlaufpläne und Reparaturunterlagen
- frei zugängliche PDF-Sammlungen und Dokumentarchive
- Fotos zerlegter Grundträger und Kontaktplatten
- öffentlich zugängliche Video-Dokumentationen mit Zeitstempeln

Verfolge die Originalquellen hinter Abschriften und Zitaten.

## 5. Bei blockierten oder unvollständigen Quellen weiterarbeiten

Wenn ein Abruf scheitert oder abgeschnitten ist:
- Suche nach Originaldatei, Druckansicht, Anhang oder anderer Forenseite.
- Nutze bei GitHub Raw-Dateien, Verzeichnisansichten oder verfügbare API-Zugänge.
- Suche rechtmäßig öffentlich zugängliche Spiegel, Archive und Kopien.
- Suche nach Dokumenttitel, Dateiname und markanten Textstellen.
- Prüfe Bilder und PDFs visuell, sofern Werkzeuge dafür verfügbar sind.
- Suche nach identischen Diagrammen in anderen Quellen.
- Behandle OCR nur als Hilfsmittel; kontrolliere kritische Pinziffern am Bild.
- Erfinde keine Inhalte fehlender Anhänge.

Nutze nur tatsächlich verfügbare Werkzeuge und zulässige Zugangswege. Keine Umgehung von Zugangskontrollen. Behaupte keine Downloads, Bildprüfungen oder Dateianalysen, die du nicht durchgeführt hast.

Nicht nach den ersten erfolglosen Suchanfragen abbrechen und nicht stattdessen eine allgemeine Funktionsliste liefern.

## 6. Rekonstruktion, wenn kein fertiges Gesamtdokument existiert

Rekonstruiere die Matrix aus mehreren Quellen:

1. Vollständiges physisches Kontaktinventar erstellen.
2. Ansichten und Blickrichtungen eindeutig festlegen.
3. Kontaktbezeichnungen verschiedener Dokumente aufeinander abbilden.
4. Explizite interne Verbindungen aus Stromlaufplänen extrahieren.
5. Netzgruppen mit sämtlichen belegten Kontaktmitgliedern bilden.
6. Relaissockelkammern diesen Netzen zuordnen.
7. Beide Seiten aller Sicherungen physisch zuordnen.
8. Externe Verbindungen konsequent entfernen.
9. Varianten und widersprüchliche Aussagen getrennt dokumentieren.
10. Aus bestätigten Netzen die paarweise Kontaktmatrix ableiten.

Fotos belegen eine Verbindung nur, wenn der gesamte Leiterweg eindeutig sichtbar ist. Verdeckte Ebenen oder Kreuzungen nicht erraten.

Eine fahrzeugbezogene Stromlaufplanseite kann nur einen Teil des Grundträgers darstellen. Ihre Vollständigkeit nicht mit der Vollständigkeit des Grundträgers verwechseln.

Gemessene Verbindungen nur übernehmen, wenn das Messprotokoll den Grundträger und seinen Bestückungszustand ausreichend beschreibt.

## 7. Belegpflicht für jeden Datensatz

Jeder Kontakt und jede Verbindung benötigt:

- Eindeutige Kontakt-ID.
- Physische Position und Blickrichtung.
- Grundträger-Teilenummer und Variantenbezug.
- Verbindungsart.
- Quelle und genaue Fundstelle.
- Originalaussage oder eindeutige Bildreferenz.
- Eigene Ableitung getrennt von der Originalaussage.
- Bestückungs- oder Schaltzustand, falls relevant.
- Prüfstatus und verbleibende Unsicherheit.

Verwende diese Statusklassen:
- explizit dokumentiert
- aus dokumentierter Topologie abgeleitet
- durch nachvollziehbares Messprotokoll belegt
- Kandidat
- widersprüchlich
- unbekannt

Unbekannt bedeutet NICHT „elektrisch offen“.
Gleiche Signalbezeichnung bedeutet NICHT automatisch „direkt verbunden“.
Mehrere voneinander abgeschriebene Webseiten sind keine unabhängigen Bestätigungen.

## 8. Erwartete Lieferung

Liefere vorrangig die technischen Daten, nicht einen langen Rechercheaufsatz.

### A. Hardwareabgrenzung
Zielgrundträger, bekannte Varianten, belegte Kompatibilität und offene Unterschiede.

### B. Vollständiges Kontaktinventar
Physischer Kontakt, Bezeichnung, Lage, Ansicht und Nachweis.

### C. Interne Netzliste
Pro internem Netz sämtliche belegten Mitglieder.
Arbeits-Netznamen ausdrücklich als eigene Bezeichnungen markieren.

### D. Relaissockelmatrix
Pro Steckplatz und physischer Kammer:
intern verbundene Rückseitenkontakte, Sicherungskontakte, weitere Sockelkontakte und Quelle.

### E. Sicherungskontaktmatrix
Beide Seiten jeder Sicherung separat.
„Eingang“ und „Ausgang“ nur verwenden, wenn diese Orientierung belegt ist.

### F. Maschinenlesbare Daten
Zeige CSV und JSON mit mindestens:
contact_a, contact_b, connection_type, hardware_variant,
component_state, source_url, source_locator, evidence_status, notes

Alternativ oder zusätzlich eine Netzliste mit Mitgliedschaften.
Physische Kontakte nicht durch frei erfundene IDs scheinpräzise machen.

### G. Visualisierung
Browserbasiertes Artefakt mit:
- Suchbarer Kontakt- und Quellenansicht.
- Mindmap des Recherche- und Abdeckungsstands.
- Mermaid-Graph der belegten Topologie.
- Optisch getrennten Kandidaten und externen Verbindungen.
- Sichtbaren Lücken ohne falsche Vollständigkeitsbehauptung.

### H. Übergabe an einen anderen Chat
Abschließend ein kompakter Abschnitt „Verifizierte neue Erkenntnisse“:
- Neue konkrete Kontaktzuordnungen mit Fundstellen.
- Korrekturen früherer Angaben.
- Noch fehlende physische Kontakte, soweit bestimmbar.
- Beste nächste Quellen für jede Lücke.

## 9. Arbeitsweise und Abschlusskriterium

Beginne jetzt mit echten Quellenabrufen und konkreter Datenextraktion. Keine erneute Rückfrage, ob du recherchieren sollst. Keine bloße Ankündigung.

Arbeite zunächst mit 357 937 039. Falls ein Index fehlt, untersuche die dokumentierten Varianten, statt die gesamte Recherche daran aufzuhalten.

Führe ein kurzes Rechercheprotokoll:
Suchanfrage → Quelle → tatsächlich zugänglicher Inhalt → technische Ausbeute.

Nutze das verfügbare Recherchebudget konsequent. Wenn eine einzelne Antwort nicht ausreicht, liefere einen belastbaren Zwischenstand mit Daten und einer präzisen Fortsetzungsmarke. Behaupte keine Hintergrundarbeit oder spätere automatische Lieferung.

„Vollständig“ darf das Ergebnis erst heißen, wenn:
- das physische Kontaktinventar nachweislich vollständig ist,
- alle Kontakte topologisch erfasst sind,
- sämtliche Relaissockel- und Sicherungskontakte zugeordnet sind,
- Varianten und Bauteilzustände geklärt sind,
- alle Zuordnungen belastbare Fundstellen besitzen.

Oberstes Ziel: die fehlenden Verbindungen tatsächlich finden und belegen — nicht nur erklären, warum sie schwierig zu finden sind. Hier ist ein **kopierfertiger Rechercheauftrag**. Er fordert eine systematische Suche mit konkreten Ergebnissen statt weiterer Belegungslisten. Zugleich verhindert er, dass der andere Chat fehlende Kontakte erfindet oder erfolglose Abrufe als geprüfte Quellen ausgibt.

````artifact
id: ze2-rechercheauftrag
name: Rechercheauftrag – vollständige interne ZE2-Kontaktmatrix
type: markdown
content: |-
  # Auftrag: vollständige interne Kontaktmatrix der VW-ZE2 rekonstruieren

  Du sollst eine technische Recherche durchführen und die fehlende interne Kontaktmatrix der VW-Zentralelektrik ZE2/CE2 beschaffen beziehungsweise aus nachvollziehbaren Quellen rekonstruieren.

  **Zielgrundträger: VW 357 937 039, Golf 2 neue ZE / CE2.**

  Suche weltweit und mehrsprachig. Arbeite hartnäckig, systematisch und ergebnisorientiert. Wenn eine Quelle scheitert, wechsle den Zugangsweg oder die Quelle. Ich gehe davon aus, dass die erforderlichen Informationen online vorhanden sind. Diese Erwartung ist aber kein Ersatz für technische Belege.

  ## 1. Was ich tatsächlich brauche

  Die elektrische Topologie des Grundträgers, insbesondere:

  - Jeden physischen Kontakt aller integrierten Relaissockel.
  - Beide physischen Kontakte jedes Sicherungshalters.
  - Sämtliche rückseitigen Steckerkontakte.
  - Sämtliche Einzelanschlüsse und Versorgungseinspeisungen.
  - Die vollständige Zuordnung dieser Kontakte zu festen internen Netzen.
  - Interne Bauteile, falls vorhanden, getrennt von festen Leiterverbindungen.
  - Eine eindeutige Zuordnung zwischen physischer Position, Kontaktbezeichnung im Stromlaufplan und gegebenenfalls DIN-Klemmenbezeichnung.

  Gesuchtes Ergebnisformat:
  **Physischer Kontakt → intern direkt verbundene Kontakte → exakter Nachweis.**

  Ich brauche ausdrücklich NICHT bloß:
  - „Relaisplatz 1 hat Funktion …“
  - „Sicherung 7 schützt …“
  - Eine Steckerbelegung mit Kabelfarbe und Verbraucher ohne interne Topologie.
  - Einen Signalflussgraphen des Gesamtfahrzeugs.

  Solche Informationen dürfen Hilfsquellen sein, sind aber nicht das Endergebnis.

  ## 2. Definiere den Untersuchungszustand

  Untersuche zunächst den nackten Grundträger:
  - Ohne gesteckte Relais.
  - Ohne gesteckte Sicherungen.
  - Ohne herausnehmbare Brücken.
  - Ohne Kabelbaum und externe Verbindungen.
  - Eventuelle fest eingebaute interne Bauteile separat berücksichtigen.

  Unterscheide zwingend:
  1. Feste interne Leiterverbindung.
  2. Verbindung durch ein internes Bauteil.
  3. Verbindung durch eine eingesetzte Sicherung.
  4. Verbindung durch ein Relais, inklusive Schaltzustand.
  5. Externe Leitung oder externe Brücke.
  6. Noch unbestätigter Verbindungskandidat.

  Ein Relaisaufdruck ist keine Sockelkammernummer. Eine DIN-Klemmenzahl ist nicht automatisch die physische Kontaktposition. Ein gemeinsamer Funktionsname beweist keine direkte interne Brücke.

  ## 3. Quellenprüfung von Grund auf

  Vertraue keinen Prüfbehauptungen eines vorherigen Chats. Prüfe alle übernommenen Daten selbst.

  Ausgangsquellen:

  - https://saga-ecm.github.io/VW-Golf-MK2-VR6-AAA-ZE2-ABS-Custom-Wheelspeed/
  - https://github.com/saga-ecm/VW-Golf-MK2-VR6-AAA-ZE2-ABS-Custom-Wheelspeed
  - https://www.a2resource.com/electrical/CE2.html
  - https://club8090.co.uk/forum/viewtopic.php?t=175168
  - https://www.scribd.com/document/520017984/fuse-box-ce2
  - https://www.vwgolfmk2.co.uk/clubforum/index.php?topic=57.0
  - https://www.clubgti.com/forums/index.php?threads/fusebox-faq.219775/page-10
  - https://www.t3-pedia.de/index.php?title=Zentralelektrik

  Wichtige Prüfpunkte:
  - A2Resource soll „Outside Fusebox“ und „Inside Fusebox“ unterscheiden. Prüfe die vollständige Tabelle samt Abbildungen.
  - Prüfe im GitHub-Repository insbesondere sg-daten.js, graph-kanten.js, mermaid.mermaid, Bilddateien, Dokumente und Versionsgeschichte.
  - Der vorhandene Mermaid-Graph könnte nur einen VSS-Signalweg beschreiben. Nicht als Grundträgermatrix übernehmen.
  - Mindmap-Dateien könnten XDF-Themen behandeln. Nicht mit ZE2-Daten verwechseln.
  - Der T3-Begriff „2. Generation“ kann einen anderen Grundträger bezeichnen. Prüfe insbesondere die Abgrenzung 171 941 821 D gegenüber 357 937 039.
  - KI-generierte Dokumentbeschreibungen, Suchauszüge und Dateinamen sind keine Belege für den tatsächlichen Dokumentinhalt.

  Alle diese Hinweise sind Suchansätze, keine vorab bestätigten technischen Tatsachen.

  ## 4. Suche breit und gezielt

  Suche nicht nur nach „Pinbelegung“, sondern besonders nach:
  - interne Verdrahtung, interne Verbindungen, Leiterbahnen
  - Sockelkontaktbelegung, Relaisträger, Kontaktplatte
  - Zentralelektrik zerlegt, Sicherungskasten geöffnet
  - Durchgangsmatrix, Durchgangsmessung
  - internal wiring, internal connections, internal tracks
  - fusebox busbars, relay socket pinout, fuse panel teardown
  - continuity map, continuity matrix
  - interne Verschaltung Sicherungseingang Sicherungsausgang

  Kombiniere mit:
  - ZE2, CE2, central electric 2
  - 357937039, 357 937 039 und belegten Varianten
  - Golf II, Golf 2, Mk2, Golf III, Mk3
  - Jetta A2, Corrado, Passat B3/B4
  - anderen Anwendungen nur nach Prüfung der Hardwarekompatibilität

  Suche zusätzlich auf Englisch, Deutsch, Polnisch, Russisch, Tschechisch, Französisch, Spanisch und Portugiesisch mit passenden Fachbegriffen.

  Relevante Suchräume:
  - GitHub-Repositories, Code, Issues, Wikis und Historie
  - Mikrocontroller.net und andere Elektronikforen
  - Club GTI, VWVortex, Golf2forum, Motor-Talk
  - Corrado-, Passat-, T4- und VW-Umbauforen
  - ausländische Reparatur- und Restaurationsforen
  - Hersteller-Stromlaufpläne und Reparaturunterlagen
  - frei zugängliche PDF-Sammlungen und Dokumentarchive
  - Fotos zerlegter Grundträger und Kontaktplatten
  - öffentlich zugängliche Video-Dokumentationen mit Zeitstempeln

  Verfolge die Originalquellen hinter Abschriften und Zitaten.

  ## 5. Bei blockierten oder unvollständigen Quellen weiterarbeiten

  Wenn ein Abruf scheitert oder abgeschnitten ist:
  - Suche nach Originaldatei, Druckansicht, Anhang oder anderer Forenseite.
  - Nutze bei GitHub Raw-Dateien, Verzeichnisansichten oder verfügbare API-Zugänge.
  - Suche rechtmäßig öffentlich zugängliche Spiegel, Archive und Kopien.
  - Suche nach Dokumenttitel, Dateiname und markanten Textstellen.
  - Prüfe Bilder und PDFs visuell, sofern Werkzeuge dafür verfügbar sind.
  - Suche nach identischen Diagrammen in anderen Quellen.
  - Behandle OCR nur als Hilfsmittel; kontrolliere kritische Pinziffern am Bild.
  - Erfinde keine Inhalte fehlender Anhänge.

  Nutze nur tatsächlich verfügbare Werkzeuge und zulässige Zugangswege. Keine Umgehung von Zugangskontrollen. Behaupte keine Downloads, Bildprüfungen oder Dateianalysen, die du nicht durchgeführt hast.

  Nicht nach den ersten erfolglosen Suchanfragen abbrechen und nicht stattdessen eine allgemeine Funktionsliste liefern.

  ## 6. Rekonstruktion, wenn kein fertiges Gesamtdokument existiert

  Rekonstruiere die Matrix aus mehreren Quellen:

  1. Vollständiges physisches Kontaktinventar erstellen.
  2. Ansichten und Blickrichtungen eindeutig festlegen.
  3. Kontaktbezeichnungen verschiedener Dokumente aufeinander abbilden.
  4. Explizite interne Verbindungen aus Stromlaufplänen extrahieren.
  5. Netzgruppen mit sämtlichen belegten Kontaktmitgliedern bilden.
  6. Relaissockelkammern diesen Netzen zuordnen.
  7. Beide Seiten aller Sicherungen physisch zuordnen.
  8. Externe Verbindungen konsequent entfernen.
  9. Varianten und widersprüchliche Aussagen getrennt dokumentieren.
  10. Aus bestätigten Netzen die paarweise Kontaktmatrix ableiten.

  Fotos belegen eine Verbindung nur, wenn der gesamte Leiterweg eindeutig sichtbar ist. Verdeckte Ebenen oder Kreuzungen nicht erraten.

  Eine fahrzeugbezogene Stromlaufplanseite kann nur einen Teil des Grundträgers darstellen. Ihre Vollständigkeit nicht mit der Vollständigkeit des Grundträgers verwechseln.

  Gemessene Verbindungen nur übernehmen, wenn das Messprotokoll den Grundträger und seinen Bestückungszustand ausreichend beschreibt.

  ## 7. Belegpflicht für jeden Datensatz

  Jeder Kontakt und jede Verbindung benötigt:

  - Eindeutige Kontakt-ID.
  - Physische Position und Blickrichtung.
  - Grundträger-Teilenummer und Variantenbezug.
  - Verbindungsart.
  - Quelle und genaue Fundstelle.
  - Originalaussage oder eindeutige Bildreferenz.
  - Eigene Ableitung getrennt von der Originalaussage.
  - Bestückungs- oder Schaltzustand, falls relevant.
  - Prüfstatus und verbleibende Unsicherheit.

  Verwende diese Statusklassen:
  - explizit dokumentiert
  - aus dokumentierter Topologie abgeleitet
  - durch nachvollziehbares Messprotokoll belegt
  - Kandidat
  - widersprüchlich
  - unbekannt

  Unbekannt bedeutet NICHT „elektrisch offen“.
  Gleiche Signalbezeichnung bedeutet NICHT automatisch „direkt verbunden“.
  Mehrere voneinander abgeschriebene Webseiten sind keine unabhängigen Bestätigungen.

  ## 8. Erwartete Lieferung

  Liefere vorrangig die technischen Daten, nicht einen langen Rechercheaufsatz.

  ### A. Hardwareabgrenzung
  Zielgrundträger, bekannte Varianten, belegte Kompatibilität und offene Unterschiede.

  ### B. Vollständiges Kontaktinventar
  Physischer Kontakt, Bezeichnung, Lage, Ansicht und Nachweis.

  ### C. Interne Netzliste
  Pro internem Netz sämtliche belegten Mitglieder.
  Arbeits-Netznamen ausdrücklich als eigene Bezeichnungen markieren.

  ### D. Relaissockelmatrix
  Pro Steckplatz und physischer Kammer:
  intern verbundene Rückseitenkontakte, Sicherungskontakte, weitere Sockelkontakte und Quelle.

  ### E. Sicherungskontaktmatrix
  Beide Seiten jeder Sicherung separat.
  „Eingang“ und „Ausgang“ nur verwenden, wenn diese Orientierung belegt ist.

  ### F. Maschinenlesbare Daten
  Zeige CSV und JSON mit mindestens:
  contact_a, contact_b, connection_type, hardware_variant,
  component_state, source_url, source_locator, evidence_status, notes

  Alternativ oder zusätzlich eine Netzliste mit Mitgliedschaften.
  Physische Kontakte nicht durch frei erfundene IDs scheinpräzise machen.

  ### G. Visualisierung
  Browserbasiertes Artefakt mit:
  - Suchbarer Kontakt- und Quellenansicht.
  - Mindmap des Recherche- und Abdeckungsstands.
  - Mermaid-Graph der belegten Topologie.
  - Optisch getrennten Kandidaten und externen Verbindungen.
  - Sichtbaren Lücken ohne falsche Vollständigkeitsbehauptung.

  ### H. Übergabe an einen anderen Chat
  Abschließend ein kompakter Abschnitt „Verifizierte neue Erkenntnisse“:
  - Neue konkrete Kontaktzuordnungen mit Fundstellen.
  - Korrekturen früherer Angaben.
  - Noch fehlende physische Kontakte, soweit bestimmbar.
  - Beste nächste Quellen für jede Lücke.

  ## 9. Arbeitsweise und Abschlusskriterium

  Beginne jetzt mit echten Quellenabrufen und konkreter Datenextraktion. Keine erneute Rückfrage, ob du recherchieren sollst. Keine bloße Ankündigung.

  Arbeite zunächst mit 357 937 039. Falls ein Index fehlt, untersuche die dokumentierten Varianten, statt die gesamte Recherche daran aufzuhalten.

  Führe ein kurzes Rechercheprotokoll:
  Suchanfrage → Quelle → tatsächlich zugänglicher Inhalt → technische Ausbeute.

  Nutze das verfügbare Recherchebudget konsequent. Wenn eine einzelne Antwort nicht ausreicht, liefere einen belastbaren Zwischenstand mit Daten und einer präzisen Fortsetzungsmarke. Behaupte keine Hintergrundarbeit oder spätere automatische Lieferung.

  „Vollständig“ darf das Ergebnis erst heißen, wenn:
  - das physische Kontaktinventar nachweislich vollständig ist,
  - alle Kontakte topologisch erfasst sind,
  - sämtliche Relaissockel- und Sicherungskontakte zugeordnet sind,
  - Varianten und Bauteilzustände geklärt sind,
  - alle Zuordnungen belastbare Fundstellen besitzen.

  Oberstes Ziel: die fehlenden Verbindungen tatsächlich finden und belegen — nicht nur erklären, warum sie schwierig zu finden sind.
````

**Wichtig:** Lass dir neben dem Artefakt unbedingt die **Netzliste beziehungsweise JSON-Daten und exakten Fundstellen** geben. Damit kann ich die neuen Erkenntnisse anschließend in unsere Matrix übernehmen und auf Widersprüche prüfen.

Monica
GPT-6 Astra
Angetrieben von

Monica Suche
52 Sekunden nachgedacht
Linkleser
18 Sekunden nachgedacht
Searching: "CE2" "internal" "fusebox" connections diagram
Basierend auf 1 Suchquellen

Linkleser
9 Sekunden nachgedacht
Call Skill: Google Search
Linkleser
4 Sekunden nachgedacht
Denkprozess


Monica
GPT-6 Astra
Call Skill: Google Search
Linkleser
0 Sekunden nachgedacht
ZE2/CE2 357 937 039 – belegter Zwischenstand
Die vollständige interne Kontaktmatrix ist mit den bisher tatsächlich gelesenen Quellen nicht nachgewiesen. Es gibt aber konkrete verwertbare Ergebnisse: eine ausdrücklich als intern bezeichnete Kontaktzuordnung, mehrere ausdrücklich externe Brücken sowie eine wichtige Hardwareabgrenzung.

Entscheidend: Die nachstehende interne Zuordnung ist auf Quellenebene dokumentiert, aber noch nicht als feste Leiterverbindung am nackten Grundträger 357 937 039 freigegeben. Dafür fehlen der eindeutige Variantenbezug und die physische Kontaktabbildung.

Untersuchungszustand bleibt: ohne Relais, Sicherungen, herausnehmbare Brücken und Kabelbaum. Keine der gefundenen Fahrzeugverbindungen wird stillschweigend in diesen Zustand übernommen.

A. Hardwareabgrenzung
Gegenstand	Tatsächlich gelesener Nachweis	Konsequenz
357 937 039	Zielteilenummer aus deinem Auftrag. Die gelesenen technischen Quellenausschnitte enthalten keine vollständige, teilenummernbezogene Kontaktmatrix.	Zielhardware bleibt festgelegt; Übertragbarkeit allgemeiner CE2-Angaben ist noch nachzuweisen.
CE2 bei A2Resource	Einleitung nennt Golf/Jetta 1989–1999, Passat 1990–1997 sowie Cabrios, Corrados und EuroVans.	Anwendungsbeschreibung, kein Beweis identischer interner Kontaktplatten aller Ausführungen.
T3 „2. Generation“	T3-Pedia, Abschnitt „Allgemeines“, nennt ausdrücklich 171941821D.	Nicht mit 357 937 039 gleichsetzen.
Spätere Generation im T3	Derselbe Abschnitt beschreibt die Ablösung durch „Generation 3“ in anderen Modellreihen und eine Umstellung der südafrikanischen T3-Produktion 1995.	Die Generationenbegriffe der T3-Seite dürfen nicht ungeprüft auf die gebräuchlichen Bezeichnungen CE1/CE2 übertragen werden.
Indexvarianten von 357 937 039	Im gelesenen Material keine belastbare technische Gegenüberstellung.	Keine Variantenkompatibilität freigegeben.
Fundstellen: A2Resource, Einleitung und Tabelle „Fuse Box“; T3-Pedia, tatsächlich gelesener Quelltext, Abschnitt „Allgemeines“.

B. Kontaktinventar – erfasster Teil, nicht vollständig
Der Einzelabruf von A2Resource lieferte die Tabelle bis zum abgeschnittenen Eintrag E/05. Damit wurden 50 vollständige Kontaktzeilen und der Anfang einer weiteren Zeile gelesen.

Diese Zahl beschreibt Tabelleneinträge, nicht ein nachgewiesen vollständiges physisches Kontaktinventar.

Quellseitige Kontaktbezeichnungen	Vollständig gelesene Zeilen	Lage/Ansicht	Nachweis
-30, -30B, -Z1, -Z2	4	Einzelanschlüsse laut Tabelle; genaue Position und Blickrichtung nicht geprüft	A2Resource, erste vier Kontaktzeilen
A1/01–A1/08	8	Kontaktgruppe A1; physische Nummerierungsansicht nicht geprüft	A2Resource, Abschnitt A1
A2/01–A2/08	8	Kontaktgruppe A2; physische Nummerierungsansicht nicht geprüft	Abschnitt A2
B/01–B/06	6	Kontaktgruppe B; physische Nummerierungsansicht nicht geprüft	Abschnitt B
C/01–C/08	8	Kontaktgruppe C; physische Nummerierungsansicht nicht geprüft	Abschnitt C
D/01–D/12	12	Kontaktgruppe D; physische Nummerierungsansicht nicht geprüft	Abschnitt D
E/01–E/04	4	Kontaktgruppe E; physische Nummerierungsansicht nicht geprüft	Abschnitt E
E/05	nur Fragment	Nicht als vollständig extrahierter Datensatz übernommen	Abruf endet innerhalb der Zeile
Die führenden Bindestriche bei -30 usw. bleiben hier als Quellenschreibweise erhalten. Ob sie Bestandteil einer Gehäusebeschriftung oder nur Tabellenformatierung sind, wurde nicht visuell geprüft.

Nicht inventarisiert: sämtliche physischen Relaissockelkammern, beide Seiten jedes Sicherungshalters, die übrigen rückseitigen Kontaktgruppen und eventuell weitere Einzelkontakte.

Die Seite verweist auf eine Rückseitenabbildung. Diese Abbildung wurde nicht visuell geprüft. Daher gibt es hier keine behauptete Zuordnung „oben links“, keine gespiegelte Steckeransicht und keine erfundene Kammernummer.

C. Konkrete Kontaktzuordnungen
C1. Ausdrücklich interne Kontaktreferenz – noch keine freigegebene Leiterkante
Kontakt A	Kontakt B	Originalfundstelle	Eigene Bewertung
E/02	U2/1	A2Resource → „Fuse Box“ → Zeile E/02 → Spalte Inside Fusebox nennt ausdrücklich U2/1.	Explizit dokumentierte interne Zuordnung auf Quellenebene. Als feste Leiterverbindung des nackten 357 937 039 weiterhin Kandidat: genaue Hardwarevariante, physische Positionen und etwaige interne Bauteile sind nicht geklärt.
Das ist mehr als eine Übereinstimmung von Funktionsnamen: Die Quelle nennt einen konkreten Gegenkontakt in der Spalte für das Innere. Sie ist deshalb der derzeit beste direkte Ansatz zur Rekonstruktion.

Allerdings beweist die Tabellenzeile allein noch nicht sämtliche von dir verlangten Eigenschaften einer physischen Leiterverbindung.

C2. Externe Verbindungen – aus der nackten Grundträgermatrix ausschließen
Alle folgenden Referenzen stehen bei A2Resource in Outside Fusebox:

Kontakt A	Kontakt B	Genaue Fundstelle	Einordnung
-30	-30B	Zeilen -30 und -30B, gegenseitige Referenzen für die Kraftstoffpumpenversorgung	Externe Verbindung; keine interne Brücke daraus ableiten
B/01	B/02	Zeilen B/01 und B/02, gegenseitige Referenzen	Externe Verbindung
B/03	D/04	B/03 nennt D/4 oder direkten Anschluss an den Lichtschalter; D/04 nennt B/3	Externe, ausstattungsabhängige Verbindung
B/04	C/03	B/04 nennt C/3 oder direkte Masse; C/03 nennt B/4	Externe, alternativ direkt zur Masse geführte Verbindung
B/05	Y/2	Zeile B/05	Externe Versorgung des Scheinwerferreinigungszweigs
E/02	D/11	Zeile E/02, modellabhängige Einspeisung	Externe Variante; nicht mit D/08 vereinigen
E/02	D/08	Zeile E/02; ergänzend nennt D/08 E/2 für A3	Externe Variante; nicht mit D/11 vereinigen
Technisch wichtige Korrektur: Aus diesen Tabellenzeilen darf insbesondere kein festes internes Netz D/08–D/11–E/02–U2/1 entstehen. Die äußeren Einspeisungsvarianten und die innere Referenz müssen getrennt bleiben.

Quelle für C1 und C2: A2Resource, Tabelle mit getrennten Spalten „Outside Fusebox“ und „Inside Fusebox“.

C3. Funktionale Gruppen – ausdrücklich keine bestätigten Netze
Diese Angaben helfen bei der weiteren Prüfung, beweisen aber für sich keine direkte Verbindung untereinander:

Eigene Arbeitsbezeichnung	In der Quelle entsprechend bezeichnete Kontakte	Was noch fehlt
FG-Masse	-Z2, A1/03, A2/05, C/03, C/04, C/05	Nachweis der gemeinsamen festen Leiterstruktur
FG-Sicherung-1	A1/01, D/02	Konkrete Sicherungsseite und Direktverbindung zwischen den Kontakten
FG-Sicherung-4	D/03, D/05	Konkrete Sicherungsseite und Direktverbindung
FG-Sicherung-14	D/09, D/11	Konkrete Sicherungsseite und Direktverbindung
Fundstelle jeweils: A2Resource → betreffende Kontaktzeile → Inside Fusebox.

Freigegebene interne Netze für 357 937 039: derzeit keine.

Vollständige paarweise Durchgangsmatrix: daraus noch nicht ableitbar.

D. Relaissockelmatrix
Keine physische Sockelkammer konnte in diesem Rechercheabschnitt belastbar zugeordnet werden.

Es wurden immerhin folgende quellenbezogene Anknüpfungspunkte gelesen:

Rückseitenkontakt	Interne Funktionszuordnung laut A2Resource	Fehlendes Bindeglied
-30B	Eingang Kraftstoffpumpenrelais	Physischer Relaisplatz und Kammer
-Z1	Ausgang Kraftstoffpumpen-/Vorglührelais	Physischer Relaisplatz, Kammer und Variantenbezug
A1/08	Ausgang Hupenrelais	Physische Sockelkammer
B/01	Versorgung Scheinwerferreinigungsrelais	Physische Sockelkammer
B/04	Scheinwerferreinigungsrelais, ohne präziseren Kontakt im gelesenen Feld	Physische Sockelkammer und elektrische Rolle
B/05	Eingang Scheinwerferreinigungsrelais	Physische Sockelkammer
B/06	Ausgang Scheinwerferreinigungsrelais	Physische Sockelkammer
Diese Tabelle ist nur eine Liste offener Zuordnungen, keine fertige Relaissockelmatrix. Insbesondere wurden daraus keine DIN-Klemmenzahlen 30/85/86/87 und keine Kammernummern erfunden.

E. Sicherungskontaktmatrix
Die gelesenen Angaben liefern folgende Sicherungsreferenzen, aber noch keine physisch bestimmten Kontaktseiten:

Sicherung laut Quelle	Referenzierende Kontakte im gelesenen Abschnitt
1	A1/01, D/02
2	A2/03
4	D/03, D/05
7	A2/02
8	A1/04
11	A1/06
12	A2/07
13	A1/07
14	D/09, D/11
19	A1/05
20	E/04
Fundstelle: jeweils die gleichnamige Kontaktzeile bei A2Resource, Spalte Inside Fusebox.

Es wurden bewusst keine Kontakte „S1 oben“, „S1 unten“, „S1a“ oder „S1b“ angelegt. Die verfügbaren Angaben reichen nicht, um diese physisch zu bestimmen.

Auch wird kein Kontakt über eine eingesetzte Sicherung hinweg mit einem anderen Kontakt vereinigt.

F. Maschinenlesbare Daten
Die Datensätze unterscheiden zwischen:

Quellenaussage: Was steht tatsächlich in der Tabelle?
Prüfstatus für das Zielteil: Darf die Aussage bereits als feste Verbindung des nackten 357 937 039 gelten?
Kandidat bei E/02–U2/1 bedeutet nicht, dass die Kontaktreferenz erfunden oder nur aus gleichen Signalnamen gebildet wurde. Die Unsicherheit betrifft die Freigabe als direkte Leiterverbindung der exakten Zielhardware.

CSV
Kopieren
contact_a,contact_b,connection_type,hardware_variant,component_state,source_url,source_locator,evidence_status,notes
E/02,U2/1,unbestätigter Verbindungskandidat,CE2; Bezug zu 357 937 039 ungeklärt,Quellzustand nicht angegeben,https://www.a2resource.com/electrical/CE2.html,Fuse Box > E/02 > Inside Fusebox,Kandidat,"Konkrete interne Gegenkontaktreferenz explizit dokumentiert; physische Lage und bauteilfreie Direktverbindung nicht nachgewiesen"
-30,-30B,externe Leitung oder externe Brücke,CE2; Bezug zu 357 937 039 ungeklärt,Kabelbaum bzw. externe Brücke vorhanden,https://www.a2resource.com/electrical/CE2.html,Fuse Box > -30 und -30B > Outside Fusebox,explizit dokumentiert,"Im nackten Untersuchungszustand nicht übernehmen; führender Bindestrich entspricht der Quellenschreibweise"
B/01,B/02,externe Leitung oder externe Brücke,CE2; Bezug zu 357 937 039 ungeklärt,externe Verbindung vorhanden,https://www.a2resource.com/electrical/CE2.html,Fuse Box > B/01 und B/02 > Outside Fusebox,explizit dokumentiert,"Gegenseitige Außenreferenzen; keine interne Brücke daraus ableiten"
B/03,D/04,externe Leitung oder externe Brücke,CE2; ausstattungsabhängig,externe Verbindung vorhanden,https://www.a2resource.com/electrical/CE2.html,Fuse Box > B/03 und D/04 > Outside Fusebox,explizit dokumentiert,"B/03 alternativ direkt am Lichtschalter; D/4 als D/04 normalisiert"
B/04,C/03,externe Leitung oder externe Brücke,CE2; ausstattungsabhängig,externe Verbindung vorhanden,https://www.a2resource.com/electrical/CE2.html,Fuse Box > B/04 und C/03 > Outside Fusebox,explizit dokumentiert,"B/04 alternativ direkt an Masse; C/3 als C/03 normalisiert"
B/05,Y/2,externe Leitung oder externe Brücke,CE2; Bezug zu 357 937 039 ungeklärt,externe Verbindung vorhanden,https://www.a2resource.com/electrical/CE2.html,Fuse Box > B/05 > Outside Fusebox,explizit dokumentiert,"Y/2 nur als Gegenkontakt gelesen; eigene Y/2-Zeile noch nicht geprüft"
E/02,D/11,externe Leitung oder externe Brücke,CE2; modellabhängige Alternative,externe Verbindung vorhanden,https://www.a2resource.com/electrical/CE2.html,Fuse Box > E/02 und D/11 > Outside Fusebox,explizit dokumentiert,"Alternative zu Einspeisung über D/08; nicht als gemeinsame interne Brücke behandeln"
E/02,D/08,externe Leitung oder externe Brücke,CE2; A3 laut D/08,externe Verbindung vorhanden,https://www.a2resource.com/electrical/CE2.html,Fuse Box > E/02 und D/08 > Outside Fusebox,explizit dokumentiert,"Alternative zu Einspeisung über D/11; nicht als gemeinsame interne Brücke behandeln"
JSON – interne Rekonstruktion
Kopieren
{
  "target_hardware": "357 937 039",
  "investigation_state": {
    "relays": "removed",
    "fuses": "removed",
    "removable_bridges": "removed",
    "external_harness": "removed",
    "fixed_internal_components": "unknown"
  },
  "complete": false,
  "confirmed_internal_nets": [],
  "connections": [
    {
      "contact_a": "E/02",
      "contact_b": "U2/1",
      "connection_type": "unbestätigter Verbindungskandidat",
      "hardware_variant": "CE2; Bezug zu 357 937 039 ungeklärt",
      "component_state": "Quellzustand nicht angegeben",
      "source_url": "https://www.a2resource.com/electrical/CE2.html",
      "source_locator": "Fuse Box > E/02 > Inside Fusebox",
      "evidence_status": "Kandidat",
      "source_assertion_status": "explizit dokumentiert",
      "source_statement": "U2/1",
      "physical_position_a": null,
      "physical_position_b": null,
      "view_direction": null,
      "notes": "Explizite interne Gegenkontaktreferenz. Nicht als nachgewiesene feste Leiterverbindung des nackten Zielgrundträgers freigegeben."
    }
  ],
  "unknown_means_open_circuit": false
}
Das folgende Artefakt enthält zusätzlich alle acht CSV-Verbindungsdatensätze als JSON, eine durchsuchbare Kontaktansicht und die Quellenprüfung.

G. Browserartefakt
Der Topologiegraph zeigt absichtlich keine bestätigte feste Leiterkante: Eine solche wäre beim aktuellen Stand eine falsche Freigabe. Der interne Kandidat ist orange, externe Verbindungen sind blau und gestrichelt.

Nutzung: Suche filtert die Kontakt-, Verbindungs- und Quellenansichten. JSON und CSV stehen direkt im Artefakt. Die Diagramme benötigen zum Rendern die öffentlich eingebundene Mermaid-Bibliothek; ohne sie bleibt der Quelltext sichtbar.

Quellenprüfung und kurzes Rechercheprotokoll
Abruf/Suche	Tatsächlich zugänglicher Inhalt	Technische Ausbeute
Acht vorgegebene Ausgangsquellen gemeinsam abgerufen	Jeweils kurze, teilweise stark abgeschnittene Auszüge	Quellen erreichbar; kein Vollständigkeitsnachweis
A2Resource anschließend einzeln abgerufen	Tabelle von Einzelanschlüssen bis E/05-Fragment	Interne E/02→U2/1-Referenz, sieben externe Datensätze, Teilinventar
GitHub-Raw: mermaid.mermaid	Vollständiger kurzer Graph	VSS-Signalweg, nicht interne Grundträgermatrix
GitHub-Raw: beide Mindmap-Dateien	Dateianfänge	Thema VR6-XDF-Editor, nicht ZE2-Kontaktplatte
GitHub-Raw: sg-daten.js, graph-kanten.js	Abgeschnittene Dateianfänge	Umfangreiche Steuergeräte-/Signalreferenzen; keine vollständige Matrixprüfung möglich
GitHub: rekursive Baum-API	Abgeschnittener Verzeichnisbaum; SHA 08beeaeac4e025cc10f4ea56152d8077e5653616 angezeigt	Reproduzierbarer Ansatz für eine Fortsetzung; Historie selbst nicht geprüft
T3-Pedia über Quelltextansicht	Abschnitt „Allgemeines“ vollständig genug für die Teilenummer	171941821D eindeutig vom Ziel zu trennen
Suche CE2 fusebox "internal" "connections"	Treffer u. a. VWVortex „CE2 Help needed“	Beiträge 1–2 anschließend gelesen; kein verwertbares Messprotokoll
Suche "357 937 039" "intern"	Überwiegend Teileangebote; ein VWVortex-Treffer zur Golf-GTI-VR6-Fusebox	Mögliche nächste Quelle; Treffertext nicht als geprüfte Verbindung übernommen
Wichtige Quellenkorrekturen
Repository-Mermaid: Die Datei führt von Geber über G1/11, U1/11 und Tacho bis zur ECU. Sie enthält damit verschiedene Komponenten und externe Leitungsabschnitte. Ihre Pfeile sind keine pauschalen festen ZE2-Verbindungen.

Tatsächlich gelesene Datei

Mindmaps: Die gelesenen Anfänge beider Dateien behandeln Kennfelderkennung, XDF und Editorentwicklung. Kein Beleg für eine ZE2-Kontaktmatrix.

mindmap.txt · mindmapv01.txt

Scribd: Der sichtbare Dokumentanfang besitzt die Struktur der A2Resource-Tabelle, der extrahierte Text ist jedoch stark beschädigt. Eine gemeinsame Herkunft liegt nahe, ist aber nicht vollständig geprüft. Das Dokument zählt deshalb nicht als unabhängige Bestätigung.

Dokument

VWVortex: Der Autor formuliert in Beitrag 2 eine eigene Schaltplaninterpretation zur Z1-Rückspeisung. Hardware- und Messzustand genügen nicht für einen bestätigten Durchgangsdatensatz.

Thread, Beiträge 1–2

Noch nicht durchgeführt: die geforderte breite Suche auf Polnisch, Russisch, Tschechisch, Französisch, Spanisch und Portugiesisch; vollständige Git-Historienanalyse; visuelle PDF-/Bildprüfung; vollständige Auswertung der langen Forenseiten. Diese Antwort ist deshalb ausdrücklich ein begrenzter Recherchezwischenstand, nicht die abgeschlossene weltweite Recherche.

H. Verifizierte neue Erkenntnisse
E/02 → U2/1 wird bei A2Resource ausdrücklich unter „Inside Fusebox“ genannt.

Fundstelle: Tabelle „Fuse Box“, Zeile E/02. Als interner Zuordnungskandidat übernehmen, noch nicht als freigegebene feste Leiterkante für 357 937 039.

Sieben konkrete externe Verbindungsdatensätze wurden extrahiert.

Besonders wichtig: 30–30B, B/01–B/02 und die alternativen Einspeisungen E/02–D/11 beziehungsweise E/02–D/08 gehören nicht automatisch in die nackte interne Netzliste.

T3-Pedia beschreibt bei „2. Generation“ ausdrücklich 171941821D.

Diese Matrix darf ohne gesonderten Nachweis nicht auf 357 937 039 übertragen werden.

Der Repository-Mermaid ist ein VSS-Signalweg; die Mindmap-Anfänge behandeln XDF.

Beide sind keine Ersatzquelle für die vollständige interne Kontaktplatte.

Präzise Fortsetzungsmarke
Arbeitsstand: ZE2-357937039 / Teilabruf A2 bis E/04 vollständig / E/05 abgeschnitten / 1 interner Kandidat / 7 externe Datensätze / 0 freigegebene interne Netze.

Offene Lücke	Beste konkrete nächste Prüfung
Restliches Rückseiteninventar	A2Resource ab E/05 vollständig erfassen; Rückseitenabbildung samt Nummerierungsansicht prüfen
E/02–U2/1 als feste Leiterverbindung	Teilenummernbezogenen Stromlaufplanausschnitt oder nachvollziehbare Messung am nackten 357 937 039 suchen
Relaissockelkammern	VWVortex „Golf GTI Vr6 fuse box“ vollständig abrufen; Suchtreffer nennt interne Verdrahtung, Inhalt bislang ungeprüft
Sicherungsseiten	Hersteller-Stromlaufpläne mit Kontaktplattenbegrenzung und physischer Sicherungsansicht beschaffen; bisherige Sicherungsreferenzen nur als Suchindex verwenden
Repository-Unterlagen	relais-extract.txt, si-extract.txt, docs/, golf2_gti_ze2_tacho_pinout.pdf und Git-Historie prüfen; diese Dateien wurden noch nicht inhaltlich ausgewertet
Lange Forenbeiträge/Anhänge	Club GTI Seite 10 vollständig und Club8090 in Druckansicht/Folgeseite prüfen; Hardware vor Übernahme identifizieren
Interne Bauteile und Varianten	Zerlegebilder mit lesbarer Teilenummer und vollständig sichtbaren Leiterlagen oder geeignetes Messprotokoll suchen
Nicht freigeben: eine Verdrahtung oder Durchgangsprüfung auf Basis vermeintlich vollständiger Netze. Der belastbare Gewinn dieses Abschnitts ist die Trennung einer konkreten internen Referenz von dokumentierten äußeren Brücken, nicht bereits die vollständige Kontaktmatrix.

**Das ist der zurückgelieferte Recherchezwischenstand – als Datengrundlage brauchbar, aber noch keine Sockelkontaktmatrix.** Ich behandle seine Angaben als übergebene Rechercheergebnisse, nicht automatisch als unabhängig bestätigte Verbindungen.

## 1. Was tatsächlich neu hinzugekommen ist

| Ergebnis im HTML | Bewertung |
|---|---|
| **50 Kontaktzeilen** | Die Anzahl stimmt mit den enthaltenen Datensätzen überein. Das bestätigt die Zählung, nicht deren vollständige Quellenprüfung. |
| **E/02 → U2/1** unter „Inside Fusebox“ | Ein konkreter Ansatz für eine interne Kontaktverbindung – wesentlich hilfreicher als ein gemeinsamer Funktionsname. |
| **Sieben externe Verbindungsdatensätze** | Korrekt von der nackten Grundträgertopologie getrennt. Modellabhängige Alternativen dürfen nicht gleichzeitig zu einem Netz zusammengeführt werden. |
| **Keine bestätigten festen Netze** | Der dargestellte Belegstand rechtfertigt diese vorsichtige Einstufung. |
| **Keine physischen Relaissockel- und Sicherungskontakte** | Die entscheidende Anforderung bleibt weiterhin unerfüllt. |

Bei meinem erneuten Abruf von [A2Resource](https://www.a2resource.com/electrical/CE2.html) waren die Spalten **„Outside Fusebox“ und „Inside Fusebox“** sowie die ersten Kontaktzeilen sichtbar. **Der zurückgegebene Ausschnitt endete allerdings schon im A2-Bereich.** Deshalb kann ich die behauptete vollständige Prüfung der 50 Zeilen damit nicht unabhängig bestätigen.

Die Kombination **E/02 / U2/1** erscheint außerdem in einem Suchauszug der Scribd-Fassung. Das stützt den Rechercheansatz, ersetzt aber keine Prüfung der vollständigen Tabellenzeile.

## 2. Drei notwendige Korrekturen am Datenmodell

### Quellenstatus und elektrische Bestätigung trennen

Die Kontakte tragen pauschal `evidence_status: "explizit dokumentiert"`. Gleichzeitig enthalten sie nur deutsche Zusammenfassungen.

Für eine belastbare Übernahme müssen getrennte Felder geführt werden:

- **Originalwortlaut der Quelle**
- **Deutsche Zusammenfassung**
- **Vom anderen Chat als gelesen gemeldet**
- **Hier unabhängig geprüft**
- **Elektrische Topologie bestätigt**

Sonst wird aus einer übernommenen Zusammenfassung versehentlich ein vermeintlich selbst geprüfter Beleg.

### Kontaktbezeichnungen einheitlich normalisieren

Im Datensatz stehen beispielsweise `E/02`, aber `U2/1` und `Y/2`.

Sinnvoll sind jeweils zwei Felder:

- Original: `U2/1`
- Normalisierte ID: `U2/01`

Dasselbe gilt für die führenden Bindestriche bei `-30` und `-Z1`: **Original erhalten, aber nicht ohne Gehäusefoto als eingeprägte Beschriftung ausgeben.**

### Mermaid-Pfeile nicht als Leitungsrichtung darstellen

Eine feste leitende Verbindung ist grundsätzlich keine gerichtete Signalflusskante. Die Pfeile im Diagramm sollten entweder ausdrücklich **„Quellenreferenz“** bedeuten oder durch ungerichtete Linien ersetzt werden.

**E/02 ↔ U2/01 bleibt vorerst ein Verbindungskandidat**, keine freigegebene Kupferbrücke.

## 3. Konsequenz für unser bisheriges Artefakt

**Meine früheren sechs Beschreibungsgleichheitsgruppen dürfen nicht als bestätigte interne Netze weitergeführt werden.** Das betrifft insbesondere die funktional abgeleitete Generator-Gruppe.

Der saubere Arbeitsstand lautet jetzt:

- **50 übergebene Kontaktbeschreibungen**
- **1 konkret benannte interne Gegenkontaktreferenz**
- **7 übergebene externe Verbindungsdatensätze**
- **0 unabhängig bestätigte vollständige interne Netze**
- **0 vollständig zugeordnete physische Relaissockel**
- **0 vollständig zugeordnete Sicherungshalter mit beiden Kontaktseiten**

## 4. Wo die weitere Recherche ansetzen muss

**Noch ein optisch erweitertes Artefakt löst die Lücke nicht.** Der nächste technische Schritt muss mindestens einen Relaissockel vollständig erschließen:

> **Physische Sockelkammer → eindeutige Kontaktbezeichnung → rückseitiger Kontakt beziehungsweise Sicherungskontakt → genaue Fundstelle.**

Parallel muss die A2Resource-Tabelle **über E hinaus** erschlossen werden, insbesondere die Gegenzeile **U2/01**. Eine gegenseitige Referenz wäre ein stärkerer Dokumentationsbeleg; die physische Sockelzuordnung liefert sie allein jedoch weiterhin nicht.

**Fazit:** Der andere Chat hat den Zwischenstand nachvollziehbarer gemacht, aber die gesuchten fehlenden Sockelinformationen noch nicht beschafft. Das sollten wir klar auseinanderhalten.

Monica
GPT-6 Astra
17 Sekunden nachgedacht
Linkleser
7 Sekunden nachgedacht
Call Skill: Google Search
2 Sekunden nachgedacht
Denkprozess


Monica
GPT-6 Astra
Call Skill: Google Search
Linkleser
0 Sekunden nachgedacht
Denkprozess


Monica
GPT-6 Astra
Call Skill: Google Search
0 Sekunden nachgedacht
Deine Trennung ist richtig. Ich habe die Recherche fortgesetzt, ohne das Artefakt nur optisch zu erweitern. Der erneute Quellenabruf liefert jetzt eine zusätzliche gegenseitige interne Kontaktreferenz. Einen vollständigen physischen Relaissockel konnte ich weiterhin nicht erschließen.

1. Jetzt unmittelbar an der Quelle geprüft
Der aktuelle Abruf von A2Resource reicht bis in G1 hinein; er endet innerhalb von G1/05. Damit waren diesmal die zuvor übergebenen 50 Kontaktzeilen sowie E/05, F/01–F/10 und G1/01–G1/04 zugänglich.

Das ist eine erneute Prüfung derselben Quelle, keine unabhängige zweite technische Bestätigung.

Konkrete interne Gegenkontaktreferenzen
Tabellenzeile	Originalwortlaut in „Inside Fusebox“	Normalisierte Zuordnung	Bewertung
E/02	U2/1	E/02 ↔ U2/01	Gegenkontaktreferenz jetzt unmittelbar gelesen; Gegenzeile U2/01 weiterhin nicht geprüft
F/02	G1/1	F/02 ↔ G1/01	Neue konkrete interne Gegenkontaktreferenz
G1/01	F/2	G1/01 ↔ F/02	Gegenseitige Referenz bestätigt innerhalb derselben Tabelle
Exakte Fundstellen: A2Resource → Fuse Box → jeweilige Kontaktzeile → Spalte Inside Fusebox.

Bei F/02 und G1/01 steht in der Spalte „Outside Fusebox“ jeweils ein Strich. Daraus folgt nicht, dass dort kein Metallkontakt vorhanden wäre.

Was daraus übernommen werden darf
F/02 ↔ G1/01 ist jetzt eine beidseitig ausdrücklich dokumentierte interne Zuordnung auf Quellenebene – nicht bloß eine Beschreibungsgleichheit.

Für die verlangte feste Leiterverbindung am nackten 357 937 039 bleibt sie dennoch ein Kandidat, solange diese Punkte fehlen:

eindeutiger Bezug der Tabelle zur konkreten Kontaktplattenvariante;
physische Nummerierungsansicht;
Nachweis, dass die Verbindung keine internen Bauteile oder entfernbaren Elemente durchläuft.
Die gegenseitigen Einträge sind zwei Fundstellen, aber keine zwei unabhängigen Quellen.

2. Neue Inventarinformation: F/10 ausdrücklich ohne Pin
Kontaktposition laut Tabelle	Original „Inside Fusebox“	Übernahme
F/10	(no pin)	Als quellseitig nicht mit einem Pin besetzte Position erfassen, nicht als vorhandenen elektrischen Kontakt
Das ist für das Inventar wichtig: Tabellenzeilen dürfen nicht pauschal als physische Kontakte gezählt werden.

Auch diese Aussage ist noch nicht anhand eines Gehäusefotos des Zielteils überprüft. Im Datenmodell wären daher getrennte Angaben sinnvoll:

position_designation: "F/10"
source_population_statement: "(no pin)"
physical_population_verified: false
3. Relaissockel: Suchhinweis gefunden, noch kein freigegebener Datensatz
Die gezielte Suche führte erneut zum Thread „Golf GTI Vr6 fuse box“.

Ein Suchauszug, nicht der vollständig gelesene Beitrag, enthält:

“Pin 6 should be 12v constant. Pin 2 is hardwired inside the fuse box … Pin 6 is part of the jumper circuit …”

Ein weiterer Suchauszug desselben Threads nennt dazu die äußere rote Brücke 30–30B.

Das wird nicht als Sockelkontaktzuordnung übernommen. Im zugänglichen Originalausschnitt fehlt weiterhin der relevante Beitrag mit eindeutigem Kontext:

Welcher Sockel ist gemeint?
Sind „2“ und „6“ Gehäusekammernummern oder eine Diagrammnummerierung?
Welche Blickrichtung gilt?
Welcher konkrete interne Gegenkontakt wird genannt?
Auf Seite 2, Beitrag #22 vom 29. Oktober 2018 war dagegen tatsächlich eine Beschreibung des kurzzeitig massegeschalteten ECU-Signals an „pin 3“ lesbar. Das ist eine Fahrzeugdiagnosebeschreibung, kein Nachweis einer festen Masseverbindung im nackten Träger. Die dort vorgeschlagene Durchgangsprüfung bei eingeschalteter Zündung übernehme ich zudem nicht als Messanweisung.

Ergebnis für die Sockelmatrix: weiterhin keine vollständige Zuordnung. Der Thread bleibt ein konkreter Suchansatz, aber keine freigegebene Kammerquelle.

4. Datenmodell: neue Verbindung mit getrennten Prüfständen
Für den neuen Datensatz lautet die Übernahme:

Kopieren
{
  "contact_a": "F/02",
  "contact_b": "G1/01",
  "source_contact_a_original": "F/02",
  "source_contact_b_original": "G1/01",
  "connection_type": "unbestätigter Verbindungskandidat",
  "hardware_variant": "CE2 laut Quelle; Bezug zu 357 937 039 ungeklärt",
  "component_state": "nicht angegeben",
  "source_url": "https://www.a2resource.com/electrical/CE2.html",
  "source_locator": "Fuse Box > F/02 und G1/01 > Inside Fusebox",
  "source_original_statements": {
    "F/02": "G1/1",
    "G1/01": "F/2"
  },
  "german_summary": "Gegenseitige interne Gegenkontaktreferenz",
  "reported_by_previous_chat": false,
  "source_text_checked_this_turn": true,
  "independent_second_source_checked": false,
  "source_assertion_status": "explizit dokumentiert",
  "evidence_status": "Kandidat",
  "electrical_topology_confirmed_for_target": false,
  "physical_position_verified": false,
  "view_direction": null,
  "notes": "Keine Beschreibungsgleichheitsableitung. Direkte bauteilfreie Leiterverbindung und Hardwarevariante nicht nachgewiesen."
}
Für E/02 ↔ U2/01 darf nun ebenfalls source_text_checked_this_turn auf true gesetzt werden – nicht jedoch die elektrische Bestätigung.

5. Aktualisierter technischer Stand
Merkmal	Stand
Zuvor übergebene 50 Kontaktzeilen	Jetzt erneut an A2Resource gelesen; physische Lage weiterhin ungeprüft
Konkret benannte interne Kontaktpaare	2: E/02–U2/01 und F/02–G1/01
Davon gegenseitig in der Tabelle referenziert	1: F/02–G1/01
Explizite Nichtbestückungsangabe	F/10: „(no pin)“
Bestätigte vollständige interne Netze für 357 937 039	0
Vollständig erschlossene physische Relaissockel	0
Sicherungshalter mit beiden physisch zugeordneten Kontaktseiten	0
Verifizierte neue Erkenntnisse
E/02 → U2/1: Originalfeld jetzt tatsächlich gelesen.
F/02 → G1/1 und G1/01 → F/2: neue, gegenseitige interne Referenz.
F/10 → „(no pin)“: Tabellenposition nicht als physischen Kontakt zählen.
Die bisherigen Funktionsgleichheitsgruppen bleiben außerhalb der bestätigten Netzliste.
Die nächste offene Quellenstelle bei A2Resource liegt innerhalb G1/05; U2/01 bleibt ungeprüft.
Für den ersten Relaissockel fehlt weiterhin die entscheidende Quelle mit Kammernummerierung, Ansicht und konkreten Gegenkontakten. Die Suchauszüge zu „Pin 2/6“ schließen diese Lücke noch nicht.
**Die neuen Angaben lassen sich jetzt auch in meinem eigenen Quellenabruf bestätigen.** Damit sind sie nicht mehr nur aus dem anderen Chat übernommen – allerdings bleibt es dieselbe technische Quelle, keine unabhängige Zweitbestätigung.

## Übernahme in den Recherchebestand

In [A2Resource → „Fuse Box“](https://www.a2resource.com/electrical/CE2.html) sind diese Originalfelder jetzt unmittelbar sichtbar:

| Position | Originalfeld „Inside Fusebox“ | Übernahmestatus |
|---|---|---|
| **E/02** | `U2/1` | Explizite interne Gegenkontaktreferenz; Gegenzeile noch nicht geprüft |
| **F/02** | `G1/1` | Explizite interne Gegenkontaktreferenz |
| **G1/01** | `F/2` | Gegenseitige Referenz zu F/02 |
| **F/10** | `(no pin)` | Laut Tabelle unbestückte Position; kein vorhandener Kontakt zu zählen |

**F/02 ↔ G1/01 ist damit stärker belegt als unsere früheren Funktionsgleichheitsgruppen.** Die passende Bezeichnung ist:

> **Quellseitig explizit dokumentierte interne Verbindung; physische Ausführung und Geltung für den konkreten 357 937 039 noch nicht verifiziert.**

So bleibt sichtbar, *was* bereits belegt ist, ohne die Verbindung vorschnell als am Zielgrundträger bestätigten Durchgang auszugeben.

## Korrigierter Umfang des Inventars

Aus dem vollständig sichtbaren Tabellenabschnitt ergeben sich:

- **65 vollständig gelesene Positionszeilen:** die bisherigen 50, zusätzlich E/05, F/01–F/10 und G1/01–G1/04.
- Darunter **eine ausdrücklich unbestückte Position: F/10**.
- **G1/05 ist nur teilweise sichtbar** und wird nicht als vollständig erfasster Datensatz gezählt.
- Daraus folgt **keine Bestätigung von 64 physisch vorhandenen Kontakten**: Die übrigen Positionen sind weiterhin nicht am Gehäuse verifiziert.

Die bisherige Kennzahl „50 Kontaktzeilen“ sollte deshalb künftig **„65 vollständig erfasste Tabellenpositionen, davon eine laut Quelle ohne Pin“** heißen.

## Wichtiger Hinweis für den ersten Relaissockel

Eine weitere jetzt sichtbare Zeile ist für die Recherche relevant:

**G1/03**
- „Outside Fusebox“: unter anderem `ECU- Fuel Pump Relay Turn-On (gas)`
- „Inside Fusebox“: `Fuel Pump Relay Power`

Das ist **noch keine Sockelkammerzuordnung**. Insbesondere darf das mehrdeutige Wort „Power“ hier nicht ungeprüft als Lastversorgung interpretiert werden: Die äußere Beschreibung nennt für die Benzinvariante ausdrücklich die ECU-Ansteuerung.

Damit bestehen für die Untersuchung des Kraftstoffpumpenrelaissockels drei konkrete Anknüpfungspunkte:

| Anschluss | Quellseitige Funktion | Noch zu finden |
|---|---|---|
| **-30B** | Kraftstoffpumpenrelais-Eingang | Physische Sockelkammer und Leiterweg |
| **-Z1** | Kraftstoffpumpen-/Vorglührelais-Ausgang | Physische Sockelkammer, Varianten und Leiterweg |
| **G1/03** | Unter anderem ECU-Ansteuerung des Kraftstoffpumpenrelais | Physische Steuerkammer und Gegenkontakt |

**Diese drei Anschlüsse werden nicht miteinander zu einem Netz verbunden.** Sie dienen als getrennte Suchansätze.

## VWVortex: Abgrenzung bestätigt

[Beitrag #22 auf Seite 2](https://www.vwvortex.com/threads/golf-gti-vr6-fuse-box.9254819/page-2) beschreibt tatsächlich ein **kurzzeitig massegeschaltetes ECU-Signal an „pin 3“**. Er belegt weder eine feste Masseverbindung noch die vollständige physische Sockelnummerierung.

Die dort genannte Durchgangsprüfung bei eingeschalteter Zündung wird **nicht als Messanleitung übernommen**. Widerstands- und Durchgangsmessungen gehören an spannungsfreie, ausreichend isolierte Stromkreise.

**Der nächste gezielte Rechercheauftrag ist damit klarer:** Den Kraftstoffpumpenrelaissockel über **-30B, -Z1 und G1/03** erschließen und dazu eine eindeutig orientierte Kammeransicht finden. Das ist ein konkreter Ansatz für die fehlende Sockelmatrix – nicht nur eine weitere Erweiterung der Funktionsliste.

Monica
GPT-6 Astra
19 Sekunden nachgedacht
Linkleser
14 Sekunden nachgedacht
Call Skill: Google Search
10 Sekunden nachgedacht
Call Skill: Google Search
3 Sekunden nachgedacht
Call Skill: Google Search
0 Sekunden nachgedacht
Übernommen: 65 vollständig erfasste Tabellenpositionen, davon F/10 laut Quelle ohne Pin. Der erneute A2Resource-Abruf bestätigt diesen Umfang bis G1/04; G1/05 bleibt abgeschnitten. Die drei Ansatzpunkte -30B, -Z1 und G1/03 bleiben strikt getrennt.

Die gezielte Sockelrecherche hat weitere Fundstellen geliefert – allerdings bislang nur Suchauszüge, keine belastbare Kammeransicht. Ich trenne diese deshalb vom Kontaktbestand.

Neue Fundstellen zum Kraftstoffpumpenrelaissockel
Quelle	Tatsächlich zugänglicher Hinweis	Technische Bedeutung und Grenze
VW Corrado Forum: „2E Motor springt nicht mehr an“	Suchauszug: „Kraftstoffpumpenrelais (Steckplatz 12 also unten rechts mit 67 oder 80 beschriftet) … Kontakte 2 + …“	Konkreter Ansatz für Steckplatz und nummerierte Sockelkontakte. Der zweite Kontakt ist abgeschnitten; Blickrichtung, Abbildung und Teilenummer nicht geprüft. „67/80“ sind hier Relaiskennzeichnungen, keine Kammernummern.
Passat35i: „ADZ Motor hat ab und an leichte Startprobleme“, Seite 6	Suchauszug nennt ausdrücklich „Steckplatz 12/Pin6“.	Mögliche präzisere Fundstelle für den bisher nur als „Pin 6“ bezeichneten Kontakt. Keine Zuordnung zu -30B aus dem Auszug ableitbar.
Wolfsburg Edition: „Leitungsverbinder an die 2er ZE“	Suchauszug: „Steckplatz 12 das Kraftstoffpumpenrelais oder das Vorglührelais mit Dauerplus (Last) zu versorgen.“ Außerdem werden Einzelkontakte Y genannt.	Ansatz zur Lastversorgung von Steckplatz 12. Der vollständige Zusammenhang zwischen Einspeisung, äußerer Brücke und Sockelkontakt fehlt.
T4Forum: „2,5L … springt an und geht nach 2min aus“	Suchauszug verweist auf „So wird’s gemacht“ und die Prüfung mehrerer Kontakte des Kraftstoffpumpenrelais an Steckplatz 12.	Konkreter Ansatz zur Reparaturunterlage hinter dem Forenzitat. Ausgabe, Seite, Prüfbild und Hardwarekompatibilität noch ungeprüft.
Keiner dieser Suchauszüge wird als elektrische Verbindung oder Messanweisung übernommen. Insbesondere ergänze ich die abgeschnittene Kontaktkombination „2 + …“ nicht aus Vermutungen.

Aktuelle Sockel-Arbeitstabelle
Die Kennzeichnung „Steckplatz 12“ ist hier zunächst ein Suchkandidat aus den neuen Fundstellen, noch keine am Zielgehäuse verifizierte Position.

Ausgangskontakt	Bereits unmittelbar gelesener Quelleninhalt	Physische Sockelkammer	Direkte interne Verbindung
-30B	A2Resource: Fuel Pump Relay Input	Unbekannt; „Steckplatz 12/Pin6“ gezielt prüfen	Noch nicht belegt
-Z1	A2Resource: Fuel Pump/Glow Plug Relay Output	Unbekannt	Noch nicht belegt
G1/03	Außen u. a. ECU- Fuel Pump Relay Turn-On (gas); innen Fuel Pump Relay Power	Unbekannt; keine Gleichsetzung mit „pin 3“ ohne Beleg	Noch nicht belegt
Nicht zulässig wäre derzeit:

-30B ↔ Steckplatz 12/Kammer 6 als bestätigte Kante einzutragen;
G1/03 ↔ Steckplatz 12/Kammer 3 allein aus ähnlichen Funktionsbeschreibungen abzuleiten;
aus einer vorgeschlagenen Relaisüberbrückung eine feste interne Verbindung zu machen.
Einordnung der Hardwareaussage bei VWVortex
Im diesmal tatsächlich gelesenen Beitrag #4 behauptet der Verfasser, die Grundkästen seien bei allen CE2-Modellen gleich; Kabelbäume unterschieden sich hingegen nach Baujahr und Ausstattung.

Das ist eine allgemeine Forenaussage zur Austauschbarkeit, kein Nachweis identischer Kontaktplatten sämtlicher Varianten. Sie ersetzt weder die Teilenummernprüfung noch die physische Kammeransicht.

Präzise Fortsetzungsmarke
Kontaktbestand unverändert: zwei ausdrücklich dokumentierte interne Kontaktpaare, davon F/02–G1/01 gegenseitig referenziert; keine freigegebene physische Sockelkante.

Nächste Quellenprüfung in dieser Reihenfolge:

Corrado-Beitrag vollständig: abgeschnittene Kontaktkombination, eventuell vorhandene Abbildung und deren Blickrichtung ermitteln.
Passat35i Seite 6: den vollständigen Zusammenhang von „Steckplatz 12/Pin6“ lesen; nach expliziter Rückseitenreferenz suchen.
Wolfsburg-Edition-Beitrag: Lastversorgung und äußere Einspeisebrücke auseinanderhalten.
Zitierte Reparaturunterlage: Ausgabe und Prüfabbildung identifizieren; erst anschließend die Nummerierung auf 357 937 039 übertragen.
Damit liegt jetzt ein konkreterer Quellenpfad zur Kammernummerierung vor. Die entscheidende Zuordnung physische Kammer → -30B/-Z1/G1/03 ist aber weiterhin offen – und wird nicht durch eine weitere Funktionsliste als gelöst dargestellt.

**Zwei der bisherigen Suchhinweise konnte ich jetzt im Originaltext nachlesen.** Sie verbessern die Quellenlage zu Steckplatz 12, liefern aber noch keine feste Verbindung zu einem rückseitigen Kontakt.

## 1. Steckplatz 12: Lastversorgung ausdrücklich beschrieben

Im [Wolfsburg-Edition-Thread, Beitrag #2 vom 23. Juni 2007](https://www.wolfsburg-edition.info/wbb5/thread/91958-leitungsverbinder-an-die-2er-ze/?postID=816999) ist unmittelbar lesbar:

> „Das Kabel in deinen Bildern hat ja eigentlich nur die Funktion auf Steckplatz 12 das Kraftstoffpumpenrelais oder das Vorglührelais mit Dauerplus (Last) zu versorgen.“

**Damit lässt sich übernehmen:**
- Der Beitrag ordnet die besprochene **externe Einspeisung** der Lastversorgung des Relais auf **Steckplatz 12** zu.
- Das ist jetzt eine gelesene Forenaussage, nicht mehr nur ein Suchauszug.

**Weiterhin nicht belegt:**
- die physische Sockelkammer;
- eine ausdrücklich benannte Verbindung zu `-30B`;
- die Bildorientierung und Teilenummer des gezeigten Grundträgers.

Der verfügbare Text endet während der anschließenden Erklärung. Die verlinkten Bilder habe ich nicht visuell verifiziert.

## 2. Kontakte 2, 4 und 6: ausdrücklich Steckplatz 12 zugeordnet

Im [T4Forum, Beitrag #1 vom 23. Juli 2011](https://www.t4forum.de/forum/index.php?thread/155951-2-5l-85kw-115ps-benziner-bj97-springt-an-und-geht-nach-2min-aus-elektr-problem/) stehen tatsächlich diese Prüfbezeichnungen:

- „Kontakt 6 gegen Masse“
- „Kontakt 2 gegen Masse“
- „Kontakt 6 gegen 4“

Der Verfasser nennt davor ausdrücklich **Steckplatz 12** und die Reparaturunterlage **„So wird’s gemacht“**.

**Neuer belastbarer Quellenbefund:** In dieser Fahrzeug- und Dokumentationsumgebung werden für Steckplatz 12 die Kontakte **2, 4 und 6** verwendet.

**Nicht daraus ableitbar:** Dass einer dieser Kontakte fest an Masse liegt oder die Kontakte 6 und 4 intern verbunden sind. Die Angaben beschreiben Prüfungen im Fahrzeug; Messart, Bedingungen und Sollwerte sind im Ausschnitt nicht ausreichend erklärt.

## 3. Abrufgrenzen der übrigen Fundstellen

| Quelle | Tatsächliches Ergebnis meines Abrufs |
|---|---|
| **Corrado-Thread** | Nur der Beginn des ersten Beitrags; die gesuchte Kontaktkombination nicht erreicht. |
| **Passat35i, Seite 6** | **HTTP 403** – Inhalt nicht gelesen. |
| **VWVortex, Seite 1** | Nur Anfang des Threads; relevante spätere Kontaktbeschreibung nicht erreicht. |

Diese Quellen bleiben offen. Ich stufe sie nicht allein aufgrund der übergebenen Suchauszüge höher ein.

## 4. Konkrete Ergänzung für die Übergabe

Die neuen Informationen gehören zunächst in ein **Register der Sockelbezeichnungen**, nicht in die elektrische Kantenliste:

| Steckplatz laut Quelle | Kontaktbezeichnungen | Belegart | Physische Ansicht | Rückseitenzuordnung |
|---|---|---|---|---|
| **12** | **2, 4, 6** | Tatsächlich gelesener Fahrzeug-Prüfbericht mit Literaturverweis | Ungeprüft | Unbekannt |
| **12** | Lastversorgung, keine Kammer genannt | Tatsächlich gelesene Beschreibung einer externen Einspeisung | Ungeprüft | Unbekannt |

**Der wichtigste nächste Fund wäre jetzt die zugehörige Prüfabbildung aus „So wird’s gemacht“, einschließlich Ausgabe und Seite.** Sie könnte die bisher fehlende Kammernummerierung und Blickrichtung liefern. Die Zuordnung zu `-30B`, `-Z1` und `G1/03` muss anschließend separat über einen Stromlaufplan oder einen eindeutigen Leiterweg belegt werden.

Damit ist ein Teilziel erreicht: **Steckplatz und einige dort verwendete Kontaktnummern sind textlich zusammengeführt.** Die fehlenden Leiterverbindungen sind dadurch aber noch nicht gelöst.

Monica
GPT-6 Astra
Angetrieben von

Monica Suche
40 Sekunden nachgedacht
Linkleser
33 Sekunden nachgedacht
Searching: "Kraftstoffpumpenrelais" "Kontakt 6" "Kontakt 4"
26 Sekunden nachgedacht
Call Skill: Google Search
21 Sekunden nachgedacht
Linkleser
0 Sekunden nachgedacht
Die Bezeichnungen für Steckplatz 12 lassen sich bestätigen. Zusätzlich ist eine bislang übersehene Variantenbehauptung aufgetaucht, die vor jeder Zusammenführung der Versorgungsnetze geklärt werden muss. Eine neue feste Kontaktkante ergibt sich daraus noch nicht.

1. Steckplatz 12: Quellenprüfung bestätigt
Im erneut gelesenen T4Forum-Beitrag #1 vom 23. Juli 2011 stehen tatsächlich:

der Verweis auf „So wird’s gemacht“;
Steckplatz 12;
die Prüfbezeichnungen Kontakt 6 gegen Masse, Kontakt 2 gegen Masse und Kontakt 6 gegen 4.
Zusätzliche Grenze: Der Verfasser schreibt ausdrücklich, den genauen Motortyp nicht zu kennen, und vermutet lediglich Simos 5S. Der Titel nennt einen T4-Benziner, Baujahr 1997. Die Zuordnung zu einer bestimmten Motor- und Stromlaufplanvariante ist damit nicht gesichert.

Das Register bleibt:

Quellenbezeichnung	Dokumentationsstatus	Physische Orientierung	Elektrische Gegenkontakte
Steckplatz 12 / Kontakt 2	Im Fahrzeug-Prüfbericht ausdrücklich genannt	Unbekannt	Unbekannt
Steckplatz 12 / Kontakt 4	Im Fahrzeug-Prüfbericht ausdrücklich genannt	Unbekannt	Unbekannt
Steckplatz 12 / Kontakt 6	Im Fahrzeug-Prüfbericht ausdrücklich genannt	Unbekannt	Unbekannt
Diese drei Bezeichnungen sind kein vollständiges Kammerinventar.

2. Neu: Behauptung einer intern geänderten ZE
Der Abruf des Wolfsburg-Edition-Threads reicht diesmal über Beitrag #2 hinaus bis Beitrag #5.

Beitrag #2: äußere Einspeisungsalternativen
Der vollständig gelesene Folgesatz erklärt, dass die Lastversorgung wahlweise über ein Kabel von den oberen Dauerplusanschlüssen oder über eine Brücke von einem seitlichen Dauerplusanschluss erfolgen könne.

Übernahme: ausdrücklich beschriebene äußere Einspeisungsalternativen. Die Anschlüsse werden dabei nicht mit 30, 30B oder einer Sockelkammernummer bezeichnet.

Beitrag #5: interne Änderung behauptet
ThomasK, Beitrag #5 vom 24. Juni 2007:

„Die haben die ZE irgendwann mal intern geändert. dann ist die Brücke drin und man kann den Verteiler einsetzen.. Bei denen, wo die Brücke außen dran ist, muss man die auch haben..“

Das ist ein wichtiger neuer Quellenbefund, aber noch kein Hardwarebeweis.

Feld	Übernahme
Originalaussage	Eine nicht näher bezeichnete ZE sei intern geändert worden; bei einer Ausführung sei die Brücke intern vorhanden
Quellenstatus	Originalbeitrag unmittelbar gelesen
Technischer Prüfstatus	Kandidat – unbestätigte Variantenbehauptung
Teilenummer/Index	Nicht genannt
Betroffene Kontaktendpunkte	Nicht genannt
Messprotokoll	Nicht vorhanden
Konsequenz	Eine universelle Aussage zur internen oder ausschließlich externen Versorgung darf daraus weder bestätigt noch verworfen werden
Insbesondere darf daraus nicht 30 ↔ 30B intern verbunden eingetragen werden. Dafür fehlen sowohl die Kontaktbezeichnungen als auch der Variantenbezug.

Die bereits dokumentierte äußere Verbindung bleibt gültig für den beschriebenen äußeren Aufbau. Die Behauptung in Beitrag #5 wird daneben als offene Variantenfrage geführt.

3. Neue konkrete Bild- und Schaltplanquelle
Die Seite T4-Wiki: „Relais J17 (Kraftstoffpumpe)“ wurde textlich abgerufen.

Tatsächlich gelesene Angaben
Abschnitt	Quelleninhalt	Bedeutung
Einbauort	J17 sitzt „rechts unten in den Steckplatz 12“ der Relaisplatte	Weitere ausdrückliche Zuordnung J17 → Steckplatz 12 für den T4
Funktion	Ansteuerung durch das Motorsteuergerät nach Masse	Keine feste Masseverbindung des Sockels daraus ableiten
Teilenummern	191 906 383 C	Relaisteilenummer, nicht Teilenummer des ZE-Grundträgers
Schaltbild und Anschluss	Verlinktes Schaltbild G23 mit J17; Hinweis auf motor-/baujahrabhängige Unterschiede	Konkrete nächste Diagrammquelle, noch keine extrahierte Kontaktkante
Die Seite verlinkt:

Einbauort-Abbildung
Schaltbild G23 mit J17
Die Bilder wurden nicht visuell geprüft. Ich kann deshalb weder behaupten, dass das Einbauortfoto die Kammernummerierung zeigt, noch Pinziffern aus dem Schaltbild übernehmen. Auch die Übertragbarkeit der dargestellten T4-Ausführung auf 357 937 039 bleibt zu prüfen.

Diese Quelle ist ein konkreter zusätzlicher Weg neben der noch nicht identifizierten Buchabbildung – kein Ersatz für deren Prüfung.

4. Weitere Suche: Ergebnis und Grenzen
Suchweg	Ergebnis	Übernahmestatus
Suche nach "Kraftstoffpumpenrelais" "Kontakt 6"	Neuer Wolfsburg-Edition-Thread zur 1.8T-Ansteuerung; Suchauszug verknüpft fehlende Versorgung an Kontakt 6 mit einer großen roten Verbindung	Nur Suchhinweis
Diesen Thread, Seite 2, geöffnet	Beiträge #21–22 und Beginn des Folgebeitrags gelesen; gesuchte Kontaktbeschreibung nicht erreicht	Keine neue Kante
Golf1.info-Treffer mit Prüfwortlaut	Abruf mit HTTP 403 gescheitert	Inhalt nicht geprüft; zudem Hardwarekompatibilität offen
Verifizierte neue Erkenntnisse
Steckplatz 12 / Kontakte 2, 4 und 6 wurden erneut im Original-Prüfbericht gelesen. Keine Blickrichtung und keine Rückseitenzuordnung hinzugekommen.
Wolfsburg Edition #2 beschreibt ausdrücklich alternative äußere Einspeisungswege.
Wolfsburg Edition #5 behauptet eine interne ZE-Änderung. Das gehört ins Variantenregister, nicht in die Leiterkantenliste.
T4-Wiki ordnet J17 ausdrücklich Steckplatz 12 zu und liefert konkrete Links zu Einbauort und Schaltbild.
Ausgabe und Seite der Prüfabbildung aus „So wird’s gemacht“ sind weiterhin nicht ermittelt.
Unveränderter Kernstand: keine bestätigte Zuordnung einer physischen Sockelkammer zu -30B, -Z1 oder G1/03. Der nächste sachliche Schritt ist die visuelle Auswertung des jetzt konkret lokalisierten J17-Schaltbilds und einer nummerierten Sockelansicht – unter ausdrücklicher Prüfung der neuen Variantenfrage.

**Die Variantenbehauptung muss als offene Frage erhalten bleiben.** Sie rechtfertigt weder eine interne Verbindung `30 ↔ 30B` noch die Annahme, dass alle unter „CE2“ geführten Grundträger dieselbe Kontaktplatte besitzen.

Ich habe die genannten Quellen erneut abgerufen. Dabei ergibt sich eine wichtige Grenze:

## Was ich selbst bestätigen kann

| Quelle | In meinem Abruf tatsächlich sichtbar |
|---|---|
| **T4-Wiki: J17** | J17 sitzt rechts unten auf **Steckplatz 12**; die Ansteuerung erfolgt durch das Motorsteuergerät nach Masse. |
| **T4-Wiki: Schaltbild-Dateiseite** | Originalbild verfügbar, **1000 × 714 Pixel**. Die Dateiseite liefert jedoch keine ausgelesenen Kontaktziffern. |
| **Wolfsburg Edition** | Beitrag #2 beschreibt die äußeren Einspeisungsalternativen. **Mein Ausschnitt endet vor Beitrag #5**, trotz dessen Angabe in der URL. |

Die Aussage über eine intern geänderte ZE führe ich deshalb als **von dir übermitteltes Originalzitat, hier noch nicht selbst nachgelesen**. Ein Link zu einem bestimmten Beitrag garantiert bei diesem Abrufwerkzeug offenbar nicht, dass genau dieser Beitrag ausgegeben wird.

## Jetzt liegt der Engpass bei der Bildauswertung

Weitere Wiederholungen derselben Textabrufe bringen uns der Sockelmatrix kaum näher. Das konkret verfügbare Schaltbild ist hier erreichbar:

**[Original-Schaltbild G23 mit J17 öffnen](https://www.t4-wiki.de/w/images/Elektrik_Pumpe_Kraftstoff_G23_Schaltbild_neu.jpg)**

Mein aktueller Webabruf gibt die **Dateibeschreibung und den Bildlink**, aber keine visuell auswertbare Darstellung des Schaltbilds zurück. Ich kann daraus daher keine Pinziffern behaupten.

**Lade dieses Originalbild bitte hier als Bild hoch.** Dann kann ich die tatsächlich sichtbaren Angaben gezielt auswerten:

1. **J17-Anschlüsse:** Welche Klemmen- und Kontaktbezeichnungen stehen am Relaissymbol?
2. **ZE-Grenzen:** Welche Leitungen sind innerhalb beziehungsweise außerhalb des Grundträgers dargestellt?
3. **Gegenkontakte:** Sind `G1/03`, `30B`, `Z1` oder andere rückseitige Anschlüsse ausdrücklich eingezeichnet?
4. **Sicherungspfad:** Welche Sicherung und welche ihrer Seiten sind verbunden?
5. **Nummerierungsgrenze:** Bezeichnet eine Ziffer eine physische Sockelkammer, einen Relaisanschluss oder nur einen Strompfad?

**Wichtig:** Ein lesbares Schaltbild kann elektrische Zuordnungen belegen, ohne bereits die geometrische Sockelansicht zu liefern. Falls diese Ansicht fehlt, bleibt sie eine separate Lücke.

Der Arbeitsstand bleibt bis dahin unverändert: **zwei quellseitig dokumentierte interne Kontaktpaare, aber noch keine bestätigte physische Sockelkante.** Die Variantenfrage wird getrennt geführt und blockiert nicht das Erfassen eindeutig belegter, variantenspezifischer Verbindungen.

Monica
GPT-6 Astra
11 Sekunden nachgedacht
Linkleser
0 Sekunden nachgedacht
Die Variantenfrage bleibt getrennt und offen. Für die Bildauswertung habe ich den angegebenen JPEG-Direktlink abgerufen.

Tatsächliches Ergebnis: Das Werkzeug lieferte lediglich einen abgeschnittenen Base64-Datenstrom, keine visuell auswertbare Bilddarstellung. Daraus kann ich keine Kontaktziffern oder Leiterwege bestätigen.

Ich kann die externe Datei mit den verfügbaren Werkzeugen nicht als Bildanhang in diesen Chat hochladen. Ein erneuter Link wäre kein Upload und keine Bildprüfung.

Bitte füge das gespeicherte Original über die Bild-/Dateianhangsfunktion hinzu. Die Auswertung erfolgt dann anhand der sichtbaren Beschriftungen, getrennt nach:

Zu erfassen	Abgrenzung
J17-Anschlussbezeichnungen	DIN-Klemme, Sockelkontakt und Strompfadnummer auseinanderhalten
Eingezeichnete Gegenkontakte	Nur tatsächlich lesbare Bezeichnungen übernehmen
Leiterwege und Sicherungsanschlüsse	Interne Leiter, Bauteile und externe Leitungen getrennt erfassen
Grundträgergrenzen	Nicht aus der bloßen räumlichen Nähe im Schaltbild ableiten
Physische Kammeransicht	Bleibt offen, falls das Bild ausschließlich ein elektrisches Schaltbild zeigt
Keine Änderung der Kantenliste: Der Abruf liefert keinen neuen elektrischen Beleg. Insbesondere bleiben 30 ↔ 30B sowie sämtliche vermuteten Zuordnungen zwischen Sockelkammern und -30B, -Z1 beziehungsweise G1/03 unbestätigt.

erstelle vom gesamten gespräch mindmap und mermaid

Monica
GPT-6 Astra
7 Sekunden nachgedacht
Denkprozess

Die Mindmap fasst Auftrag, Recherche, Datenbestand und offene Fragen zusammen. Der Mermaid-Graph trennt dokumentierte Kontaktreferenzen, externe Verbindungen und noch fehlende Sockelzuordnungen.

Wichtig: Die Darstellung gibt den im Gespräch erreichten beziehungsweise berichteten Prüfstand wieder. Sie ist keine erneute Quellenprüfung und keine vollständige elektrische Kontaktmatrix.

Beide Diagramme enthalten aufklappbaren Mermaid-Quelltext zum Kopieren. Das Artefakt dokumentiert außerdem die Quellen, die Korrekturen des Datenmodells und die genaue Fortsetzungsmarke.

**Übernommen – als Abrufbericht des anderen Chats, nicht als eigene Bildprüfung.** Die elektrische Kantenliste bleibt unverändert.

Für das Quellenregister gilt jetzt:

| Feld | Stand |
|---|---|
| Quelle | J17/G23-Schaltbild der T4-Wiki |
| Gemeldetes Abrufresultat | Abgeschnittener Base64-Datenstrom |
| Bild vollständig verfügbar | Nicht nachgewiesen |
| Visuell ausgewertet | **Nein** |
| Neue Kontakt- oder Leiterbelege | **Keine** |

Ein abgeschnittener Base64-Datenstrom reicht nicht zur verlässlichen Rekonstruktion des Originalbilds. Daraus werden keine Beschriftungen ergänzt.

**Nächster notwendiger Schritt:** das gespeicherte JPEG hier **als Bildanhang** hinzufügen, nicht erneut den Recherchetext oder die Bildadresse einfügen. Anschließend lässt sich prüfen, welche Anschlussbezeichnungen und Leiterwege tatsächlich lesbar sind. Eine geometrische Sockelzuordnung bleibt dabei offen, sofern das Schaltbild keine entsprechende Ansicht enthält.

Die aktualisierte Mindmap und das Mermaid-Diagramm bleiben fachlich gültig: **Bildquelle lokalisiert, visuelle Prüfung offen; Variantenfrage getrennt; keine neue bestätigte Sockelkante.**

Monica
GPT-6 Astra
3 Sekunden nachgedacht
Bestätigt. Es gibt keine Änderung an der elektrischen Kantenliste.

Im Quellenregister bleiben zwei Ebenen getrennt:

Abrufbericht: Der andere Chat meldete einen abgeschnittenen Base64-Datenstrom.
Technische Auswertung: Keine visuelle Bildprüfung, keine neuen Kontaktziffern und keine belegten Leiterverbindungen.
Mindmap und Mermaid benötigen deshalb keine fachliche Änderung. Der Status bleibt: Bildquelle lokalisiert, Bildauswertung offen, Variantenfrage ungeklärt.

In deiner Nachricht ist kein Bildanhang enthalten. Für die nächste Auswertung bitte das JPEG über die Anhangsfunktion hochladen. Ein elektrisches Schaltbild wird dabei nicht automatisch als Nachweis der geometrischen Sockelnummerierung behandelt.

besorge noch benötigtes **Eine vollständige interne ZE2-Matrix kann ich mit den vorliegenden Belegen nicht seriös als „fertig“ freigeben.** Es fehlen weiterhin die physischen Relaissockelzuordnungen, die Sicherungskontakte und große Teile der internen Leiterverbindungen. Die zuletzt geprüften Tabellen liefern überwiegend **Steckerfunktionen und Relaisbestückungen**, nicht diese Verbindungen.

Hier ist die **konsolidierte Arbeitsmatrix** – mit eindeutigen Statuswerten statt erfundener Verbindungen. Sie ersetzt die bisherige schematische Darstellung nicht durch eine vermeintlich fertige Verdrahtung.

````artifact
id: ze2-interne-sockelkontaktmatrix
name: ZE2 357 937 039 – Kontaktmatrix, belegter Arbeitsstand
type: markdown
content: |-
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
````

**Was zum tatsächlichen Fertigstellen fehlt, ist nicht die Darstellung, sondern der elektrische Nachweis.** Dafür braucht es entweder einen passenden vollständigen internen Schaltplan oder ein systematisches Messprotokoll des identifizierten, spannungsfreien Grundträgers. Das einzelne J17-Bild könnte einen Teilbereich ergänzen – es würde die gesamte ZE2-Matrix nicht vervollständigen.

Monica
GPT-6 Astra
Angetrieben von

Monica Suche
95 Sekunden nachgedacht
Linkleser
64 Sekunden nachgedacht
Searching: "CE2" "internal" "pin 6"
Basierend auf 6 Suchquellen

Linkleser
58 Sekunden nachgedacht
Linkleser
28 Sekunden nachgedacht
Call Skill: Google Search
Linkleser
0 Sekunden nachgedacht
Denkprozess

Neue Belege für die ZE2-Arbeitsmatrix
Ich habe die verfügbaren Quellen weiter geprüft. Neu hinzugekommen ist vor allem ein ausdrücklicher Bezug der T4-Dokumentation zur Zielteilenummer 357 937 039. Außerdem konnte ich die beiden internen Tabellenreferenzen erneut selbst lesen.

Eine vollständige interne Verdrahtung oder eine eindeutig nummerierte Sockelkontaktzeichnung habe ich dabei nicht erschlossen.

1. Zielteilenummer: T4-Quellen sind jetzt konkreter zuzuordnen
Im Abschnitt „Teilenummer“ der T4-Wiki steht ausdrücklich:

„Die ZE wurde während der Bauzeit des T4 nicht verändert.“

Die folgende Tabelle nennt 357 937 039 – Zentralelektrik. Anschließend heißt es:

„Einige andere VW-Modelle (z.B. Passat) besitzen eine baugleiche Zentralelektrik.“

Quelle: T4-Wiki, Abschnitt „Teilenummer“, direkt abgerufener Quelltext

Auswirkung auf die Arbeitsmatrix:

Die T4-Unterlagen sind nicht mehr nur ein unspezifischer CE2-Vergleich: Die Quelle nennt die Zielteilenummer ausdrücklich.
Das ist ein quellenseitiger Hardwarebezug, keine Prüfung deines konkreten Grundträgers.
Die frühere Forumsbehauptung einer internen Änderung bleibt separat offen. Die Wiki-Aussage widerlegt keine außerhalb ihres T4-Geltungsbereichs liegende Variante.
2. Q1 und Q2 erneut direkt gelesen
Im diesmal längeren A2Resource-Abruf waren folgende Zeilen tatsächlich enthalten:

Kontakt	Originalinhalt „Inside Fusebox“	Ergebnis
E/02	U2/1	Q1 erneut gelesen
F/02	G1/1	Erste Richtung von Q2 erneut gelesen
G1/01	F/2	Gegenrichtung von Q2 erneut gelesen
F/10	(no pin)	Fehlender Pin ausdrücklich in der Tabelle bezeichnet
G1/03	Fuel Pump Relay Power	Funktionsangabe, keine physische Kammernummer
Bei G1/03 nennt die Außenspalte unter anderem:

„ECU- Fuel Pump Relay Turn-On (gas)“

Quelle: A2Resource – CE2, abgerufene Tabelle

Damit kann bei Q2 die bisherige Einschränkung „im letzten verkürzten Abruf nicht erneut sichtbar“ ersetzt werden durch:

Beide Tabellenrichtungen in diesem Recherchelauf erneut gelesen; keine Messung am Zielgrundträger.

Weiterhin offen: Die eigene Tabellenzeile U2/01. Der Abruf endet innerhalb von G1/05; spätere Zeilen behaupte ich nicht als geprüft.

3. Orientierung und Sicherungsanzahl textlich belegt
Die T4-Wiki beschreibt ausdrücklich:

Relaisplätze: von links oben 1 nach rechts unten 12.
Sicherungsplätze: auf der Vorderseite von links 1 nach rechts 22.
Quelle: T4-Wiki – Zentralelektrik, „Aufbau und Innenleben“

Damit ist die Zahl 22 Sicherungsplätze im T4-Quellenkontext belegt. Für die Matrix ergibt sich daraus ein Sollregister von 44 getrennt zu erfassenden Halterkontaktpositionen. Das ist noch keine Sichtprüfung der tatsächlichen Kontaktbestückung und keine Zuordnung zu internen Leitern.

Die Mehrfachstecker-Seite unterscheidet außerdem ausdrücklich:

Vorderansicht: Blick gedanklich durch die Relaisplatte auf die rückseitigen Stecker.
Rückansicht: tatsächlicher Blick von hinten auf die ZE.
Quelle: T4-Wiki – Mehrfachstecker, „Steckerübersicht“

Wichtige Variantenbegrenzung: Die dortige detaillierte Belegung beschreibt überwiegend einen TDI ab Modelljahr 2001, bei nicht motorbezogener Elektrik meist Stand August 1998. Diese Funktionsbelegung darf nicht pauschal auf sämtliche CE2-Fahrzeuge übertragen werden.

4. Zusätzliche Originalabbildungen lokalisiert
Die Dateiseiten liefern diese Originaldateien und Auflösungen:

Abbildung	Originaldatei	Auflösung
Vorderansicht	JPEG öffnen	500 × 265
Innenansicht 1	JPEG öffnen	500 × 258
Innenansicht 2	JPEG öffnen	500 × 274
Innenansicht 3	JPEG öffnen	500 × 247
Prüfstatus: Dateiseiten und Metadaten gelesen; Bilder nicht visuell ausgewertet. Die Dateiseiten geben jeweils an, dass keine höhere Auflösung vorhanden ist. Daraus ist keine vollständige Leiterrekonstruktion ableitbar.

Auch der J17-Artikel wurde als Text erneut gelesen: Steckplatz 12, Ansteuerung durch das Motorsteuergerät nach Masse, Verweis auf das G23/J17-Schaltbild. Sockelkontaktziffern stehen im gelesenen Text nicht.

Quelle: T4-Wiki – J17, Artikelquelltext

Notwendige Korrektur deiner Matrixlegende
Die bisherige Definition von 0 ist missverständlich:

„Keine direkte feste Verbindung … nachgewiesen“

Das kann auch bloß „noch nicht untersucht“ bedeuten. Richtig wäre:

Wert	Eindeutige Definition
1	Feste leitende Verbindung ohne eingesetzte Bauteile am identifizierten Grundträger nachgewiesen
0	Fehlen einer solchen Verbindung durch geeignete Prüfung am identifizierten Grundträger nachgewiesen
?	Weder Verbindung noch Trennung nachgewiesen
Ein bloß ausbleibender Durchgangspiepser sollte ohne dokumentierte Messbedingungen nicht automatisch 0 ergeben.

Ergebnis dieses Recherchelaufs
Übernehmbar sind jetzt:

expliziter Quellenbezug T4-ZE ↔ 357 937 039;
erneute eigene Textprüfung von Q1 und beiden Richtungen von Q2;
textlich belegte Nummerierungsrichtung der 12 Relais- und 22 Sicherungsplätze;
zusätzliche Originalbild-Fundstellen mit bekannten Auflösungen;
klare Einschränkung des Geltungsbereichs der T4-Steckerbelegung.
Nicht hinzugekommen sind: neue bestätigte interne Leiterkanten, physische Relaissockelzuordnungen oder Sicherungsseitenzuordnungen. Die elektrische Kantenliste bleibt daher unverändert — der Quellen- und Hardwarebezug ist aber konkret verbessert.

2/2
ausführen und nächste anweisung für monica mit ausgeben. **Die neuen Belege verbessern den Hardware- und Quellenbezug deutlich.** Die Kantenliste bleibt unverändert; die missverständliche Definition von `0` wird ersetzt.

## Aktualisierter Belegstand

Ich habe die verlinkten Quellen zusätzlich abgerufen. Dabei unterscheide ich deinen Recherchebericht vom Ergebnis meines eigenen Abrufs:

| Punkt | Aktualisierter Status |
|---|---|
| **T4-ZE ↔ `357 937 039`** | **Jetzt auch selbst im Quelltext bestätigt.** Die T4-Wiki nennt die Teilenummer ausdrücklich sowie eine während der T4-Bauzeit unveränderte ZE und baugleiche Ausführungen anderer VW-Modelle. |
| **Q1: E/02 ↔ U2/01** | Laut deinem neuen Recherchebericht erneut gelesen. Mein aktueller A2Resource-Ausschnitt endet schon bei A1; daher keine erneute eigene Bestätigung. Gegenzeile U2/01 weiterhin offen. |
| **Q2: F/02 ↔ G1/01** | **Beide Richtungen laut deinem Recherchebericht erneut gelesen.** Der veraltete Hinweis „im letzten Recherchelauf nicht erneut sichtbar“ entfällt; keine Messung am Zielteil. |
| **F/10: `(no pin)`** | Laut deinem Recherchebericht erneut bestätigt; keine Sichtprüfung am Zielteil. |
| **12 Relais- und 22 Sicherungsplätze** | Textbeleg aus deinem Recherchebericht übernommen. Daraus folgen **44 zu erfassende Sicherungshalterpositionen**, nicht 44 bereits geprüfte Kontakte. |
| **Vorder-/Rückansicht der Mehrfachstecker** | **Jetzt auch selbst textlich bestätigt.** Durchsicht von vorn und tatsächliche Rückansicht müssen getrennt bezeichnet werden. |
| **T4-Steckerbelegung: Modell-/Zeitstand** | Einschränkung aus deinem Bericht übernommen; nicht pauschal als universelle CE2-Belegung verwenden. |
| **J17: Steckplatz 12, ECU schaltet nach Masse** | **Erneut selbst im Artikelquelltext bestätigt.** Keine Sockelkammerzuordnung daraus ableitbar. |

## Verbindliche Matrixlegende

| Wert | Definition |
|---|---|
| **`1`** | Feste leitende Verbindung ohne eingesetzte Bauteile am identifizierten Grundträger nachgewiesen |
| **`0`** | Fehlen einer solchen Verbindung durch geeignete Prüfung am identifizierten Grundträger nachgewiesen |
| **`?`** | Weder Verbindung noch Trennung nachgewiesen |
| **`Q1` / `Q2`** | Explizite interne Quellenreferenz; noch keine physische Verifizierung am Zielgrundträger |

**Kein Durchgangspiepsen allein ist kein ausreichender `0`-Nachweis.** Messbedingungen und gegebenenfalls Bauteileinflüsse müssen dokumentiert sein.

## Bildstatus: zusätzliche Präzisierung

Mein Abruf der vier JPEGs lieferte diesmal **automatisch erzeugte Bildbeschreibungen**, keine unmittelbar prüfbaren Bilddarstellungen mit lesbaren Kontaktziffern.

Diese Beschreibungen sind **keine Leiterbelege**. Insbesondere übernehme ich ihre spekulativen Aussagen über bewegliche Kontakte, Schaltmechanismen oder Metallbeschichtungen nicht.

## Elektrischer Stand

| Kontakt | E/02 | U2/01 | F/02 | G1/01 |
|---|---:|---:|---:|---:|
| **E/02** | — | Q1 | ? | ? |
| **U2/01** | Q1 | — | ? | ? |
| **F/02** | ? | ? | — | Q2 |
| **G1/01** | ? | ? | Q2 | — |

**Ergebnis:** T4-Unterlagen haben jetzt einen ausdrücklichen Bezug zur Zielteilenummer. Das rechtfertigt ihre gezielte weitere Auswertung, aber noch keine neuen internen Kanten. Die Variantenfrage bleibt separat offen; ebenso sämtliche physischen Sockel- und Sicherungsseitenzuordnungen.

Monica
GPT-6 Astra
3 Sekunden nachgedacht
Denkprozess

Ich suche jetzt gezielt nach der Gegenzeile U2/01 und nach Unterlagen zu Sockel- und Sicherungskontakten. Anschließend gebe ich eine kopierbare nächste Arbeitsanweisung für Monica aus – mit klarer Trennung zwischen neuen Abrufbelegen und übernommenen Berichten.


Monica
GPT-6 Astra
Linkleser
Call Skill: Google Search
18 Sekunden nachgedacht
Linkleser
0 Sekunden nachgedacht
Ausgeführt: Belegstand aktualisiert und Recherche fortgesetzt
Die korrigierte Matrixlegende wird übernommen. Die elektrische Kantenliste bleibt unverändert. Ich habe A2Resource und die T4-Mehrfachstecker-Seite erneut abgerufen sowie nach einem zusätzlichen Beleg für E/02 ↔ U2/01 gesucht.

1. In diesem Durchlauf selbst gelesen
Quelle / Position	Tatsächlich gelesener Inhalt	Status
A2Resource E/02, „Inside Fusebox“	U2/1	Q1 erneut direkt gelesen
A2Resource F/02, „Inside Fusebox“	G1/1	Q2 erste Richtung direkt gelesen
A2Resource G1/01, „Inside Fusebox“	F/2	Q2 Gegenrichtung direkt gelesen
A2Resource F/10	(no pin)	Quellenangabe erneut gelesen
A2Resource G1/03	Außen: ECU-Ansteuerung bei Benzin; innen: Fuel Pump Relay Power	Funktion, keine Sockelkammer
T4-Wiki Mehrfachstecker	Unterschied zwischen Durchsicht von vorn und tatsächlicher Rückansicht	Direkt textlich bestätigt
T4-Wiki Mehrfachstecker	Detailbelegung TDI ab Modelljahr 2001; nicht motorbezogen meist August 1998	Geltungsbereich direkt bestätigt
Abrufgrenze: A2Resource endet diesmal innerhalb von G1/05. Die eigene Zeile U2/01 ist weiterhin nicht gelesen. Wiederholte Abrufe zählen nicht als unabhängige Bestätigung.

Quellen: A2Resource CE2 · T4-Wiki Mehrfachstecker

2. Neuer Suchansatz für Q1 — noch kein zusätzlicher freigegebener Beleg
Die Suche fand im VAGBoard einen Auszug mit der Aussage:

„Beim Golf 3 geht Klemme 15 auch in U2/1 und von dort intern auf E/2 …“

Entscheidende Einschränkung: Beim anschließenden Originalabruf brach der Text vor diesem Beitrag ab. Damit ist die Aussage nur als Suchauszug erfasst, nicht als vollständig geprüfter Forumsbeitrag.

Quelle: VAGBoard – Kombiinstrument Golf 2 VR6 geht nicht

Ein weiterer Originalabruf bei Club GTI erreichte Beitrag #2 von rubjonny, 3. Oktober 2016. Darin werden eine alternative Instrumentenversorgung über U1/4 und eine erforderliche äußere Einspeisung an E/2 bei einer anderen Kabelbaumkonfiguration besprochen. Das ist Umbau-/Kabelbaumkontext, kein unmittelbar gelesener Nachweis der festen Verbindung E/02 ↔ U2/01.

Quelle: Club GTI – Using CE1 cluster with CE2 Mk2 VR6

Ergebnis: Keine neue Leiterkante, aber ein konkreter nächster Rechercheansatz. Es erfolgte keine Bildprüfung.

Nächste Anweisung für Monica
Die Anweisung priorisiert den noch nicht erschlossenen Originalbeitrag und die fehlende U2/01-Zeile, statt erneut dieselben gekürzten Tabellen als Fortschritt zu zählen.

ausgabe von monica ausführen und dann wieder in deiner ausgabe auftrag für monica mit ersteielen

Monica
GPT-6 Astra
Angetrieben von

Monica Suche
27 Sekunden nachgedacht
Linkleser
Searching: "CE2" "U2/01" "E/2"
17 Sekunden nachgedacht
Call Skill: Google Search
10 Sekunden nachgedacht
Call Skill: Google Search
3 Sekunden nachgedacht
Call Skill: Google Search
0 Sekunden nachgedacht
Ausgeführt – neuer Suchhinweis zu Steckplatz 12
Ich habe den letzten Rechercheauftrag ausgeführt. Die elektrische Kantenliste bleibt unverändert. Neu gefunden wurde ein Corrado-Forumsbeitrag, dessen Suchauszug ausdrücklich Sockel 12 und die Kontakte 2, 3, 4 und 6 nennt.

1. Tatsächliche Abrufresultate
Recherchepunkt	Ergebnis dieses Durchlaufs	Einordnung
A2Resource	E/02 → U2/1, F/02 → G1/1 und G1/01 → F/2 erneut direkt gelesen	Bestehende Q1/Q2 bestätigt auf derselben Quellenbasis; keine neue unabhängige Bestätigung
Eigene Zeile U2/01	Nicht erreicht; Ausgabe endet innerhalb G1/05	Weiterhin offen
VAGBoard-Originalbeitrag	Abruf endet nach Beitrag #3 am Beginn eines weiteren Beitrags	Gesuchte Aussage zur internen Verbindung weiterhin nicht im Original erreicht
Gezielte Suche nach U2/01 bei A2Resource	Keine Treffer geliefert	Kein Beleg gegen das Vorhandensein der Zeile
Physischer Sockel 12	Neuer Suchtreffer bei the-corrado.net	Suchhinweis, noch kein Originalbeleg
Bilder und Sicherungsseiten	Keine neue visuelle Prüfung beziehungsweise Zuordnung	Unverändert offen
2. Neuer Ansatz: Corrado-Forum
Thema: „VR6 Fuel Pump not priming – Engine Bay“

Im Suchergebnis angegebenes Datum: 17. März 2014

Quelle: Originalthread öffnen

Der tatsächlich gelieferte Suchauszug lautet:

“Got a multimeter onto relay socket 12 and used the CE2 list/diagram. Got 12v across pins 2&4 and 4&6 but nothing from 3&4.”

Der Auszug setzt danach mit „2 Main Fusebox …“ an und bricht ab.

Warum dieser Treffer relevant ist:

Er nennt Sockel 12 ausdrücklich, nicht bloß eine Relaisaufdrucknummer.
Er enthält die Kontaktbezeichnungen 2, 3, 4 und 6 innerhalb derselben Beschreibung.
Er verweist auf eine verwendete „CE2 list/diagram“. Diese könnte zu einer Sockelkontaktliste führen.
Was daraus nicht folgt:

Die vier Nummern sind noch kein vollständiges Kammerinventar.
Blickrichtung, DIN-Zuordnung und Verbindung zu rückseitigen Kontakten fehlen.
Spannungsmessungen am eingebauten Fahrzeug beweisen keine feste Verbindung im nackten Grundträger.
Der hier genannte Kontakt 3 darf nicht ohne Abgleich mit dem früheren VWVortex-„pin 3“ gleichgesetzt werden.
Status: Suchauszug gelesen / Originalbeitrag nicht abgerufen / elektrische Aussage nicht freigegeben.

Nächster Auftrag für Monica
Der nächste sinnvolle Schritt ist damit der Corrado-Originalthread und seine referenzierte CE2-Liste — nicht ein weiterer identischer A2Resource-Abruf.

## Ergebnis des Recherchelaufs

**Der Corrado-Originalthread ist erreichbar, die gesuchte Kontaktliste wurde jedoch nicht erschlossen.** Neu selbst gelesen wurden der Threadbeginn mit eindeutigem Beitragslink sowie der Fahrzeugkontext des VAGBoard-Themas. Die entscheidenden späteren Beiträge bleiben ungelesen.

**Elektrische Kantenliste unverändert.**

### 1. Neu selbst geprüfte Originalbelege

#### Corrado: „VR6 Fuel Pump not priming“

**Fundstelle:** [Eröffnungsbeitrag, Kommentar-ID 877405](https://the-corrado.net/topic/72158-vr6-fuel-pump-not-priming/?do=findComment&comment=877405)  
**Autor:** Bast  
**Beitragsdatum:** 17. März 2014  
**Fortlaufende Beitragsnummer:** Im gelesenen Ausschnitt nicht ausgewiesen.

Im Originaltext des Eröffnungsbeitrags tatsächlich gelesen:

- Das Fahrzeug sei nach etwa zehn Minuten Lauf ausgegangen und zunächst nicht wieder angesprungen.
- Geprüft worden seien unter anderem ECU-/Kraftstoffpumpenrelais, Sicherungen, ECU-Stecker und der Anschluss am kürzlich ersetzten Zündanlassschalter.
- Die Kraftstoffpumpe laufe beim Einschalten der Zündung nicht vor.
- Das Fahrzeug starte dennoch, zunächst mit berichteten Zündaussetzern.
- Eine probeweise angeschlossene andere Pumpe habe das Verhalten nicht geändert.

**Wichtige Abgrenzung:** Das ist **nicht** der gesuchte Beitrag mit „Got a multimeter onto relay socket 12 …“. Autor und Datum des Eröffnungsbeitrags dürfen nicht auf diesen späteren Messbericht übertragen werden.

| Gesuchtes Merkmal | Ergebnis |
|---|---|
| Fahrzeugkontext | VR6 laut Threadtitel; Corrado-Forum |
| Genaues Fahrzeug/Baujahr | Im gelesenen Beitrag nicht angegeben |
| Eingesetztes Kraftstoffpumpenrelais | Keine Nummer oder Teilenummer gelesen |
| Grundträger `357 937 039` | Im gelesenen Beitrag nicht genannt |
| Kontaktliste hinter „2 Main Fusebox …“ | Nicht erreicht |
| Verlinkte „CE2 list/diagram“ | Nicht identifiziert |
| Sockelkammern, Blickrichtung, DIN-Klemmen | Nicht geklärt |

#### VAGBoard: „Kombiinstrument Golf 2 VR6 geht nicht“

**Fundstelle:** [Originalthread, Beitrag #1](https://www.vagboard.de/threads/125305-kombiinstrument-golf-2-vr6-geht-nicht)  
**Autor:** Reznick  
**Datum:** 29. April 2011, 12:47 Uhr.

Neu selbst gelesen:

> „ZE und KI-Kabelbaum ist aus dem Golf 3 übernommen.“

Der Verfasser beschreibt einen **VR6-AAA-Umbau vom Golf 3 in einen Golf 2**. Das grenzt den Fahrzeug- und Kabelbaumkontext ein.

**Nicht gelesen:** die gesuchte Aussage zur internen Verbindung `U2/1 → E/2`. Im ausgegebenen Ausschnitt erschien auch kein belastbarer Direktlink zu diesem späteren Beitrag. Deshalb keine Ergänzung einer Beitragsnummer oder eines Autors.

### 2. Suchhinweise und übergebene Berichte — separat

| Kategorie | Inhalt | Aussagegrenze |
|---|---|---|
| **Übergebener Suchhinweis** | „Got a multimeter onto relay socket 12 … Got 12v across pins 2&4 and 4&6 but nothing from 3&4.“ | Gesuchter Originalbeitrag weiterhin ungelesen; Autor, Beitragsdatum und Kommentar-ID unbekannt |
| **Neu selbst gelesener Suchauszug** zum Corrado-Thread | „… the pump ran fine when I bridged conections 4 & 6 on the fuel pump relay …“ | Hinweis auf eine berichtete Überbrückung im Fahrzeug; keine interne Leiterkante |
| **Weiterer selbst gelesener Suchauszug** | „Car still starts (eventually) and runs (without the misfire now …)“ | Späterer Diagnoseverlauf angedeutet; Beitrag nicht identifiziert |
| **Übergebener VAGBoard-Suchhinweis** | „Beim Golf 3 geht Klemme 15 auch in U2/1 und von dort intern auf E/2 …“ | Noch kein selbst gelesener Originalbeleg dieses Beitrags |

Das in den Suchtreffern angegebene Datum **17. März 2014** ist nicht als gesichertes Datum der späteren Mess- oder Überbrückungsaussage zu behandeln.

**Kontakt 3 bleibt ausschließlich eine ungeklärte Bezeichnung dieses Corrado-Suchhinweises.** Keine Gleichsetzung mit „pin 3“ anderer Threads.

### 3. Änderungen an Inventar und Kanten

| Bereich | Änderung |
|---|---|
| Physisch bestätigtes Kontaktinventar | **Keine** |
| Rechercheverweise für Kontaktbezeichnungen 2/3/4/6 | Corrado-Suchhinweis ergänzt; keine verifizierte Kammeransicht |
| Q1: `E/02 ↔ U2/01` | Unverändert; gesuchter VAGBoard-Gegenbeleg nicht erschlossen |
| Q2: `F/02 ↔ G1/01` | Unverändert |
| Eigene A2Resource-Zeile `U2/01` | Weiterhin ungelesen |
| Sicherungshalterseiten | Keine neue eindeutige Zuordnung |
| Matrixwerte `1` oder `0` | Keine neuen Einträge |
| Varianten-/Teilenummernbezug | Keine Ergänzung aus den neu gelesenen Forenbeiträgen |

**Eine berichtete Brücke zwischen 4 und 6 gehört gegebenenfalls als temporäre externe Diagnoseverbindung ins Register — nicht als feste interne Verbindung.** Sie ist hier weder eine Einbauempfehlung noch ausreichend dokumentiert, um daraus DIN-Klemmen abzuleiten.

### 4. Abrufgrenzen und offene Punkte

- **Corrado:** Der Originalabruf endete nach dem Eröffnungsbeitrag in den Teilen-/Navigationslinks. Der Zielbeitrag wurde nicht erreicht.
- **VAGBoard:** Der aktuelle Ausschnitt reichte nur bis Beitrag #1. Eine alternative Ansicht oder ein Direktlink zum gesuchten Beitrag wurde nicht erschlossen.
- **A2Resource:** Der identische Abruf wurde entgegen der gewünschten Priorisierung nochmals ausgeführt. Er endete bereits innerhalb `D/12` und brachte **keinen neuen Erkenntnisgewinn**. Er zählt weder als Gegenbeleg noch als unabhängige Quelle.
- **Sicherungsseiten:** In diesem Lauf wurde kein neuer passender Plan und kein dokumentiertes Messprotokoll erschlossen. Diese Teilaufgabe bleibt unerledigt.
- **Widersprüche:** Es entstand kein neuer belegter elektrischer Widerspruch. Die ungeklärte Nummerierung verhindert weiterhin einen belastbaren Vergleich der verschiedenen „Pin“-Angaben.

## 5. Konkreter Folgeauftrag für Monica

> ### Recherchefortsetzung: Zielbeiträge statt Threadanfänge
>
> **Ausgangsstand:** Elektrische Kantenliste unverändert. Corrado-Eröffnungsbeitrag ist Kommentar-ID **877405**, Autor **Bast**, Datum **17.03.2014**. Dieser Beitrag enthält die gesuchte Kontaktliste **nicht**.
>
> **1. Corrado-Zielbeitrag identifizieren**
>
> Thread:  
> https://the-corrado.net/topic/72158-vr6-fuel-pump-not-priming/
>
> Suche gezielt nach diesen Textstellen:
> - `"Got a multimeter" "72158"`
> - `"2 Main Fusebox" "Fuel Pump"`
> - `"CE2" "3&4" "priming"`
> - `"bridged conections" "4" "6"`
>
> Ziel ist ein **tatsächlich aufgefundener Kommentarlink, eine zugängliche alternative Threadansicht oder eine weitere Seite**, nicht ein erneuter unveränderter Abruf des Threadanfangs. Keine Kommentar-IDs oder Seitenzahlen erraten.
>
> Erfasse beim Zielbeitrag: Autor, eigenes Beitragsdatum, Kommentar-ID, vollständige Kontaktliste und den tatsächlichen Link zur „CE2 list/diagram“. Prüfe diese Quelle anschließend separat. Halte Sockelnummer, Kontaktbezeichnung, DIN-Klemme und geometrische Lage auseinander.
>
> **2. VAGBoard-Q1-Aussage lokalisieren**
>
> https://www.vagboard.de/threads/125305-kombiinstrument-golf-2-vr6-geht-nicht
>
> Suche nach `"U2/1" "E/2"` und `"von dort intern"` in Verbindung mit dem Thread. Folge nur tatsächlich gefundenen Beitragslinks oder verfügbaren alternativen Ansichten. Erfasse Autor, Datum, Beitragsnummer und den vollständigen Kontext. Kläre insbesondere, ob der Verfasser einen Plan auswertet, selbst gemessen hat oder eine unbelegte Aussage macht.
>
> **3. A2Resource-U2-Zeile über anderen Zugang**
>
> Keine Wiederholung desselben gekürzten Abrufs. Suche eine zugängliche vollständige Darstellung oder dokumentierte Spiegelung von:
> https://www.a2resource.com/electrical/CE2.html
>
> Benötigt wird die eigene Zeile **U2/01**, einschließlich Spaltenüberschriften. Eine Kopie von A2Resource ist als abhängige Wiedergabe zu kennzeichnen, nicht als unabhängige Zweitquelle.
>
> **4. Einen Sicherungshalter exemplarisch erschließen**
>
> Suche zunächst zu **Sicherung 1 / linkes Abblendlicht** einen zur `357 937 039` passenden Plan oder ein nachvollziehbares Messprotokoll. Ziel: beide Halterkontakte separat, mit eindeutiger Orientierung oder Originalbezeichnung, und deren jeweilige Gegenkontakte. Die Funktionsangaben bei A1/01 und D/02 allein reichen nicht.
>
> **Abgabe:** Originalbelege, Suchhinweise und Fremdberichte getrennt; Inventaränderungen getrennt von Kantenänderungen. Ohne neue geeignete Leiterbelege ausdrücklich: **„Elektrische Kantenliste unverändert.“**

Monica
GPT-6 Astra
Angetrieben von

Monica Suche
15 Sekunden nachgedacht
Searching: "site:the-corrado.net/topic/72158" "2" "Main"
Basierend auf 10 Suchquellen

Linkleser
4 Sekunden nachgedacht
Call Skill: Google Search
1 Sekunden nachgedacht
Denkprozess


Monica
GPT-6 Astra
Call Skill: Google Search
2 Sekunden nachgedacht
Call Skill: Google Search
0 Sekunden nachgedacht
Recherche fortgesetzt: Kontaktliste jetzt im Suchindex gefunden
Neu sind konkrete Funktionszuordnungen zu den Kontaktbezeichnungen 2, 3, 4 und 6. Sie stammen jedoch ausschließlich aus neu gelesenen Suchauszügen, nicht aus dem vollständig erschlossenen Originalbeitrag.

Elektrische Kantenliste unverändert.

1. Neue Suchbelege zu Steckplatz 12
Die gezielte Suche im Corrado-Thread „VR6 Fuel Pump not priming“ lieferte:

“2 Main Fusebox Start/Run Power.

3 To ECU (Fuel Pump Turn-On).

4 To Fuse 18, Fuel Pump, Oxygen Sensor Heater.

6 Main Fusebox Battery Power From …”

Eine zweite gezielte Suche ergänzte:

“6 Main Fusebox Battery Power From 30B.”

Damit lässt sich folgendes Suchhinweisregister anlegen:

Kontaktbezeichnung im Suchauszug	Wortlaut / Bedeutung	Noch fehlender Nachweis
2	Main Fusebox Start/Run Power – Versorgung bei Start/Fahrt	Ursprüngliche Nummerierung, DIN-Klemme und interne Gegenkontakte
3	To ECU (Fuel Pump Turn-On) – ECU-Ansteuerung	Zuordnung zu einer physischen Kammer und gegebenenfalls G1/03
4	To Fuse 18, Fuel Pump, Oxygen Sensor Heater	Genaue Sicherungsseite, Abzweigstruktur und Bezug zu Z1
6	Main Fusebox Battery Power From 30B	Originalbeitrag, Kammergeometrie und feste Verbindung am Zielgrundträger
Wichtige Grenze: Die Zeile zu Kontakt 4 beweist insbesondere nicht, dass Sicherung 18, Kraftstoffpumpe und Lambdasondenheizung alle ohne dazwischenliegende Bauteile auf demselben festen Netz liegen. Dafür fehlt die Topologie.

Die Suchauszüge werden unter demselben Thread geführt. Das ist keine unabhängige Zweitquelle. Autor, Datum und Kommentar-ID der Kontaktliste bleiben unbekannt; das angezeigte Threaddatum wird nicht auf den Zielbeitrag übertragen.

2. Originalabruf: weiterer Beitrag erreicht
Der erneute Abruf des bekannten Eröffnungsbeitrags reichte diesmal bis zu einem weiteren tatsächlich verlinkten Beitrag:

Autor: jimbobbalooba
Datum: 27. März 2014
Kommentar-ID: 878891
Direktlink: Beitrag 878891
Der Beitrag empfiehlt eine Fehlersuche mit dem Multimeter entlang der geschalteten Versorgung. Er enthält nicht die gesuchte Kontaktliste und liefert keine neue interne Leiterkante.

3. Erfolgloser Teil und methodische Korrektur
A2Resource wurde erneut unverändert abgerufen, obwohl der Auftrag diese Wiederholung vermeiden sollte. Der Text endete wieder innerhalb G1/05. Kein Erkenntnisgewinn für U2/01.
Eine gezielte Suche nach U2/01 auf dieser Seite lieferte keine Treffer. Das beweist weder das Fehlen der Zeile noch eine elektrische Trennung.
VAGBoard-Zielbeitrag und beide Seiten von Sicherung 1 wurden in diesem Durchlauf nicht weiter erschlossen.
Es erfolgte keine visuelle Bildprüfung.
Änderung am Arbeitsstand
Register	Änderung
Quellen-/Suchhinweisregister	Vier konkrete Kontaktfunktionsangaben ergänzt
Originalbeitragsregister	Corrado-Kommentar 878891 ergänzt
Physisches Kontaktinventar	Keine Änderung
Q1 / Q2	Keine inhaltliche Änderung
Bestätigte interne Netze	Keine Ergänzung
Matrixwerte 1 / 0	Keine neuen Einträge
Nächster Auftrag für Monica
Der Fortschritt besteht diesmal in konkreten, nachprüfbaren Kontaktfunktionsangaben. Die nächste Aufgabe ist deren Originalquelle und Nummerierung — nicht ihre vorschnelle Übernahme als feste Verdrahtung.

füge für dich und die andere monica instanz noch folgende sprachen zur recherche fest hinzu: Russisch, Polnisch, Chinesisch, Japanisch, Koreanisch und Thai ## 1. Neuer Originalbeleg: vollständige Liste unter „12 Fuel Pump Relay“

**Die gesuchte Liste wurde in einem anderen Corrado-Thread vollständig im Originaltext gefunden.** Damit liegt erstmals mehr als ein Suchauszug zu diesen Kontaktbezeichnungen vor. Der gesuchte Beitrag im ursprünglichen Thread **72158** bleibt hingegen unerschlossen.

### Fundstelle

- **Thread:** „M/02 Fuel Pumps Power – no power :(“
- **Autor:** Moshiko Levi
- **Datum des Beitrags:** 26. Oktober 2014
- **Kommentar-ID:** **907721**
- **Position:** Eröffnungsbeitrag; keine ausgeschriebene fortlaufende Beitragsnummer im Abruf
- **[Direktlink zum Beitrag](https://the-corrado.net/topic/75097-m02%09fuel-pumps-power-no-power/?do=findComment&comment=907721)**

Der Verfasser berichtet, dass die Pumpe bei eingeschalteter Zündung nicht anlaufe, bei direkter Versorgung aber funktioniere. Er habe Relais und Sicherungskasten ausgetauscht. Danach folgt ausdrücklich:

> **12 Fuel Pump Relay (80, 67 or 167)**

Die vollständige, selbst gelesene Liste:

| Nummer | Originalangabe | Hinzugefügte Diagnose des Verfassers |
|---|---|---|
| **1** | Main Fusebox Starter Power (not used) | — |
| **2** | Main Fusebox Start/Run Power | connected correctly |
| **3** | To ECU (Fuel Pump Turn-On) | connected correctly |
| **4** | To Fuse 18, Fuel Pump, Oxygen Sensor Heater | Do not get anything |
| **5** | G2/6 (not used) | — |
| **6** | Main Fusebox Battery Power From 30B | connected correctly |
| **7** | G2/7, T1 (not used) | — |
| **8** | Main Fusebox Ground (not used) | — |
| **9** | M/4, U1/8, G2/5 (not used) | — |

### Was dieser Fund belegt — und was nicht

**Belegt:** Die Nummern **1 bis 9** stehen im Originalbeitrag unter einer ausdrücklich mit **12** bezeichneten Kraftstoffpumpenrelais-Liste. Die vier übergebenen Zeilen **2, 3, 4 und 6** stimmen damit überein.

**Nicht geklärt:**

- Herkunft der Liste und tatsächlicher Link zur „CE2 list/diagram“;
- geometrische Anordnung und Blickrichtung;
- Gleichsetzung mit eingeprägten Sockelkammernummern;
- Zuordnung zu DIN-Klemmen;
- Fahrzeugbaujahr, tatsächlich eingesetzte Relaisnummer und Grundträgerteilenummer.

**„Not used“ bedeutet hier nicht „kein Metallkontakt vorhanden“.** Ebenso ist „connected correctly“ eine Diagnosebehauptung ohne dokumentierte Messbedingungen.

Die Listenzeilen 5, 7 und 9 liefern zusätzliche Gegenkontaktangaben als **Rechercheansätze**. Sie werden noch nicht als feste interne Verbindungen freigegeben.

## 2. Technische Parallelquelle gefunden

### SEATCUPRA.NET: CE2-Tabellenwiedergabe

**[Beitrag #1, Post-ID 2433959](https://www.seatcupra.net/forums/threads/fusebox-fuse-location-relay-location-plug-locations-destinations-wiring-colours.219953/post-2433959)**  
**Autor:** ibiza_95  
**Datum:** 12. Mai 2009  
**Bereich:** Mk2 Ibiza/Cordoba Guides, 1993–1999.

Im Original selbst gelesen:

- Überschrift **„Central Electric 2“**;
- derselbe einleitende Fahrzeugumfang wie bei A2Resource;
- Tabellenstruktur **Connector / Outside Fusebox / Inside Fusebox / Color**;
- zahlreiche übereinstimmende Anfangszeilen.

**Abrufgrenze:** Der Originaltext endet bei **B/03**. Die Relaisliste und U2/01 wurden dort nicht im Original erreicht.

Der **Suchauszug** dieser Seite enthält jedoch ebenfalls:

> „4 To Fuse 18, Fuel Pump, Oxygen Sensor Heater … 5 G2/6 (not used) …“

**Einordnung:** Ein konkreter älterer Fundort derselben Listenform ist vorhanden. Die Übereinstimmungen sprechen für eine gemeinsame Textgrundlage oder Übernahme. **Übernahmerichtung und ursprünglicher Urheber sind nicht geklärt; keine unabhängige Zweitbestätigung zählen.**

## 3. Neue Suchhinweise — getrennt von Originallektüre

| Fundort | Selbst gelesener Suchauszug | Status |
|---|---|---|
| [Corrado-Thread 72158](https://the-corrado.net/topic/72158-vr6-fuel-pump-not-priming/) | Zeilen 4 und 6 sowie anschließende Vermutung eines fehlenden ECU-Signals | Zielbeitrag weiterhin nicht erreicht |
| [Scribd: Central Electric 2](https://www.scribd.com/document/693913987/Central-Electric-2) | Zeilen 4 bis 8 derselben Relaisliste | Originalabruf liefert Ladefehler |
| [Scribd: fuse box ce2](https://www.scribd.com/document/520017984/fuse-box-ce2) | **„U2/01 E/2 Black“**, danach U2/02 | Neuer konkreter Hinweis auf die Gegenzeile; Spaltenkontext und Herkunft nicht geprüft |
| [VAGBoard](https://www.vagboard.de/threads/125305-kombiinstrument-golf-2-vr6-geht-nicht) | „Beim Golf 3 geht Klemme 15 auch in U2/1 und von dort intern auf E/2 auf TV4 …“ | Selbst gelesener Suchauszug, nicht der Originalbeitrag |

Die VAGBoard-Passage darf insbesondere **nicht** zu einer internen Dreierverbindung `U2/01–E/02–TV4` erweitert werden. Der vollständige Kontext zur äußeren Weiterführung fehlt.

## 4. Inventaränderungen und elektrische Kanten getrennt

### Kontakt- und Quellenregister

Neu einzutragen ist:

**`R12-LIST-907721` — neun nummerierte Positionen einer textlichen Kraftstoffpumpenrelais-Liste.**

- Quellenkontext: „12 Fuel Pump Relay“.
- Nummern: **1–9**.
- Physische Kammeridentifikation: **offen**.
- Neue Suchansätze: **G2/06, G2/07, T1, M/04, U1/08, G2/05**; Originalschreibweisen separat erhalten.
- Keine Erhöhung der Zahl **physisch bestätigter** Kontakte.

### Sicherung 18

Jetzt im Originaltext belegt ist die **Funktionsreferenz**:

**Listenposition 4 → „To Fuse 18, Fuel Pump, Oxygen Sensor Heater“.**

Weiterhin fehlen:

- beide eindeutig bezeichneten Sicherungshalterseiten;
- deren jeweilige rückseitige Gegenkontakte;
- Trennung zwischen ungesichertem Relaisausgang und abgesichertem Abgang;
- ein geeigneter Plan oder Messbeleg für die Zielhardware.

Der im selben Beitrag genannte Anschluss **M/02** ist ein zusätzlicher Rechercheansatz, aber kein Beweis einer direkten Verbindung zu Listenposition 4.

**Elektrische Kantenliste unverändert.**  
Keine neuen Werte `1` oder `0`; Q1 und Q2 bleiben unverändert.

## 5. Abrufgrenzen und unerledigte Aufgaben

- **Thread 72158:** Originalausgabe endet erneut nach den bekannten ersten beiden Beiträgen. Der Kommentarlink 878891 beginnt ebenfalls am Threadanfang. Autor, Datum und Kommentar-ID der gesuchten Liste bleiben unbekannt.
- **VAGBoard:** Ausgabe endet am Beginn von Beitrag #3. Kein neuer Zielbeitragslink gefunden.
- **A2Resource:** Kein erneuter identischer gekürzter Abruf durchgeführt.
- **Sicherung 18:** Neue Original-Funktionsreferenz, aber noch kein Halterseitenplan.
- **Sicherung 1:** Alternative in diesem Lauf nicht erschlossen.
- **Variantenfrage:** Keine neuen Belege. Keiner der neu gelesenen Listenbeiträge nennt `357 937 039`.

## 6. Konkreter Folgeauftrag für Monica

> ### Ziel: Herkunft der Neuner-Liste und Sicherung-18-Pfad erschließen
>
> **1. Bekannten vollständigen Listenbeleg verwenden**  
> Corrado-Kommentar **907721**, Moshiko Levi, **26.10.2014**, enthält die gesamte Liste unter „12 Fuel Pump Relay (80, 67 or 167)“. Nicht erneut nach deren bloßer Existenz suchen.
>
> **2. Technische Tabellenquelle gezielt erschließen**  
> SEATCUPRA.NET, Beitrag **2433959**, ibiza_95, **12.05.2009**, enthält eine umfangreiche CE2-Tabelle. Der bisherige Originalabruf endet bei B/03. Suche eine tatsächlich zugängliche Volltext-/Druckdarstellung oder einen vorhandenen Quellenlink. Benötigt werden die Abschnitte **U2**, **Relaisplatz 12** und eine gegebenenfalls zugehörige Nummerierungsabbildung. Keine alternativen URLs als bereits vorhanden behaupten.
>
> **3. Q1-Gegenzeile verfolgen**  
> Der Suchindex von Scribd-Dokument **520017984** zeigt „U2/01 E/2 Black“. Erschließe die vollständige Zeile samt Spaltenüberschriften und Quellenangabe. Kennzeichne eine A2Resource-Kopie als abhängig. Q1 bleibt bis dahin einseitig im A2Resource-Original gelesen.
>
> **4. Sicherung 18 priorisieren**  
> Suche einen passenden Stromlaufplan mit **J17, S18 und M/02**, ergänzend mit **G1/03, Z1 und 30B**. Erfasse ausschließlich tatsächlich eingezeichnete Anschlüsse. Unterscheide Relaisausgang, beide Sicherungsseiten, Pumpenleitung und Lambdasondenheizung. Die Listenposition 4 allein definiert kein gemeinsames Netz.
>
> **5. Ursprünglichen Corrado-Zielbeitrag nur über neuen Zugang verfolgen**  
> In Thread **72158** nach einem tatsächlich auffindbaren Kommentarlink zur Formulierung „Got a multimeter onto relay socket 12“ suchen. Ohne neuen Zugang nicht erneut den Threadanfang abrufen.
>
> **Abgabe:** Neue Originalbelege mit Fundstellen; abhängige Wiedergaben separat; physisches Inventar nicht mit Listenpositionen vermischen. Ohne geeignete Leiterbelege: **„Elektrische Kantenliste unverändert.“**

Monica
GPT-6 Astra
3 Sekunden nachgedacht
Die sechs Sprachen sind ab jetzt fest im Rechercheauftrag ergänzt: Russisch, Polnisch, Chinesisch, Japanisch, Koreanisch und Thai — zusätzlich zu Deutsch und Englisch.

Das gilt für die weitere Recherche in diesem Chat. Die andere Monica-Instanz erhält dieselbe Vorgabe über den nachstehenden Übergabeauftrag; ich kann ihre Einstellungen nicht direkt ändern.

Deinen neuen Recherchebericht übernehme ich als übergebenen Belegstand, nicht als eigene Originallektüre. Insbesondere gilt:

R12-LIST-907721: neun textlich nummerierte Listenpositionen, keine bestätigte Kammergeometrie.
SEATCUPRA.NET: mögliche abhängige Tabellenwiedergabe.
U2/01 → E/2: neuer Suchhinweis zur Gegenzeile, noch keine hier selbst geprüfte vollständige Tabellenzeile.
Elektrische Kantenliste unverändert.
Erweiterter Folgeauftrag für beide Monica-Instanzen
Die Spracherweiterung ist damit festgehalten; neue fremdsprachige Quellen wurden in dieser Antwort noch nicht recherchiert.

## Ergebnis

**Neu sind ein gezielter polnischer Quellenhinweis auf interne CE2-Verbindungen und ein weiter reichender Originalabruf der SEATCUPRA-Tabelle.** Der Scribd-Abruf zeigt dagegen eine beschädigte Textausgabe, die nicht zur zuverlässigen Übernahme von Anschlusskennungen geeignet ist.

Die Herkunft und geometrische Nummerierung der Neuner-Liste sowie der vollständige Sicherung-18-Pfad bleiben offen.

**Elektrische Kantenliste unverändert.**

## 1. Neu selbst geprüfte Originalinhalte

### A. SEATCUPRA: Tabelle diesmal bis E/05 lesbar

**Fundstelle:** [Beitrag #1, Post-ID 2433959](https://www.seatcupra.net/forums/threads/fusebox-fuse-location-relay-location-plug-locations-destinations-wiring-colours.219953/post-2433959)  
**Autor:** ibiza_95  
**Datum:** 12. Mai 2009.

Der aktuelle Abruf reicht über die bisherige Grenze B/03 hinaus bis **E/05**; anschließend beginnt F/01 und wird abgeschnitten.

Selbst gelesen wurden die Spaltenüberschriften:

> `Connector Outside Fusebox Inside Fusebox Color`

Deutsch: **Anschluss – außerhalb des Sicherungskastens – innerhalb des Sicherungskastens – Farbe.**

Die Zeile E/02 lässt sich unter diesen Überschriften wie folgt wiedergeben:

| Spalte | Originalinhalt |
|---|---|
| Connector | `E/02` |
| Outside Fusebox | `D/11 or D/8 (Start/Run Power for cluster, 1991+ Corrado, Passat, all other models), Immobilizer Module` |
| Inside Fusebox | `U2/1` |
| Color | `Black` |

**Übersetzung:** Außerhalb werden D/11 oder D/8 für die Versorgung des Kombiinstruments bei Start/Fahrt sowie das Wegfahrsperrenmodul genannt; innerhalb steht U2/1; Farbe Schwarz.

**Bedeutung für Q1:** Die bereits übergebene Quellenreferenz von E/02 auf U2/1 ist nun auch in dieser Tabellenwiedergabe selbst gelesen. **Die eigene Gegenzeile U2/01 wurde weiterhin nicht erreicht.**

**Hardware und Herkunft:**

- Überschrift: „Central Electric 2“.
- Genannter Umfang: Golf/Jetta 1989–1999, Passat 1990–1997, Cabrios, Corrados und EuroVans.
- Die Teilenummer **357 937 039** steht im gelesenen Abschnitt nicht.
- Aufbau und Formulierungen stimmen mit der übergebenen Beschreibung der A2Resource-Tabelle überein. Deshalb **nicht als unabhängige Zweitbestätigung zählen**.
- Ein ausdrücklicher Herkunftsverweis wurde im gelesenen Ausschnitt nicht gefunden.
- `CE2.gif` erscheint lediglich als Text. **Keine Bildprüfung und keine daraus abgeleitete Kammernummerierung.**

**Nicht erschlossen:** vollständiger Zugang, Abschnitt U2, Relaisplatz 12 und Nummerierungsabbildung. Der längere Ausschnitt ist kein vollständiger Abruf und kein neuer alternativer Zugangsweg.

### B. Scribd: Originalabruf vorhanden, Text jedoch unzuverlässig

**Fundstelle:** [Dokument 520017984, „fuse box ce2“](https://www.scribd.com/document/520017984/fuse-box-ce2)

Selbst gelesen:

- Anzeige: **10 Seiten**;
- Uploader: **Mohamed Anter El-khouly**;
- angezeigter Titel: „MK2 Golf CE2 Fuse Box Wiring Guide“;
- ausdrücklicher Hinweis: **„AI-enhanced title and description“**.

Der Titel ist somit **kein belastbarer Originaltitel oder Herkunftsnachweis**.

Die extrahierte Tabelle enthält erhebliche Zeichenverfälschungen, beispielsweise:

> `Cnmmhctnr N u t s l ...`

Auch Zahlen und Anschlussbezeichnungen sind betroffen. Ob die Ursache OCR, Schriftkodierung oder eine andere Extraktionsstörung ist, lässt sich aus dem Abruf nicht bestimmen.

**Folge:** Keine stillschweigende Rekonstruktion von Kennungen. Die gesuchte Zeile **U2/01** wurde in der Originalausgabe nicht erreicht. Der übergebene Suchhinweis `U2/01 E/2 Black` bleibt ein Suchhinweis.

Es wurde keine Zugangsbeschränkung umgangen.

### C. Polnische Fachquelle: passender Thread identifiziert

**Fundstelle:** [Elektroda, Thema 3201928](https://www.elektroda.pl/rtvforum/topic3201928.html)

Im Originalabruf tatsächlich gelesen wurde der Titel:

> **„VW all - Połączenia wewnętrzne skrzynki bezpieczników CE2“**

Deutsch:

> **„VW allgemein – interne Verbindungen des CE2-Sicherungskastens“**

Das ist ein unmittelbar zum Rechercheproblem passender Quellenpfad.

**Grenze:** Der Abruf endet nach Navigation und Teilen des Seitenkopfes. **Kein Beitragskörper, kein Autor, kein Plan und keine Messung wurden im Original gelesen.** Eine konkrete Grundträgerteilenummer ist damit nicht belegt.

## 2. Neue Suchhinweise und übernommene Berichte

### Neu selbst gelesene Suchauszüge

#### Polnisch: ausdrücklich interne Verbindungen gesucht

Zum Elektroda-Thema liefert der Suchindex:

> „Jak w tytule - szukam schematu WEWNĘTRZNEGO połączeń. Na necie jest wieele opisów co pod który pin w złączkach z tyłu, co na którym …“

**Übersetzung:**

> „Wie im Titel – ich suche einen Plan der INTERNEN Verbindungen. Im Netz gibt es viele Beschreibungen, was an welchen Pin der rückseitigen Stecker gehört, was an welchem …“

Der Auszug ist unvollständig. Das Suchergebnis nennt **10. Mai 2016**; dieses Datum wurde nicht am Originalbeitrag geprüft.

**Einordnung:** Ein sehr passender Rechercheansatz, aber bislang nur die **Suche eines anderen Nutzers nach einem internen Plan**, nicht dessen Auffindung.

#### Polnisch: ausdrückliche A2Resource-Verweise

Die Suche fand außerdem:

- [VWGolf.pl: „Schemat/fotka bezpieczników golf 2 1.6D“](https://forum.vwgolf.pl/viewtopic.php?t=609913) – Suchauszug mit A2Resource-CE2-Verweis.
- [Passat-Forum: „schemat przkaźników“](https://forum.vw-passat.pl/topic/1334-schemat-przka%C5%BAnik%C3%B3w/) – Suchauszug mit `http://www.a2resource.com/electrical/CE2.html`.

Diese Verweise zeigen **konkrete mögliche Herkunftsabhängigkeiten**. Die dortigen Beiträge wurden nicht im Original gelesen; zusätzliche eigenständige Inhalte sind deshalb weder bestätigt noch ausgeschlossen.

#### Russisch: Teilenummer im Katalogkontext

Die russische Suche fand einen [T4-Katalogeintrag bei avto.pro](https://avto.pro/catalog/volkswagen/transporter/rele-elektrobenzonasosa-m1814/). Der Suchauszug enthält:

> `357937039, Центральный блок электрообор.`

Deutsch, mit beibehaltener Kürzung:

> `357937039, zentraler Block der elektrischen Ausrüstung …`

**Einordnung:** Kataloghinweis mit Zielteilenummer und T4-Kontext. **Keine interne Schaltung und keine Variantenverifizierung.** Originalseite nicht gelesen.

### Unverändert übernommener Bericht

**R12-LIST-907721** bleibt in diesem Durchlauf ein **übergebener Bericht**:

- Moshiko Levi, 26.10.2014, Kommentar-ID 907721;
- neun Listenpositionen unter „12 Fuel Pump Relay (80, 67 or 167)“;
- keine physisch bestätigten Sockelkammern.

Der Beitrag wurde hier nicht erneut abgerufen. Seine Listenposition 4 wird insbesondere **nicht** als gemeinsames ungesichertes Netz aus Relaisausgang, S18, Kraftstoffpumpe und Lambdasondenheizung interpretiert.

## 3. Sprachprotokoll

Die acht verbindlichen Suchsprachen sind registriert. Chinesisch umfasst vereinfachte und bei Bedarf traditionelle Schrift.

| Sprache | Tatsächlich ausgeführte Anfrage / Arbeit | Ergebnis und Status |
|---|---|---|
| **Deutsch** | Keine neue deutschsprachige Suche | **Offen für nächsten Durchlauf** |
| **Englisch** | Direkte Originalabrufe von SEATCUPRA und Scribd; keine neue Suchanfrage | E/02 gelesen; U2 und Relaisliste nicht erreicht. **Teilbearbeitet** |
| **Russisch** | `"357937039" внутренняя схема` | Katalog-/Handelstreffer, darunter T4 mit Zielteilenummer; kein interner Plan erschlossen. **Teilbearbeitet** |
| **Polnisch** | `CE2 schemat wewnętrzny przekaźnik pompy paliwa 18` | Thematisch unbrauchbare Ergebnisse; nicht als negative Sachauskunft gewertet |
| **Polnisch** | `"CE2" "schemat" "bezpieczników"` | Elektroda-Thema zu internen Verbindungen und A2Resource-Verweise gefunden. **Teilbearbeitet** |
| **Chinesisch, vereinfacht** | `"CE2" "保险丝盒"` | Unter anderem chinesisch dargestellte Reddit-Treffer und Handel; kein geeigneter Leiterbeleg. **Teilbearbeitet** |
| **Chinesisch, traditionell** | Keine eigene Anfrage | **Offen** |
| **Japanisch** | Keine Anfrage | **Offen** |
| **Koreanisch** | Keine Anfrage | **Offen** |
| **Thai** | Keine Anfrage | **Offen** |

Die chinesischen Reddit-Treffer verwenden `?tl=zh-hans`. Sie sind daher **nicht als eigenständige chinesische Originalquellen gezählt**. Außerdem erzeugt `CE2` ohne Fahrzeugbezug viele Treffer zu anderen elektrischen Produkten.

**Keine erfolglose oder unergiebige Suche belegt die Nichtexistenz passender Unterlagen.**

## 4. Inventar und elektrische Kanten

### Quellenregister

Neu beziehungsweise ergänzt:

| Registereintrag | Änderung |
|---|---|
| SEATCUPRA 2433959 | Lesbarer Bereich bis E/05; E/02 → U2/1 als Tabellenreferenz erfasst |
| Scribd 520017984 | Extraktionsstörung dokumentiert; keine Kennungen daraus übernommen |
| Elektroda 3201928 | Neuer Quellenpfad speziell zu internen CE2-Verbindungen |
| Mehrsprachige Herkunftsprüfung | Polnische A2Resource-Verweise und chinesische Übersetzungsansichten erkannt |

### Physisches Inventar

**Keine Änderung.** Keine neue Kammer geometrisch identifiziert, keine Sicherungshalterseite eindeutig bezeichnet und kein Metallkontakt visuell geprüft.

### Kanten und Matrix

- **Q1:** zusätzliche abhängige Tabellenwiedergabe gelesen; eigene U2/01-Gegenzeile weiterhin offen.
- **Q2:** unverändert.
- **S18/R12:** keine neue interne Kante.
- **Matrix:** keine neuen `1` oder `0`; unbekannte Beziehungen bleiben `?`.

**Elektrische Kantenliste unverändert.**

## 5. Unerledigte Aufgaben

1. Vollständiger Zugang zur SEATCUPRA-Tabelle einschließlich Quellenverweis.
2. Unverfälschte U2/01-Zeile mit Spaltenzuordnung.
3. Originalbeiträge und mögliche Anhänge des polnischen Elektroda-Themas.
4. Nummerierungsabbildung zu R12-LIST-907721.
5. S18 mit **beiden getrennten Halterseiten** und rückseitigen Gegenkontakten.
6. Zielteilnachweis `357 937 039` bei technischen Plänen und Messberichten.
7. Japanische, koreanische, thailändische und traditionell-chinesische Suche.
8. Ursprünglicher Corrado-Zielbeitrag: bewusst nicht erneut über denselben gekürzten Threadanfang verfolgt.

## 6. Ausführbarer Folgeauftrag für Monica

> ### Verbindlicher Sprachumfang – bei jeder weiteren Übergabe vollständig mitgeben
>
> Recherchiere in **Deutsch, Englisch, Russisch, Polnisch, Chinesisch, Japanisch, Koreanisch und Thai**. Chinesisch zunächst vereinfacht, ergänzend traditionell. Verwende echte landessprachliche Begriffe; protokolliere konkrete Anfragen, Ergebnisse und offene Sprachen. Nicht jede Sprache muss in jedem Durchlauf abgeschlossen werden.
>
> ### A. Zuerst den neuen polnischen Quellenpfad bearbeiten
>
> https://www.elektroda.pl/rtvforum/topic3201928.html
>
> Titel: „VW all - Połączenia wewnętrzne skrzynki bezpieczników CE2“.
>
> Bisher ist nur der Titel im Original gelesen. Der Suchauszug enthält die ausdrückliche Suche nach einem internen Verbindungsplan.
>
> 1. Suche gezielt:
>    - `site:elektroda.pl/rtvforum/topic3201928.html "CE2"`
>    - `"CE2" "połączenia wewnętrzne"`
>    - `"357937039" "schemat"`
> 2. Erschließe nur tatsächlich gefundene Beitragslinks, öffentlich zugängliche Ansichten oder Anhänge.
> 3. Erfasse Autor, Datum, Beitragsnummer und etwaige Planherkunft.
> 4. Unterscheide eine bloße Plananfrage von Antworten mit Plan oder Messung.
> 5. Keine Zugangsbeschränkungen umgehen.
>
> ### B. Offene Sprachen systematisch vorziehen
>
> Die folgenden Anfragen sind **vorgeschlagene nächste Suchen, noch nicht ausgeführt**. Jede Zeile getrennt suchen:
>
> | Sprache | Kurze Suchanfragen |
> |---|---|
> | Deutsch | `"357 937 039" interne Verdrahtung` · `CE2 Sicherung 18 Stromlaufplan` |
> | Englisch | `CE2 relay socket 12 pin numbering` · `CE2 S18 M/02` |
> | Russisch | `CE2 внутренняя схема` · `Golf J17 реле бензонасоса` |
> | Polnisch | `CE2 połączenia wewnętrzne` · `Golf S18 przekaźnik pompy paliwa` |
> | Chinesisch, vereinfacht | `"357937039" 保险丝盒` · `Golf 内部接线图 燃油泵继电器` |
> | Chinesisch, traditionell | `Golf 保險絲盒 內部接線圖` |
> | Japanisch | `"357937039" ヒューズボックス` · `Golf 燃料ポンプリレー 端子配列` |
> | Koreanisch | `"357937039" 퓨즈 박스` · `Golf 연료 펌프 릴레이 핀 배열` |
> | Thai | `"357937039" กล่องฟิวส์` · `Golf ขารีเลย์ ปั๊มน้ำมันเชื้อเพลิง` |
>
> Ergänze bei Bedarf einzeln **J17, S18, M/02, G1/03, Z1 oder 30B**. Keine überladenen Anfragen. Übersetzungsansichten englischer Quellen sind keine unabhängigen landessprachlichen Belege.
>
> ### C. Q1 und Listenherkunft weiterführen
>
> - **SEATCUPRA, Post 2433959:** Jetzt bis E/05 lesbar; E/02 nennt intern U2/1. U2, Relaisplatz 12, Bild und Quellenverweis fehlen weiterhin. Kein erneuter identischer Abruf ohne begründeten neuen Zugangsweg.
> - **Scribd 520017984:** Textausgabe stark verfälscht. Keine Kennungen daraus rekonstruieren. Nur lesbare öffentliche Darstellung oder nachvollziehbare andere Wiedergabe verwenden.
> - **R12-LIST-907721:** Übergebener vollständiger Listenbericht; neun Listenpositionen, keine verifizierten Kammern. Herkunft und Blickrichtung offen.
>
> ### D. Sicherung 18 als getrennten Topologieauftrag behandeln
>
> Benötigt werden Relaisausgang, beide S18-Halterkontakte und rückseitige Gegenkontakte. Äußere Leitungen, Relais, Sicherung und herausnehmbare Brücken separat erfassen. **Listenposition 4 und M/02 nicht allein aufgrund gleicher Funktion verbinden.**
>
> ### E. Verbindliche Abgabe- und Belegregeln
>
> Originallektüre, Suchauszug, Fremdbericht, Bildprüfung und Messung getrennt ausweisen. Originalpassagen mit deutscher Übersetzung dokumentieren; Kennungen unverändert lassen.
>
> **Matrix:** `1` nur für nachgewiesene feste Verbindung am identifizierten nackten Grundträger; `0` nur für geeignet nachgewiesene Trennung; sonst `?`. Q1/Q2 bleiben Quellenreferenzen ohne physische Zielteilverifizierung.
>
> Abschluss mit Quellenregister, Sprachprotokoll, Inventaränderungen, Kantenänderungen und nächstem Auftrag **einschließlich aller acht Suchsprachen**. Ohne geeignete neue Leiterbelege: **„Elektrische Kantenliste unverändert.“**

Monica
GPT-6 Astra
Angetrieben von

Monica Suche
19 Sekunden nachgedacht
Linkleser
13 Sekunden nachgedacht
Searching: site:elektroda.pl/rtvforum/topic3201928.html CE2 wewnętrzne
Basierend auf 10 Suchquellen

6 Sekunden nachgedacht
Call Skill: Google Search
1 Sekunden nachgedacht
Call Skill: Google Search
0 Sekunden nachgedacht
Ergebnis des nächsten Rechercheschritts
Neu sind zwei polnische Suchauszüge, die auf Antworten im Elektroda-Thema hindeuten, sowie japanische Angebote mit der Zielteilenummer. Ein interner Plan, ein Anhang oder eine Kammerabbildung wurde nicht erschlossen.

Elektrische Kantenliste unverändert.

Den von dir übermittelten Bericht behandle ich weiterhin als übergebenen Stand. Nachfolgend sind ausschließlich die in diesem Durchlauf zusätzlich geprüften Inhalte aufgeführt.

1. Elektroda: Originalabruf weiterhin ohne Beitragskörper
Thema 3201928: „VW all – Połączenia wewnętrzne skrzynki bezpieczników CE2“

Der Originalabruf zeigt erneut Titel, Navigation und Seitenkopf. Er endet vor den eigentlichen Beiträgen.

Nicht im Original gelesen: Autor, Beitragsdatum, Antworten, Anhänge oder elektrische Zeichnungen. Dieser Abruf brachte daher keinen neuen technischen Originalbeleg.

2. Neue polnische Suchhinweise: mögliche Antworten zum Lesen von Stromlaufplänen
Die Suche nach "CE2" "połączenia wewnętrzne" erschloss zwei zusätzliche Textstellen auf Elektroda-Suchübersichtsseiten. Der Suchindex ordnet sie jeweils dem bekannten CE2-Thementitel zu.

A. Hinweis auf das graue Feld im VW-Stromlaufplan
Fundort: Elektroda-Suchübersicht „Skrzynka bezpieczników vw“

Suchauszug:

„Weź dowolny schemat VW, szare pole na górze, to właśnie skrzynka bezpieczników/przekaźników.“

Übersetzung:

„Nimm einen beliebigen VW-Schaltplan; das graue Feld oben ist der Sicherungs-/Relaiskasten.“

Einordnung: Ein konkreter Hinweis auf eine mögliche Antwort im gesuchten Thread. Er ist kein gefundener interner Plan. Auch der Ausdruck „beliebiger VW-Schaltplan“ ersetzt keinen Nachweis, dass ein bestimmter Plan zur Zielhardware passt.

B. Hinweis auf Fortsetzungskennzeichnungen
Fundort: Elektroda-Suchübersicht „Schematy poziomu paliwa“

Suchauszug:

„a,b... to linie, które są powiązane z dalszą częścią schematu. Na przykład na 1 stronie znajduje …“

Übersetzung:

„a, b … sind Linien, die mit dem weiteren Teil des Schaltplans verbunden sind. Zum Beispiel befindet sich auf Seite 1 …“

Der Auszug bricht mitten im Satz ab.

Einordnung: Möglicherweise wird im Thread ein konkreter mehrseitiger Plan diskutiert. Das ist bislang nur ein Rechercheansatz: Weder der Plan selbst noch seine Herkunft oder ein Anhang sind bekannt.

Für beide Textstellen fehlen weiterhin Originalbeitrag, Autor, eigenes Datum und Beitragsnummer. Die Suchübersichten sind keine unabhängigen technischen Zweitquellen.

3. Japanisch: Zielteilenummer gefunden, aber nur im Handelskontext
Ausgeführte Suche:

"357937039" ヒューズボックス

Japanischer Golf-3-Angebotstext
Fundort: Yahoo!フリマ, Angebot j1071882954

Im Suchauszug:

„VW ゴルフ3 ヒューズボックス リレー 中古品番：357937039“

Übersetzung:

„VW Golf 3, Sicherungskasten/Relais, gebraucht, Teilenummer: 357937039.“

Ein weiterer Treffer bei Yahoo! Auctions verwendet dieselbe Angebotskennung. Nicht als unabhängigen zweiten Fund zählen.

Japanischer Vanagon-Angebotstext
Fundort: Rakuten, gebrauchter Sicherungskasten für VW Vanagon 70AAF

Der Suchauszug nennt unter anderem:

„メーカー純正品番:357937039“

„セントラルエレクトリクス“

Übersetzung:

„Originalteilenummer des Herstellers: 357937039“

„Zentralelektrik.“

Aussagegrenze beider Angebote: Nur Suchauszüge gelesen. Keine Originalseite geöffnet, keine Fotos geprüft, keine interne Verdrahtung dokumentiert. Fahrzeugzuordnungen bleiben Verkäuferangaben, keine Variantenverifizierung.

4. Sprachprotokoll dieses Durchlaufs
Sprache	Tatsächliche Arbeit	Ergebnis
Deutsch	Keine neue Suche	Offen
Englisch	Keine neue Suche	Offen
Russisch	Keine neue Suche	Vorherigen Stand übernommen
Polnisch	site:elektroda.pl/rtvforum/topic3201928.html CE2 wewnętrzne	Unpassende Treffer; kein Erkenntnisgewinn
Polnisch	"CE2" "połączenia wewnętrzne"	Zwei neue Suchauszüge mit möglichen Antwortpassagen
Japanisch	"357937039" ヒューズボックス	Zielteilenummer in Handelsangeboten; keine Topologie
Chinesisch, vereinfacht/traditionell	Keine neue Suche	Vorherigen Stand übernommen; traditionell weiterhin offen
Koreanisch	Keine Suche	Weiterhin offen
Thai	Keine Suche	Weiterhin offen
Keine Bildprüfung durchgeführt. SEATCUPRA und Scribd wurden in diesem Durchlauf nicht erneut abgerufen.

5. Änderungen am Register
Bereich	Änderung
Quellenregister	Zwei polnische Antwort-Suchhinweise und japanische Teilenummern-Angebote ergänzt
Physisch bestätigtes Kontaktinventar	Keine
R12-LIST-907721	Unverändert; übergebener Listenbericht
Q1 / Q2	Unverändert
Sicherung 18 / Relaisplatz 12	Keine neuen Leiterbelege
Matrixwerte 1 / 0	Keine neuen Einträge
Elektrische Kantenliste unverändert.

6. Folgeauftrag für die andere Monica-Instanz
Der aussichtsreichste neue Ansatz sind die polnischen Antwortpassagen: Sie könnten zu einem tatsächlich diskutierten Stromlaufplan führen. Dass dieser Plan vorhanden oder für 357 937 039 geeignet ist, bleibt allerdings zu prüfen.

## Ergebnis dieses Durchlaufs

**Die erste polnische Antwortpassage wurde im Suchindex erneut gefunden.** Die Suche nach ihrer exakten Wortfolge liefert auch den bekannten CE2-Thread. Der zugehörige Originalbeitrag mit Autor, Datum und Beitragsnummer ist jedoch weiterhin nicht erschlossen.

Die beiden Suchübersichten wurden gelesen, soweit die Textausgabe reicht. **Im ausgegebenen Abschnitt stehen weder die gesuchten Antwortpassagen noch ein ihnen zugeordneter Beitrags- oder Anhangslink.**

Die koreanische Suche wurde begonnen; Thai, traditionelles Chinesisch und die vertiefte japanische Suche bleiben offen.

**Elektrische Kantenliste unverändert.**

## 1. Neu selbst gelesene Seiteninhalte

### Polnische Suchübersicht „skrzynka bezpieczników vw“

**Fundstelle:** [Elektroda-Suchübersicht: Sicherungskasten VW](https://poszukaj.elektroda.pl/szukaj,skrzynka-bezpiecznik%C3%B3w-vw.html)

Selbst gelesen wurde der Anfang der Ergebnisübersicht mit tatsächlichen Links zu verschiedenen VW-Themen.

**Nicht im ausgegebenen Abschnitt enthalten:**

- die Passage „Weź dowolny schemat VW …“;
- ein dieser Passage zugeordneter Direktlink;
- eine Autorenangabe;
- ein konkreter CE2-Plan oder Anhang.

Die Ausgabe endet innerhalb der Ergebnisliste. Deshalb lässt sich daraus **nicht** schließen, dass die Passage auf der vollständigen Seite fehlt.

### Polnische Suchübersicht „schematy poziomu paliwa“

**Fundstelle:** [Elektroda-Suchübersicht: Kraftstoffstand-Schaltpläne](https://poszukaj.elektroda.pl/szukaj,schematy-poziomu-paliwa.html)

Auch hier wurde nur der Anfang der Ergebnisübersicht ausgegeben.

Ein sichtbarer Treffer enthält zwar „W załączniku schematy od Golfa V“ – deutsch: „Im Anhang Schaltpläne vom Golf V“. Er gehört aber zu einem **Seat-Toledo-IV-Thema** und nicht nachweislich zur gesuchten CE2-Antwort.

**Abgrenzung:** Diese Anhangserwähnung ist **kein Nachweis eines Anhangs im CE2-Thread** und wurde nicht weiterverfolgt.

### Belegstatus

Dies sind selbst gelesene **Suchübersichten**, keine neu gelesenen Originalbeiträge des CE2-Threads. Es wurde in diesem Durchlauf **kein neuer technischer Originalbeleg für die interne Verdrahtung** erschlossen.

## 2. Neue Suchhinweise – getrennt von Originallektüre

### A. Polnische Passage zum grauen Feld bestätigt

**Tatsächliche Suchanfrage:**

`"Weź dowolny schemat VW"`

Das Ergebnis lieferte:

1. den [CE2-Thread 3201928](https://www.elektroda.pl/rtvforum/topic3201928.html);
2. die oben genannte Suchübersicht mit folgendem Auszug:

> „Weź dowolny schemat VW, szare pole na górze, to właśnie skrzynka bezpieczników/przekaźników.“

**Deutsche Übersetzung:**

> „Nimm einen beliebigen VW-Schaltplan; das graue Feld oben ist der Sicherungs-/Relaiskasten.“

Im selben Suchauszug erscheinen:

> „10 Maj 2016 16:55 Odpowiedzi: 4“

Das bedeutet **10. Mai 2016, 16:55 Uhr; Antworten: 4**. Diese Angaben stammen aus der Ergebnisübersicht. Sie sind **nicht als Datum oder Beitragsnummer des gesuchten Autors verifiziert**.

**Erkenntnisgewinn:** Der übergebene Text ist jetzt selbst als Suchauszug gelesen; die exakte Suche führt auch zum bekannten CE2-Thema. Ein Direktlink zum Antwortbeitrag fehlt weiterhin.

**Elektrische Aussagegrenze:** Die Passage erklärt allgemein die Darstellung eines VW-Stromlaufplans. Sie belegt weder einen bestimmten Plan noch eine konkrete Leiterverbindung.

### B. Fortsetzungslinien: Zielpassage nicht wiedergefunden

Tatsächlich ausgeführt:

- `"a,b" "to linie" "schematu"`
- `"które są powiązane z dalszą częścią schematu"`

Die gelieferten Ergebnisse waren themenfremd. Daraus folgt **keine Widerlegung** des übergebenen Suchauszugs.

Die Passage bleibt ein **übergebener Suchhinweis**:

> „a,b... to linie, które są powiązane z dalszą częścią schematu. Na przykład na 1 stronie znajduje …“

**Deutsche Übersetzung des unvollständigen Textes:**

> „a,b… sind Linien, die mit dem weiteren Teil des Schaltplans zusammenhängen. Zum Beispiel befindet sich auf Seite 1 …“

Autor, Originalbeitrag, vollständiger Kontext und eventuelle Anhänge bleiben unbekannt. Insbesondere ist noch nicht bestätigt, dass beide polnischen Passagen aus demselben Thema stammen.

### C. Koreanische Suche: nur englischsprachige Katalog-/Handelstreffer

**Tatsächliche Anfrage:**

`"357937039" 퓨즈 박스`

`퓨즈 박스` bedeutet **Sicherungskasten**.

Unter den gelieferten Suchtreffern:

| Quelle | Selbst gelesener Suchauszug | Einordnung |
|---|---|---|
| [Volkswagen-Teilekatalog](https://parts.vw.com/p/Volkswagen__/Fuse-and-Relay-Center/53040177/357937039.html) | „Genuine Volkswagen Part # 357937039 (357-937-039) – Fuse and Relay Center …“ | Neuer offizieller Katalogansatz zur Teileidentität; Originalseite nicht gelesen |
| [ECS Tuning](https://www.ecstuning.com/b-genuine-volkswagen-audi-parts/fuse-box-panel/357937039/) | Nennt 357937039 und unter anderem Corrado, Eurovan T4, Golf II und Golf III | Händlerzuordnung, keine Variantenverifizierung |
| [Module Mechanics](https://modulemechanics.com/product/357937039-fuse-relay-module-oem-audi-80/) | Titel ordnet 357937039 einem Audi 80 zu | Ungeprüfte Verkäuferzuordnung; nicht auf die Zielhardware übertragen |

**Ergebnis:** Eine echte koreanischsprachige Anfrage wurde ausgeführt, aber **keine koreanische technische Quelle** erschlossen. Die Treffer enthalten keine auswertbare interne Schaltung.

## 3. Quellenabhängigkeiten und übernommener Stand

- Elektroda-Suchübersichten sind **Auszüge aus Forumsinhalten**, keine unabhängigen Bestätigungen.
- Exakte Suche und Suchübersicht dürfen nicht als zwei unabhängige Belege für dieselbe Aussage gezählt werden.
- Händlerzuordnungen belegen weder identische Innenausführung noch Variantenkompatibilität.
- Der offizielle VW-Katalogtreffer ist zunächst nur ein **Suchhinweis**, kein gelesener Teilekatalogeintrag.
- **R12-LIST-907721**, SEATCUPRA bis E/05 und die Scribd-Extraktionsfehler wurden in diesem Durchlauf nicht erneut geprüft. Sie bleiben übernommener Stand.
- Keine neue Grundlage zur Herkunft der Neuner-Liste oder zur Unabhängigkeit der CE2-Tabellen gefunden.

## 4. Sprachprotokoll

**Verbindlicher Umfang:** Deutsch, Englisch, Russisch, Polnisch, Chinesisch, Japanisch, Koreanisch und Thai; Chinesisch vereinfacht und ergänzend traditionell.

| Sprache | Arbeit in diesem Durchlauf | Status |
|---|---|---|
| Deutsch | Keine neue Anfrage | Offen |
| Englisch | Englische Suchauszüge als Ergebnisse der koreanischen Anfrage gelesen; keine eigene englische Anfrage | Technische Suche offen |
| Russisch | Keine neue Anfrage | Fortsetzung offen |
| Polnisch | Drei oben vollständig protokollierte Anfragen; zwei übergebene Suchübersichten abgerufen | Teilbearbeitet; Originalantworten offen |
| Chinesisch, vereinfacht | Keine neue Anfrage | Fortsetzung offen |
| Chinesisch, traditionell | Keine Anfrage | **Priorisiert offen** |
| Japanisch | Keine neue Anfrage; Hardware-Angebote nicht abgerufen | **Technische Vertiefung offen** |
| Koreanisch | `"357937039" 퓨즈 박스` | Begonnen; zweite, technische Anfrage offen |
| Thai | Keine Anfrage | **Priorisiert offen** |

Die vorgeschlagenen, aber nicht ausgeführten Anfragen werden ausdrücklich **nicht als erledigt** gezählt.

## 5. Inventar, Kanten und Abrufgrenzen

### Inventaränderungen

**Keine.**

- Keine neue physische Sockelkammer identifiziert.
- Keine Sicherungshalterseite identifiziert.
- Keine Fotos visuell geprüft.
- Keine Kammergeometrie oder DIN-Zuordnung bestätigt.

### Elektrische Kantenänderungen

**Keine.**

- Q1 und Q2 bleiben Quellenreferenzen ohne physische Zielteilverifizierung.
- U2/01 bleibt ohne neu gelesene vollständige Gegenzeile.
- S18 bleibt ohne getrennte Dokumentation beider Halterkontakte.
- Keine Verbindung zwischen Listenposition 4 und M/02 abgeleitet.
- Keine neuen Matrixwerte `1` oder `0`; ungeklärte Beziehungen bleiben `?`.

**Elektrische Kantenliste unverändert.**

### Abrufgrenzen und unerledigte Aufgaben

Die Elektroda-Übersichten wurden vor den gesuchten Passagen abgeschnitten. Kein neuer Antwort-Direktlink, öffentlicher Anhang oder alternativer vollständiger Zugang wurde gefunden. Der bereits bekannte gekürzte CE2-Threadanfang wurde nicht erneut als Fortschritt verwendet.

Die technischen Kernaufgaben – **U2/01, Listennummerierung, S18 und Hardwarebezug** – sind in diesem Durchlauf nicht gelöst worden.

## 6. Neuer ausführbarer Folgeauftrag für Monica

> ### Verbindlicher Sprachumfang
>
> **Deutsch, Englisch, Russisch, Polnisch, Chinesisch, Japanisch, Koreanisch und Thai.** Chinesisch vereinfacht und ergänzend traditionell. Diesen Umfang in jede weitere Übergabe übernehmen. Tatsächliche Anfragen, Quellentyp und offene Sprachen protokollieren.
>
> ### 1. Zuerst die noch offenen Sprachsuchen ausführen
>
> Folgende Anfragen sind **noch nicht ausgeführt**:
>
> - Koreanisch: `Volkswagen Golf 내부 배선도 퓨즈 박스`
> - Thai: `"357937039" กล่องฟิวส์`
> - Thai: `Volkswagen Golf แผนผังวงจร กล่องฟิวส์`
> - Chinesisch traditionell: `"357937039" 保險絲盒`
> - Chinesisch traditionell: `Volkswagen Golf 保險絲盒 內部接線圖`
> - Japanisch: `Golf CE2 内部配線図`
> - Japanisch: `Golf 燃料ポンプリレー 端子配列`
>
> Anschließend kurze technische Suchen in den übrigen Sprachen:
>
> - Deutsch: `CE2 Sicherung 18 interne Verdrahtung`
> - Englisch: `CE2 fuse 18 internal wiring`
> - Russisch: `CE2 внутренняя схема`
> - Polnisch: `CE2 połączenia wewnętrzne`
> - Chinesisch vereinfacht: `Golf 保险丝盒 内部接线图`
>
> Handelsangebote und automatisch übersetzte Seiten getrennt führen. Bei unergiebigen Treffern Fahrzeugbezug ändern oder Kennungen einzeln ergänzen; fehlende Treffer nicht als elektrische Negativaussage werten.
>
> ### 2. Polnische Antworten gezielt lokalisieren
>
> Bekannter Thread:  
> https://www.elektroda.pl/rtvforum/topic3201928.html
>
> Die exakte Suche `"Weź dowolny schemat VW"` liefert den Thread und einen Suchübersichts-Auszug mit der grauen-Feld-Erklärung. **Autor und Originalbeitrag sind weiterhin unbekannt.**
>
> Nächste, noch nicht ausgeführte Anfragen:
>
> - `site:elektroda.pl/rtvforum/ "szare pole na górze"`
> - `site:elektroda.pl/rtvforum/topic3201928.html "schematu"`
> - `site:elektroda.pl "a,b" "dalszą"`
> - `site:elektroda.pl "Na przykład na 1 stronie"`
>
> Nur tatsächlich gefundene öffentliche Links und Anhänge verfolgen. Suchübersichtsdatum nicht als Antwortdatum übernehmen. Zunächst prüfen, ob die Fortsetzungslinien-Passage überhaupt zum selben Thread gehört.
>
> ### 3. Technische Kernaufgaben beibehalten
>
> - **U2/01:** vollständige unverfälschte Zeile mit Spaltenüberschriften und Herkunft suchen.
> - **R12-LIST-907721:** Herkunft, Blickrichtung und geometrische Nummerierung klären; neun Listenpositionen bleiben von physischen Kammern getrennt.
> - **S18:** Relaisausgang, beide Halterkontakte, rückseitige Gegenkontakte und äußere Leitungen getrennt erfassen. Suchkennungen einzeln oder in kleinen Kombinationen: **J17, S18, M/02, G1/03, Z1, 30B**.
> - **Hardware:** Zielteilenummer **357 937 039** nachweisen; Varianten separat behandeln.
>
> Neuer optionaler Katalogansatz:
>
> https://parts.vw.com/p/Volkswagen__/Fuse-and-Relay-Center/53040177/357937039.html
>
> Bisher nur Suchauszug gelesen. Ein Katalogeintrag könnte die Teileidentität unterstützen, ersetzt aber keinen internen Leiterbeleg.
>
> ### 4. Verbindliche Beleg- und Abgaberegeln
>
> Übergebene Berichte, Suchauszüge, Originallektüre, Bildprüfung und Messungen trennen. Originalpassagen mit deutscher Übersetzung dokumentieren; Kennungen unverändert lassen. Keine URLs, Kommentar-IDs oder Seitenzahlen erraten und keine Zugangsbeschränkungen umgehen.
>
> `1` nur bei nachgewiesener fester Verbindung am identifizierten nackten Grundträger; `0` nur bei geeignet nachgewiesener Trennung; sonst `?`. Relais, Sicherungen, Kabelbaum und herausnehmbare Brücken separat behandeln.
>
> Ausgabe mit Quellenabhängigkeiten, Sprachprotokoll, Inventar- und Kantenänderungen sowie neuem Folgeauftrag **einschließlich aller acht Suchsprachen**. Ohne geeignete neue Leiterbelege ausdrücklich: **„Elektrische Kantenliste unverändert.“**

Monica
GPT-6 Astra
Angetrieben von

Monica Suche
34 Sekunden nachgedacht
Searching: Volkswagen Golf 내부 배선도 퓨즈 박스
Basierend auf 9 Suchquellen

Linkleser
3 Sekunden nachgedacht
Searching: "357937039" กล่องฟิวส์
Basierend auf 9 Suchquellen

0 Sekunden nachgedacht
Denkprozess


Monica
GPT-6 Astra
Angetrieben von

Monica Suche
Searching: Volkswagen Golf แผนผังวงจร กล่องฟิวส์
Basierend auf 10 Suchquellen

0 Sekunden nachgedacht
Searching: "357937039" 保險絲盒
Basierend auf 10 Suchquellen

0 Sekunden nachgedacht
Ergebnis dieses Durchlaufs
Neu ist ein selbst gelesener offizieller VW-Katalogeintrag zur Teilenummer 357937039. Er bestätigt die Teilebezeichnung und nennt Cabrio und Corrado als Fahrzeugzuordnungen. Eine interne Schaltung enthält der ausgegebene Abschnitt nicht.

Die offenen koreanischen, thailändischen und traditionell-chinesischen Suchen wurden teilweise bearbeitet. Kein neuer technischer Leiterbeleg wurde erschlossen.

Elektrische Kantenliste unverändert.

1. Neuer Originalbeleg: offizieller VW-Teilekatalog
Fundstelle: Volkswagen – „Fuse and Relay Center“, 357937039

Im Originalabruf tatsächlich gelesen:

Feld	Originalinhalt
Bezeichnung	Fuse and Relay Center
Teilenummer	357937039
Feld „Supersession(s)“	357-937-039
Weitere Bezeichnungen	Fuse Box. Relay and Fuse Plate.
Fahrzeugzuordnung	Fits Cabrio, Corrado
Lageangabe	LOWER.
Übersetzung: Sicherungs- und Relaiszentrale beziehungsweise Sicherungs-/Relaisträger; passend für Cabrio und Corrado; Lageangabe „unten“.

Aussagegrenzen
Belegt ist die offizielle Katalogführung der Zielteilenummer als Sicherungs-/Relaisträger.
357-937-039 enthält dieselben Ziffern wie 357937039. Obwohl es im Feld „Supersession(s)“ steht, lässt sich daraus keine technische Nachfolgeversion oder interne Änderung ableiten.
Der gelesene Abschnitt nennt keine Baujahre, CE2-Bezeichnung, Anschlussbelegung oder Innenansicht.
Die Lageangabe „LOWER“ definiert keine Blickrichtung für Kontaktbilder.
Cabrio und Corrado sind die hier gelesenen Zuordnungen, keine nachgewiesen vollständige Verwendungsliste.
Dieser Katalogeintrag identifiziert kein konkretes untersuchtes Exemplar und ersetzt keinen Nachweis seiner Innenausführung.
Quellenregister: neuer offizieller Teileidentitätsbeleg; kein Leiterbeleg.

2. Neue Suchergebnisse – getrennt von Originallektüre
Koreanisch: technische Anfrage ausgeführt
Anfrage:

Volkswagen Golf 내부 배선도 퓨즈 박스

Sinngemäß: Volkswagen Golf, interne Verdrahtungszeichnung, Sicherungskasten.

Die Ergebnisse enthielten überwiegend Pinterest-Verweise auf allgemeine Golf-Sicherungspläne sowie einen englischen Diagnosebeitrag zu einem Golf von 1996.

Ergebnis: Keine koreanischsprachige technische Originalquelle und kein auswertbarer interner CE2-Plan erschlossen. Die Treffer wurden nicht als passende Leiterbelege übernommen.

Thai: Teilenummernsuche ausgeführt
Anfrage:

"357937039" กล่องฟิวส์

กล่องฟิวส์ bedeutet Sicherungskasten.

Die Suche lieferte englische Katalog- und Handelstreffer, darunter:

UroTuning: „Fuse Box and Relay Plate“ – Suchauszug mit Zielteilenummer und Mk2-/Mk3-Zuordnung.
ECS Tuning: „Fuse Box panel“ – bereits bekannter Händleransatz.
Den oben anschließend im Original gelesenen VW-Katalogeintrag.
Einordnung: Eine thailändische Anfrage ist bearbeitet, aber keine thailändische Fachquelle gefunden. Verkäuferzuordnungen werden nicht zur Variantenverifizierung verwendet.

Die zweite Anfrage

Volkswagen Golf แผนผังวงจร กล่องฟิวส์

wurde angestoßen, endete jedoch mit einem Zeitüberschreitungsfehler. Sie zählt als versuchter, nicht ausgewerteter Suchlauf, nicht als Suche ohne Treffer.

Chinesisch, traditionell: Teilenummernsuche ausgeführt
Anfrage:

"357937039" 保險絲盒

Die ausgegebenen Ergebnisse waren themenfremd, unter anderem zu Apps und anderen Arten von Behältern. Sie zeigen keine brauchbare Berücksichtigung der Zielteilenummer.

Ergebnis: Kein verwertbarer Quellenhinweis. Daraus folgt keine Aussage über die Existenz chinesischsprachiger CE2-Unterlagen. Eine fahrzeugbezogene technische Folgeanfrage bleibt erforderlich.

3. Sprachprotokoll
Verbindlich bleiben Deutsch, Englisch, Russisch, Polnisch, Chinesisch, Japanisch, Koreanisch und Thai, mit vereinfachtem und traditionellem Chinesisch.

Sprache	Arbeit in diesem Durchlauf	Offener nächster Schritt
Deutsch	Keine neue Suche	Technische S18-/CE2-Suche
Englisch	Offiziellen VW-Katalog im Original gelesen; englische Suchauszüge gelesen	Interne Verdrahtung gezielt suchen
Russisch	Keine neue Suche	Technische Vertiefung
Polnisch	Keine neue Suche	Originalantworten im Elektroda-Thema
Chinesisch, vereinfacht	Keine neue Suche	Fahrzeugbezogene technische Suche
Chinesisch, traditionell	"357937039" 保險絲盒	Technische Anfrage mit Golf-/VW-Bezug
Japanisch	Keine neue Suche	Interne Verdrahtung und Relaiskontaktanordnung
Koreanisch	Volkswagen Golf 내부 배선도 퓨즈 박스	Suche stärker auf Golf II/III beziehungsweise CE2 begrenzen
Thai	Teilenummernsuche ausgewertet; technische Anfrage mit Zeitüberschreitung	Technische Anfrage erneut oder kürzer ausführen
Keine Fotos oder Zeichnungen visuell geprüft. Die Elektroda-Antworten, SEATCUPRA, Scribd und die Corrado-Listenbeiträge wurden in diesem Durchlauf nicht erneut gelesen.

4. Änderungen am Arbeitsstand
Register	Änderung
Teileidentität	Offizieller VW-Katalogbeleg für 357937039 ergänzt
Quellen-/Suchregister	UroTuning als weiterer Handelsfund; Sprachsuchläufe dokumentiert
Physisches Kontaktinventar	Keine Änderung
R12-LIST-907721	Unverändert; übergebener Listenbericht
Q1 / Q2	Unverändert
U2/01-Gegenzeile	Weiterhin nicht vollständig neu gelesen
S18-Halterseiten	Weiterhin ungeklärt
Matrixwerte 1 / 0	Keine neuen Einträge
Elektrische Kantenliste unverändert.

5. Folgeauftrag für beide Monica-Instanzen
Priorität bleibt jetzt die technische Topologie: Weitere Teileangebote bringen wenig zusätzlichen Nutzen; gesucht sind die U2-Gegenzeile, eine belastbare Sockelnummerierung und beide Seiten von S18.

# ZE2 / CE2 357 937 039 – nächster Rechercheauftrag

## Verbindlicher Sprachumfang
Deutsch, Englisch, Russisch, Polnisch, Chinesisch, Japanisch, Koreanisch und Thai.
Chinesisch vereinfacht und ergänzend traditionell.
Diesen vollständigen Umfang in jeder weiteren Übergabe beibehalten.
Tatsächliche Anfragen, erfolglose Abrufe und offene Sprachen unterscheiden.

## Neuer übergebener Originalbeleg
https://parts.vw.com/p/Volkswagen__/Fuse-and-Relay-Center/53040177/357937039.html

Laut Bericht im Original gelesen:
- Fuse and Relay Center
- Part Number: 357937039
- Supersession(s): 357-937-039
- Fuse Box. Relay and Fuse Plate.
- Fits Cabrio, Corrado
- LOWER.

Bedeutung:
Offizieller Katalogbeleg zur Teileidentität, kein interner Leiterbeleg.
Die Schreibweise mit Bindestrichen belegt keine technische Nachfolgeversion.
Keine Baujahre, Innenausführung oder vollständige Verwendungsliste gelesen.
Weitere reine Handelsangebote jetzt nachrangig behandeln.

## 1. Technische japanische und chinesische Suche vorziehen
Folgende Anfragen sind noch nicht ausgeführt:
- Golf CE2 内部配線図
- Golf 燃料ポンプリレー 端子配列
- Volkswagen Golf 保險絲盒 內部接線圖
- Golf 保险丝盒 内部接线图

Bei neueren Golf-Generationen als Fehlertreffern Golf 2/Golf 3 ergänzen.
Varianten der Modellschreibweise einzeln erproben.
Übersetzungsansichten nicht als eigenständige Originalquellen zählen.

## 2. Thai-Suche mit dokumentiertem Fehler fortsetzen
Bereits ausgewertet:
"357937039" กล่องฟิวส์
Ergebnis: englische Katalog- und Handelsseiten, keine Thai-Fachquelle.

Angestoßen, aber wegen Zeitüberschreitung nicht ausgewertet:
Volkswagen Golf แผนผังวงจร กล่องฟิวส์

Diese technische Anfrage erneut oder in kürzerer Form ausführen.
Einen technischen Abruffehler niemals als „keine Treffer“ ausweisen.

## 3. Koreanisch und übrige Sprachen gezielt vertiefen
Bereits ausgeführt:
Volkswagen Golf 내부 배선도 퓨즈 박스
Ergebnis: allgemeine englische Bild-/Diagnosetreffer, kein CE2-Leiterbeleg.

Neue kurze technische Suchansätze:
- Koreanisch: Golf 3 퓨즈 박스 배선도
- Deutsch: CE2 Sicherung 18 interne Verdrahtung
- Englisch: CE2 fuse 18 internal wiring
- Russisch: CE2 внутренняя схема
- Polnisch: CE2 połączenia wewnętrzne

Jede tatsächlich ausgeführte Anfrage protokollieren.
Keine pauschale Behauptung, alle Sprachen seien vollständig recherchiert.

## 4. Elektroda: Antwortbeitrag statt Threadanfang
https://www.elektroda.pl/rtvforum/topic3201928.html

Übergebener Suchauszug:
„Weź dowvolny schemat VW“ ist NICHT die bestätigte Schreibweise.
Für die Suche den tatsächlich übergebenen Wortlaut verwenden:
„Weź dowolny schemat VW, szare pole na górze, to właśnie
skrzynka bezpieczników/przekaźników.“

Autor, eigenes Datum und Beitragsnummer weiterhin unbekannt.
Suchübersichtsdatum nicht als Antwortdatum übernehmen.

Zweite übergebene Passage:
„a,b... to linie, które są powiązane z dalszą częścią schematu.
Na przykład na 1 stronie znajduje …“

Zunächst prüfen, ob diese zweite Passage überhaupt zum selben Thread gehört.
Nur tatsächlich gefundene öffentliche Beitragslinks und Anhänge verfolgen.
Kein erneuter identischer gekürzter Abruf ohne begründeten neuen Zugang.

## 5. Technische Kernziele
A. U2/01:
Vollständige unverfälschte Zeile mit Spaltenüberschriften und Quellenherkunft.

B. R12-LIST-907721:
Herkunft, Blickrichtung und geometrische Nummerierung der neun Positionen.
Textliche Listenpositionen nicht als physisch bestätigte Kammern behandeln.

C. S18:
Relaisausgang, beide Sicherungshalterkontakte und rückseitige Gegenkontakte.
Äußere Leitungen, Sicherung, Relais und herausnehmbare Brücken separat.
Kennungen einzeln oder in kleinen Gruppen:
J17, S18, M/02, G1/03, Z1, 30B.
Gleiche Funktionsangaben begründen keine feste Leiterkante.

D. Zielhardware:
Technischen Plan oder Messobjekt auf 357 937 039 beziehen.
Der offizielle Katalogeintrag allein verifiziert keine Innenausführung.

## 6. Belegregeln und Ausgabe
Übergebene Berichte, Suchauszüge, Originallektüre, Bildprüfung und Messung trennen.
Originalpassagen mit deutscher Übersetzung dokumentieren.
Anschlusskennungen nicht stillschweigend korrigieren.
Abhängige Tabellenwiedergaben nicht als unabhängige Bestätigungen zählen.
Keine URLs, Kommentar-IDs oder Seitenzahlen erfinden.
Keine Zugangsbeschränkungen umgehen.

Matrix:
1 nur bei nachgewiesener fester Verbindung am identifizierten nackten Grundträger.
0 nur bei geeignet nachgewiesener Trennung.
Sonst ?.
Q1 und Q2 bleiben Quellenreferenzen ohne physische Zielteilverifizierung.

Abgabe:
- Neue Originalbelege.
- Suchhinweise und Quellenabhängigkeiten.
- Sprachprotokoll mit Fehlern und offenen Aufgaben.
- Inventaränderungen getrennt von Kantenänderungen.
- Nächster Auftrag einschließlich aller acht Suchsprachen.

Ohne geeignete neue Leiterbelege:
„Elektrische Kantenliste unverändert.“

Monica
GPT-6 Astra
23 Sekunden nachgedacht
Call Skill: Google Search
Linkleser
11 Sekunden nachgedacht
Call Skill: Google Search
3 Sekunden nachgedacht
Linkleser
0 Sekunden nachgedacht
Denkprozess


Monica
GPT-6 Astra
Call Skill: Google Search
0 Sekunden nachgedacht
Ergebnis
Neu ist ein japanischer Originalbericht zur Fehlersuche an einem Golf Country. Er nennt das Kraftstoffpumpenrelais „No.80“, berichtete Durchgangsprüfungen sowie den Austausch des Sicherungs-/Relaisträgers. Die ausgegebene Passage enthält jedoch keine Anschlusskennungen, keine internen Leiterverbindungen und keine Grundträgerteilenummer.

Die vier priorisierten japanischen und chinesischen Suchanfragen wurden ausgeführt. Die chinesischen Ergebnisse betreffen überwiegend neuere Golf-Generationen.

Elektrische Kantenliste unverändert.

1. Neuer Originalinhalt: japanischer Golf-Country-Diagnosebericht
Fundstelle: VW GOLF COUNTRY ENTHUSIAST – Fehlersuche und Reparatur bei Motorstörungen

Merkmal	Im Abruf festgestellt
Seitentitel	ＶＷ ＧＯＬＦ ＣＯＵＮＴＲＹ ＥＮＴＨＵＳＩＡＳＴ
Beitragsüberschrift	エンジン不調原因調査＆修理
Datumsangabe an der Überschrift	'15/06/26 NEW!! – 26. Juni 2015
Autor	Im gelesenen Abschnitt nicht angegeben
Fahrzeugkontext	Golf Country; Baujahr und Motorkennbuchstabe nicht gelesen
Beitragsnummer	Keine Forumsbeitragsnummer; eigenständige Webseite
Grundträger 357 937 039	Im gelesenen Abschnitt nicht genannt
Tatsächlich gelesene Aussagen
Auswertung eines Schaltplans:

「まずは、配線図で燃料ポンプの運転条件を調べて」

Übersetzung:

„Zunächst habe ich anhand des Schaltplans die Betriebsbedingungen der Kraftstoffpumpe untersucht.“

Der Bericht erwähnt damit einen verwendeten Schaltplan. Ein Quellenverweis oder eine auswertbare Darstellung dieses Plans wurde im ausgegebenen Abschnitt nicht erschlossen.

Berichtete Durchgangsprüfung:

「コネクター＆ケーブルの導通確認で問題なし。」

Übersetzung:

„Bei der Durchgangsprüfung von Steckverbindern und Kabeln keine Probleme.“

Austausch des Pumpenrelais:

「燃料ポンプリレー"No.80"を交換しました。」

Übersetzung:

„Ich habe das Kraftstoffpumpenrelais ‚No.80‘ ausgetauscht.“

Austausch des Sicherungs-/Relaisträgers:

Der Verfasser berichtet anschließend, einen gebrauchten Sicherungs-/Relaisträger beschafft und eingebaut zu haben. Der Pumpenausfall sei danach erneut aufgetreten. Auch weitere Durchgangsprüfungen an pumpenbezogenen Leitungen und Anschlüssen hätten laut Bericht keine Auffälligkeiten ergeben.

Technische Einordnung
Dies ist ein eigener Diagnosebericht mit behaupteten Messungen und Teilewechseln, aber kein reproduzierbares Messprotokoll:

Messpunkte, Messwerte, Prüfstrom und Isolationszustand fehlen.
Keine Prüfung am identifizierten nackten Grundträger dokumentiert.
Keine Unterscheidung beider S18-Halterkontakte.
Keine Zuordnung zu M/02, G1/03, Z1 oder 30B.
Keine geometrische Sockelnummerierung.
Der Relaisaufdruck 80 ist weder eine Sockelnummer noch eine DIN-Klemme.
Die erwähnten Teilenummern 6N0 905 865 und 357 905 865 betreffen im Bericht den Zündanlassschalter, nicht den gesuchten Sicherungs-/Relaisträger.

Abrufgrenze: Die Ausgabe endet während des weiteren Diagnoseverlaufs. Die abschließende Fehlerursache wurde nicht gelesen. Wiederholte Bildbeschriftungen wie „Fuel Pomp Relays“ ersetzen keine Bildprüfung.

2. Neue Suchhinweise – nicht als Originalbelege übernommen
Japanisch: weitere passende Diagnoseansätze
Die Anfrage Golf 燃料ポンプリレー 端子配列 lieferte zusätzlich:

Fundstelle	Gelesener Suchauszug	Aussagegrenze
Yahoo!知恵袋: Golf 3, Baujahr 1993, keine 12 V an der Pumpe	Hinweise auf Leitungsunterbrechung, Kontakt- oder Masseprobleme zwischen Relais und Pumpe	Originalbeitrag nicht gelesen; keine interne Topologie
„VW ゴルフⅢ 燃料ポンプの交換“ – Pumpentausch	Nennt das Relais 167 unten rechts am Sicherungs-/Relaiskasten	Suchhinweis zur Einbaulage; keine geprüfte Kammeransicht
みんカラ: Austausch des Kraftstoffpumpenrelais	Vermutung des Verfassers, 67, 80 und 167 könnten gleich sein	Keine bestätigte Austauschbarkeit; Originalkontext nicht gelesen
Diese Quellen werden nicht mit R12-LIST-907721 zu einer elektrischen Bestätigung zusammengeführt.

Chinesisch: überwiegend falsche Fahrzeuggeneration
Die vereinfachte und traditionelle Suche lieferte vor allem:

Golf von 2011 beziehungsweise Golf VI;
Golf VII und VIII;
einen Scribd-Treffer zum Golf IV;
chinesische Übersetzungsansichten von Reddit.
Keiner dieser Suchauszüge lieferte einen passenden internen CE2-Leiterbeleg. Übersetzungsansichten mit tl=zh-hant beziehungsweise tl=zh-hans zählen nicht als eigenständige chinesische Originalquellen.

Der notwendige nächste Schritt ist eine Eingrenzung auf Golf II/Golf III, CE2 oder die Zielteilenummer, nicht die Übernahme der gefundenen neueren Sicherungspläne.

3. Elektroda: keine neue Antwort erschlossen
Der bekannte CE2-Thread 3201928 wurde nochmals abgerufen. Die Ausgabe endet erneut im Seitenkopf beziehungsweise bei den Teilen-Links.

Das war eine Wiederholung des bereits bekannten gekürzten Zugangs ohne technischen Erkenntnisgewinn und entsprach nicht der gewünschten Priorisierung.

Weiterhin nicht gelesen:

die Antwort zum grauen Feld;
Autor, Datum und Beitragsnummer dieser Antwort;
die Fortsetzungslinien-Passage im Original;
ein zugehöriger Plan oder Anhang.
Es wurde kein neuer alternativer Zugang gefunden.

4. Sprachprotokoll dieses Durchlaufs
Sprache	Tatsächlich ausgeführte Arbeit	Ergebnis
Deutsch	Keine neue Suche	Offen
Englisch	Keine neue Suche	Offen
Russisch	Keine neue Suche	Offen
Polnisch	Bekannten Elektroda-Thread erneut abgerufen; keine neue Suchanfrage	Nur Seitenkopf, kein Fortschritt
Japanisch	Golf CE2 内部配線図	Unter anderem unpassende CE-Verbindungstechnik und allgemeine Golf-Verkabelung
Japanisch	Golf 燃料ポンプリレー 端子配列	Golf-Country-Originalbericht erschlossen; weitere Diagnosehinweise
Chinesisch, traditionell	Volkswagen Golf 保險絲盒 內部接線圖	Überwiegend neuere Golf-Generationen
Chinesisch, vereinfacht	Golf 保险丝盒 内部接线图	Überwiegend neuere Golf-Generationen
Koreanisch	Keine neue Suche	Technische Vertiefung offen
Thai	Keine neue Suche	Zuvor fehlgeschlagene technische Anfrage weiterhin offen
Keine Zeichnung oder Fotografie visuell geprüft. Die angezeigten Fehlermeldungen im Verlauf werden nicht als ausgeführte Suchanfragen oder als Suchläufe ohne Treffer gezählt.

5. Quellenregister, Inventar und Kanten
Quellenregister
Neu einzutragen:

JP-COUNTRY-20150626

Japanischsprachiger Diagnosebericht.
Golf Country; Relaisaufdruck 80 ausdrücklich genannt.
Schaltplanauswertung und Durchgangsprüfungen berichtet.
Sicherungs-/Relaisträger ausgetauscht.
Messbedingungen, Planherkunft, Zielteilenummer und abschließende Diagnose offen.
Im gelesenen Abschnitt kein A2Resource-Verweis; daraus folgt noch kein gesicherter Nachweis vollständiger Quellenunabhängigkeit.
Der offizielle VW-Katalogeintrag bleibt in diesem Durchlauf übergebener Stand, nicht erneut selbst gelesen.

Inventar und elektrische Matrix
Bereich	Änderung
Physisch bestätigte Kontakte	Keine
Geometrie von Relaisplatz 12	Keine
U2/01-Gegenzeile	Nicht erschlossen
S18-Halterseiten	Nicht erschlossen
Q1 / Q2	Unverändert
Neue Matrixwerte 1 oder 0	Keine
Elektrische Kantenliste unverändert.

6. Nächster ausführbarer Auftrag
Der neue japanische Bericht ist ein konkreter Ansatz zur Ermittlung eines verwendeten Schaltplans, aber noch kein Beleg für dessen Inhalt oder die interne Verdrahtung des Zielteils.

## Ergebnis

**Neu erschlossen wurde ein japanischer Reparaturbericht mit ausdrücklicher Nennung `357_937_039`.** Er beschreibt die Fehlersuche an einem Golf Country, den Austausch des Sicherungs-/Relaisträgers und eine anschließend entdeckte Lötstellenbeschädigung **im herausnehmbaren Relais 32**.

Damit liegt ein neuer technischer Erfahrungsbericht mit textlichem Zielteilebezug vor — **aber kein Durchgangsbeleg am nackten Grundträger**. Außerdem wurde ein zweiter japanischer Originalbericht zur Position des Kraftstoffpumpenrelais gelesen.

**Elektrische Kantenliste unverändert.**

## 1. Neue Originalbelege

### 1.1 Japanischer Golf-Country-Bericht mit Zielteilenummer

**Fundstelle:** [VW GOLF COUNTRY ENTHUSIAST – Untersuchung und Reparatur einer Motorstörung](http://vwgolf2countryjp.web.fc2.com/fuelpomprelays_20150626.html)  
**Seitenüberschrift:** `【 エンジン不調原因調査＆修理 】'15/06/26 NEW!!`  
**Datumsangabe:** auf der Seite als `'15/06/26` angegeben.  
**Autor:** Im gelesenen Ausschnitt kein Personenname ausgewiesen.  
**Quellentyp:** Persönlicher Reparaturbericht, keine übersetzte Forumsansicht.

#### A. Ausdrücklicher Teilebezug

> 入手したヒューズ＆リレーパネルです。 VW品番：357_937_039 後期型ですね。

**Übersetzung:**

> „Dies ist der beschaffte Sicherungs- und Relaisträger. VW-Teilenummer: 357_937_039. Das ist die spätere Ausführung.“

Die Schreibweise **`357_937_039`** wird hier unverändert aus der Textausgabe übernommen.

**Einordnung:**

- Der Autor ordnet seinem beschafften Bauteil ausdrücklich die Zielteilenummer zu.
- „Spätere Ausführung“ ist eine **Einordnung des Verfassers**, keine verifizierte Variantengrenze.
- Die eingeprägte Teilenummer wurde **nicht auf einem Foto geprüft**.
- Fahrzeugkontext ist ein **Golf Country**; ein genaues Baujahr wurde im gelesenen Abschnitt nicht genannt.

#### B. Schaltplan und Durchgangsprüfung werden erwähnt

> まずは、配線図で燃料ポンプの運転条件を調べて…

**Übersetzung:**

> „Zunächst untersuchte ich anhand des Schaltplans die Betriebsbedingungen der Kraftstoffpumpe …“

Später:

> こうなれば、徹底的に燃ポン関係の配線や端子を探るしかないと考え、テスターで導通をしらべたのですが、どこも異常なし。

**Übersetzung:**

> „Nun blieb aus meiner Sicht nur, die Leitungen und Anschlüsse der Kraftstoffpumpe gründlich zu untersuchen. Ich prüfte mit einem Messgerät den Durchgang, fand aber nirgends eine Auffälligkeit.“

**Beleggrenze:** Keine Messpunktpaare, Widerstandswerte oder eindeutige Angaben zum Ausbauzustand. Insbesondere ist **keine Messung des identifizierten nackten Grundträgers dokumentiert**. Die pauschale Aussage „nirgends eine Auffälligkeit“ erzeugt weder Matrixwerte `1` noch `0`.

Der erwähnte Schaltplan wurde im ausgegebenen Inhalt **nicht als konkreter Dokumentlink erschlossen**.

#### C. Fehlerfund betrifft das eingesetzte Relais, nicht die ZE-Innenverdrahtung

Der Verfasser beschreibt zunächst den Austausch des Kraftstoffpumpenrelais **No.80**, anschließend des Zündanlassschalters und des Sicherungs-/Relaisträgers. Der Fehler tritt jeweils erneut auf.

Danach:

> ３２番のリレー…デジファントのコントロールリレーです。

**Übersetzung:**

> „Relais Nummer 32 … das Steuerrelais der Digifant.“

Zum geöffneten Relais:

> 改めて端子（No.30）を触ると確かに緩い感じ。…ハンダ付け部分に微細な亀裂があるではないですか！

**Übersetzung:**

> „Als ich den Anschluss (No.30) erneut berührte, fühlte er sich tatsächlich locker an. … An der Lötstelle war ein feiner Riss!“

Anschließend berichtet der Autor vom Entfernen des alten Lots und erneutem Verlöten.

**Wichtig:** `No.30` bezeichnet hier nach dem Text einen Anschluss **des geöffneten Relais 32**. Keine Übertragung auf eine ZE-Kammer, Listenposition oder einen neuen internen Grundträgerknoten.

**Abrufgrenze:** Die Ausgabe bricht nach der beschriebenen Lötstellenreparatur ab. Eine abschließende Erfolgskontrolle wurde nicht gelesen.

### 1.2 Japanischer Bericht zum Kraftstoffpumpenwechsel

**Fundstelle:** [燃料ポンプの交換 – Austausch der Kraftstoffpumpe](https://hekesiry.web.fc2.com/maintenance/fuel_pomp.html)  
**Datumsangabe:** September 2013.  
**Autor:** Auf der abgerufenen Seite kein Personenname ausgewiesen.  
**Fahrzeugzuordnung:** Der Suchtreffer bezeichnet die Seite als „VW ゴルフⅢ“; diese Modellangabe ist vom eigentlichen gelesenen Seitenkörper zu unterscheiden.

Originalpassage:

> ヒューズリレーボックス、下列右端の167番／燃料ポンプリレーを外し…

**Übersetzung:**

> „… das Relais Nummer 167 / Kraftstoffpumpenrelais ganz rechts in der unteren Reihe des Sicherungs-/Relaiskastens entfernen …“

**Erkenntniswert:** Eigenständiger japanischer Erfahrungsbericht mit einer textlichen Positionsbeschreibung des eingesetzten Relais.

**Nicht belegt:**

- ausdrückliche Steckplatznummer **12**;
- Kammernummerierung oder Blickrichtung einer Anschlusszeichnung;
- Teilenummer **357 937 039**;
- interne Verbindungen oder Sicherung-18-Halterseiten.

Die Positionsbeschreibung wird deshalb **nicht** zur geometrischen Verifizierung von R12-LIST-907721 verwendet.

## 2. Neue Suchhinweise und Quellenabhängigkeiten

### Weitere japanische Quelle

Die Anfrage `Golf CE2 内部配線図` lieferte:

[みんカラ: 室内配線の整理 – Ordnen der Innenraumverkabelung](https://minkara.carview.co.jp/userid/354998/car/260549/1698831/note.aspx)

Suchauszug:

> フォルクスワーゲン ゴルフ …（ゴルフ2）｜室内配線の整理

**Übersetzung:** „Volkswagen Golf … (Golf 2) – Ordnen der Innenraumverkabelung.“

**Status:** Nur Suchauszug gelesen. Möglicher Kabelbaum-/Einbaukontext; kein Hinweis auf einen bereits nachgewiesenen internen ZE-Plan.

### Neuer Dokumentkandidat aus der vereinfachten chinesischen Suche

Die Anfrage `Golf 保险丝盒 内部接线图` lieferte unter anderem:

[Scribd 741371360 – „Loom schematic“](https://www.scribd.com/document/741371360/Loom-schematic)

Angezeigter Suchtitel:

> “MK2 Golf Fuse Box and Loom Diagrams”

**Übersetzung:** „Golf-Mk2-Sicherungskasten- und Kabelbaumdiagramme.“

**Status:** Nur Suchtreffer. Inhalt, Titelherkunft, Lesbarkeit und CE1-/CE2-Zuordnung ungeprüft. Das ist **nicht** das bereits bekannte beschädigt extrahierte Dokument 520017984.

### Quellenabhängigkeit

- Bei den beiden japanischen Originalberichten wurde im gelesenen Text **keine Wiedergabe der bekannten CE2-Neuner-Liste** erkannt.
- Daraus folgt keine gesicherte Unabhängigkeit aller verwendeten technischen Informationen. Insbesondere bleibt die Herkunft des im Country-Bericht erwähnten Schaltplans unbekannt.
- Reddit-Treffer mit `?tl=ja` wurden als Übersetzungsansichten erkannt und nicht als japanische Originalbelege gezählt.
- Die chinesischen Anfragen lieferten überwiegend anderssprachige, übersetzte oder thematisch unpassende Ergebnisse. Eine chinesische Anfrage macht diese Quellen nicht zu chinesischen Originalquellen.
- Der offizielle VW-Katalogbeleg bleibt in diesem Durchlauf ein **übergebener Originalbericht**; er wurde nicht erneut abgerufen.

## 3. Sprachprotokoll

Alle folgenden vier Anfragen wurden tatsächlich ausgeführt und ausgewertet:

| Sprache | Tatsächliche Anfrage | Ergebnis |
|---|---|---|
| Japanisch | `Golf CE2 内部配線図` | Golf-2-Innenraumverkabelung als Suchhinweis; außerdem themenfremde Treffer |
| Japanisch | `Golf 燃料ポンプリレー 端子配列` | Zwei anschließend gelesene japanische Reparaturberichte |
| Chinesisch, traditionell | `Volkswagen Golf 保險絲盒 內部接線圖` | Unter anderem Golf 6, neuere Fahrzeuge und Übersetzungsseiten; kein geeigneter CE2-Beleg erschlossen |
| Chinesisch, vereinfacht | `Golf 保险丝盒 内部接线图` | Neuer Scribd-Dokumentkandidat; ansonsten überwiegend Diagramm-Aggregatoren |

### Offene Sprachen und Fehlerstatus

| Sprache | Status dieses Durchlaufs |
|---|---|
| Deutsch | Keine neue Anfrage; technische Vertiefung offen |
| Englisch | Keine eigene neue Anfrage; englische Suchtreffer nicht als englischer Recherchelauf zählen |
| Russisch | Keine neue Anfrage; offen |
| Polnisch | Keine neue Anfrage; Elektroda-Antworten weiterhin offen |
| Chinesisch | Beide Schriftvarianten begonnen; Eingrenzung auf Golf 2/Golf 3 noch nicht ausgeführt |
| Japanisch | Zwei technische Originalseiten gelesen; Plan- und Kammerprüfung offen |
| Koreanisch | Neue Anfrage `Golf 3 퓨즈 박스 배선도` noch nicht ausgeführt |
| Thai | Technische Anfrage in diesem Durchlauf **nicht erneut ausgeführt** |

**Thai-Fehlerprotokoll:** Die frühere Zeitüberschreitung bei `Volkswagen Golf แผนผังวงจร กล่องฟิวส์` ist ein **übergebener technischer Fehler**, kein negatives Suchergebnis. Sie bleibt unerledigt; in diesem Durchlauf gab es keinen ausgewerteten Wiederholungsversuch.

Die in der Ausgabe sichtbaren allgemeinen Fehlermeldungen liefern keine belastbaren Suchergebnisse und werden nicht als erfolglose Fachsuchen gezählt.

## 4. Änderungen an Inventar und Kanten

### Quellenregister

Neu aufzunehmen:

| Quelle | Belegklasse | Relevanz |
|---|---|---|
| Golf-Country-Bericht, 26.06.2015 laut Seitenangabe | Originaltext eines Reparaturberichts | Textliche Nennung `357_937_039`; Fahrzeugdiagnose; Fehler im Relais |
| Kraftstoffpumpenwechsel, September 2013 | Originaltext eines Reparaturberichts | Relais 167, untere Reihe rechts |
| Scribd 741371360 | Suchhinweis | Möglicher Golf-Mk2-Kabelbaum-/Sicherungskastenplan |
| Minkara-Innenraumverkabelung | Suchhinweis | Golf-2-Verkabelungskontext |

### Physisches Inventar

**Keine Änderung.** Keine Bilder visuell geprüft, keine neuen Kontakte identifiziert, keine Sicherungshalterseiten unterschieden.

### Elektrische Kanten

**Keine Änderung.**

- U2/01 weiterhin nicht neu vollständig gelesen.
- Herkunft und Geometrie der Neuner-Liste weiterhin offen.
- S18 weiterhin ohne beide nachgewiesenen Halterseiten.
- Q1/Q2 bleiben Quellenreferenzen ohne physische Zielteilverifizierung.
- Keine neuen `1` oder `0`; ungeklärte Beziehungen bleiben `?`.

**Elektrische Kantenliste unverändert.**

## 5. Neuer ausführbarer Folgeauftrag für Monica

> ### Verbindlicher Sprachumfang
>
> **Deutsch, Englisch, Russisch, Polnisch, Chinesisch, Japanisch, Koreanisch und Thai.** Chinesisch vereinfacht und ergänzend traditionell. Diesen vollständigen Umfang in jeder weiteren Übergabe beibehalten. Tatsächliche Anfragen, technische Fehler, nicht ausgewertete Abrufe und offene Aufgaben getrennt protokollieren.
>
> ### 1. Thai-Wiederholung und koreanische Vertiefung zuerst
>
> Noch auszuführen:
>
> - `Volkswagen Golf แผนผังวงจร กล่องฟิวส์`
> - Bei erneutem Fehler kürzer: `Golf 3 แผนผังวงจร กล่องฟิวส์`
> - `Golf 3 퓨즈 박스 배선도`
>
> Die übergebene Thai-Zeitüberschreitung bleibt ein Abruffehler, bis ein Wiederholungsversuch ausgewertet wurde.
>
> ### 2. Neuen japanischen Teilebeleg gezielt erschließen
>
> http://vwgolf2countryjp.web.fc2.com/fuelpomprelays_20150626.html
>
> Neu im Original gelesen: Golf-Country-Diagnosebericht; Text nennt `357_937_039`; ein verwendeter Schaltplan wird erwähnt. Der Fehlerfund betrifft eine Lötstelle an `No.30` im geöffneten Relais 32, nicht eine ZE-Leiterkante.
>
> Suche nach tatsächlich verfügbaren Bild-/Planlinks oder einer Quellenangabe auf dieser Seite und ihrer vorhandenen Navigation. **Keinen erneuten identischen gekürzten Textabruf als Fortschritt zählen.**
>
> Nur bei tatsächlich sichtbaren Bildern Teilenummer, Blickrichtung und Kennungen erfassen. Die bisherigen Textplatzhalter „Fuel Pomp Relays“ sind keine Bildprüfung. Ein vollständiger Reparaturabschluss wäre Quellenkontext, aber kein vorrangiger Leiterbeleg.
>
> ### 3. Neuen Dokumentkandidaten prüfen
>
> https://www.scribd.com/document/741371360/Loom-schematic
>
> Bisher nur Suchtreffer „MK2 Golf Fuse Box and Loom Diagrams“. Prüfe öffentlich zugänglichen Inhalt auf:
>
> - CE1 oder CE2;
> - Originaltitel, Autor und Planherkunft;
> - U2/01 mit Spaltenüberschriften;
> - J17/S18 und getrennte Sicherungshalterseiten;
> - Grundträgerteilenummer.
>
> Keine Zugangsbeschränkungen umgehen. Extraktionsfehler nicht stillschweigend korrigieren. Eine bekannte Tabellenkopie bleibt abhängig.
>
> ### 4. Chinesisch eingrenzen und übrige Sprachen bearbeiten
>
> Noch nicht ausgeführte nächste Anfragen:
>
> - Traditionell: `Golf 2 保險絲盒 內部接線圖`
> - Vereinfacht: `Golf 3 保险丝盒 内部接线图`
> - Japanisch: `ゴルフ2 ヒューズボックス 内部配線図`
> - Deutsch: `CE2 Sicherung 18 interne Verdrahtung`
> - Englisch: `CE2 fuse 18 internal wiring`
> - Russisch: `CE2 внутренняя схема`
> - Polnisch: `CE2 połączenia wewnętrzne`
>
> Kurze Kombinationen verwenden; Modellschreibweisen einzeln variieren. **J17, S18, M/02, G1/03, Z1 und 30B** bei Bedarf einzeln ergänzen.
>
> ### 5. Elektroda nur über einen neuen belegten Zugang
>
> https://www.elektroda.pl/rtvforum/topic3201928.html
>
> Bestätigten Suchwortlaut verwenden: **„Weź dowolny schemat VW“**, nicht „dowvolny“. Autor, eigenes Datum und Beitragsnummer fehlen weiterhin.
>
> Bei der Passage über `a,b...` zunächst die Threadzugehörigkeit klären. Nur tatsächlich gefundene öffentliche Beitragslinks und Anhänge verfolgen; Suchübersichtsdatum nicht als Antwortdatum übernehmen.
>
> ### 6. Elektrische Belegregeln und Abgabe
>
> Textliche Listenposition, Steckplatz, physische Kammer, DIN-Klemme und Strompfadnummer getrennt halten. Relais, Sicherungen, Kabelbaum und herausnehmbare Brücken sind keine festen Grundträgerkanten.
>
> `1` nur bei nachgewiesener fester Verbindung am identifizierten nackten Grundträger; `0` nur bei geeignet nachgewiesener Trennung; sonst `?`. Q1/Q2 bleiben Quellenreferenzen ohne physische Zielteilverifizierung.
>
> Originallektüre, Suchauszug, übergebenen Bericht, Bildprüfung und Messung getrennt dokumentieren. Originalpassagen mit deutscher Übersetzung und unveränderten Anschlusskennungen angeben.
>
> Abgabe mit Quellenabhängigkeiten, Sprach- und Fehlerprotokoll, getrennten Inventar-/Kantenänderungen und Folgeauftrag **einschließlich aller acht Suchsprachen**. Ohne geeignete neue Leiterbelege: **„Elektrische Kantenliste unverändert.“**

Monica
GPT-6 Astra
14 Sekunden nachgedacht
Linkleser
Call Skill: Google Search
3 Sekunden nachgedacht
Call Skill: Google Search
0 Sekunden nachgedacht
Denkprozess


Monica
GPT-6 Astra
Call Skill: Google Search
8 Sekunden nachgedacht
Linkleser
0 Sekunden nachgedacht
Ergebnis dieses Durchlaufs
Die zuvor fehlgeschlagene Thai-Suche wurde diesmal mit auswertbaren Ergebnissen wiederholt. Eine anschließende Eingrenzung auf Golf 3 lieferte einen neuen Scribd-Dokumentkandidaten. Beide geprüften Scribd-Dokumente waren jedoch nicht inhaltlich zugänglich.

Die koreanische Vertiefung wurde ausgeführt. Die russische Anfrage ohne Fahrzeugbezug lieferte überwiegend themenfremde Treffer.

Keine neuen technischen Originalbelege. Elektrische Kantenliste unverändert.

1. Dokumentabrufe: keine Planinhalte zugänglich
Dokument	Tatsächlich ausgegebener Inhalt	Konsequenz
Scribd 741371360 – „Loom-schematic“	Fehlermeldung: „A required part of this site couldn’t load.“	Keine Prüfung von CE1/CE2, Autor, Planherkunft oder Anschlüssen möglich
Scribd 543644233 – „Central-eletrica-Golf-MK3“	Dieselbe Ladefehlermeldung, zusätzlich Browserprüfhinweis	Ebenfalls keine technischen Inhalte gelesen
Abgrenzung: Das sind dokumentierte Zugangs-/Ladeprobleme, keine beschädigten Tabellenextraktionen wie beim zuvor beschriebenen Dokument 520017984. Die konkrete Ursache ist nicht festgestellt. Es wurden keine Zugangsbeschränkungen umgangen.

2. Neue Suchhinweise
A. Thai: Wiederholung erfolgreich, zunächst falsche Generationen
Ausgeführt:

Volkswagen Golf แผนผังวงจร กล่องฟิวส์

Sinngemäß: Volkswagen Golf, Schaltplan, Sicherungskasten.

Die ausgegebenen Suchtreffer betreffen unter anderem:

Golf VI GTI, 2009–2013;
Golf VII, 2013–2020;
übersetzte Quora-/JustAnswer-Seiten;
einen Reddit-Beitrag mit ?tl=th.
Ergebnis: Der neue Suchlauf lieferte auswertbare Treffer; die frühere Zeitüberschreitung bleibt als historischer Fehler dokumentiert. Kein passender CE2-Leiterbeleg wurde gefunden. Die Ausgabe war am Ende abgeschnitten; eine vollständige Auswertung aller Treffer wird nicht behauptet.

B. Thai: Eingrenzung auf Golf 3 bringt Dokumentkandidaten
Zusätzlich ausgeführt:

"Golf 3" กล่องฟิวส์

Neuer Treffer:

Scribd 543644233 – „Central-eletrica-Golf-MK3“

Angezeigter Suchtitel:

“Golf 3 Fuse Box Diagram Details”

Suchauszug:

“This document provides a summary of the central electric fuse box layout for Volkswagen Golf, Jetta, Passat, Cabrio, Corrado, …”

Übersetzung:

„Dieses Dokument bietet eine Zusammenfassung der Anordnung des Zentralelektrik-Sicherungskastens für Volkswagen Golf, Jetta, Passat, Cabrio, Corrado, …“

Einordnung: Mögliche weitere Wiedergabe einer bekannten CE2-Übersicht. Titelherkunft, tatsächlicher Inhalt und Quellenabhängigkeit sind ungeprüft. Die ähnliche Fahrzeugaufzählung allein beweist keine Übernahme von A2Resource.

Der anschließende Originalabruf lieferte nur die oben dokumentierte Fehlermeldung. Keine U2-Zeile oder Relaisliste gelesen.

C. Koreanisch: technische Vertiefung ohne passenden CE2-Fund
Ausgeführt:

Golf 3 퓨즈 박스 배선도

Sinngemäß: Golf 3, Sicherungskasten, Verdrahtungsplan.

Die Ergebnisse enthielten allgemeine Nachrüst-/Sicherungsanleitungen, übersetzte Seiten und einen koreanischen Golf-VI-Treffer:

Daum: „골프6세대 휴즈박스 배선도“

Übersetzung des Titels:

„Verdrahtungsplan des Sicherungskastens der sechsten Golf-Generation.“

Nur Suchauszug gelesen. Wegen der ausdrücklich anderen Generation nicht als Zielhardwarequelle weiterverfolgt. Die Zahl 3 in der Anfrage hat die Ergebnisse nicht zuverlässig auf Golf III begrenzt.

D. Russisch: Anfrage zu unspezifisch
Ausgeführt:

CE2 внутренняя схема

Sinngemäß: CE2, interne Schaltung.

Die Ergebnisse betrafen überwiegend Boss-CE-2-Gitarreneffekte und andere Elektronik.

Ergebnis: Kein verwertbarer VW-Quellenhinweis. Für die nächste Anfrage ist ein ausdrücklicher Fahrzeugbezug erforderlich. Das Suchergebnis sagt nichts über die Existenz russischer CE2-Unterlagen aus.

3. Übergebener Stand und Quellenabhängigkeiten
Die japanischen Reparaturberichte wurden in diesem Durchlauf nicht erneut geprüft. Übernommen bleiben insbesondere:

die textliche Nennung 357_937_039 im Golf-Country-Bericht;
der berichtete Lötstellenfehler im herausnehmbaren Relais 32;
die Positionsbeschreibung des Relais 167 im zweiten Bericht.
Daraus entstehen weiterhin keine Grundträgerkanten.

Für den neuen Scribd-Kandidaten ist weder eine unabhängige Herkunft noch eine Abhängigkeit bestätigt. Automatische Übersetzungsansichten und mehrfach indexierte Inhalte zählen nicht als unabhängige Quellen.

4. Sprach- und Fehlerprotokoll
Sprache	Arbeit in diesem Durchlauf	Status
Deutsch	Keine neue Anfrage	Offen
Englisch	Englische Suchauszüge gelesen; keine eigene Anfrage	Technische Suche offen
Russisch	CE2 внутренняя схема	Ausgewertet; themenfremde Treffer
Polnisch	Keine neue Anfrage, kein Elektroda-Abruf	Originalantworten offen
Chinesisch, vereinfacht	Keine neue Anfrage	Golf-II/III-Eingrenzung offen
Chinesisch, traditionell	Keine neue Anfrage	Golf-II/III-Eingrenzung offen
Japanisch	Keine neue Anfrage oder Originallektüre	Plan-/Bildlinks offen
Koreanisch	Golf 3 퓨즈 박스 배선도	Ausgewertet; kein passender CE2-Beleg
Thai	Zwei oben protokollierte Anfragen	Ausgewertet; neuer Dokumentkandidat
Fehlerstatus: Zwei Scribd-Ladefehler. Keine neue Thai-Zeitüberschreitung. Allgemeine Fehlermeldungen im Gespräch werden nicht als ausgeführte Fachsuchen gezählt.

5. Inventar und Kanten
Quellenregister: Scribd 543644233 als ungeprüfter Dokumentkandidat ergänzt; Abruffehler beider Dokumente erfasst.
Physisches Inventar: keine Änderung; keine Bildprüfung.
U2/01, R12-Geometrie und beide S18-Halterseiten: weiterhin offen.
Q1/Q2: unverändert.
Matrix: keine neuen 1 oder 0; ungeklärte Beziehungen bleiben ?.
Elektrische Kantenliste unverändert.

6. Folgeauftrag für beide Monica-Instanzen
Der Fortschritt dieses Laufs betrifft die abgearbeiteten Sprachsuchen und dokumentierten Zugangsgrenzen, nicht die elektrische Rekonstruktion.

## Ergebnis

**Der aktuelle Originalabruf ergänzt den übergebenen Stand zu JP-COUNTRY-20150626:** Die Seite nennt ausdrücklich **`357_937_039`** und beschreibt einen Fehlerfund **im herausnehmbaren Relais 32**. Der Abschluss der Reparatur bleibt abgeschnitten.

Außerdem wurde über einen tatsächlich vorhandenen Link ein japanischer Bericht von **Mai 2011** erschlossen, der die textliche Lagebeschreibung des Kraftstoffpumpenrelais 167 enthält. Eine Abbildung oder Kammergeometrie wurde nicht geprüft.

Die offenen technischen Suchen auf **Thai und Koreanisch wurden ausgeführt**. Die neue traditionell-chinesische Anfrage scheiterte dagegen an einer Zeitüberschreitung.

**Elektrische Kantenliste unverändert.**

## 1. Selbst geprüfte Originalbelege

### A. JP-COUNTRY-20150626: Teilebezug und Fehlerfund jetzt direkt gelesen

**Quelle:** [Golf Country – エンジン不調原因調査＆修理](http://vwgolf2countryjp.web.fc2.com/fuelpomprelays_20150626.html)  
**Seitenangabe:** `'15/06/26`  
**Autor, Baujahr und Motor:** Im abgerufenen Abschnitt nicht festgestellt.

Der erneute Abruf ist **keine neue Quellenentdeckung**. Er erlaubt aber, die im aktuellen Übergabetext noch fehlenden Passagen direkt zu prüfen.

#### Textliche Teilenummer

> 入手したヒューズ＆リレーパネルです。 VW品番：357_937_039 後期型ですね。

**Übersetzung:**

> „Dies ist der beschaffte Sicherungs- und Relaisträger. VW-Teilenummer: 357_937_039. Das ist die spätere Ausführung.“

**Einordnung:**

- Damit ist die Zielteilenummer **im Originaltext** gelesen.
- Keine fotografische Prüfung einer eingeprägten Teilenummer.
- „Spätere Ausführung“ bleibt die Aussage des Verfassers, keine belegte Variantengrenze.
- Die Textzuordnung identifiziert noch keine interne Leiterstruktur.

#### Beschriebener Fehlerfund

> ３２番のリレーはどうだったっけ？ デジファントのコントロールリレーです。

**Übersetzung:**

> „Was war eigentlich mit Relais Nummer 32? Das ist das Digifant-Steuerrelais.“

Anschließend:

> 改めて端子（No.30）を触ると確かに緩い感じ。…ハンダ付け部分に微細な亀裂があるではないですか！

**Übersetzung:**

> „Als ich den Anschluss (No.30) erneut berührte, fühlte er sich tatsächlich locker an. … An der Lötstelle war ein feiner Riss!“

Der Autor berichtet danach, das alte Lot entfernt und die Stelle erneut verlötet zu haben.

**Aussagegrenze:** Dieser Befund betrifft das **geöffnete Relais 32**, nicht den nackten Sicherungs-/Relaisträger. `No.30` wird nicht als ZE-Kammer oder R12-Listenposition übernommen. Eine erfolgreiche abschließende Fahrzeugprüfung wurde nicht gelesen: Der Abruf bricht bei „早速ハ…“ ab.

#### Schaltplan und Bilder

Im gelesenen Text wird die Nutzung eines Schaltplans erwähnt. **Ein konkreter Planlink wurde nicht ausgegeben.** Wiederholte Texte wie „Fuel Pomp Relays“ erlauben keine Bildprüfung.

Über die vorhandene [Wartungsnavigation](http://vwgolf2countryjp.web.fc2.com/maintenance.html) wurden diese tatsächlichen weiterführenden Links gefunden:

- [Motor/Elektrik Nr. 1](http://vwgolf2countryjp.web.fc2.com/mainte_engine.html)
- [Motor/Elektrik Nr. 2](http://vwgolf2countryjp.web.fc2.com/mainte_engine_2.html)

Die beiden Unterseiten wurden **noch nicht abgerufen**. Sie sind Navigationsansätze, keine nachgewiesenen Planfundstellen.

### B. Japanischer Pumpenbericht: Originalpassage bestätigt

**Quelle:** [燃料ポンプの交換 – Austausch der Kraftstoffpumpe](https://hekesiry.web.fc2.com/maintenance/fuel_pomp.html)  
**Datum auf der Seite:** September 2013.

Original:

> ヒューズリレーボックス、下列右端の167番／燃料ポンプリレー

**Übersetzung:**

> „Relais Nummer 167 / Kraftstoffpumpenrelais ganz rechts in der unteren Reihe des Sicherungs-/Relaiskastens.“

Damit ist der übergebene Suchhinweis jetzt direkt am Seiteninhalt geprüft.

**Nicht festgestellt:** Zielteilenummer, ausdrückliche Steckplatznummer 12, Kammernummerierung oder geometrische Blickrichtung. Der gelesene Seitenkörper nennt das genaue Fahrzeugmodell nicht; die übergebene Golf-III-Zuordnung bleibt davon getrennt.

Die Seite berichtet außerdem, dass der Pumpentausch das ursprüngliche Startproblem zunächst nicht beseitigt habe. Daraus entsteht kein Grundträgerbefund.

### C. Neu erschlossener verlinkter Bericht von Mai 2011

Der Pumpenbericht verlinkt ausdrücklich auf:

**[燃料フィルター – Kraftstofffilter](https://hekesiry.web.fc2.com/maintenance/fuel_filter.html)**  
**Datum auf der Seite:** Mai 2011.

Original:

> ヒューズリレーボックス、下列右端の167番が燃料ポンプリレーだ。その上がLED用のウィンカーリレーだ。

**Übersetzung:**

> „Im Sicherungs-/Relaiskasten ist Nummer 167 ganz rechts in der unteren Reihe das Kraftstoffpumpenrelais. Darüber befindet sich das Blinkrelais für LED-Blinker.“

**Erkenntniswert:** Eine tatsächlich verlinkte frühere Fundstelle für dieselbe Lagebeschreibung.

**Abhängigkeit:** Gleiche Website; der Bericht von 2013 verweist auf diesen Beitrag. **Keine unabhängige Zweitbestätigung.** Die erwähnte LED-Blinker-Ausstattung gehört zum beschriebenen Fahrzeugzustand und ist kein allgemeiner Serienbeleg.

In der Textausgabe erscheinen leere Tabellenzellen, aber keine auswertbaren Bildansichten. Daher **keine sichtbare Beschriftung oder Kontaktgeometrie geprüft**.

## 2. Neue Suchhinweise

### Thai: technische Anfrage erfolgreich ausgewertet

**Anfrage:** `Golf 3 แผนผังวงจร กล่องฟิวส์`

Neben unpassenden Treffern erschien ein [thailändisches Handbuchangebot](http://www.tkmanual.com/product/1277/cd-%E0%B8%84%E0%B8%B9%E0%B9%88%E0%B8%A1%E0%B8%B7%E0%B8%AD-%E0%B8%A7%E0%B8%87%E0%B8%88%E0%B8%A3%E0%B9%84%E0%B8%9F%E0%B8%9F%E0%B9%89%E0%B8%B2-wiring-diaram-volkswagen-golf-jetta-1998-12).

Suchauszug:

> คู่มือ วงจรไฟฟ้า … VOLKSWAGEN Golf, Jetta 1998-12 … ภาษา : สเปน (Spanish)

**Übersetzung:**

> „Handbuch, elektrische Schaltpläne … VOLKSWAGEN Golf, Jetta 1998-12 … Sprache: Spanisch.“

**Status:** Nur Suchauszug; Handelsangebot, keine gelesenen Pläne. Die Angabe `1998-12` bleibt unverändert und wird nicht zu einer gesicherten Modelljahresspanne umgedeutet. Kein CE2-Zielhardwarebeleg.

Die frühere Thai-Zeitüberschreitung bleibt im Fehlerverlauf erhalten; dieser **kürzere Wiederholungsansatz wurde nun ausgewertet**.

### Koreanisch: zwei neue Dokumentkandidaten

**Anfrage:** `Golf 3 퓨즈 박스 배선도`

Gefunden wurden unter anderem:

- [Scribd 455337376 – GOLF3-pdf](https://it.scribd.com/document/455337376/GOLF3-pdf), Suchtitel „System Wiring Diagrams Article Text“.
- [Scribd 718081032 – golf-mk3-diagram](https://de.scribd.com/document/718081032/golf-mk3-diagram), Suchtitel „VW Golf MK3 Wiring and Fuse Diagrams“.

**Status:** Ausschließlich Suchtreffer. Keine Originallektüre, keine Planprüfung, keine bestätigte CE2- oder Teilenummernzuordnung. Die lokalisierten Scribd-Adressen sind keine koreanischen Originalquellen und begründen keine Unabhängigkeit.

## 3. Sprach- und Fehlerprotokoll

| Sprache | Tatsächliche Arbeit dieses Durchlaufs | Ergebnis / offen |
|---|---|---|
| **Deutsch** | `CE2 Sicherung 18 interne Verdrahtung` | Ausgewertet; überwiegend Gebäudeinstallation statt Fahrzeugtechnik. Kein geeigneter Treffer. |
| **Englisch** | Keine eigene Suchanfrage | Technische Suche offen. |
| **Russisch** | Keine Anfrage | Offen. |
| **Polnisch** | Keine Anfrage; Elektroda nicht erneut abgerufen | Antwortbeiträge und Threadzugehörigkeit der zweiten Passage offen. |
| **Chinesisch, vereinfacht** | Keine Anfrage | Generationseingrenzung offen. |
| **Chinesisch, traditionell** | `"Golf 2" 保險絲盒 接線圖` | **Zeitüberschreitung; keine Ergebnisse ausgewertet.** |
| **Japanisch** | Zwei übergebene Seiten und zwei tatsächlich verlinkte Seiten abgerufen; keine Suchanfrage | Originaltext und Navigation geprüft; indexierte Zusatzpassagen und Bilder offen. |
| **Koreanisch** | `Golf 3 퓨즈 박스 배선도` | Ausgewertet; neue Dokumentkandidaten, keine technische Originallektüre. |
| **Thai** | `Golf 3 แผนผังวงจร กล่องฟิวส์` | Ausgewertet; kein geeigneter CE2-Plan erschlossen. |

**Technischer Abruffehler und unergiebige Suche bleiben getrennt.** Keines dieser Ergebnisse beweist, dass passende Unterlagen nicht existieren.

## 4. Quellenregister, Inventar und Kanten

### Registeränderungen

- **JP-COUNTRY-20150626:** Zielteilenummer im Text direkt bestätigt; Fehlerfund im Relais 32 gelesen; Abschluss weiterhin abgeschnitten.
- **JP-PUMP-201309:** Originalpassage zur Lage von Relais 167 geprüft.
- **JP-FILTER-201105:** Neu erschlossener, ausdrücklich verlinkter Vorläuferbericht; abhängig vom selben Website-Kontext.
- **Scribd 455337376 / 718081032:** Neue, ungeprüfte Plan-Suchhinweise.

### Physisches Inventar

**Keine Änderung.** Keine Kammer, Sicherungshalterseite oder interne Stromschiene neu identifiziert.

### Elektrische Kanten

**Keine Änderung.**

- U2/01 weiterhin nicht vollständig neu gelesen.
- R12-LIST-907721 weiterhin ohne bestätigte Geometrie.
- S18 weiterhin ohne getrennte Halterkontakte und Gegenkontakte.
- Q1/Q2 bleiben Quellenreferenzen ohne physische Zielteilverifizierung.
- Keine neuen `1` oder `0`; ungeklärte Beziehungen bleiben `?`.

**Elektrische Kantenliste unverändert.**

## 5. Nächster ausführbarer Folgeauftrag

> ### Verbindlicher Sprachumfang
> **Deutsch, Englisch, Russisch, Polnisch, Chinesisch, Japanisch, Koreanisch und Thai.** Chinesisch vereinfacht und ergänzend traditionell. Diesen Umfang in jeder weiteren Übergabe vollständig beibehalten. Anfragen, erfolgreiche Auswertungen, Abruffehler und offene Arbeiten getrennt protokollieren.
>
> ### 1. Fehler und neue Dokumentkandidaten zuerst
> - Die traditionell-chinesische Anfrage `"Golf 2" 保險絲盒 接線圖` endete mit Zeitüberschreitung. Erneut oder kürzer ausführen; nicht als „keine Treffer“ behandeln.
> - Öffentlich zugängliche Inhalte von **Scribd 455337376** und **718081032** prüfen. Die tatsächlichen Links stehen im Bericht.
> - Zunächst Originaltitel, Planherkunft, Modelljahr, CE1/CE2 und Lesbarkeit klären. Danach gezielt **U2/01, J17, S18, M/02, G1/03, Z1, 30B** suchen. Such- und automatisch erzeugte Dokumenttitel nicht als Planinhalt zählen.
>
> ### 2. Japanische Navigation statt erneutem identischem Abruf
> Tatsächlich gefundene, noch ungelesene Seiten:
> - http://vwgolf2countryjp.web.fc2.com/mainte_engine.html
> - http://vwgolf2countryjp.web.fc2.com/mainte_engine_2.html
>
> Nach einem konkreten Schaltplanverweis oder öffentlich zugänglichen Zeichnungslink suchen. Keine Bilddateinamen erraten. JP-COUNTRY-20150626 nennt im Originaltext `357_937_039`; die gelesene Lötstellenbeschädigung betrifft **Relais 32**, nicht den Grundträger. Reparaturabschluss weiterhin offen.
>
> ### 3. Kurze mehrsprachige technische Folgeanfragen
> Folgende Vorschläge sind noch nicht ausgeführt:
>
> | Sprache | Nächster Suchansatz |
> |---|---|
> | Deutsch | `"CE2" "Golf" "S18"` |
> | Englisch | `"CE2" "fuse 18" wiring` |
> | Russisch | `"CE2" внутренняя схема` |
> | Polnisch | `"CE2" połączenia wewnętrzne` |
> | Chinesisch, vereinfacht | `"CE2" 大众 电路图` |
> | Chinesisch, traditionell | `"Golf 3" 保險絲盒 繼電器` |
> | Japanisch | `"ゴルフ2" 配線図 燃料ポンプ` |
> | Koreanisch | `"Golf 3" 연료 펌프 릴레이 배선도` |
> | Thai | `"Golf 3" วงจร รีเลย์ปั๊มน้ำมันเชื้อเพลิง` |
>
> ### 4. Elektroda separat
> Keinen erneuten identischen Seitenkopfabruf. Den korrekten Wortlaut **„Weź dowolny schemat VW“** verwenden und nach einem tatsächlichen Antwortlink suchen. Autor, eigenes Datum und Beitragsnummer fehlen. Die Passage über `a,b...` erst nach belegter Threadzugehörigkeit zuordnen.
>
> ### 5. Belegregeln und Abgabe
> Originallektüre, Suchauszug, übergebenen Bericht, Bildprüfung und Messung trennen. Originalpassagen deutsch übersetzen, Kennungen unverändert lassen. Abhängige Wiedergaben nicht mehrfach als Bestätigung zählen.
>
> **Kernziele:** U2/01 mit Spaltenüberschriften; Herkunft und Geometrie der Neuner-Liste; beide S18-Halterkontakte mit getrennten Gegenkontakten; technischer Bezug auf **357 937 039**.
>
> Relais, Sicherungen, äußere Leitungen und herausnehmbare Brücken separat behandeln. `1` nur bei nachgewiesener fester Verbindung am identifizierten nackten Grundträger; `0` nur bei geeignet nachgewiesener Trennung; sonst `?`.
>
> Abschluss mit Sprach-/Fehlerprotokoll, Quellenabhängigkeiten, getrennten Inventar- und Kantenänderungen sowie Folgeauftrag mit **allen acht Suchsprachen**. Ohne geeignete Leiterbelege: **„Elektrische Kantenliste unverändert.“**

Monica
GPT-6 Astra
51 Sekunden nachgedacht
Linkleser
Call Skill: Google Search
23 Sekunden nachgedacht
Call Skill: Google Search
36 Sekunden nachgedacht
Linkleser
2 Sekunden nachgedacht
Call Skill: Google Search
0 Sekunden nachgedacht
Ergebnis
Neu gefunden wurde eine direkt zugängliche Quellenadresse für die CE2-Tabelle mit U2/01: xjamiex.com – Central Electric 2. Bislang wurden davon nur Suchauszüge gelesen, nicht die vollständige Originalzeile. Der Fund ist deshalb ein gezielter nächster Zugang, noch keine abgeschlossene U2/01-Verifizierung.

Zusätzlich wurde ein Club-GTI-Originalbeitrag mit Autor, Datum und Beitragsnummer gelesen. Er beschreibt eine Anschlussanpassung bei einem CE1-/CE2-Instrumentenumbau und erwähnt E/2. Das ist eine Umbauanweisung, kein Nachweis einer festen Grundträgerverbindung.

Die traditionell-chinesische Wiederholung lieferte diesmal Ergebnisse. Beide neuen Scribd-Kandidaten lieferten dagegen nur eine Browserprüfseite.

Elektrische Kantenliste unverändert.

1. U2/01: konkreter neuer Quellenzugang
Suchanfrage
"U2/01" "Inside Fusebox"

A. HTML-Seite mit passendem Tabellenkontext
Fundstelle: Central Electric 2 – xjamiex.com

Der Suchauszug enthält:

“Inside Fusebox, Color.”

und:

“U2/01, Gauge Cluster (lights/gauges) (1991+ Corrado, Passat, all other …”

Übersetzung:

„Innerhalb des Sicherungskastens, Farbe.“

„U2/01, Kombiinstrument (Leuchten/Instrumente) (Corrado ab 1991, Passat, alle anderen …“

Status: Suchauszug, keine Originallektüre. Die vollständige Zeile einschließlich der Zuordnung zu E/2 und der Spaltenüberschriften wurde auf dieser Seite noch nicht gelesen.

Die Adresse ist ein Kandidat für eine alternative HTML-Wiedergabe der bekannten CE2-Tabelle. Ihr Verhältnis zu A2Resource muss am Seiteninhalt geprüft werden; eine unabhängige Quelle ist damit nicht nachgewiesen.

B. Suchauszüge weiterer Tabellenwiedergaben
Ein Scribd-Treffer 889794968 zeigt:

“U2/01 Gauge Cluster (lights/gauges) (1991+ Corrado, Passat, all other models) E/2 Black”

Übersetzung:

„U2/01 Kombiinstrument (Leuchten/Instrumente) (Corrado ab 1991, Passat, alle anderen Modelle) E/2 Schwarz.“

Ein weiterer Scribd-Treffer 1054099071 enthält dieselben wesentlichen Angaben, allerdings mit anderer Zeilenaufteilung.

Wichtig: Diese Suchauszüge dürfen nicht zu einer selbst gelesenen Originaltabellenzeile zusammengesetzt werden. Sie liefern einen Suchhinweis auf die Gegenzeile von Q1, aber keine neue elektrische Bestätigung.

Quellenabhängigkeit
Die Suche lieferte außerdem:

Scribd 751105167: Dokumentadresse benennt ausdrücklich die xjamiex-Seite.
Scribd 500188068: Suchauszug enthält den Navigationspfad
A2Resource > Electrical Systems > Fuse Box Information > Central Electric 2.
Das sind konkrete Hinweise auf Wiedergaben derselben Quellenfamilie, nicht auf mehrere unabhängige Messungen.

2. Neuer Originalbeitrag: CE1-Instrument an CE2-Kabelbaum
Quelle: Club GTI – Using CE1 cluster with CE2 Mk2 VR6

Merkmal	Direkt gelesen
Technischer Antwortautor	rubjonny
Datum	3. Oktober 2016
Beitragsnummer	#2
Fahrzeugkontext	Golf Mk2 mit CE2-/VR6-Umbau; CE1-GTI-Kombiinstrument und Mk3-Instrumentenkabelbaum
Belegart	Anschluss-/Umbauanweisung im Forum
Zielteilenummer	Im gelesenen Abschnitt nicht genannt
Messung am nackten Grundträger	Nicht dokumentiert
Originalpassage
“7 - blk - ignition switch pin 15 (ignition live) -> U1/4 (will have to move a pin here, mk3 plugs have ignition feed elsewhere and need an ignition jumped to E/2 to power it)”

Übersetzung:

„7 – schwarz – Zündschalteranschluss 15 (Zündungsplus) → U1/4 (hier muss ein Kontakt umgesetzt werden; Mk3-Stecker haben die Zündungsversorgung an anderer Stelle und benötigen eine Zündungsplus-Brücke zu E/2 zur Versorgung).“

Aussagegrenze
Beschrieben wird eine Anpassung der äußeren Instrumentenverkabelung.
Die erwähnte Brücke zu E/2 ist keine nachgewiesene interne Grundträgerbrücke.
Die Passage enthält keine ausdrückliche U2/01–E/2-Durchgangsmessung.
U1/4 und U2/01 dürfen nicht gleichgesetzt werden.
Der Suchauszug desselben Threads enthielt außerdem die Frage:

“Can I splice to U2/01 instead?”

Übersetzung:

„Kann ich stattdessen an U2/01 anschließen?“

Diese Frage wurde im Originalabruf nicht erreicht: Die Ausgabe bricht innerhalb von Beitrag #4 ab. Autor, Datum und Nummer der konkreten Frage werden daher nicht aus dem umgebenden Kontext ergänzt.

Weiterer T4-Suchhinweis
Der T4-Thread 283925, Seite 2 erschien ebenfalls mit U2/01 und E/2 im Suchauszug.

Der Abruf lieferte jedoch überwiegend den wiedergegebenen Startbeitrag und den Beginn späterer Antworten. Die gesuchte Tabellenpassage wurde nicht gelesen. Die Angaben des Startbeitrags dürfen nicht als Autor und Datum dieser Passage übernommen werden.

3. Japanische Navigation geprüft
Die beiden bisher offenen Seiten wurden abgerufen:

Seite	Tatsächlich gelesen	Grenze
Motor/Elektrik Nr. 1	Wartungsverzeichnis mit 19 Einträgen; unter anderem Massekabel, Kontaktmittel sowie Plusleitungen zwischen Lichtmaschine/Anlasser und Batterie	Ausgabe bricht im ersten Wartungsabschnitt ab
Motor/Elektrik Nr. 2	Wartungsverzeichnis mit tatsächlichen Einzelbeitragslinks, unter anderem zum Wischerrelais	Ausgabe bricht während Eintrag 28 ab
Beispiel aus Nr. 1:

ｵﾙﾀﾈｰﾀ・ｽﾀｰﾀｰSOL～ﾊﾞｯﾃﾘｰ間 ﾌﾟﾗｽ側配線整備

Übersetzung:

„Instandhaltung der Plusverkabelung zwischen Lichtmaschine, Anlassermagnetschalter und Batterie.“

Kein konkreter CE2-Schaltplanverweis im gelesenen Teil gefunden. Wegen der abgeschnittenen Ausgaben ist damit nicht ausgeschlossen, dass weiter unten relevante Angaben stehen.

Der tatsächlich vorhandene Link zum Wischerrelaiswechsel wurde nicht abgerufen. Er ist kein bereits geprüfter Grundträgerbeleg und hat gegenüber der U2/01-Tabellenseite geringere Priorität.

4. Scribd-Kandidaten: nur Browserprüfung
Dokument	Abrufbefund
455337376 – GOLF3-pdf	HTML-Seite mit Titel „Client Challenge“, JavaScript-Hinweis und Ladefehlertext
718081032 – golf-mk3-diagram	Gleicher Typ Browserprüfseite; kein Planinhalt
Keine technische Originallektüre möglich. Insbesondere wurden weder Modelljahr und Planherkunft noch CE1/CE2 oder Anschlusskennungen geprüft.

Das ist ein Zugangsproblem, keine fehlerhafte Extraktion einer bereits erreichten Tabelle. Die ausgegebenen JavaScript-Hinweise beweisen nicht, welche konkrete technische Ursache den Abruf verhindert hat.

5. Sprach- und Fehlerprotokoll
Sprache	Tatsächliche Arbeit dieses Durchlaufs	Ergebnis
Deutsch	Keine neue Anfrage	Offen
Englisch	"CE2" "U2/01" "E/2" sowie "U2/01" "Inside Fusebox"	Club-GTI-Originalbeitrag und gezielter HTML-Tabellenkandidat
Russisch	Keine neue Anfrage	Offen; nächste Suche ausdrücklich mit VW-/Golf-Bezug
Polnisch	Keine neue Anfrage; Elektroda nicht abgerufen	Offen
Chinesisch, vereinfacht	Keine neue Anfrage	Offen
Chinesisch, traditionell	"Golf 2" 保險絲盒 接線圖	Wiederholung diesmal ausgewertet; kein geeigneter CE2-Plan
Japanisch	Zwei Wartungsseiten abgerufen; keine Suchanfrage	Navigation teilweise gelesen, kein Plan erschlossen
Koreanisch	Keine neue Anfrage; die zuvor gefundenen Dokumente geprüft	Beide Dokumentabrufe ohne Planinhalt
Thai	Keine neue Anfrage	Übergebene erfolgreiche Suchläufe bleiben unverändert
Die traditionell-chinesische Suche lieferte unter anderem eine taiwanische Golf-Fragensammlung, ein ausdrücklich als CE1 bezeichnetes Kabelbaumangebot und Golf-VI-/Übersetzungstreffer. Kein technischer Originalplan daraus gelesen.

Fehlerstatus: Die frühere chinesische Zeitüberschreitung bleibt historisch dokumentiert; der aktuelle Wiederholungsversuch war auswertbar. Hinzu kommen zwei Scribd-Browserprüfseiten. Allgemeine Fehlermeldungen im Gespräch zählen nicht als Fachsuchergebnisse.

6. Register, Inventar und Matrix
Registeränderungen
Club GTI, Thread 284415, Beitrag #2: neuer gelesener Originalbeitrag mit Autor und Datum; äußere Umbauverkabelung.
xjamiex CE2: neuer konkreter HTML-Quellenkandidat; bisher Suchauszug.
Weitere CE2-Tabellenwiedergaben: Hinweise auf Quellenabhängigkeit erfasst, keine unabhängigen Bestätigungen.
Japanische Wartungsnavigation: beide offenen Seiten teilweise gelesen.
Scribd 455337376 / 718081032: Zugangsstatus dokumentiert.
Physisches Inventar und elektrische Kanten
Keine Änderungen.

U2/01 weiterhin nicht vollständig mit Spaltenüberschriften im Original gelesen.
Q1/Q2 bleiben Quellenreferenzen ohne physische Zielteilverifizierung.
R12-Geometrie und beide S18-Halterseiten bleiben offen.
Keine Bildprüfung und keine neue Messung.
Keine neuen 1 oder 0; ungeklärte Beziehungen bleiben ?.
Elektrische Kantenliste unverändert.

7. Ausführbarer Folgeauftrag
Nächster sinnvoller Schritt ist die vollständige U2/01-Zeile auf der gefundenen HTML-Seite, nicht ein weiterer identischer Scribd-Abruf. Selbst eine bestätigte Tabellenzeile würde zunächst den Quellenbeleg zu Q1 vervollständigen, nicht automatisch eine Matrixkante freigeben.

Vorgeschlagene Nachfragen

















