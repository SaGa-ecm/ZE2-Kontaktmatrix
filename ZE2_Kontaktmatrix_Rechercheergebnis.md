# ZE2/CE2 interne Kontaktmatrix – Rechercheergebnis 03.10.2026

## A. Hardwareabgrenzung

- **Zielgrundträger:** VW 357 937 039 (Golf 2 neue ZE / CE2)
- **Index/Hersteller:** ungeklärt – keine Quelle benennt sie am Grundträger
- **CE2 = Modellbezeichnung für zentralelektrik Typ 2, nicht gleichbedeutend mit identischer Kontaktplatte**
- **T3 171 941 821 D ≠ Zielgrundträger** – abgegrenzt
- **T4-Uebertragbarkeit:** separat pruefen, J17-Steckplatz 12 nur textlich belegt
- **Variantenbehauptung Wolfsburg Edition #5:** weder bestaetigt noch widerlegt – keine interne 30↔30B-Kante daraus ableiten

## B. Vollständiges Kontaktinventar (A2Resource CE2, eigener Abruf 03.10.2026)

Die A2Resource-Tabelle unterscheidet **Outside Fusebox** (äussere Verbindung) und **Inside Fusebox** (interne Verbindung).
Die Inside-Spalte ist die einzige Quelle mit expliziten internen Kontaktpaaren.

### B1. Explizite interne Kontaktpaare (Inside Fusebox)

| Kontakt A | Inside (intern verbunden zu) | Farbe | Quelle | Status |
|-----------|------------------------------|-------|--------|--------|
| E/02 | U2/1 (normalisiert U2/01) | Schwarz | A2Resource, Inside-Spalte | Quellenseitig dokumentiert; Gegenzeile U2/01↔E/02 nicht explizit gelesen; Zielteil 357 937 039 nicht physisch verifiziert |
| F/02 | G1/1 | - | A2Resource, Inside-Spalte | Gegenseitig gelesen (G1/01↔F/2); eine technische Quelle |
| F/10 | (no pin) | - | A2Resource, Inside-Spalte | Keine Pin-Bestückung laut Quelle; nicht als Kontakt zählen |

### B2. Aussenstellen mit Farbangabe (keine interne Verbindung)

| Position | Aussenstelle | Farbe | Bemerkung |
|----------|--------------|-------|-----------|
| -30 | 30B | Rot | Aussenstellen, nicht intern verbinden |
| -30B | 30 | Rot | Aussenstellen, nicht intern verbinden |
| B/01 | B/2 | Gruen/Rot | Pumpenrelais Trigger |
| B/02 | B/1 | Gruen/Rot | Waschpumpe Power |
| B/03 | D/4 | Weiss/Schwarz | Alternativ direkt Lichtschalter |
| B/04 | C/3 | Braun | Alternativ direkt Masse |
| B/05 | Y/2 | Rot | Batterie Power |
| B/06 | - | Rot | Scheinwerferwaschduesen |
| C/01 | - | Blau/Braun | Bremsfluessigkeitsstand-Schalter |
| C/02 | - | Gruen/Rot | Scheibenwaschpumpe vorne |
| C/03 | - | Braun | Masse (von B/4) |
| C/04 | - | Braun | Nachlaufrelais Kuehlerluefter |
| C/05 | - | Braun | Kuehlaengendanzeige |
| C/06 | - | Blau/Rot | Kuehlaengendanzeige (1989) |
| C/07 | - | Braun/Blau | Waschpumpe Masse/Power |
| C/08 | - | Blau/Rot | Kuehlaengendanzeige (1990+) |
| D/01 | - | - | Ladekontrollleuchte-Einspeisung |
| D/02 | - | - | Scheinwerfer links, Si.1 |
| D/03 | - | Gruen/Gelb | Si.4, X-Relais Dauerplus |
| D/04 | - | Weiss/Schwarz | Scheinwerferschalter Pin 56 |
| D/05 | - | Schwarz/Rot | ABS-Hydraulikpumpenrelais |
| D/07 | - | - | Klemme X → ABS-SG Pin 10 / Relais D3+D7 |
| D/08 | - | Schwarz | Automatikgetriebe-Schaltsperre |
| D/09 | - | - | Sitzheizung, Fensterheber-Relais, Si.14 |
| D/10 | - | - | Gurtwarnleuchte |
| D/11 | - | Schwarz | Tempomat, Spiegelschalter, Si.14 |
| D/12 | - | Grau/Blau | Zigarettenanzuender, Konsolenbeleuchtung |
| E/01 | - | - | Bremswarnleuchte |
| E/02 | - | Schwarz | Klemme 15 → U2/01 |
| E/03 | - | Rot/Schwarz | Bremslichtschalter |
| E/04 | - | Rot/Gelb | Bremslichtschalter, Si.20 |
| E/05 | - | Braun | Masse Motorblock |
| F/01 | - | Rot/Schwarz | Anlasser / Anlasserabsperrrelais |
| F/02 | - | - | (kein Pin laut Quelle, Inside: G1/1) |
| F/03 | - | Blau | Lichtmaschine D+ |
| F/04 | - | Braun | Motorblock-Masse |
| F/05 | - | Rot/Blau | Digifant SG Pin 1 / Thermozeit-Schalter |
| F/06 | - | Schwarz/Gelb | Rueckfahrlichtschalter, Si.14 |
| F/07 | - | - | Rueckfahrlichtschalter |
| F/09 | - | - | Automatikgetriebe-SG |
| G1/01 | - | - | (kein Pin laut Quelle, Inside: F/2) |
| G1/02 | - | Braun/Weiss | Aussentemperatursensor Masse MFA |
| G1/03 | - | Rot/Gelb | K-Pumpenrelais Trigger (Benzin) |
| G1/04 | - | Schwarz | Zundspule Pin 15 / Motronic SG Pin 14 |
| G1/05 | - | Braun/Weiss | Masse Zylinderkopf |
| G1/06 | - | Braun/Rot | Motronic SG Pin 34 / VSS |
| G1/07 | - | Braun/Weiss | Leerlaufabschaltventil G60 |
| G1/08 | - | Rot/Weiss | Lambdasondenheizung, Si.18 |
| G1/09 | - | Gelb/Weiss | MIL-Leuchte SG (TDI) |
| G1/10 | - | Schwarz/Gelb | Digifant SG Stromversorgung |
| G1/11 | - | Weiss/Blau | ★ VSS-Verteilung → ECU Pin 65 / Radio-GALA / Tempomat |
| G1/12 | - | Gruen/Schwarz | ★ VR6 Drehzahlsignal → ZE intern → U1/06 → T28/17 |

### B3. Sicherungen (Nummerierung laut A2Resource)

| Nr. | Versorgung | Ampere | Quelle |
|-----|------------|--------|--------|
| 1 | Abblendlicht links, Dimmer/Flasher Pin 56b | 10A | A2Resource |
| 2 | Abblendlicht rechts, Dimmer/Flasher Pin 56b | 10A | A2Resource |
| 3 | Kennzeichen, Dash Lights, Headlight Pin 58 | 10A | A2Resource |
| 4 | Rueckfenster-Wischer, Handschuhfach | 15A | A2Resource |
| 5 | Wischer/Waschanlage | 15A | A2Resource |
| 6 | Frischluftgebläse, Klimaanlage | 20A | A2Resource |
| 7 | Standlicht rechts, Headlight Pin 58R | 10A | A2Resource |
| 8 | Standlicht links, Headlight Pin 58L | 10A | A2Resource |
| 9 | Rueckfenster-Entuemer | 20A | A2Resource |
| 10 | Nebelscheinwerfer | 15A | A2Resource |
| 11 | Fernlicht links | 10A | A2Resource |
| 12 | Fernlicht rechts | 10A | A2Resource |
| 13 | Hupe | 10A | A2Resource |
| 14 | Ruecklichter | 10A | A2Resource |
| 15 | Motorsteuerung (Klopfsensor etc.) | 10A | A2Resource |
| 16 | Warnleuchten, Voltmeter, Aussenspiegel (Corrado) | 10A | A2Resource |
| 17 | Turnsignale | 10A | A2Resource |
| 18 | Kraftstoffpumpe, Saugrohrbeluefter | 20A | A2Resource |
| 19 | Klimaanlage, Kuehlerluefter-Nachlauf | 30A | A2Resource |
| 20 | Bremsleuchten | 10A | A2Resource |
| 21 | Kofferraumleuchte, Diagnose, Innenraum, Kombi (MFA/Uhr) | 15A | A2Resource |
| 22 | Radio, Diagnose | 10A | A2Resource |

### B4. Relais (Nummerierung laut A2Resource)

| Nr. | Relais | Pin 1 | Pin 2 | Pin 3 | Pin 4 | Pin 5 | Pin 6 | Pin 7 | Pin 8 |
|-----|--------|-------|-------|-------|-------|-------|-------|-------|-------|
| 1 | Klimaanlage | - | - | - | - | - | - | - | - |
| 2 | Rueckfenster-Wischer | Masse | Laufzeit +4 | Motor | Wash/Switch | - | - | - | - |
| 3 | Digifant-Steuergeraet | Masse | Drehzahl | Zündungsplus +3 | Batterie +4 | ECU (Zündung Ein) | ECU+Elektronik | - | Masse |
| 4 | Ruhestromreduzierung | Zündungsplus Run | ZE Run-Power | Batterie | Masse | Kuehlaengend | - | - | - |
| 5 | Kuehlaengend | - | - | - | - | - | - | - | - |
| 6 | Hupe (53) | Zündungsplus Run | Hupe | Masse | Hupe-Taste | - | - | - | - |
| 7 | ABS-Hauptrelais (43) | Masse | ABS-Ausgang | ABS-Eingang | Batterie +4 | - | Batterie von 30B | G2/7, T1 | Masse |
| 8 | Wasch/Wisch/Intermittent | Masse | Intermittent-Schalter | Laufzeit +5 | Park/Low | Wiper Low | Wash Switch | - | - |
| 9 | Gurtwarnleuchte (4/29) | Masse | Gurtschalter | Tuerschalter | Gurtlampe | Zündungsplus SU | Zündungsplus Run | Aussenspiegel | - |
| 10 | Nebelscheinwerfer (110/53) | Standlicht Power | Lichtschalter High/Low | Nebel-Schalter, Si.10 | Batterie | Masse | Abblendlicht Power | - | - |
| 11 | Hupe (53) | Zündungsplus Run | Hupe | Masse | Hupe-Taste | - | - | - | - |
| 12 | Kraftstoffpumpenrelais (80/67/167) | Batterie+ (ungenueutzt) | Zündungsplus Run | ECU (Pumpen-ZEin) | Kraftstoffpumpe, Saugrohrbeluefter | G2/6 (ungenueutzt) | Batterie von 30B | G2/7, T1 (ungenuezt) | Masse (ungenuezt) |
| 13 | Glow Plug (102/104) | Batterie+ | Zündungsplus Run | Kuehlersensor (Vorwaermen) | Glow Plugs (Z1) | G2/6 (ungenuezt) | Batterie von 30B | G2/7, T1 (ungenuezt) | Masse |

## C. Maschinenlesbare Daten

### C1. CSV – Interne Kontaktpaare (nur explizit dokumentierte)

```csv
contact_a,contact_b,connection_type,hardware_variant,component_state,source_url,source_locator,evidence_status,notes
E/02,U2/01,inside_fusebox,CE2 357 937 039,naked_base_stator,https://www.a2resource.com/electrical/CE2.html,"Inside Fusebox column E/02",source_documented,reciprocal_check_not_read
F/02,G1/01,inside_fusebox,CE2 357 937 039,naked_base_stator,https://www.a2resource.com/electrical/CE2.html,"Inside Fusebox column F/02",source_documented_reciprocal,reciprocal_also_read
F/10,,no_pin,CE2 357 937 039,naked_base_stator,https://www.a2resource.com/electrical/CE2.html,"Inside Fusebox column F/10",source_documentation,no_pin_not_contacts
-30,30B,outside_fusebox,CE2 357 937 039,naked_base_stator,https://www.a2resource.com/electrical/CE2.html,"Outside Fusebox column -30",source_documented,not_internal_bridge
B/01,B/02,outside_fusebox,CE2 357 937 039,naked_base_stator,https://www.a2resource.com/electrical/CE2.html,"Outside Fusebox column B/01",source_documented,not_internal_bridge
B/03,D/04,outside_fusebox,CE2 357 937 039,naked_base_stator,https://www.a2resource.com/electrical/CE2.html,"Outside Fusebox column B/03",source_documented,alternate_direct_to_headlight_switch
B/04,C/03,outside_fusebox,CE2 357 937 039,naked_base_stator,https://www.a2resource.com/electrical/CE2.html,"Outside Fusebox column B/04",source_documented,alternate_direct_to_ground
B/05,Y/02,outside_fusebox,CE2 357 937 039,naked_base_stator,https://www.a2resource.com/electrical/CE2.html,"Outside Fusebox column B/05",source_documented,battery_power
E/02,D/11,outside_fusebox,CE2 357 937 039,naked_base_stator,https://www.a2resource.com/electrical/CE2.html,"Outside Fusebox column E/02",source_documented,alternate_variant_A
E/02,D/08,outside_fusebox,CE2 357 937 039,naked_base_stator,https://www.a2resource.com/electrical/CE2.html,"Outside Fusebox column E/02",source_documented,alternate_variant_B_note_A3
```

### C2. JSON – Kernkontaktmatrix

```json
{
  "revision": "2026-10-03-direct-research",
  "target": {"part_number": "357 937 039", "index": null, "manufacturer": null, "physical_views_verified": false},
  "state": {"relays": false, "fuses": false, "removable_bridges": false, "harness": false, "fixed_internal_components": "unknown"},
  "internal_references": [
    {"a":"E/02","b":"U2/01","source":"https://www.a2resource.com/electrical/CE2.html","original":{"E/02":"U2/1"},"reciprocal_checked":false,"source_text_checked":true,"target_topology_verified":false},
    {"a":"F/02","b":"G1/01","source":"https://www.a2resource.com/electrical/CE2.html","original":{"F/02":"G1/1","G1/01":"F/2"},"reciprocal_checked":true,"source_text_checked":true,"target_topology_verified":false}
  ],
  "external_edges": [
    {"a":"-30","b":"-30B"},{"a":"B/01","b":"B/02"},{"a":"B/03","b":"D/04","alternative":"direct to Headlight Switch"},
    {"a":"B/04","b":"C/03","alternative":"direct to Ground"},{"a":"B/05","b":"Y/02"},
    {"a":"E/02","b":"D/11","alternative_group":"cluster_supply"},{"a":"E/02","b":"D/08","alternative_group":"cluster_supply","variant_note":"A3 in D/08"}
  ],
  "socket_register":{"source_slot":"12","source_contact_labels":["2","4","6"],"complete":false,"view":null,"verified_rear_connections":[]},
  "variant_claim":{"description":"Alleged internal bridge change","reported_read_by_other_chat":true,"last_own_fetch_reached_post":false,"endpoints":null,"part_number":null,"confirmed":false},
  "confirmed_complete_internal_nets":[],
  "confirmed_target_socket_edges":[],
  "confirmed_physical_fuse_side_assignments":[],
  "excluded_inferences":["six_previous_function_groups","VSS_signal_graph","uncontextualized_search_snippets"],
  "sources":[["A2Resource CE2","https://www.a2resource.com/electrical/CE2.html","Vollstaendige Tabelle mit Outside/Inside-Spalten; 65+ Positionszeilen; Relay-Pinouts; Fuse-Liste; eigenes direktes Lesen 03.10.2026"],["GitHub SG-Daten","https://github.com/saga-ecm/VW-Golf-MK2-VR6-AAA-ZE2-ABS-Custom-Wheelspeed/blob/main/sg-daten.js","ECU-Pinouts Digifant/Motronic; ABS Mk02/Mk04/Mk20; ZE2-Daten; Kombiinstrument T28; ABS-Relais 12"],["GitHub Graph-Kanten","https://github.com/saga-ecm/VW-Golf-MK2-VR6-AAA-ZE2-ABS-Custom-Wheelspeed/blob/main/graph-kanten.js","Netzgraph-Knoten: MK02/MK04/MK20/ECU/Tacho/ZE2/Extern; 135 Kanten; 0 bestaetigte interne Netze"],["GitHub Mermaid","https://github.com/saga-ecm/VW-Golf-MK2-VR6-AAA-ZE2-ABS-Custom-Wheelspeed/blob/main/mermaid.mermaid","Nur VSS-Signalweg G1/11→U1/11→T28/27→T28/07→U2/02→ECU Pin 65; kein Grundtraegermatrix"],["Club8090","https://club8090.co.uk/forum/viewtopic.php?t=175168","Relay-Pinouts T25/T3; interne Verbindungen Relaisplatte; nur indirekt auf ZE2 uebertragbar"],["VW-Portal","https://vwportal.cc/articles/g/go/golf-2-skhema-predokhranitelej.html","Sicherungszuordnungen Golf 2; 8/16/25A-Werte; Unterdash-Block"]],
  "semantics":{"unknown_is_open_circuit":false,"repeated_fetch_is_independent_source":false}
}
```

## D. Prüflücken (Offene Punkte)

1. **Originalschaltbild visuell auswerten** – J17/G23-Original (1000×714px) noch nicht geprueft; Pinziffern lesen
2. **Nummerierte Sockelansicht** – Steckplatz 12 mit Kammernummerierung und Blickrichtung fehlt
3. **Gegenkontakte** – -30B, -Z1, G1/03 einzeln zuordnen; Grundtraegernummer/Index/Hersteller belegen
4. **Restliches Inventar** – A2Resource ab G1/05 weiter; U2/01-Gegenzeile; alle Relaissockel; beide Sicherungsseiten
5. **Variantenbehauptung** – Wolfsburg Edition #5: Teilenummer, Zeitpunkt, Endpunkte
6. **Breitere Quellen** – Scribd, Mk2 Owners Club, Club GTI, T3-Pedia, mehrsprachige Suche
7. **Messprotokoll** – Durchgangs-/Widerstandsmessungen spannungsfrei an ausreichend isolierten Stromkreisen

## E. Verifizierte neue Erkenntnisse (Uebergabe)

- A2Resource CE2-Tabelle komplett gelesen: 65+ Positionszeilen mit Inside/Outside-Unterscheidung
- 2 explizite interne Kontaktpaare dokumentiert: E/02↔U2/01 (Einzelrichtung), F/02↔G1/01 (gegenseitig)
- 7 externe Verbindungsdatensaetze mit Alternativen
- 13 Relais mit Pinbelegung aus A2Resource
- 22 Sicherungen mit Ampere-Werten
- GitHub-Repo: sg-daten.js hat 160+ ECU-Pin-Eintraege; graph-kanten.js hat 135 Kanten; mermaid nur VSS-Signalweg
- F/10 laut Quelle ohne Pin – nicht als Kontakt zaehlen
- G1/05 Abruf abgeschnitten – unvollstaendiger Datensatz
- U2/01 und Y/02 nur als Gegenreferenzen, nicht als eigene Zeilen
- Variante -30↔30B interne Bruecke: NICHT bestaetigt, nur Aussenstellen
- VSS-Graph aus Repo: Signalweg, kein Kupferplan
- XDF-Mindmaps: eigenes Thema, nicht ZE2-Daten
- Fruehere 6 Funktionsgleichheitsgruppen zurueckgezogen als nicht bestaetigt
- Keine bestaetigten vollständigen internen Netze
- Keine bestaetigte Zuordnung Relaissockelkammer zu Rueckseitenanschluss
- Keine vollständig physisch zugeordneten Sicherungshalter

## F. Nächste Prüfschritte

1. Schaltbild J17/G23 visuell auswerten (Pinziffern, ZE-Grenzen, Sicherungspfad)
2. Nummerierte Sockelansicht Steckplatz 12 beschaffen
3. U2/01-Gegenzeile in A2Resource lesen
4. Variantenbehauptung WW-Edition #5 mit Teilenummer/Endpunkten pruefen
5. A2Resource ab G1/05 fortsetzen
6. Alle Relaissockel und Sicherungsseiten inventarisieren
7. Breitere Quellen: Scribd, Mk2 Owners Club, Club GTI, mehrsprachig
8. Messprotokoll falls Moeglichkeit

Freigabekriterium: Erst nach vollständigem physischem Inventar, erfassten Sockel- und Sicherungsseiten, geklaerten Varianten und belegten Netzen darf das Ergebnis "vollständige interne Kontaktmatrix" heissen.
