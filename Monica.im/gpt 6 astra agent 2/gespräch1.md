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