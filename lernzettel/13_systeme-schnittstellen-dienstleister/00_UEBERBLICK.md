# 13 Shop-Systeme, Schnittstellen, Logistik, Dienstleister und Projektmanagement

**Prüfungsbereiche:** Teil 2 Geschäftsprozesse im E-Commerce (120 Min., 30 %); Fachgespräch (20 %, projektorientierte Arbeitsweisen und Fachwissen zum Gebiet); Teil 1 nur soweit nötig | **Priorität:** C | **Lernzeit Erstdurchgang:** ca. 105 Min. (dazu ca. 20 Min. Lernkarte „Dienstleister steuern“ und ca. 85 Min. Fallaufgaben) | **Verordnung:** § 11 Abs. 2 Nr. 1 / A1 (Schnittstellen B2B/B2C, API, ERP, PIM, CRM, PSP, Logistik; mit Dienstleistern kooperieren, nur teilweise), A8 (nur Daten-Import/-Export und Datenaufbereitung), § 13 Abs. 1 Nr. 6 (projektorientierte Arbeitsweisen: Scrum, Kanban, klassisch, Priorisierung, Nutzwertanalyse), § 8 Nr. 2 (Beschaffung, Warenwirtschaft, Wareneingang, Lager; Teil 1)

## Worum es geht – Big Picture

Ein Onlineshop ist kein einzelnes Programm, sondern ein Verbund aus Shopsystem, Warenwirtschaft (ERP/WWS), Produktdaten (PIM), Kundendaten (CRM, Newsletter), Zahlungsanbietern (PSP), Marktplätzen, Preissuchmaschinen und Logistikdienstleistern. Diese Systeme sind über Schnittstellen verbunden: per API (direkte Kommunikation, Echtzeit möglich) oder per Produktdatenfeed (Datei in festen Abständen). Damit der Datenaustausch funktioniert, müssen die Daten sauber aufbereitet sein (Format, eine Information pro Spalte, Plausibilitätsprüfung). Hinter den Daten steht der Warenfluss: Wareneingang mit Prüf- und Rügepflicht nach § 377 HGB (beim beiderseitigen Handelskauf), Lagerhaltung, Versand. Ob man Lager, IT, Marketing oder Content selbst macht oder auslagert, ist eine Make-or-Buy-Entscheidung; wer auslagert, muss den Leistungsumfang festlegen (Lastenheft, Pflichtenheft, SLA, AV-Vertrag) und die Leistung kontrollieren. Neue Funktionen und Systemwechsel laufen als Projekt, agil (Scrum, Kanban) oder klassisch, und Aufgaben werden priorisiert, z. B. mit einer Nutzwertanalyse. In der schriftlichen Prüfung kommt das meist als Teilaufgabe vor (welche Systeme anbinden, Feed oder API, Vor- und Nachteile des Outsourcings, § 377 HGB, Scrum-Elemente ordnen, Nutzwertanalyse rechnen). Vieles kennst du aus dem Alltag (Shopsystem, Warenwirtschaft, Feed- und Automatisierungstools); hier geht es darum, Fachbegriffe und Schemata prüfungssicher zu formulieren, und LF12 brauchst du zusätzlich für den Report (Upload bis Di 17.11.2026, 12 Uhr) und das Fachgespräch im Januar.

## Lernreihenfolge

| Nr | Lernzettel | Kern/Überfliegen | Minuten | Danach kannst du ... |
|---|---|---|---|---|
| 1 | [Schnittstellenmanagement B2B/B2C (Teil 1)](LF09_Schnittstellenmanagement-im-B2B-und-B2C_E-Commerce_OSZHandel1.md) | Kern | 20 | Schnittstelle und API definieren, die drei Hauptgruppen nennen und begründen, welche Systeme (ERP, PIM, CRM, PSP, Marktplätze, Logistik) an einen Shop angebunden werden. |
| 2 | [Schnittstellenmanagement B2B/B2C (Teil 2)](LF09_Schnittstellenmanagement-im-B2B-und-B2C-2_E-Commerce_OSZHandel1.md) | Überfliegen | 8 | Merkmale moderner APIs (HTTP/REST, Versionierung, Sicherheit/Governance) und B2B-Echtzeitdaten (Preise, Bonität, Verfügbarkeit) erklären. |
| 3 | [Daten-Import und Daten-Export](LF09_Daten-Import-Daten-Export_E-Commerce_OSZHandel1.md) | Überfliegen | 7 | Import und Export unterscheiden, geeignete Datenformate wählen, Feed und API abgrenzen und Vor- und Nachteile der Automatisierung nennen. |
| 4 | [Datenaufbereitung](LF09_Datenaufbereitung_E-Commerce_OSZHandel1.md) | Überfliegen | 7 | die vier Schritte der Datenaufbereitung nennen, Formatfehler in einer Tabelle finden, Datenvalidierung und Data Warehouse erklären. |
| 5 | [Logistische Anforderungen](LF09_Logistische-Anforderungen_E-Commerce_OSZHandel1.md) | Kern | 18 | Warenwirtschaft, WWS, Waren- und Datenfluss definieren, die Wareneingangsprüfung mit § 377 HGB anwenden und Lagerkennzahlen berechnen. |
| 6 | [Outsourcing](LF09_Outsourcing_E-Commerce_OSZHandel1.md) | Kern | 15 | Outsourcing begründen oder ablehnen, die kritische Menge berechnen und den Leistungsumfang über Lastenheft, SLA und AV-Vertrag festlegen. |
| 7 | [Projektmanagement LF01](LF01_Projektmanagement-und-Projektmethoden_E-Commerce_OSZHandel1.md) | Überfliegen | 5 | Agilität, Sprint und Priorisierung kurz erklären und entscheiden, ob Scrum zu einer Fallsituation passt. |
| 8 | [Projektmanagement LF12](LF12_Projektmanagement-und-Projektmethoden_E-Commerce_OSZHandel1.md) | Kern | 25 | das Agile Manifest, Scrum (Rollen, Events, Artefakte), Kanban und die Priorisierungsschritte erklären sowie eine Nutzwertanalyse rechnen und beurteilen. |

Summe: 105 Minuten. Danach die Lernkarte „Dienstleister steuern“ (Abschnitt Lücken & Ergänzungen, ca. 20 Min.) und die drei Fallaufgaben (ca. 85 Min.).

## Begriffslandkarte

🔎 markiert Begriffe, die nur in den Ergänzungen der Lernzettel stehen (nicht im Original).

- **Systemlandschaft des Onlineshops**
  - **Shopsystem** (Frontend für Kunden, Backend für Verwaltung)
  - **Schnittstellen** = Transferpunkte durch Arbeitsteilung; technisch der „Dolmetscher“ zwischen Systemen
    - Hauptgruppen: **B2B** (betriebsextern), **B2C** (betriebsextern), **betriebsintern**
    - Ziele: Zielabstimmung, **Insellösungen vermeiden**, Konfliktmanagement, Übersetzeraufgaben, Mitarbeiter schulen
    - technische Wege
      - **API** (Programmierschnittstelle, meist HTTP/REST, Daten oft als JSON 🔎; Echtzeit möglich)
      - **Produktdatenfeed** (Datei, z. B. CSV oder XML 🔎, in festen Abständen)
      - manueller CSV-/Excel-Upload
    - angebundene Systeme
      - **ERP/WWS**: Bestände, Aufträge, Einkauf, Rechnung → Logistik
      - **PIM**: Produktdaten zentral → Grundlage für Multichannel
      - **CRM/Newsletter**: Kundendaten → Personalisierung (DSGVO, AV-Vertrag 🔎)
      - **PSP**: Zahlungsabwicklung
      - **Marktplätze, Preissuchmaschinen**: Produktdaten raus, Bestellungen rein, Bestand synchron
      - **Logistikdienstleister**: Sendungsverfolgung, Lieferoptionen (Packstation, Wunschtermin, Ablageort); Versandlabel 🔎
      - **soziale Netzwerke**: Inhalte im Shop ausspielen
    - B2B-Besonderheiten: Einkaufsberechtigung, individuelle Preise, Echtzeitabfrage von Preisen, Bonität, Verfügbarkeit
- **Daten**
  - **Import** (Hersteller/intern → Shop/WWS) und **Export** (Shop → Google Shopping, idealo, Amazon, Affiliate-Netzwerke)
  - **Datenaufbereitung**: Sammeln/Ermitteln → Bereinigen/Prüfen → Formatieren/Anreichern → Speichern/Verwenden
    - **Datenvalidierung** (Plausibilitätsprüfung nach dem Formatieren)
    - **Data Warehouse** (zentraler Speicher nur aufbereiteter Daten)
  - Pflichtinhalte in Produktdaten und Feeds: GPSR-Angaben (seit 13.12.2024) 🔎
- **Logistik**
  - **Warenwirtschaft** (Beschaffung – Lager – Absatz) → **WWS** (Planung, Steuerung, Kontrolle)
    - **Warenfluss** (physisch) und **Datenfluss** (Informationen)
  - **Wareneingang**: äußere Prüfung (sofort, beim Frachtführer) → inhaltliche Prüfung (unverzüglich) → **Mängelrüge** (§ 377 HGB, nur beiderseitiger Handelskauf)
  - **Lager**: Aufgaben, Anforderungen, Risiken, **Lagerkennzahlen** (Formeln 🔎)
  - **Distributionslogistik**: Ziele Verfügbarkeit, Kostenminimierung, Einflussnahme; Erfolgsfaktoren „Kosten senken“ und „Umsatz steigern“
- **Dienstleister**
  - **Make or Buy** 🔎 → **Outsourcing** (extern) bzw. **Insourcing** (zurückholen); interne und externe Dienstleister 🔎
  - Auswahl: K.-o.-Kriterien → **Nutzwertanalyse**; Kosten: **kritische Menge** 🔎
  - Leistungsumfang 🔎: **Lastenheft** (Auftraggeber) → **Pflichtenheft** (Auftragnehmer) → Vertrag (**Werk-** oder **Dienstvertrag**, **SLA**, **AV-Vertrag**)
  - Leistungskontrolle 🔎: KPI (Perfect Order Rate, On-Time Shipping Rate, Reaktionszeit) → Eskalation
- **Projektmanagement**
  - **klassisch/plangetrieben**: V-Modell, RUP; Wasserfall, Meilensteine, Gantt, magisches Dreieck 🔎
  - **agil**: Agiles Manifest (4 Leitsätze)
    - **Scrum** (Zählung nach Scrum Guide 2020 🔎): 3 Verantwortlichkeiten (Product Owner, Scrum Master, Developers), 5 Events (Sprint, Sprint Planning, Daily Scrum, Sprint Review, Sprint Retrospective), 3 Artefakte (Product Backlog, Sprint Backlog, Inkrement)
    - **Kanban**: Board, Pull-Prinzip, WIP-Limit 🔎, kein Sprint-Takt
    - **Scrumban** (Hybrid)
  - **Priorisierung**: SMART-Ziel → relevant/nicht relevant → Walking Skeleton → ABC („Rock, Pebble & Sand“, Pareto) → KPI-getrieben → Nutzwertanalyse; außerdem Eisenhower (wichtig/dringend) 🔎

## Geklärte Widersprüche

1. **Scrum-Begriffe: LF01, LF12 und Scrum Guide 2020**
   - Abweichung: [LF01](LF01_Projektmanagement-und-Projektmethoden_E-Commerce_OSZHandel1.md) nennt Sprints von „1–4 Wochen“, [LF12](LF12_Projektmanagement-und-Projektmethoden_E-Commerce_OSZHandel1.md) „1 Woche bis 1 Monat“ und den „Daily Sprint“ (ein Tag des Sprints, im Lösungsblatt sogar „25 h“). LF12 lässt den Product Backlog von Scrum Master und Product Owner führen und den Scrum Master Daily Scrum und Retrospektive leiten.
   - In der Prüfung: 3 Verantwortlichkeiten, 5 Events, 3 Artefakte; Sprint mit fester Länge, höchstens ein Monat; Daily Scrum höchstens 15 Minuten; den Product Backlog verantwortet der Product Owner; „Daily Sprint“ nicht verwenden. LF01 ist eine Teilmenge von LF12, gründlich lernst du nur LF12.
   - Warum: So steht es im Scrum Guide 2020, der weiterhin die aktuelle offizielle Fassung ist. Laut Scrum Guide ist das Daily Scrum ein Termin der Developers, die Retrospektive einer des ganzen Scrum-Teams; dass der Scrum Master beide moderiert (Material), ist in der Praxis verbreitet und als Antwort vertretbar. Die drei Daily-Fragen des Materials kannst du als Beispiel nennen (seit dem Scrum Guide 2020 stehen sie dort nicht mehr).

2. **Scrum „für große Teams“**
   - Abweichung: LF12 (Aufgabe 3.1) ordnet Scrum großen bzw. vielen Teams zu, Kanban kleinen Teams.
   - In der Prüfung: Die Aussage des Materials wiedergeben („Scrum koordiniert die Zusammenarbeit großer bzw. mehrerer Teams, Kanban gliedert übersichtliche Aufgaben kleiner Teams“) und als Unterschied zusätzlich Board/Pull-Prinzip, feste Sprints und Rollen nennen.
   - Warum: Das ist die Lösung des Materials. 🔎 Ergänzung (nicht im Original): Ein einzelnes Scrum-Team ist laut Scrum Guide 2020 klein (typischerweise höchstens 10 Personen); große Vorhaben arbeiten mit mehreren Scrum-Teams.

3. **Agiles Manifest: vier statt fünf Leitsätze**
   - Abweichung: Das Lösungsblatt in [LF12](LF12_Projektmanagement-und-Projektmethoden_E-Commerce_OSZHandel1.md) (Aufgabe 1.2) nennt fünf Paare und ordnet „strikte Planung“ falsch zu.
   - In der Prüfung: genau vier Leitsätze (Individuen und Interaktionen, funktionierende Software, Zusammenarbeit mit dem Kunden, Reagieren auf Veränderung, jeweils „wichtiger als“ die rechte Seite).
   - Warum: Das Manifest von 2001 hat vier Leitsätze; die rechte Seite ist nicht wertlos, nur nachrangig.

4. **„Scrum sinnvoll?“ ohne Alternative und Priorisierung nach Wichtigkeit/Dringlichkeit**
   - Abweichung: [LF01](LF01_Projektmanagement-und-Projektmethoden_E-Commerce_OSZHandel1.md) Aufgabe 5 verneint Scrum beim Shop-Rebranding, nennt aber keine Alternative; „Wichtigkeit und Dringlichkeit“ wird nicht als Methode benannt.
   - In der Prüfung: „Eher nein, klassisches (Wasserfall-)Vorgehen mit Phasen und Meilensteinen, weil die Anforderungen feststehen.“ Für Wichtigkeit/Dringlichkeit das Eisenhower-Prinzip nennen.
   - Warum: Bei „Begründen Sie“ und „Beurteilen Sie“ gibt die Alternative oft den letzten Punkt.

5. **Nutzwertanalyse in LF12: Gewichtssumme 1,01 und falsche Ideallösung**
   - Abweichung: In der Beispieltabelle von [LF12](LF12_Projektmanagement-und-Projektmethoden_E-Commerce_OSZHandel1.md) ergeben die Gewichte 1,01; die Ideallösung ist mit 100 statt 80 Punkten (ungewichtet) und 10 statt 10,1 (gewichtet) angesetzt.
   - In der Prüfung: Gewichte immer auf 1,00 (100 %) prüfen bzw. normieren. Korrekt: ungewichtete Wertigkeiten 0,79 / 0,64 / 0,45; gewichtet 0,81 / 0,68 / 0,44. Rangfolge unverändert (Alternative 1).
   - Warum: Wertigkeit = Ist ÷ Ideal; das Ideal ist Anzahl Kriterien × Höchstpunkte bzw. Höchstpunkte × Σ Gewichte.

6. **Ablauf der Nutzwertanalyse: zwei Fassungen der 6 Schritte**
   - Abweichung: [LF09_Kompatibilität](../07_vertriebskanaele-markt-wettbewerb/LF09_Kompatibilität-von-neuen-Vertriebswegen_E-Commerce_OSZHandel1.md) (Block Vertriebskanäle) hat den Schritt „Bewertungsmaßstab festlegen“ und nennt die fehlende WaWi-Schnittstelle als K.-o.-Kriterium (dass K.-o.-Kriterien vor der Bewertung geprüft werden, steht dort als Ergänzung); die Ergänzung in [LF12](LF12_Projektmanagement-und-Projektmethoden_E-Commerce_OSZHandel1.md) fasst Maßstab und Bewertung zusammen und endet mit „Rangfolge bilden“.
   - In der Prüfung: das Schema aus LF09_Kompatibilität: Alternativen festlegen → Kriterien definieren → gewichten (Summe 100 %) → Bewertungsmaßstab festlegen → bewerten → gewichtete Punkte summieren und auswählen; K.-o.-Kriterien (z. B. keine WaWi-Schnittstelle) vorher prüfen.
   - Warum: Ein einheitliches Schema für alle Blöcke; inhaltlich ist beides richtig.

7. **SMART: Was bedeutet das „A“?**
   - Abweichung: [LF12](LF12_Projektmanagement-und-Projektmethoden_E-Commerce_OSZHandel1.md) sagt „aktivierend“, [LF07_Marketingziele](../09_online-marketing-ziele-werbeformate/LF07_Marketingziele-Werbeziele_E-Commerce_OSZHandel1.md) „attraktiv (accepted/achievable)“ bzw. „aktiv beeinflussbar“.
   - In der Prüfung: wie im Block Online-Marketing: „A = attraktiv/akzeptiert (erreichbar und von den Beteiligten angenommen)“, eine zweite Lesart darfst du nennen.
   - Warum: Mehrere Lesarten sind üblich; entscheidend ist, dass du sie erklärst.

8. **ABC-Priorisierung („Rock, Pebble & Sand“) und Artikel-ABC**
   - Abweichung: [LF12](LF12_Projektmanagement-und-Projektmethoden_E-Commerce_OSZHandel1.md) nennt nur „A = höchstens ca. 20 % der Aufgaben für ca. 80 % der Wirkung“.
   - In der Prüfung: dieselben Richtwerte wie bei der Artikel-ABC im Block Kostenrechnung/Sortiment ([LF02_Sortimentserweiterung](../01_kostenrechnung-kalkulation-sortiment/LF02_Sortimentserweiterung-bereinigung-diversifikation_E-Commerce_OSZHandel1.md)): A ca. 80 %, B ca. 15 %, C ca. 5 % der Wirkung bzw. des Wertes.
   - Warum: Gleiches Verfahren (Pareto), nur auf Aufgaben statt Artikel angewendet.

9. **Schnittstellenmanagement Teil 1 und Teil 2 überschneiden sich**
   - Abweichung: [Teil 1](LF09_Schnittstellenmanagement-im-B2B-und-B2C_E-Commerce_OSZHandel1.md) und [Teil 2](LF09_Schnittstellenmanagement-im-B2B-und-B2C-2_E-Commerce_OSZHandel1.md) behandeln API, ERP, CRM, PIM, PSP und Logistik doppelt; die Aufgabenblätter sind fast gleich. Die Prüfungszuordnung von Teil 2 ist nur geschätzt (PDF-Kopf ohne Nummerierung).
   - In der Prüfung: Teil 1 ist die Basis; aus Teil 2 nur die technischen API-Merkmale (HTTP/REST, Versionierung, Sicherheit, Governance) und die B2B-Echtzeitdaten (individuelle Preise, Bonität, Verfügbarkeit). Bei „Hauptgruppen“ immer B2B, B2C und betriebsintern nennen (die Originallösung zu Aufgabe 4 in Teil 1 vergisst sie).
   - Warum: Teil 2 bringt sonst nichts Neues.

10. **Was ist eine Schnittstelle, was eine API? Drei Formulierungen**
    - Abweichung: Teil 1: Schnittstelle = durch Arbeitsteilung entstandene Transferpunkte (organisatorisch), API = „Stück Software, das anderen Programmen zur Anbindung zur Verfügung gestellt wird“. Teil 2: Schnittstelle = Berührungspunkt, über den Informationen übertragen und übersetzt werden; API = „Software-Vermittler zwischen zwei Anwendungen“. [Daten-Import](LF09_Daten-Import-Daten-Export_E-Commerce_OSZHandel1.md): API legt fest, wie Daten auf der einen Seite gelesen und auf der anderen ausgegeben werden.
    - In der Prüfung: „Eine API (Application Programming Interface) ist eine Programmierschnittstelle, über die zwei Anwendungen direkt miteinander kommunizieren und Daten ohne manuelle Verarbeitung austauschen.“ Bei „Schnittstelle“ allgemein die organisatorische Definition aus Teil 1.
    - Warum: Diese Fassung deckt alle drei Varianten ab.

11. **Indirekter Vertriebskanal**
    - Abweichung: [Schnittstellen Teil 1](LF09_Schnittstellenmanagement-im-B2B-und-B2C_E-Commerce_OSZHandel1.md) definiert ihn als Kanal mit „nur informativem Charakter“, der zum Shop weiterleitet. [LF09_Vertriebskanäle](../07_vertriebskanaele-markt-wettbewerb/LF09_Vertriebskanäle_E-Commerce_OSZHandel1.md) definiert ihn über zwischengeschaltete Absatzmittler.
    - In der Prüfung: indirekter Vertrieb = ein oder mehrere Absatzmittler (Händler) zwischen Unternehmen und Endkunde.
    - Warum: Das ist die klassische Definition, und die Vor-/Nachteile-Tabelle in Teil 1 passt nur zu ihr. Die Definition aus Teil 1 beschreibt eher Referral-Kanäle.

12. **„Der Webshop ist nur die Hülle, alle Daten kommen aus dem ERP“**
    - Abweichung: So steht es in [Teil 2](LF09_Schnittstellenmanagement-im-B2B-und-B2C-2_E-Commerce_OSZHandel1.md). In vielen Systemlandschaften gibt es je Datenart ein führendes System, z. B. Produktdaten im Shop oder PIM, Bestände im ERP/WWS.
    - In der Prüfung: Die ERP-Shop-Schnittstelle als essenziell beschreiben (Aufträge und Artikel ins ERP, Bestände zurück). Wenn nach der Systemlandschaft gefragt wird, das „führende System je Datenart“ nennen.
    - Warum: Die Aussage des Materials gilt nur für ERP-zentrierte Landschaften. Gegenbeispiel aus der Praxis: das Shopsystem als Produktdaten-Master, die WaWi nur für Bestand, Einkauf und Fulfillment.

13. **Feed oder API, und die Kopfzeilen der Datenblätter**
    - Abweichung: Die Datenblätter erwähnen Feed und API nebeneinander, ohne sie scharf zu trennen. [Datenaufbereitung](LF09_Datenaufbereitung_E-Commerce_OSZHandel1.md) trägt den Kopf „Teil 2-4“, [Daten-Import](LF09_Daten-Import-Daten-Export_E-Commerce_OSZHandel1.md) „Teil 2-1“.
    - In der Prüfung: Feed = Datei (z. B. CSV/XML), die in festen Abständen an eine Plattform geht (Google Shopping, idealo, Amazon); API = direkte Abfrage zwischen Programmen, auch in Echtzeit. Bestände und Preise mit hoher Änderungsfrequenz → API; Produkttexte und Bilder → Feed reicht. Beide Blätter gehören zu Geschäftsprozesse im E-Commerce. GPSR-Pflichtangaben (seit 13.12.2024) gehören in die Produktdaten und in jeden Feed.
    - Warum: Eine einheitliche Zuordnung; die Kleinschrift der Gartner-Grafik (Stichprobe, Jahr) ist nicht sicher lesbar und wird nicht verwendet.

14. **§ 377 HGB im Blatt „Logistische Anforderungen“**
    - Abweichung: [LF09_Logistische-Anforderungen](LF09_Logistische-Anforderungen_E-Commerce_OSZHandel1.md) schreibt „Mängel dem Lieferschein mitteilen“, sagt nicht, dass § 377 HGB nur beim beiderseitigen Handelskauf gilt, und die Lösung zu Aufgabe 6 ist aus Aufgabe 5 kopiert.
    - In der Prüfung: Beim beiderseitigen Handelskauf Ware unverzüglich prüfen, offene Mängel unverzüglich, versteckte unverzüglich nach Entdeckung dem Verkäufer anzeigen, sonst gilt die Ware als genehmigt. B2C: keine Rügepflicht. Darstellung identisch mit [LF05_Mangelhafte-Lieferung](../04_vertragsstoerungen-maengel-verzug/LF05_Mangelhafte-Lieferung-und-Annahmeverzug_E-Commerce_OSZHandel1.md) im Block Vertragsstörungen.
    - Warum: So steht es im Gesetz; der Lieferschein ist ein Papier, kein Empfänger.

15. **Flexibilität: Anforderung an die Logistik, aber kein Hauptziel der Distributionslogistik**
    - Abweichung: [Teil 1](LF09_Schnittstellenmanagement-im-B2B-und-B2C_E-Commerce_OSZHandel1.md) nennt Flexibilität als Anforderung an die E-Commerce-Logistik; in Aufgabe 3 ist sie dagegen eine falsche Antwortoption für die Hauptziele der Distributionslogistik (Lösung a, b, e). Die Ziele stehen nur im Lösungsblatt, nicht im Infoblatt.
    - In der Prüfung: Hauptziele = Verfügbarkeit, Kostenminimierung, Einflussnahme. Anforderungen = schnelle Kommissionierung und Lieferung, Flexibilität, optimale Verpackungsgröße, schnelle Warenannahme.
    - Warum: Zwei verschiedene Fragen, zwei verschiedene Listen.

16. **Aufgaben der Lagerhaltung oder Anforderungen an ein Lager?**
    - Abweichung: Die Lösung zu Aufgabe 11 in [LF09_Logistische-Anforderungen](LF09_Logistische-Anforderungen_E-Commerce_OSZHandel1.md) („zu berücksichtigen“) nennt die Aufgaben der Lagerhaltung; die Frage passt eher zu den Anforderungen.
    - In der Prüfung: genau auf das Verb achten. Aufgaben = Verkaufsbereitschaft sichern, zeitliche Überbrückung, Preisvorteile, Umformung, Veredlung. Anforderungen = warengerecht, geräumig, übersichtlich, sachgerecht eingerichtet, sicher.
    - Warum: Beide Listen werden gern vertauscht.

17. **Dienstleistersteuerung steht fast nur in Ergänzungen**
    - Abweichung: [LF09_Outsourcing](LF09_Outsourcing_E-Commerce_OSZHandel1.md) behandelt nur Bereiche sowie Vor- und Nachteile; Lastenheft/Pflichtenheft, SLA, Dienst- und Werkvertrag, AV-Vertrag und Make-or-Buy stehen nur als Ergänzung (dort und in [LF12](LF12_Projektmanagement-und-Projektmethoden_E-Commerce_OSZHandel1.md)). LF12 setzt außerdem den Product Backlog mit dem Lastenheft gleich.
    - In der Prüfung: Diese Ergänzungen sind verbindliche Lernbasis (siehe Lernkarte unten). Product Backlog und Lastenheft sind ähnlich (kundenorientiert, ohne Lösungsweg), aber der Backlog ändert sich laufend, das Lastenheft ist Vertragsgrundlage. SLA-Kennzahlen mit denselben Formeln wie in [LF10_Leistungsqualität](../05_rueckabwicklung-retouren-qualitaet-prozesse/LF10_Leistungsqualität_E-Commerce_OSZHandel1.md) (Perfect Order Rate, On-Time Shipping Rate, nicht „One-Time“).
    - Warum: Die Verordnung verlangt „Dienstleistungsumfang definieren und Leistungserbringung kontrollieren“; ohne diese Begriffe fehlt dir die Antwort.

## Formeln des Blocks

Ausführlich mit Beispielen: [../../FORMELSAMMLUNG.md](../../FORMELSAMMLUNG.md)

| Formel | Variablen |
|---|---|
| Teilnutzwert = g × p; Gesamtnutzwert = Σ (g × p) | g = Gewicht des Kriteriums (Σ g = 1,00), p = Punkte der Alternative |
| Wertigkeit = erreichter Wert ÷ Wert der Ideallösung (gewichtet: Gesamtnutzwert ÷ Ideal-Nutzwert; ungewichtet: Punktsumme ÷ Ideal-Punktsumme) | Ideal gewichtet = Höchstpunkte × Σ g; ungewichtet = Anzahl Kriterien × Höchstpunkte |
| Kosten Eigenleistung = Kf + kv × x; Kosten Fremdleistung = p × x (+ G) | Kf = Fixkosten eigen, kv = variable Kosten je Einheit eigen, p = Preis je Einheit Dienstleister, G = Grundgebühr, x = Menge (🔎 Ergänzung) |
| Kritische Menge = Kf ÷ (p − kv), mit Grundgebühr (Kf − G) ÷ (p − kv) | unter der kritischen Menge ist Outsourcing günstiger, darüber die Eigenleistung (🔎 Ergänzung) |
| Ø Lagerbestand = (AB + EB) ÷ 2 oder (Jahresanfangsbestand + 12 Monatsendbestände) ÷ 13 | AB/EB = Anfangs-/Endbestand zu Einstandspreisen (🔎 Ergänzung) |
| Umschlagshäufigkeit = Wareneinsatz ÷ Ø Lagerbestand | beides zu Einstandspreisen (🔎 Ergänzung) |
| Ø Lagerdauer = 360 ÷ Umschlagshäufigkeit | in Tagen; nennt die Aufgabe 365 Tage, mit 365 rechnen (🔎 Ergänzung) |
| Perfect Order Rate = fehlerfreie Aufträge ÷ alle Aufträge × 100 | aus Block Rückabwicklung, als SLA-Kennzahl nutzbar (🔎 Ergänzung) |
| On-Time Shipping Rate = termingerecht abgewickelte Aufträge ÷ alle Aufträge × 100 | aus Block Rückabwicklung (🔎 Ergänzung) |
| Meldebestand = Tagesverbrauch × Wiederbeschaffungszeit + Mindestbestand | Wiederbeschaffungszeit in Tagen (🔎 Ergänzung, siehe Lücken) |

## Top-Prüfungsfallen

1. **Drei Schnittstellen-Hauptgruppen** sind B2B (extern), B2C (extern) und **betriebsintern**, nicht „B2B, B2C, C2C“.
2. **Feed ≠ API:** Feed = Datei in festen Abständen; API = direkte Kommunikation zwischen Programmen, auch in Echtzeit. Bestände beim Verkauf über mehrere Kanäle brauchen Echtzeit, sonst Überverkäufe.
3. **PIM ≠ ERP ≠ CRM:** PIM = Produktinformationen, ERP/WWS = Bestände, Aufträge, Einkauf, Rechnungen, CRM = Kundenbeziehungen und Kundenhistorie.
4. **Wichtigster Aspekt der Datenaufbereitung = Datenformat**; Formatkriterium = eine Information pro Spalte; Bereinigen kommt vor Formatieren; Datenvalidierung ist die Plausibilitätsprüfung danach (49,90 € werden durch Kommafehler zu 4,99 €).
5. **Warenfluss = physisch, Datenfluss = Informationen** zwischen Einkauf, Lager und Verkauf.
6. **Wareneingang:** äußere Prüfung **sofort** in Anwesenheit des Frachtführers, inhaltliche Prüfung **unverzüglich** (ohne schuldhaftes Zögern); Rüge an den **Verkäufer**; § 377 HGB nur beim **beiderseitigen Handelskauf**; versteckte Mängel unverzüglich nach Entdeckung; versäumte Rüge = Ware gilt als genehmigt.
7. **Aufgaben der Lagerhaltung ≠ Anforderungen an ein Lager**; Umformung (umpacken, sortieren) ≠ Veredlung (Qualität steigt durch Lagern).
8. **Hauptziele der Distributionslogistik:** Verfügbarkeit, Kostenminimierung, Einflussnahme; Flexibilität gehört nicht dazu.
9. **Kritische Menge richtig deuten:** unter ihr ist Outsourcing günstiger, über ihr die Eigenleistung; zusätzlich qualitative Gründe nennen.
10. 🔎 **Lastenheft** (Auftraggeber: Was und Wofür) ≠ **Pflichtenheft** (Auftragnehmer: Wie und Womit); **Werkvertrag** (Erfolg, Abnahme) ≠ **Dienstvertrag** (Tätigkeit); Paketdienst braucht keinen AV-Vertrag, Fulfillment-Dienstleister schon.
11. **Agil und Scrum:** vier Leitsätze im Agilen Manifest; Review = Was (Ergebnis, mit Stakeholdern), Retrospektive = Wie (Arbeitsprozess, Team); Scrum Master ist kein Chef, der Product Owner vertritt den Kunden und verantwortet den Backlog.
12. **Nutzwertanalyse:** Gewichte müssen 100 % ergeben, die **gewichtete** Summe entscheidet (ungewichtet kann eine andere Rangfolge herauskommen), Ideal = Kriterien × Höchstpunkte; Schwäche: Gewichte und Punkte sind subjektiv.

## Fachbegriffe Deutsch–Englisch

| Deutsch | Englisch | Kurzbedeutung |
|---|---|---|
| Schnittstelle | interface | Übergabepunkt zwischen Systemen, Abteilungen oder Unternehmen |
| Programmierschnittstelle | API (application programming interface) | Software-Vermittler, über den zwei Anwendungen Daten austauschen |
| Produktdatenfeed | product (data) feed | Datei mit Produktdaten, die in festen Abständen an eine Plattform geht |
| Warenwirtschaftssystem / Unternehmensressourcenplanung | merchandise/inventory management system; ERP (enterprise resource planning) | Bestände, Aufträge, Einkauf, Rechnungen |
| Produktinformationsmanagement | PIM (product information management) | zentrale Verwaltung von Produktdaten |
| Kundenbeziehungsmanagement | CRM (customer relationship management) | Kundendaten und Kundenhistorie |
| Zahlungsdienstleister | PSP (payment service provider) | wickelt Zahlungen im Shop ab |
| Insellösung | isolated solution, data silo | System ohne Anbindung, Daten müssen manuell übertragen werden |
| Stammdaten | master data | dauerhafte Grunddaten, z. B. Artikelmaße, Gewicht |
| Datenaufbereitung / Datenbereinigung | data preparation / data cleansing | Rohdaten sammeln, prüfen, formatieren, anreichern |
| Datenlager | data warehouse | zentraler Speicher aufbereiteter Daten aus vielen Quellen |
| Echtzeit | real time | Daten sind sofort aktuell |
| Überverkauf | overselling | mehr verkauft als vorhanden |
| Wareneingang | goods receipt, goods-in | Annahme und Prüfung gelieferter Ware |
| Mängelrüge | notice of defects | Anzeige eines Mangels beim Verkäufer |
| Kommissionierung / Verpackung / Versand | picking / packing / shipping | Schritte vom Lagerplatz bis zum Paket |
| Auftragsabwicklung (Logistik) | fulfil(l)ment | Lagerung, Kommissionierung, Versand, Retouren |
| Sendungsverfolgung | (parcel) tracking | Status der Sendung abrufen |
| letzte Meile | last mile | Weg vom Paketdepot bis zum Endkunden |
| Umschlagshäufigkeit | inventory turnover | wie oft der Lagerbestand pro Jahr umgeschlagen wird |
| Auslagerung / Eigen- oder Fremdleistung | outsourcing / make or buy | Aufgabe an Externe vergeben oder selbst erledigen |
| Kernkompetenz | core competence | was ein Unternehmen am besten kann |
| Dienstleistungsvereinbarung | SLA (service level agreement) | vereinbarte, messbare Leistungsqualität |
| Lastenheft / Pflichtenheft | (customer) requirements specification / functional specification | Anforderungen des Auftraggebers / Umsetzungsplan des Auftragnehmers |
| Auftragsverarbeitungsvertrag | DPA (data processing agreement) | Vertrag nach Art. 28 DSGVO mit Dienstleistern, die Kundendaten verarbeiten |
| Nutzwertanalyse | weighted scoring model, utility analysis | Alternativen mit gewichteten Kriterien vergleichen |
| Meilenstein | milestone | wichtiger Zwischentermin im Projekt |
| Wasserfallmodell | waterfall model | Phasen laufen streng nacheinander ab |
| Produkt-/Sprint-Backlog | product / sprint backlog | priorisierte Anforderungsliste / Auswahl für den Sprint |
| Sprint-Überprüfung / Rückblick | sprint review / sprint retrospective | Ergebnis prüfen / Arbeitsweise verbessern |
| Inkrement | increment | fertiges, nutzbares Teilergebnis |
| Interessengruppe | stakeholder | alle, die vom Projekt betroffen sind oder es beeinflussen |

## Spickzettel

(🔎 = Ergänzung, nicht im Original)

- **Schnittstelle:** Transferpunkt durch Arbeitsteilung; Hauptgruppen B2B, B2C (extern), betriebsintern. **Ziele:** Zielabstimmung, keine Insellösungen, Konfliktmanagement, Übersetzer, Schulung.
- **API** = Programmierschnittstelle, zwei Anwendungen tauschen Daten direkt aus (HTTP/REST, JSON 🔎). **Feed** = Datei in festen Abständen (CSV, XML 🔎). Bestand bei mehreren Kanälen → Echtzeit 🔎.
- **Shop-Anbindungen:** ERP/WWS (unabdingbar), PIM (Multichannel), CRM/Newsletter (Personalisierung, DSGVO), PSP (essenziell), Marktplätze/Preissuchmaschinen, Logistik (Tracking, Lieferoptionen), Social Media.
- **B2B:** Einkaufsberechtigung, individuelle Preise, Echtzeit für Preise, Bonität, Verfügbarkeit. **Ohne eigenes Lager:** eine Schnittstelle je Dienstleister.
- **Daten:** Import = rein (Herstellerdaten), Export = raus (Google Shopping, idealo, Amazon, Affiliate). Excel/CSV, eine Info pro Spalte; PDF/E-Mail ungeeignet.
- **Aufbereitung:** Sammeln → Bereinigen → Formatieren/Anreichern → Speichern. Validierung = Plausibilität. DWH = nur aufbereitete Daten.
- **WWS:** Planung, Steuerung, Kontrolle; Waren- (physisch) und Datenfluss (Info) vom Wareneingang bis zum Verkauf.
- **Wareneingang:** außen sofort mit Frachtführer (bestätigen lassen/Annahme verweigern), innen unverzüglich; § 377 HGB: beiderseitiger Handelskauf, Rüge an Verkäufer, sonst genehmigt.
- **Lager:** Aufgaben (Verkaufsbereitschaft, Überbrückung, Preisvorteile, Umformung, Veredlung) ≠ Anforderungen (warengerecht, geräumig, übersichtlich, sachgerecht, sicher). UH = Wareneinsatz ÷ Ø Bestand; Lagerdauer = 360 ÷ UH 🔎.
- **Distributionslogistik:** Verfügbarkeit, Kostenminimierung, Einflussnahme.
- **Outsourcing:** wenn günstiger, schneller und/oder besser. Vorteile: Zeit, Kosten (keine Personalfixkosten), Kerngeschäft, Angebot erweitern, Qualität. Nachteile: Abhängigkeit, Kommunikation, Kontrollverlust, Dienstleisterkosten, weniger Weiterbildung. Kritische Menge = Kf ÷ (p − kv) 🔎.
- 🔎 **Dienstleister steuern:** Lastenheft (AG: Was) → Pflichtenheft (AN: Wie) → Werk-/Dienstvertrag, SLA mit KPI, AV-Vertrag Art. 28 DSGVO → Kontrolle per KPI → Eskalation.
- **Agiles Manifest:** Menschen > Prozesse, funktionierendes Ergebnis > Doku, Kundenzusammenarbeit > Verträge, Reagieren auf Veränderung > Plan.
- **Scrum:** PO (Kunde, Backlog), Scrum Master (Hindernisse, Coach), Developers. Planning → Sprint (≤ 1 Monat, Daily ≤ 15 Min. 🔎) → Review (Was) → Retro (Wie). Artefakte: Product Backlog, Sprint Backlog, Inkrement.
- **Kanban:** Board, Pull-Prinzip, WIP-Limit 🔎, kein Scrum Master, kein Sprint. **Scrumban** = Hybrid. Agil bei unklaren Anforderungen, klassisch (Wasserfall 🔎) bei festen.
- **Priorisierung:** SMART-Ziel → relevant? → Walking Skeleton → ABC (Rock/Pebble/Sand, 80/15/5) → KPI → Nutzwertanalyse (Σ Gewichte = 100 %, gewichtete Summe entscheidet).

## Lücken & Ergänzungen

**1. Dienstleister steuern (A1: Dienstleistungsumfang definieren, Leistungserbringung kontrollieren) – Material deckt nur Outsourcing-Bereiche sowie Vor- und Nachteile ab. Lernkarte, ca. 20 Min.**

🔎 Ergänzung (nicht im Original):
- **Ablauf:** Bedarf und Make-or-Buy klären → **Lastenheft** (Auftraggeber: Was und Wofür, mit Budget und Termin) → Anbieter anfragen, K.-o.-Kriterien prüfen, **Nutzwertanalyse** → **Pflichtenheft**/Angebot (Auftragnehmer: Wie und Womit) → **Vertrag** → Umsetzung und **Abnahme** → laufende **Leistungskontrolle** → bei Abweichungen **Eskalation**.
- **Vertragsart:** **Werkvertrag** (§ 631 BGB): ein Erfolg ist geschuldet, z. B. fertige Schnittstelle oder App; mit Abnahme (§ 640 BGB), die Vergütung wird bei Abnahme fällig (§ 641 BGB), bei Mängeln Nacherfüllung usw. (§ 634 BGB). **Dienstvertrag** (§ 611 BGB): eine Tätigkeit ist geschuldet, z. B. laufende SEA-Betreuung oder Support nach Stunden, kein bestimmter Erfolg.
- **SLA** mit messbaren Kennzahlen und Zielwert, z. B. Versand am Bestelltag bei Bestelleingang bis 14 Uhr ≥ 97 %, Perfect Order Rate ≥ 98 %, Fehlversandquote (fehlerhafte ÷ alle Sendungen × 100) ≤ 0,5 %, Lagerbestandsgenauigkeit ≥ 99 %, Reaktionszeit bei Störungen ≤ 2 Std., Shop-Verfügbarkeit ≥ 99,9 %. Rechenbeispiel Verfügbarkeit: 99,9 % in einem 30-Tage-Monat (720 Std.) erlauben 720 × 0,001 = 0,72 Std. = 43,2 Min. Ausfall.
- **Datenschutz:** Verarbeitet der Dienstleister Kundendaten im Auftrag (Fulfillment, Newsletter, Kundenservice-Tool), ist ein **AV-Vertrag nach Art. 28 DSGVO** nötig; die Verantwortung bleibt beim Shop. Paketdienste gelten meist als eigenständig Verantwortliche.
- **Leistungskontrolle:** regelmäßiges KPI-Reporting, feste Abstimmungstermine, Stichproben (z. B. Testbestellungen), Abweichung dokumentieren, Ursachen gemeinsam analysieren, Nachbesserung mit Frist; vertragliche Folgen nur, wenn vereinbart (z. B. Vertragsstrafe, Bonus-Malus, Kündigungsrecht).
- **Intern vs. extern:** interne Dienstleister (eigene IT, Grafik, Buchhaltung) haben kurze Wege und Know-how im Haus, aber Fixkosten; externe (Fulfillment, Agentur, App-Anbieter, Steuerberater) sind spezialisiert und flexibel, aber es entsteht Abhängigkeit.

**2. Shopsystem-Arten (§ 11 Abs. 2 Nr. 1: technische Voraussetzungen einschätzen) – das Material nennt nur Magento und Shopware als Beispiele.**

🔎 Ergänzung (nicht im Original):
- **SaaS-/Mietshop** (z. B. Shopify): Hosting, Updates und Sicherheit übernimmt der Anbieter, monatliche Gebühr, schnell startklar; Anpassungen über Themes und Apps, dadurch Abhängigkeit vom Anbieter.
- **Open-Source- oder Lizenz-Software, selbst oder beim Hoster betrieben** (z. B. Shopware, WooCommerce, Magento Open Source bzw. Adobe Commerce): sehr anpassbar, aber Server, Updates und Sicherheit liegen beim Händler bzw. seiner Agentur.
- **Eigenentwicklung:** maximal individuell, teuer und abhängig von den Entwicklern.
- **Headless Commerce:** Frontend und Backend getrennt, verbunden über APIs.
- **Auswahlkriterien:** Gesamtkosten, verfügbare Schnittstellen (WaWi, PSP, Marktplätze, Feeds), Skalierbarkeit bei Lastspitzen (Black Week), Mehrsprachigkeit und Mehrländerfähigkeit, B2B-Funktionen, rechtssichere Checkout-Funktionen. Fehlende WaWi-Schnittstelle ist ein K.-o.-Kriterium (wie bei neuen Vertriebskanälen).

**3. Fulfillment-Prozess (logistische Anforderungen) – das Material behandelt Warenwirtschaft, Wareneingang und Lager, aber nicht die Prozesskette im Versand.**

🔎 Ergänzung (nicht im Original):
- **Prozesskette:** Wareneingang → Einlagerung → Kommissionierung (Picking) → Verpackung (Packing) → Versand (Label, Trackingnummer zurück an Shop/Marktplatz) → Retourenbearbeitung.
- **Kommissionierung:** auftragsorientiert (ein Auftrag nach dem anderen) oder serienorientiert/zweistufig (erst Artikel für viele Aufträge sammeln, dann auf die Aufträge verteilen); „Mann zur Ware“ oder „Ware zum Mann“.
- **Dropshipping, Lieferzeit und letzte Meile:** siehe [LF10_Leistungsqualität](../05_rueckabwicklung-retouren-qualitaet-prozesse/LF10_Leistungsqualität_E-Commerce_OSZHandel1.md).

**4. Beschaffung (Teil 1, § 8 Nr. 2) – nur bei Zeitpuffer.** Die Lagerkennzahlen stehen als Ergänzung in [LF09_Logistische-Anforderungen](LF09_Logistische-Anforderungen_E-Commerce_OSZHandel1.md).

🔎 Ergänzung (nicht im Original): **Meldebestand** = Tagesverbrauch × Wiederbeschaffungszeit + Mindestbestand. Beispiel: 40 Gummiköder-Sets pro Tag, 6 Tage Lieferzeit, Mindestbestand 120 → 40 × 6 + 120 = 360 Sets. Erreicht der Bestand 360, wird bestellt (im WWS als automatischer Bestellvorschlag).

**5. Projektorientiertes Arbeiten im Report und im Fachgespräch (§ 13 Abs. 1 Nr. 6 und 7) – im Material nur Methoden, keine Projektphasen, keine Kommunikations- und Kooperationsbedingungen.**

🔎 Ergänzung (nicht im Original):
- **Projektmanagementphasen nach DIN 69901:** Initialisierung, Definition, Planung, Steuerung, Abschluss. Werkzeuge: Projektauftrag (SMART-Ziel, Budget, Termin), Stakeholder-Übersicht, Projektstrukturplan, Meilensteine und Gantt-Diagramm, Risikoliste, Statusberichte, Abschluss mit Lessons Learned (entspricht der Retrospektive).
- **Kommunikations- und Kooperationsbedingungen:** wer beteiligt ist (Geschäftsführung, Einkauf, Lager, Kundenservice, Agentur/Dienstleister, Ausbildende), über welche Wege abgestimmt wird (Meetings, Tickets, Chat), wer freigibt, wie Konflikte gelöst wurden. Dazu nach der schriftlichen Prüfung eine Lernkarte (ca. 15 Min.) zum eigenen Projekt anlegen.
- Report-Gliederung nach § 13 Abs. 5: Aufgabenstellung, Zielsetzung, Planung, Vorgehen, Ergebnis, Reflexion. Die Begriffe aus [LF12](LF12_Projektmanagement-und-Projektmethoden_E-Commerce_OSZHandel1.md) (Priorisierung, Nutzwertanalyse, agil oder klassisch) passen in „Planung“ und „Vorgehen“.

**6. Statistiken erstellen und auswerten (A8) – das Material behandelt nur Daten-Import/-Export und Datenaufbereitung.** Diagrammwahl, Mittelwerte, Prozent vs. Prozentpunkte und Indexzahlen stehen als Ergänzung in der [FORMELSAMMLUNG](../../FORMELSAMMLUNG.md), Abschn. 2.4, 2.7 und 2.8; gelernt werden sie laut [LERNPLAN](../../LERNPLAN.md) am So 25.10. zusammen mit Block 03 Kennzahlen.

**7. Englische Fachbegriffe (§ 11 Abs. 1 Nr. 4):** siehe Tabelle oben; in Fallaufgabe 1 steht eine englische Marktplatz-Meldung zum Üben.

## Fallaufgaben im IHK-Stil

**Ausgangssituation (für alle drei Fälle):** Die Wobblerwerk GmbH (fiktives Unternehmen) betreibt einen Onlineshop für Raubfischzubehör mit rund 4.000 Artikeln einschließlich Varianten. Produktdaten werden im Shopsystem gepflegt, Bestände, Einkauf und Versand laufen über die Warenwirtschaft. Sie arbeiten als Kaufmann im E-Commerce im Team E-Commerce-Management.

### Fall 1: Neuer Marktplatz, Daten und Schnittstellen (20 Punkte, Richtzeit 24 Min.)

Wobblerwerk will das Sortiment zusätzlich auf einem großen Online-Marktplatz und bei einer Preissuchmaschine anbieten. Gleichzeitig liefert ein neuer Lieferant (Köderbau Nord GmbH, fiktiv) seine Artikeldaten als Excel-Datei. Ausschnitt:

| Artikel | Hersteller | EK netto | VK brutto | lieferbar ab |
|---|---|---|---|---|
| Shad 12 cm Motoroil, 5 Stk. | Köderbau Nord GmbH, Musterstr. 1 12345 Musterstadt | 3,10 | 7,99 | 01.12.26 |
| Shad 15 cm Firetiger, 4 Stk. | Köderbau Nord GmbH, Musterstr. 1 12345 Musterstadt | 3,6 | 0,99 | 2026-12-01 |
| Shad 18 cm Perch, 3 Stk. | | 4,20 | 11,99 | Montag, 7. Dezember 2026 |

1.1 Erläutern Sie zwei Systeme bzw. Schnittstellen, die für den Verkauf über den Marktplatz zwingend angebunden sein müssen. (4 Punkte)

1.2 Unterscheiden Sie einen Produktdatenfeed von einer API. Begründen Sie, welchen Weg Sie a) für Produkttexte und Bilder und b) für Lagerbestände wählen. (4 Punkte)

1.3 Nennen Sie drei Mängel der Lieferantendatei und je eine Maßnahme. (6 Punkte)

1.4 Nennen Sie drei Angaben, die ein Online-Angebot nach der EU-Produktsicherheitsverordnung (GPSR) enthalten muss. (3 Punkte)

1.5 Der Marktplatz schickt folgende Meldung: *„Your listing for SKU WW-SHAD-18 has been suppressed because the required attribute 'manufacturer_contact' is missing. Please update your feed within 7 days.“* Erläutern Sie auf Deutsch, was passiert ist und was Sie jetzt tun. (3 Punkte)

### Fall 2: Fulfillment auslagern? (25 Punkte, Richtzeit 30 Min.)

Wobblerwerk versendet bisher selbst. Im Durchschnitt sind es 3.000 Sendungen pro Monat, im November und Dezember (Black Week, Weihnachten) je 6.000. Das Lager ist zu klein, das Lagerteam arbeitet in den Spitzen am Limit. Ein Fulfillment-Dienstleister hat ein Angebot gemacht:

| | Eigenlogistik | Fulfillment-Dienstleister |
|---|---|---|
| Fixkosten pro Monat | 9.600 € | 600 € (Grundgebühr) |
| variable Kosten je Sendung (ohne Porto) | 2,10 € | 4,50 € |

2.1 Berechnen Sie die monatlichen Kosten beider Alternativen bei 3.000 und bei 6.000 Sendungen sowie die kritische Menge. (6 Punkte)

2.2 Berechnen Sie die Jahreskosten beider Alternativen (10 Monate mit 3.000 und 2 Monate mit 6.000 Sendungen) und treffen Sie eine kostenbasierte Entscheidung. (3 Punkte)

2.3 Nennen Sie je zwei qualitative Gründe für und gegen das Outsourcing in dieser Situation. (4 Punkte)

2.4 Formulieren Sie drei messbare Kennzahlen mit Zielwert für das Service Level Agreement. (3 Punkte)

2.5 Nach dem Start meldet der Dienstleister für Oktober: 3.200 Aufträge, davon 2.960 fehlerfrei (vollständig, richtig, pünktlich, unbeschädigt) und 3.040 SLA-gerecht am Bestelltag versandt. Vereinbart sind eine Perfect Order Rate von mindestens 98 % und eine Versandquote am Bestelltag von mindestens 97 %. Berechnen Sie beide Quoten, beurteilen Sie das Ergebnis und nennen Sie eine Maßnahme. (4 Punkte)

2.6 Welcher Vertrag ist aus Datenschutzsicht zusätzlich nötig? Begründen Sie. (2 Punkte)

2.7 Beim Dienstleister trifft eine Lieferung Wathosen eines Großhändlers ein, ein Karton ist sichtbar eingedrückt. Beschreiben Sie, was beim Wareneingang zu tun ist und was Wobblerwerk deshalb im Vertrag mit dem Dienstleister regeln sollte. (3 Punkte)

### Fall 3: Projekt „Köderberater“ mit einer Agentur (25 Punkte, Richtzeit 30 Min.)

Wobblerwerk will einen digitalen Köderberater in den Shop einbauen: Kunden wählen Zielfisch, Gewässer und Jahreszeit und bekommen passende Köder vorgeschlagen. Welche Funktionen die Kunden wirklich nutzen, ist noch unklar. Drei Agenturen haben angeboten; das Team hat sie bewertet (Skala 1 bis 10):

| Kriterium | Gewicht | Agentur A | Agentur B | Agentur C |
|---|---|---|---|---|
| Preis | 0,35 | 6 | 9 | 7 |
| Erfahrung mit dem Shopsystem | 0,25 | 9 | 6 | 8 |
| Schnittstellen-Know-how (WaWi, Produktdaten) | 0,25 | 8 | 6 | 9 |
| Support und Reaktionszeit | 0,15 | 7 | 8 | 5 |

3.1 Vor der Anfrage bei den Agenturen wurde ein Lastenheft erstellt. Erläutern Sie, wer Lastenheft und Pflichtenheft erstellt und was jeweils darin steht. (4 Punkte)

3.2 Führen Sie die Nutzwertanalyse durch und entscheiden Sie sich für eine Agentur. (7 Punkte)

3.3 Beurteilen Sie das Ergebnis kritisch. (2 Punkte)

3.4 Entscheiden Sie begründet, ob das Projekt mit Scrum oder klassisch durchgeführt werden sollte. (3 Punkte)

3.5 Nennen Sie die drei Scrum-Verantwortlichkeiten und ordnen Sie zu, wer sie in diesem Projekt sinnvollerweise übernimmt. (3 Punkte)

3.6 Unterscheiden Sie Sprint Review und Sprint Retrospektive. (2 Punkte)

3.7 Die Agentur soll den Köderberater fertig programmieren und zur Abnahme übergeben; danach soll sie ihn nach Stundenaufwand betreuen. Ordnen Sie beiden Leistungen die Vertragsart zu. (2 Punkte)

3.8 Formulieren Sie ein SMART-Ziel für den Köderberater. (2 Punkte)

### Musterlösungen

**Fall 1**

1.1 (je System 2 Punkte: Nennung 1, Begründung 1; zwei davon)
- **Warenwirtschaft/ERP:** Bestände aller Kanäle abgleichen, sonst Überverkäufe; Marktplatz-Bestellungen übernehmen und an Lager/Versand und Rechnung weitergeben.
- **Marktplatz- bzw. Feed-Schnittstelle (Shop/PIM als Datenquelle):** Produktdaten (Titel, Bilder, Attribute, Preise, GPSR-Angaben) an Marktplatz und Preissuchmaschine übertragen, Bestellungen zurückholen.
- **Logistikdienstleister:** Versandlabel erzeugen, Trackingnummer an den Marktplatz zurückmelden.
- Bewertungshinweis: Nur genannt, ohne Begründung = 1 Punkt je System.

1.2 (4 Punkte)
- Feed: Datei bzw. Datenquelle (z. B. CSV/XML), die in festen Abständen ausgewählte Produktdaten an eine Plattform schickt (1).
- API: Programmierschnittstelle, über die zwei Programme direkt miteinander kommunizieren; Daten können bei Bedarf bzw. in Echtzeit übertragen werden (1).
- a) Texte und Bilder: Feed reicht, weil sie sich selten ändern (1).
- b) Bestände: API bzw. Echtzeitabgleich, weil sich der Bestand mit jedem Verkauf auf jedem Kanal ändert; sonst Überverkäufe, Stornos und schlechte Verkäuferbewertungen (1).

1.3 (je Mangel 1 Punkt, je Maßnahme 1 Punkt; drei davon)
- Herstellername und Adresse in einer Zelle → eigene Spalten für Name, Straße, PLZ, Ort (plus E-Mail) anfordern oder mit „Text in Spalten“ trennen.
- Artikelbezeichnung enthält Länge, Farbe und Stückzahl → als eigene Attribute bzw. Variantenmerkmale anlegen (Filter, Varianten, Marktplatz-Attribute).
- Drei verschiedene Datumsformate → ein einheitliches Format festlegen (z. B. ISO 8601: JJJJ-MM-TT), per Makro oder Importregel umwandeln.
- VK 0,99 € liegt unter dem EK (3,60 €) und ist unplausibel (vermutlich Tipp- oder Kommafehler) → Datenvalidierung mit Untergrenze (z. B. VK nicht unter EK), Rückfrage beim Lieferanten bzw. Einkauf.
- Herstellerangaben in Zeile 3 fehlen → Datensatz unvollständig, GPSR-Pflichtangabe fehlt → beim Lieferanten nachfordern, Artikel erst danach freigeben.
- „3,6“ statt „3,60“ → einheitliches Zahlenformat mit zwei Nachkommastellen (Dezimalkomma bzw. -punkt beachten).

1.4 (je Angabe 1 Punkt; drei davon; Art. 19 GPSR)
- Name, eingetragener Handelsname oder Marke des Herstellers mit Postanschrift und elektronischer Adresse.
- Bei Herstellern außerhalb der EU: Name und Kontaktdaten der verantwortlichen Person in der EU.
- Angaben zur Identifizierung des Produkts (z. B. Abbildung, Typ, Artikelnummer).
- Warn- und Sicherheitshinweise in einer für Verbraucher leicht verständlichen Sprache.

1.5 (3 Punkte)
- Das Angebot für den Artikel WW-SHAD-18 wurde gesperrt bzw. ausgeblendet und ist für Kunden nicht mehr sichtbar (1).
- Grund: Im Feed fehlt das Pflichtfeld „Herstellerkontakt“ (1).
- Maßnahme: Herstellerkontakt beim Lieferanten anfordern, im Shop bzw. PIM pflegen, Feed innerhalb von 7 Tagen aktualisieren und prüfen, ob das Angebot wieder aktiv ist; zusätzlich eine Feed-Regel, die Artikel ohne Herstellerangaben vor dem Export zurückhält (1).

**Fall 2**

2.1 (6 Punkte: je Menge 2, kritische Menge 2)
- 3.000 Sendungen: Eigen = 9.600 + 3.000 × 2,10 = 9.600 + 6.300 = **15.900 €**; Fremd = 600 + 3.000 × 4,50 = 600 + 13.500 = **14.100 €** → Outsourcing 1.800 € günstiger.
- 6.000 Sendungen: Eigen = 9.600 + 6.000 × 2,10 = 9.600 + 12.600 = **22.200 €**; Fremd = 600 + 6.000 × 4,50 = 600 + 27.000 = **27.600 €** → Eigenlogistik 5.400 € günstiger.
- Kritische Menge: 9.600 + 2,10 x = 600 + 4,50 x → 9.000 = 2,40 x → x = **3.750 Sendungen**. Probe: 9.600 + 3.750 × 2,10 = 17.475 € = 600 + 3.750 × 4,50 = 17.475 €.

2.2 (3 Punkte)
- Eigen: 10 × 15.900 + 2 × 22.200 = 159.000 + 44.400 = **203.400 €**.
- Fremd: 10 × 14.100 + 2 × 27.600 = 141.000 + 55.200 = **196.200 €**.
- Outsourcing ist rein kostenbezogen um **7.200 € pro Jahr** günstiger. Bewertungshinweis: Folgefehler aus 2.1 werden berücksichtigt.

2.3 (je Grund 1 Punkt; zwei dafür, zwei dagegen)
- Dafür: Kapazität in Spitzen (Black Week) flexibel, das eigene Lager ist zu klein; Fokus auf das Kerngeschäft (Sortiment, Beratung, Marketing); Fixkosten werden zu variablen Kosten; Spezialist bringt Know-how und Qualität.
- Dagegen: Abhängigkeit vom Dienstleister; Kontrollverlust (Verpackungsqualität, Beilagen, Sonderwünsche); höherer Kommunikationsbedarf; Schnittstelle WaWi ↔ Dienstleister muss aufgebaut werden; Lager-Know-how geht verloren; bei Mengen über 3.750 pro Monat teurer.

2.4 (je Kennzahl mit Zielwert 1 Punkt; ohne Zielwert 0 Punkte)
- z. B. Versand am Bestelltag bei Bestelleingang bis 14 Uhr ≥ 97 %; Perfect Order Rate ≥ 98 %; Fehlversandquote ≤ 0,5 %; Lagerbestandsgenauigkeit ≥ 99 %; Wareneingang innerhalb von 24 Std. geprüft und gebucht; Retouren innerhalb von 48 Std. bearbeitet; Antwort auf Anfragen innerhalb von 4 Std.

2.5 (4 Punkte)
- Perfect Order Rate = 2.960 ÷ 3.200 × 100 = **92,5 %** (1).
- Versandquote am Bestelltag = 3.040 ÷ 3.200 × 100 = **95 %** (1).
- Beide Zielwerte (98 % und 97 %) werden verfehlt (1).
- Maßnahme: Abweichung dokumentieren, Ursachen mit dem Dienstleister analysieren (z. B. Pickfehler, zu wenig Personal), Nachbesserungsplan mit Frist, vereinbarte Folgen anwenden (z. B. Vertragsstrafe oder Malus, nur wenn vertraglich vereinbart); vor der Black Week Kapazität und Personal verbindlich abstimmen (1).

2.6 (2 Punkte)
- Auftragsverarbeitungsvertrag nach Art. 28 DSGVO (1), weil der Dienstleister im Auftrag und nach Weisung von Wobblerwerk Kundendaten (Namen, Adressen) verarbeitet; die Verantwortung für den Datenschutz bleibt bei Wobblerwerk (1).

2.7 (3 Punkte)
- Äußere Prüfung sofort in Anwesenheit des Frachtführers; Schaden schriftlich bestätigen lassen oder die Annahme verweigern (1).
- Inhaltliche Prüfung unverzüglich; Mängel unverzüglich dem Verkäufer (Großhändler) anzeigen, da beiderseitiger Handelskauf, sonst gilt die Ware als genehmigt (§ 377 HGB) (1).
- Im Vertrag regeln, dass der Dienstleister den Wareneingang unverzüglich prüft und Abweichungen sofort meldet, weil Wobblerwerk sonst seine Mängelrechte gegenüber dem Lieferanten verliert (1).

**Fall 3**

3.1 (4 Punkte)
- Lastenheft: erstellt der Auftraggeber, also Wobblerwerk (1); beschreibt, WAS der Köderberater leisten soll und WOFÜR, z. B. Filter nach Zielfisch, Gewässer und Jahreszeit, Empfehlung direkt in den Warenkorb, mobil nutzbar, Anbindung an Produktdaten und Bestand, Budget und Termin (1).
- Pflichtenheft: erstellt der Auftragnehmer, also die Agentur (1); beschreibt, WIE und WOMIT die Anforderungen umgesetzt werden (Technik, Schnittstellen, Aufwand, Zeitplan) (1).

3.2 (7 Punkte: je Agentur 2 für Rechenweg und Ergebnis, Entscheidung 1)
- Gewichte: 0,35 + 0,25 + 0,25 + 0,15 = 1,00.
- A: 0,35 × 6 + 0,25 × 9 + 0,25 × 8 + 0,15 × 7 = 2,10 + 2,25 + 2,00 + 1,05 = **7,40**
- B: 0,35 × 9 + 0,25 × 6 + 0,25 × 6 + 0,15 × 8 = 3,15 + 1,50 + 1,50 + 1,20 = **7,35**
- C: 0,35 × 7 + 0,25 × 8 + 0,25 × 9 + 0,15 × 5 = 2,45 + 2,00 + 2,25 + 0,75 = **7,45**
- Entscheidung: **Agentur C** mit dem höchsten gewichteten Nutzwert (7,45; Wertigkeit 7,45 ÷ 10 = 74,5 %).

3.3 (2 Punkte)
- Die Abstände sind sehr klein (0,05 bzw. 0,10 Punkte); schon eine leicht andere Gewichtung oder Punktvergabe ändert die Rangfolge. Gewichte und Punkte sind subjektiv. Ungewichtet läge sogar A vorn (30 gegenüber 29 und 29).
- Deshalb: Gewichtung im Team prüfen, Referenzen oder ein Probeprojekt einholen, K.-o.-Kriterien vorab klären (z. B. AV-Vertrag, Starttermin) und die Support-Schwäche von C (5 Punkte) im SLA absichern.

3.4 (3 Punkte)
- Scrum bzw. agil (1), weil unklar ist, welche Funktionen Kunden nutzen, und sich die Anforderungen durch Kundenfeedback ändern werden (1). In kurzen Sprints entsteht früh ein nutzbares Teilergebnis (Walking Skeleton: Zielfisch wählen → Empfehlung → Warenkorb), das getestet und angepasst wird; ein klassisches Vorgehen passt nur bei feststehenden Anforderungen (1).

3.5 (je Verantwortlichkeit mit Zuordnung 1 Punkt)
- **Product Owner:** E-Commerce-Manager bzw. -Managerin von Wobblerwerk; vertritt Kunden und Geschäftsinteressen, verantwortet und priorisiert den Product Backlog.
- **Scrum Master:** meist bei der Agentur; sorgt für die Einhaltung von Scrum, beseitigt Hindernisse, coacht das Team, ist kein Vorgesetzter.
- **Developers (Team):** Entwickler und Designer der Agentur; setzen die Backlog-Einträge im Sprint selbstorganisiert um.

3.6 (2 Punkte)
- Sprint Review: Was wurde erreicht? Das Ergebnis wird den Stakeholdern vorgeführt, Feedback fließt in den Backlog (1).
- Sprint Retrospektive: Wie haben wir gearbeitet? Das Team reflektiert den Arbeitsprozess und legt Verbesserungen für den nächsten Sprint fest (1).

3.7 (2 Punkte)
- Programmierung mit Abnahme: **Werkvertrag** (§ 631 BGB), ein Erfolg ist geschuldet (1).
- Betreuung nach Stundenaufwand: **Dienstvertrag** (§ 611 BGB), eine Tätigkeit ist geschuldet (1).

3.8 (2 Punkte)
- Beispiel: „Bis 31.03.2027 nutzen mindestens 15 % der mobilen Besucher der Kategorie Kunstköder den Köderberater, und ihre Conversion-Rate liegt mindestens 0,5 Prozentpunkte über der von Besuchern ohne Köderberater.“
- Bewertungshinweis: spezifisch, messbar und terminiert = 2 Punkte; fehlt der Termin oder die Messgröße, höchstens 1 Punkt.
