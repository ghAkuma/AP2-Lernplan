# Datenaufbereitung (LF09, LF09_Datenaufbereitung_E-Commerce_OSZHandel1)
**Prüfungszuordnung:** Teil 2-4 [sic, im Kopf so angegeben; inhaltlich wie die Schwesterdatei Teil 2-1] Geschäftsprozesse im E-Commerce > 04 Kaufmännische Steuerung und Kontrolle nutzen > 03 Statistiken erstellen und auswerten > 02 Datenaufbereitung (sichtbarer Seitenkopf: Lernfeld 9 – Online-Vertriebskanäle auswählen, Stand 16.03.2022)
**Schwierigkeit:** 1 | **Rechenanteil:** nein | **Lernzeit:** ca. 30 Min

## Kerninhalt

**Ausgangsproblem**
- Jedes System nutzt Daten: Warenwirtschaftssystem, Shopsystem, Analysetools (z. B. Google Analytics).
- Damit alle Systeme reibungslos zusammenarbeiten, ist das **Datenformat** die zentrale Schwierigkeit.
- Nur weil man alle Herstellerdaten in einer Excel-Tabelle bekommt, kann man diese nicht einfach ins Shopsystem hochladen.
- **Rohdaten** müssen mit großem Zeiteinsatz **formatiert und richtig strukturiert** werden, damit sie ihren Zweck erfüllen. Bild im Material: Rohdaten sind wie Legosteine, die man noch nicht zusammenstecken kann, weil sie noch Unebenheiten haben.

**Prozess der Datenaufbereitung (4 Schritte)**

| Schritt | Leitfragen |
|---|---|
| 1. Sammlung & Ermittlung der Daten | Welche Daten haben wir schon? Welche müssen wir noch sammeln, um sie in einen Zusammenhang zu bringen? |
| 2. Bereinigung & Prüfung der Daten | Welche Daten sind Ausreißer/irrelevant? Welche sind fehlerhaft? Welche fehlen noch? |
| 3. Formatierung & Anreicherung der Daten | Welche Formatierung sollen die Daten haben? Welche externen Datensätze müssen angefügt werden, um einen relevanten Zusammenhang zu erzeugen? |
| 4. Speicherung / Verwendung der Daten | Daten zur Auswertung des Anwendungsfalls verwenden bzw. für später abspeichern |

**Problem Datenformat: Beispiel Datum** (Tabelle aus dem Bild, dasselbe Datum in vier Formaten):

| A | B | C | D |
|---|---|---|---|
| 11.06.18 | Montag, 11. Juni 2018 | 11.06.2018 | 2018-06-11 |

- Lösung: ein **Makro** bzw. eine **API**, die das Datum in die passende (einheitliche) Formatierung bringt.
- **Datenvalidierung:** Damit die Daten nach der Formatierung in einem realistischen Rahmen bleiben, prüft ein Algorithmus Plausibilität, z. B. Alarm, wenn der formatierte Kaufpreis unter einem bestimmten Wert liegt. So wird verhindert, dass der Preis durch die Formatierung einen neuen (falschen) Wert bekommt, z. B. weil das Komma eine Stelle zu weit links steht (49,90 € wird zu 4,99 €).

**Data Warehouse (DWH)**
- Zentraler Speicher, in dem alle Daten z. B. eines ganzen Unternehmens gespeichert und gepflegt werden.
- Enthält **nur bereits aufbereitete Daten**.
- Ermöglicht eine **globale Sicht** auf die Daten, da diese aus vielen verschiedenen **heterogenen Quellen** eingespielt und zusammengetragen werden.

**Lösungen, Anbieter, Tools**
- Große Anbieter: **improvado, alteryx, Microsoft Power BI, tableau prep**.
- Viele arbeiten mit **KI-Lösungen**, die bei der Datenaufbereitung viel Zeit sparen.

**Gartner-Grafik (aus dem Aufgabenblatt, Bild): "Expensive, talented resources are misaligned."**
Frage der Studie: Welche Tätigkeiten führt der Data Scientist (bzw. die Advanced-Analytics-Ressource) Ihres Unternehmens für das Marketing-Analytics-Team aus? (Mehrfachnennungen möglich)

| Tätigkeit | Anteil der Befragten |
|---|---|
| Data Visualization (Datenvisualisierung) | 48 % |
| Preparing Data for Analysis (Daten für die Analyse aufbereiten) | 46 % |
| Chart, Dashboards and Stats | 37 % |
| Predictive Models (Prognosemodelle) | 37 % |
| Text Analysis | 34 % |
| Product Recommendations | 32 % |
| Image Recognition | 30 % |
| Regression Analysis | 30 % |
| Writing Queries (Abfragen schreiben) | 30 % |
| Content Personalization | 29 % |
| A/B and MVT (A/B- und multivariate Tests) | 27 % |
| Speech Analysis | 27 % |
| Recommender Systems | 22 % |

Kernaussage: Die zweithäufigste Tätigkeit teurer Fachkräfte ist Datenaufbereitung (46 %), wertschöpfende Analysen wie Prognosemodelle (37 %) oder Personalisierung (29 %) kommen seltener vor.

## Formeln & Rechenwege
Keine Rechenanteile.

## Aufgaben aus dem Material

**Aufgabe 1:** Was ist der wichtigste Aspekt bei der Datenaufbereitung? a) Datengröße b) Datenformat c) Datenfrequenz

**Lösung:** b) Datenformat.

**Aufgabe 2:** Sie wollen Ihre Produkte bei Idealo.de anbieten. Aus dem Hilfecenter erfahren Sie kaum, wie Ihr Datenfeed (ähnlicher Aufbau wie eine Excel-Tabelle) aufgebaut sein soll. Was müssen Sie den Support-Mitarbeiter fragen? (2 Antworten)

**Lösung:**
a) Welche Produktdaten brauchen Sie von uns und in welcher Reihenfolge sollen sie in der Excel angeordnet sein?
b) Welche Formatierungen sollen die jeweiligen Daten haben?

**Aufgabe 3:** Beschreiben Sie das Problem mit folgender Formatierung von Kundendaten, die Ihnen ein Kollege zum Einpflegen als Excel-Tabelle schickt (Tabelle aus dem Bild):

| | A: Kunde | B: Adresse | C: Produkt gekauft | D: Anzahl |
|---|---|---|---|---|
| 2 | Hannes Hensel | Gretelstraße 12 17450 Hammeln | Produkt A2 | 3 |
| 3 | Lina Lustig | Pusteweg 345 38628 Dinnheim | Produkt B3 | 4 |
| 4 | Peter Panne | Landstraße 1 11123 Dummdorf | Produkt B1 | 6 |
| 5 | Aaron Amen | Große Straße 55 76444 Krümeln | Produkt C4 | 8 |
| 6 | Malte Malz | Alter Platz 69 69696 Lusten | Produkt A1 | 2 |
| 7 | Kriss Kunde | Waldschulweg 123 45678 Hansdorf | Produkt C2 | 11 |

**Lösung laut Material:** Adressangaben und Namen der Kunden sind nicht einzeln aufgelistet (eine Info pro Zelle: Vorname: Hannes / Nachname: Hensel / Straße: Gretelstraße / Hausnummer: 12 / usw.).

Ergänzend ausformuliert: Richtige Struktur wäre je eine Spalte für Vorname, Nachname, Straße, Hausnummer, PLZ, Ort, Produkt, Anzahl. Sonst kann das System z. B. nicht nach PLZ/Ort filtern, keine personalisierte Anrede ("Hallo Hannes") erzeugen und Felder beim Import nicht zuordnen. Besonderheit: Mehrteilige Straßennamen ("Große Straße", "Alter Platz") machen das automatische Trennen schwierig.

**Aufgabe 4:** Lesen Sie die Studie von Gartner (Grafik oben) und erläutern Sie, warum es für ein Unternehmen so wichtig ist, seine Daten aufzubereiten.

**Lösung laut Material:** Data-Wissenschaftler in vielen Unternehmen verwenden viel Zeit auf Datenaufbereitung statt auf die Bildung relevanter Einblicke, die dem Unternehmen wirtschaftlich weiterhelfen.

Ergänzend ausformuliert: 46 % der Data Scientists bereiten Daten auf; damit sind teure, hochqualifizierte Fachkräfte mit Vorarbeit gebunden ("misaligned"). Sind die Daten von vornherein sauber, einheitlich und strukturiert (bzw. automatisiert aufbereitet), bleibt mehr Kapazität für wertschöpfende Analysen (Prognosen, Personalisierung, Produktempfehlungen), und Entscheidungen beruhen auf korrekten Daten.

## Ergänzungen & Aktualisierungen

🔎 Ergänzung (nicht im Original): Gängige **Kriterien der Datenqualität**: Vollständigkeit, Richtigkeit (Korrektheit), Einheitlichkeit/Konsistenz (gleiches Format überall), Aktualität, Eindeutigkeit (keine Dubletten).

🔎 Ergänzung (nicht im Original): Das Format **2018-06-11** (Spalte D) entspricht der internationalen Norm **ISO 8601** (JJJJ-MM-TT); es ist eindeutig und sortierbar und wird deshalb oft als Zielformat beim Datenaustausch gewählt.

🔎 Ergänzung (nicht im Original): In Excel lassen sich zusammengesetzte Zellen (Aufgabe 3) z. B. mit "Daten > Text in Spalten" oder der Blitzvorschau aufteilen. Die Datenbefüllung eines DWH wird in der Praxis oft als **ETL-Prozess** bezeichnet (Extract = aus Quellen holen, Transform = aufbereiten, Load = ins DWH laden).

🔎 Ergänzung (nicht im Original): Bei **Kundendaten** gilt die DSGVO: Personenbezogene Daten müssen u. a. sachlich richtig und erforderlichenfalls aktuell sein (Grundsatz der Richtigkeit, Art. 5 Abs. 1 lit. d DSGVO) und dürfen nur im erforderlichen Umfang verarbeitet werden (Datenminimierung, Art. 5 Abs. 1 lit. c DSGVO). Saubere Datenaufbereitung (Dubletten entfernen, Fehler korrigieren) unterstützt das.

## Prüfungsfallen
- **Wichtigster Aspekt = Datenformat**, nicht Datengröße oder Datenfrequenz.
- **Reihenfolge der 4 Prozessschritte** merken: Sammeln/Ermitteln -> Bereinigen/Prüfen -> Formatieren/Anreichern -> Speichern/Verwenden. Bereinigen kommt VOR Formatieren.
- **Datenvalidierung** ist nicht das Formatieren selbst, sondern die anschließende Plausibilitätsprüfung (z. B. Preis-Untergrenze, Komma-Fehler).
- **Anreicherung** bedeutet, externe Datensätze hinzuzufügen, nicht Daten zu löschen.
- **Data Warehouse enthält nur aufbereitete Daten** aus vielen heterogenen Quellen (globale Sicht), nicht die Rohdaten.
- Bei Fragen an einen Plattform-Support (Idealo) immer beide Punkte nennen: **welche Daten in welcher Reihenfolge** UND **welche Formatierung**.

## Lernkarten

**F:** Was versteht man unter Rohdaten und warum müssen sie aufbereitet werden?
**A:** Unbearbeitete Daten, z. B. vom Hersteller. Sie haben oft ein uneinheitliches oder unpassendes Format und müssen formatiert und strukturiert werden, damit Shop, WWS und Analysetools sie verarbeiten können.

**F:** Nennen Sie die vier Schritte der Datenaufbereitung in der richtigen Reihenfolge.
**A:** 1. Sammlung & Ermittlung, 2. Bereinigung & Prüfung, 3. Formatierung & Anreicherung, 4. Speicherung/Verwendung.

**F:** Welche Fragen stellt man im Schritt "Bereinigung & Prüfung"?
**A:** Welche Daten sind Ausreißer oder irrelevant? Welche sind fehlerhaft? Welche fehlen noch?

**F:** Was ist Datenvalidierung? Nennen Sie ein Beispiel.
**A:** Eine (automatische) Plausibilitätsprüfung nach der Formatierung, ob Daten in einem realistischen Rahmen liegen. Beispiel: Alarm, wenn ein Kaufpreis unter einem Mindestwert liegt, weil das Komma verrutscht ist (Wobbler für 4,99 € statt 49,90 €).

**F:** Mit welchem Hilfsmittel lässt sich laut Material ein uneinheitliches Datumsformat vereinheitlichen?
**A:** Mit einem Makro bzw. einer API, die alle Datumswerte in die passende Formatierung bringt.

**F:** Was ist ein Data Warehouse?
**A:** Ein zentraler Speicher, in dem alle (bereits aufbereiteten) Daten eines Unternehmens aus vielen heterogenen Quellen zusammengeführt und gepflegt werden; er ermöglicht eine globale Sicht auf die Daten.

**F:** Sie möchten Ihr Angelsortiment bei Idealo listen, die Feed-Vorgaben sind unklar. Welche zwei Fragen stellen Sie dem Support?
**A:** 1. Welche Produktdaten werden benötigt und in welcher Reihenfolge (Spalten) sollen sie angeordnet sein? 2. Welche Formatierung sollen die einzelnen Daten haben (z. B. Preisformat, Datumsformat)?

**F:** Ein Kollege schickt Kundendaten mit einer Spalte "Kunde" (Vor- und Nachname) und einer Spalte "Adresse" (Straße, Nr., PLZ, Ort). Was ist das Problem?
**A:** Die Informationen sind nicht einzeln (eine Info pro Zelle) erfasst. Sie lassen sich nicht sauber importieren, filtern oder für personalisierte Ansprache nutzen. Benötigt werden getrennte Spalten für Vorname, Nachname, Straße, Hausnummer, PLZ und Ort.

**F:** Was sagt die Gartner-Grafik über die Arbeit von Data Scientists aus?
**A:** 46 % von ihnen bereiten Daten für die Analyse auf (zweithäufigste Tätigkeit nach Visualisierung mit 48 %). Teure Fachkräfte werden mit Vorarbeit gebunden statt mit wertschöpfenden Analysen.

**F:** Warum ist Datenaufbereitung für ein Unternehmen wirtschaftlich wichtig?
**A:** Saubere, einheitliche Daten sparen Zeit und Personalkosten, verhindern Fehler (z. B. falsche Preise) und schaffen Kapazität für Analysen, aus denen sich Umsatz steigernde Entscheidungen ableiten lassen.

**F:** Nennen Sie zwei Anbieter von Tools zur Datenaufbereitung.
**A:** Z. B. Microsoft Power BI, tableau prep, alteryx, improvado.

## Bezüge
- LF09_Daten-Import-Daten-Export_E-Commerce_OSZHandel1: Excel/CSV, eine Info pro Spalte
- LF09_Schnittstellenmanagement-im-B2B-und-B2C_E-Commerce_OSZHandel1: Datenaustausch zwischen verschiedenen Systemen
- LF10_Qualitätssicherung-von-Prozessen_E-Commerce_OSZHandel1: Datenqualitätsmanagement von Produktdaten
- LF09_Datenschutz_E-Commerce_OSZHandel1: Kundendaten rechtskonform verarbeiten
- LF09_Erhebung-von-Kundendaten_E-Commerce_OSZHandel1: Kundendaten sammeln vor Aufbereitung
- LF09_Auswertung-von-Seitenbesuchen_E-Commerce_OSZHandel1: Analysetools nutzen aufbereitete Daten
