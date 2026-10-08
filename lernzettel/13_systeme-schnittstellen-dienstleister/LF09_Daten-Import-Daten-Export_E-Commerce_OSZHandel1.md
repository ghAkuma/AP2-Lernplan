# Daten-Import und Daten-Export (LF09, LF09_Daten-Import-Daten-Export_E-Commerce_OSZHandel1)
**Prüfungszuordnung:** Teil 2-1 Geschäftsprozesse im E-Commerce > 04 Kaufmännische Steuerung und Kontrolle nutzen > 03 Statistiken erstellen und auswerten > 01 Daten-Import/Daten-Export (sichtbarer Seitenkopf: Lernfeld 9 – Online-Vertriebskanäle auswählen, Stand 16.03.2022)
**Schwierigkeit:** 1 | **Rechenanteil:** nein | **Lernzeit:** ca. 25 Min

## Kerninhalt

**Warum Datenimport/-export?**
- Nutzerdaten werden gesammelt und analysiert, um dem Nutzer das zu zeigen, was er wahrscheinlich sehen möchte (Beispiel im Material: Netflix-Doku "The Social Dilemma" über Social Media).
- Analyse von Nutzerdaten ist im gesamten E-Commerce extrem wichtig für richtige geschäftliche Entscheidungen, Ziel: Umsatzsteigerung.
- Dafür sind Export und Import von Daten essenziell, sowohl **automatisch** als auch **manuell**.

**1. Datenimport**
- Hauptbereich: **Produktdaten bzw. Artikelstammdaten**, die ins **Shopsystem** und/oder **Warenwirtschaftssystem (WWS)** importiert werden.
- Ohne eingepflegte Produktdaten kann ein Unternehmen keine Produkte anbieten, deshalb müssen sie **fehlerfrei** importiert werden.
- Herkunft der Daten:
  - **intern**: das Unternehmen vertreibt nur eigene Produkte (Eigenmarke/Hersteller selbst),
  - **extern**: Daten kommen vom **Hersteller/Lieferanten**.
- Optimalfall: Daten kommen als **Excel-Tabelle** oder **CSV-Datei** und sind **einzeln** gespeichert (eine Information pro Zelle bzw. pro Komma-getrenntem Feld).

**2. Datenexport**
- Findet größtenteils statt bei der Arbeit mit **Suchmaschinen, Preisvergleichsdiensten und Affiliate-Netzwerken**, also Plattformen wie Amazon, Google Shopping oder Idealo.
- Diese Plattformen brauchen, genau wie das eigene Shopsystem, die **Produktdatensätze**, um überhaupt verkaufen zu können.
- Wege des Exports:
  - einzelne **CSV-Dateien oder Excel-Tabellen hochladen** (manuell),
  - **Produktdatenfeed** (automatisiert): schickt in bestimmten Abständen die ausgewählten Daten aus einer Datenquelle an die Plattform.
- Werbetreibende auf Facebook oder Google können über den jeweiligen **Anzeigenmanager** Ergebnisse u. a. als Excel-Tabelle herunterladen (Export von Kampagnendaten).

**3. API (Application Programming Interface)**
- Schnittstelle, die es **zwei Programmen ermöglicht, miteinander zu kommunizieren**.
- In der API wird definiert, wie auf der einen Seite die Daten **gelesen** und auf der anderen Seite **ausgegeben** werden.

**4. Automatisierung**
- Trend im E-Commerce: Statt eines Mitarbeiters, der Daten aus einer Hersteller-E-Mail in ein Excel-Sheet überträgt, gibt es **Produktdatenfeeds und APIs**, die nach einmaligem Aufsetzen alles automatisch erledigen.
- Größte Schwierigkeit: das **Aufsetzen** dieser Tools. Stellt der Hersteller seine Daten in einem anderen Format bereit, müssen APIs bzw. Feeds **angepasst** werden.

**Übersicht: Datenwege**

| Richtung | Was | Von/Nach | Formate/Wege |
|---|---|---|---|
| Import | Produkt-/Artikelstammdaten | Hersteller/intern -> Shop/WWS | Excel, CSV, Produktdatenfeed, API |
| Export | Produktdatensätze | Shop/WWS -> Google Shopping, Idealo, Amazon, Affiliate-Netzwerke | CSV/Excel-Upload, Produktdatenfeed, API |
| Export | Kampagnenergebnisse | Facebook/Google Anzeigenmanager -> eigene Auswertung | Excel-Download |

## Formeln & Rechenwege
Keine Rechenanteile.

## Aufgaben aus dem Material

**Aufgabe 1:** Der Hersteller fragt Sie, in welchem Format Sie die Produktdaten erhalten wollen. Welche wählen Sie? (mehrere möglich)
a) Als Excel-Datei b) In einer E-Mail c) Als CSV-Datei d) Als PDF-Datei e) Über einen Produktdatenfeed

**Lösung:** a) Excel-Datei, c) CSV-Datei, e) Produktdatenfeed.
Begründung: Diese Formate sind strukturiert (eine Information pro Zelle/Feld) und maschinell importierbar. E-Mail und PDF sind unstrukturiert und müssten manuell abgetippt werden (Fehlerquelle, Zeitaufwand).

**Aufgabe 2:** Was ist beim Datenimport/-export über eine Excel-Tabelle bzgl. des Formates essenziell wichtig? (nur eine richtig)
a) Alle relevanten Informationen/Daten sind vorhanden b) Jede Information hat eine eigene Spalte c) Informationen, die zusammengehören, sind immer in einer Spalte (z. B. Adresse)

**Lösung:** b) Jede Information hat eine eigene Spalte. (Auf dem Lösungsblatt sind die Optionen versehentlich als f/g/h statt a/b/c beschriftet; richtig ist die mittlere Option.)
Begründung: a) ist zwar wünschenswert, betrifft aber den Inhalt, nicht das Format; c) ist genau falsch, zusammengesetzte Felder (Straße + Hausnummer + PLZ + Ort) lassen sich nicht sauber importieren.

**Aufgabe 3:** Nennen Sie 3 Plattformen, an die ein E-Commerce-Unternehmen für die Zusammenarbeit Produktdaten exportieren muss.

**Lösung:**
- Suchmaschinen: z. B. Google Shopping
- Preisvergleichsdienste: z. B. Idealo
- Affiliate-Netzwerke: z. B. AWIN
(Laut Informationsblatt zusätzlich: Marktplätze wie Amazon.)

**Aufgabe 4:** Welche Vor- und Nachteile hat die Automatisierung im Bereich Datenimport/-export für ein Unternehmen und dessen Mitarbeiter?

**Lösung laut Material:**
- Mitarbeiter, die nur Daten einpflegen können, verlieren ihren Job.
- (Oder) Mitarbeiter müssen ab jetzt APIs und Produktdatenfeeds pflegen statt einzelne Datensätze einzupflegen.
- Mehr Automatisierung = weniger Mitarbeiter = weniger Kosten für das Unternehmen.

⚠️ Hinweis: Die Musterlösung ist unvollständig und trennt Vor- und Nachteile nicht. Prüfungsgerechte Antwort (abgeleitet aus dem Informationsblatt):

| | Vorteile | Nachteile |
|---|---|---|
| Unternehmen | Zeit- und Personalkostenersparnis; weniger Übertragungsfehler; Daten regelmäßig und aktuell an Plattformen (Feed in festen Abständen); skalierbar bei vielen Artikeln | Aufwand und Kosten für das einmalige Aufsetzen; Anpassungsbedarf, sobald Hersteller/Plattform das Format ändert; Abhängigkeit von Technik/Know-how; fehlerhafte Regeln wirken sich auf alle Datensätze aus |
| Mitarbeiter | Monotone Abtipparbeit entfällt; anspruchsvollere Aufgaben (Pflege/Kontrolle von Feeds und APIs) | Arbeitsplätze für reine Dateneingabe fallen weg; Weiterbildungsbedarf (technische Kenntnisse) |

## Ergänzungen & Aktualisierungen

🔎 Ergänzung (nicht im Original): **CSV** = "Comma-Separated Values", eine Textdatei, in der Felder durch ein Trennzeichen getrennt sind. In deutschen Excel-Versionen wird meist das **Semikolon** als Trennzeichen verwendet, weil das Komma Dezimaltrennzeichen ist. Typische Importprobleme: falsches Trennzeichen, falsche Zeichenkodierung (Umlaute, deshalb UTF-8), Dezimalkomma vs. Dezimalpunkt bei Preisen.

🔎 Ergänzung (nicht im Original): Seit 13.12.2024 gilt die **EU-Produktsicherheitsverordnung (GPSR, VO (EU) 2023/988)**. Bei Online-Angeboten müssen u. a. Name/Handelsname/Marke sowie Postanschrift und elektronische Adresse (z. B. E-Mail oder Kontaktformular-URL) des Herstellers (bei Herstellern außerhalb der EU zusätzlich die verantwortliche Person in der EU), Angaben zur Identifizierung des Produkts sowie Warn- und Sicherheitshinweise angezeigt werden (Art. 19 GPSR). Diese Angaben müssen deshalb Teil der importierten Produktdaten sein und in Feeds mitgeführt werden.

🔎 Ergänzung (nicht im Original): Praxisbeispiel Angelshop: Produktdaten (z. B. Kunstköder mit Varianten Farbe/Gewicht) liegen im Shopsystem; ein Feed-Tool exportiert sie automatisiert an Google Shopping und Preisvergleichsportale. Bestände kommen aus der Warenwirtschaft über eine Schnittstelle. Massen-Importe/-Exporte im Shop laufen über CSV/Excel-Vorlagen.

## Prüfungsfallen
- **Import vs. Export verwechseln:** Import = Daten kommen INS eigene System (Herstellerdaten -> Shop/WWS). Export = Daten gehen AUS dem eigenen System an Dritte (Shop -> Google Shopping/Idealo).
- **"Alle Informationen vorhanden" ist nicht das Format-Kriterium.** Formatkriterium = eine Information pro Spalte/Zelle.
- **E-Mail und PDF sind keine guten Datenformate** für den Import (unstrukturiert, nicht maschinenlesbar).
- **API vs. Produktdatenfeed:** Ein Feed ist eine Datei/Datenquelle, die in festen Abständen an eine Plattform übermittelt wird. Eine API ist eine Programmierschnittstelle, über die zwei Programme direkt miteinander kommunizieren (Daten lesen und ausgeben).
- **Bei Vor-/Nachteil-Fragen** immer beide Seiten UND beide Perspektiven (Unternehmen, Mitarbeiter) abdecken.

## Lernkarten

**F:** Welche Daten müssen im E-Commerce vor allem in Shop- und Warenwirtschaftssystem importiert werden?
**A:** Produktdaten bzw. Artikelstammdaten. Ohne sie kann das Unternehmen keine Produkte anbieten, deshalb müssen sie fehlerfrei importiert werden.

**F:** Woher können Produktdaten stammen?
**A:** Intern (das Unternehmen vertreibt eigene Produkte) oder extern vom Hersteller/Lieferanten.

**F:** In welcher Form sollten Produktdaten idealerweise geliefert werden?
**A:** Als Excel-Tabelle oder CSV-Datei, wobei jede Information einzeln gespeichert ist (eine Information pro Zelle bzw. Feld), oder automatisiert über einen Produktdatenfeed.

**F:** Ein Lieferant von Angelruten schickt die neuen Artikeldaten als PDF-Katalog. Warum ist das problematisch und was schlagen Sie vor?
**A:** PDF ist nicht strukturiert und nicht maschinell importierbar; die Daten müssten manuell abgetippt werden (Zeitaufwand, Fehlerrisiko). Vorschlag: Daten als Excel/CSV mit einer Information pro Spalte oder als Produktdatenfeed anfordern.

**F:** Nennen Sie drei Plattformtypen mit Beispiel, an die Produktdaten exportiert werden.
**A:** Suchmaschinen (Google Shopping), Preisvergleichsdienste (Idealo), Affiliate-Netzwerke (AWIN); außerdem Marktplätze (Amazon).

**F:** Was ist ein Produktdatenfeed?
**A:** Eine automatisierte Datenübermittlung, die in bestimmten Abständen die ausgewählten Produktdaten aus einer Datenquelle an eine Plattform (z. B. Google Shopping) schickt.

**F:** Was ist eine API?
**A:** Application Programming Interface: eine Schnittstelle, über die zwei Programme miteinander kommunizieren. In ihr wird festgelegt, wie Daten auf der einen Seite gelesen und auf der anderen Seite ausgegeben werden.

**F:** Was ist die größte Schwierigkeit bei der Automatisierung über Feeds und APIs?
**A:** Das (einmalige) Aufsetzen. Ändert der Hersteller oder die Plattform das Datenformat, müssen Feed bzw. API angepasst werden.

**F:** Nennen Sie je zwei Vor- und Nachteile der Automatisierung des Datenimports für das Unternehmen.
**A:** Vorteile: Personalkosten- und Zeitersparnis, weniger Übertragungsfehler, aktuelle Daten. Nachteile: Aufwand/Kosten für Einrichtung, Anpassungsbedarf bei Formatänderungen, technische Abhängigkeit.

**F:** Welche Auswirkungen hat die Automatisierung für die Mitarbeiter?
**A:** Reine Dateneingabe-Stellen können wegfallen; die übrigen Mitarbeiter pflegen und kontrollieren künftig APIs und Feeds statt einzelner Datensätze und brauchen dafür Weiterbildung.

**F:** Wie kommen Sie als Werbetreibender an die Ergebnisse Ihrer Facebook- oder Google-Kampagnen für eine eigene Auswertung?
**A:** Über den jeweiligen Anzeigenmanager, aus dem die Ergebnisse u. a. als Excel-Tabelle exportiert werden können.

**F:** Warum ist eine Excel-Spalte "Adresse" mit Straße, Hausnummer, PLZ und Ort ungeeignet für den Import?
**A:** Weil zusammengehörige, aber unterschiedliche Informationen in einer Zelle stehen; das Zielsystem erwartet jede Information in einer eigenen Spalte (Straße, Hausnummer, PLZ, Ort), sonst ist kein fehlerfreier Import möglich.

## Bezüge
- LF09_Datenaufbereitung_E-Commerce_OSZHandel1: Rohdaten formatieren, eine Info pro Zelle
- LF09_Schnittstellenmanagement-im-B2B-und-B2C_E-Commerce_OSZHandel1: Schnittstellen und Datenaustausch zwischen Systemen
- LF09_Schnittstellenmanagement-im-B2B-und-B2C-2_E-Commerce_OSZHandel1: APIs, Systemanbindung, Automatisierung
- LF09_Online-Vertriebskanäle_E-Commerce_OSZHandel1: Marktplätze und Preisvergleich als Exportziele
- LF09_Abrechnungsmodelle_E-Commerce_OSZHandel1: Affiliate-Netzwerke und Preisvergleichsportale
- LF10_Qualitätssicherung-von-Prozessen_E-Commerce_OSZHandel1: Produktdatenqualität und Datenbezug
