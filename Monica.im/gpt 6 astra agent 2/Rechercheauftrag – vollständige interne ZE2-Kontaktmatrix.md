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