# Schnittstellenmanagement im B2B- und B2C-Bereich (Teil 2): technische Schnittstellen, APIs, ERP, B2B-Echtzeitdaten (LF09, LF09_Schnittstellenmanagement-im-B2B-und-B2C-2_E-Commerce_OSZHandel1)
**Prüfungszuordnung:** Geschäftsprozesse im E-Commerce > Online-Vertriebskanal auswählen und einsetzen > Schnittstellenmanagement im B2B und B2C Bereich (PDF-Kopf ohne Nummerierung; entspricht Teil 2-1 > 01 > 05 > 01 wie im Parallel-Dokument)
**Schwierigkeit:** 2 | **Rechenanteil:** nein | **Lernzeit:** ca. 40 Min

## Kerninhalt

### 0. Schlagwörter (Glossar aus dem Material)

| Abkürzung | Bedeutung |
|---|---|
| **CRM** | Customer Relationship Management-System (Kundenbeziehungsmanagement) |
| **API** | Application Programming Interface (Programmierschnittstelle) |
| **ERP** | Enterprise Resource Planning (Warenwirtschaft, Unternehmensressourcenplanung) |
| **USP** | Unique Selling Point/Proposition (Alleinstellungsmerkmal, "Verkaufsargument") |
| **Governance** | etwa "Einhalten einer allgemein bekannten Struktur", Regelungssystem |

### 1. Schnittstellen auf technischer Ebene
- **Schnittstelle:** Berührungspunkt innerhalb eines Softwaresystems, über den Informationen **übertragen und übersetzt** werden. Beispiel: Ton oder Video abspielen ist nur über eine Schnittstelle möglich, weil die Daten erst (z. B. von der Grafikkarte) in etwas Sichtbares übersetzt werden müssen.
- Schnittstellen sorgen dafür, dass jedes System mit jedem internen und externen System ohne Probleme kommunizieren kann → Schnittstelle als **"Dolmetscher"**.

**Schaubild USB-Stecker (nur im PDF-Bild):** Zwei Systeme mit unterschiedlichen Eigenschaften werden über eine Schnittstelle verbunden, deren Eigenschaften **physikalisch, elektrisch und mechanisch** festgelegt sind.

| System links | Schnittstelle (Verbindung) | System rechts |
|---|---|---|
| 5 V, 1-aktiv, Stecker | elektrisch, Signal, mechanisch | 3 V, 0-aktiv, Buchse |

Aussage: Auch wenn das keine Softwareschnittstelle ist, ist das Prinzip der Übertragung dasselbe. Innerhalb eines Softwaresystems heißt die Schnittstelle **API**.

### 2. API (Application Programming Interface)
- fungiert als **Software-Vermittler**, der die **Kommunikation zwischen zwei Anwendungen** ermöglicht
- Beispiele aus dem Alltag: TikTok nutzen, Sofortnachricht senden, Wettervorhersage auf dem Smartphone abrufen → jedes Mal wird eine API benutzt

### 3. Merkmale moderner APIs
- richten sich nach **Standards** (in der Regel **HTTP und REST**), entwicklerfreundlich, einfach zugänglich, allgemein bekannt
- werden eher wie **Produkte statt wie Code** behandelt: für bestimmte Zielgruppen konzipiert (z. B. Entwickler mobiler Apps); Versionen werden so verwaltet, dass Nutzererwartungen an Wartung und Lebenszyklus erfüllt werden
- wegen hochgradiger Standardisierung **höhere Maßstäbe an Sicherheit und Governance**; werden überwacht und verwaltet, um Leistung und Skalierung zu gewährleisten
- eigener **Software Development Lifecycle (SDLC)**: Entwerfen, Testen, Erstellen, Verwalten, Versionieren; Nutzung und Versionierung sind gut dokumentiert

### 4. Schnittstellen in B2B und B2C (gemeinsam)
Grundsätzlich **kein großer Unterschied**: In beiden Bereichen kommen Shopsysteme und damit ähnliche Schnittstellen zum Einsatz.

| Schnittstelle | Bedeutung laut Material |
|---|---|
| **ERP ↔ Webshop** | essenziell: im Shop angelegte Aufträge und Artikel werden ins ERP übertragen und dort weiterverarbeitet; je besser implementiert, desto schneller kann der Kunde bestellen, Artikel aufrufen, Merkliste einsehen; "der Webshop ist nur die Hülle, alle Daten kommen aus dem ERP" |
| **Lagerlogistik ↔ ERP** | ERP und Shop müssen Daten an den Logistikdienstleister senden, um die Lieferung zu garantieren; **Stammdaten und Metadaten (z. B. Artikelmaße)** sind relevant für den Dienstleister (B2C) bzw. die eigene Logistik (B2B) |
| **CRM ↔ Shop** | Kundenanfragen besser bearbeiten; Kundendaten austauschen und **personalisierte Inhalte** bereitstellen |

### 5. Wichtige Schnittstellen im B2C-Bereich
- **Marketing- und Newsletter-Systeme:** gezielte Kundenansprache → Umsatzsteigerung
- **(Payment) Service Provider:** Anbindung eines oder mehrerer Zahlungsanbieter, essenziell; PSP bieten Plugins für gängige Shopsysteme wie **Magento oder Shopware**
- **Marktplätze und Preissuchmaschinen:** größte Säulen des Onlinehandels, beachtliches Umsatzpotenzial; Schnittstellen unabdingbar für die Synchronisation von Produktdaten und Bestellungen
- **Soziale Netzwerke:** Facebook-Timeline, Instagram-Feed, YouTube-Video in Echtzeit im Shop ausspielen, ohne doppelte Content-Arbeit
- **Multi- vs. Cross-Channel:** Multi-Channel-Vertrieb = eigene und fremde Kanäle (Mischung direkt/indirekt). Multi-Channel-Marketing: Kanäle **unabhängig** bedient. Cross-Channel-Marketing: Botschaften über alle Kanäle **aufeinander abgestimmt** → konsistenteres Kundenerlebnis.
  - Schaubild Cross-Channel: Kampagne 1 → E-Mail-Marketing → Online-Shop; Kampagne 2 → SEA → Website ↔ Display-Marketing → Online-Shop; Kampagne 3 → TV → Social Media → Website (Kanäle verkettet)
  - Schaubild Multi-Channel: Kampagnen 1–3 strahlen jeweils parallel auf TV, Print-Anzeigen, Website, E-Mail-Marketing, Social Media aus (Kanäle unverbunden)

### 6. Logistische Anforderungen (überwiegend B2C)
Anbindung des Onlineshops an Logistikdienstleister (z. B. DHL): optimierte Prozesse, höhere Kundenzufriedenheit, **Sendungsverfolgungsnummer**, weitere USPs bei Lieferoptionen (Packstation, Wunschtermin, Ablageort).
Schaubild "Erfolgsfaktoren in der Logistik des Onlinehändlers": **Kosten senken** durch Insourcing vs. Outsourcing, Bestandsmanagement, Retourenmanagement; **Umsatz steigern** durch Kundenzufriedenheit, Unterstützung des Multichannel-Vertriebs, Nachhaltigkeit.

### 7. Schnittstellen im B2B-Bereich am Beispiel eines Großhändlers

| Merkmal | B2B (Großhändler) | B2C |
|---|---|---|
| Kundenkreis | nicht die "breite Masse"; Kunden müssen Bedingungen erfüllen, um **einkaufsberechtigt** zu sein | breite Masse, jeder kann kaufen |
| Preise | **individuelle Preise/Angebote**, meist mit **Mengenrabatten** | einheitlich |
| Datenaktualität | Schnittstellen zum ERP (Beispiel **SAP**) liefern Daten **live/in Echtzeit**: **Preise, Bonität, Artikelverfügbarkeit** werden über APIs ("http ports") übertragen und übersetzt | viele Daten einheitlich und **tagesaktuell** (einmal täglich geändert); wichtig v. a. die **Verfügbarkeitsanzeige** (z. B. für **Click and Collect**) |

**Aufwand des Schnittstellenmanagements:**
- **ohne eigenes Lager:** sehr aufwendig, weil zu **jedem Dienstleister** eine funktionierende, aktuelle Schnittstelle nötig ist
- **mit eigenem Lager:** nur **eine** Schnittstelle (beim Großhändler z. B. über eine SAP-Lösung)

**Fazit:** Das Management der verschiedenen Schnittstellen ist essenziell für einen reibungslosen Ablauf und einen funktionierenden Webshop.

## Formeln & Rechenwege
Keine Rechenanteile.

## Aufgaben aus dem Material

**Aufgabe 1:** Nennen Sie die Vorteile des B2C-Vertriebs über Online-Marktplätze.
**Lösung:** Hoher Bekanntheitsgrad, hohe Reichweite; Kunden haben hohes Vertrauen in bekannte Marktplätze; Auslagerung von Tätigkeiten wie Lagerung, Versand oder Payment kann vorteilhaft sein.

**Aufgabe 2:** Welche Gefahren drohen einem Unternehmen, das auf allen Marktplätzen gleichermaßen Präsenz zeigt?
**Lösung:** Verzettelung durch das **Gießkannenprinzip**; effektiver ist es meist, Schwerpunkte zu setzen. (Ergänzend: viele Schnittstellen müssen gepflegt werden, hoher Aufwand und Gebühren, Fehlerrisiko bei Beständen.)

**Aufgabe 3:** Welche 3 sind die Hauptziele der Distributionslogistik? a. Verfügbarkeit, b. Kostenminimierung, c. Flexibilität, d. vertikale Vernetzung, e. Einflussnahme
**Lösung:** **A, B und E** (Verfügbarkeit, Kostenminimierung, Einflussnahme).
⚠️ Hinweis: Das Infoblatt dieses Dokuments behandelt die Distributionslogistik-Ziele gar nicht (auch das Parallel-Dokument nennt sie nur im Lösungsblatt). 🔎 Ergänzung (nicht im Original, sinngemäß nach der zitierten Quelle mm-logistik.vogel.de): Verfügbarkeit = ausreichende Produktmenge zeitnah; Kostenminimierung = Transport-, Bestands-, Fehlmengen-, Auftragsabwicklungskosten senken; Einflussnahme = Mitbestimmung bei Vermarktung/Präsentation.

**Aufgabe 4:** Was ist eine Schnittstelle? (zu allgemein, daher: Was ist eine API?) Der Zusatz "Nenne außerdem die 3 Hauptgruppen" ist im PDF **durchgestrichen** (nur im Bild sichtbar).
**Lösung (Original):** Durch Arbeitsteilung entstandene Transferpunkte zwischen Funktionsbereichen, Sparten, Projekten, Personen, Unternehmen usw. Eine Programmierschnittstelle (API) ist das Stück Software einer Lösung, das anderen Programmen (meist bereits eingesetzten Business-Applikationen) zur Anbindung zur Verfügung gestellt wird.
⚠️ Hinweis: Passender zur umformulierten Frage ist die Definition aus diesem Infoblatt: Eine API ist ein **Software-Vermittler, der die Kommunikation zwischen zwei Anwendungen ermöglicht**, sodass Daten ohne manuelle Verarbeitung ausgetauscht werden; moderne APIs basieren meist auf HTTP/REST. Falls doch nach den 3 Hauptgruppen gefragt wird: B2B (betriebsextern), B2C (betriebsextern), betriebsintern.

**Aufgabe 5:** Was ist der Unterschied zwischen Multi-Channel-Marketing und Cross-Channel-Marketing?
**Lösung:** Im Multi-Channel-Marketing werden die Kanäle unabhängig voneinander bedient. Beim Cross-Channel-Marketing werden die Botschaften über alle Kanäle hinweg aufeinander abgestimmt, sodass Kunden ein konsistenteres Erlebnis bekommen.

## Ergänzungen & Aktualisierungen
- ⚠️ Hinweis zur Aussage "Der Webshop ist nur die Hülle, alle Daten kommen aus dem ERP": Das gilt nicht für jede Systemlandschaft. Oft gibt es pro Datenart ein **führendes System** ("Single Source of Truth"): z. B. Bestände im ERP/WaWi, Produkttexte und Attribute im PIM oder im Shop. Praxisbeispiel Onlineshop: Produktdaten liegen im Shopsystem (inkl. Varianten-Attributen), Bestände/Einkauf/Fulfillment in der WaWi.
- 🔎 Ergänzung (nicht im Original): Auch im B2C ist heute **Echtzeit-Bestandsabgleich** wichtig, sobald über mehrere Kanäle (Shop + Marktplätze) verkauft wird, sonst drohen **Überverkäufe**. Preise ändern sich im B2C durch Dynamic Pricing teils mehrmals täglich.
- 🔎 Ergänzung (nicht im Original): Klassischer B2B-Datenaustausch erfolgt häufig per **EDI** (Electronic Data Interchange, z. B. Standard EDIFACT) für Bestellungen, Lieferavis und Rechnungen. Seit **1.1.2025** müssen alle inländischen Unternehmen im B2B **E-Rechnungen empfangen** können (strukturierte Formate wie XRechnung oder ZUGFeRD); die Pflicht zur Ausstellung folgt stufenweise ab 1.1.2027 (Vorjahresumsatz über 800.000 €) bzw. 1.1.2028 (alle; Ausnahmen u. a. Kleinbetragsrechnungen bis 250 € und Kleinunternehmer nach § 19 UStG). Gilt nur für inländische B2B-Umsätze, nicht für Rechnungen an Verbraucher.
- 🔎 Ergänzung (nicht im Original): Gängige Datenformate an Schnittstellen sind **CSV, XML und JSON** (REST-APIs nutzen meist JSON).

## Prüfungsfallen
- **Schnittstelle (allgemein) vs. API (Software):** API ist eine spezielle, softwaretechnische Schnittstelle zwischen Anwendungen.
- **B2B-Besonderheiten:** individuelle Preise, Mengenrabatte, Bonitätsprüfung, Einkaufsberechtigung → Echtzeitdaten aus dem ERP. Im B2C laut Material reicht meist tagesaktuell, außer bei der Verfügbarkeitsanzeige.
- **Ohne eigenes Lager = viele Schnittstellen** (zu jedem Dienstleister); mit eigenem Lager = eine.
- **Stamm- und Metadaten (Maße, Gewicht)** braucht der Logistikdienstleister, z. B. für Paketgröße und Versandkosten.
- **Click and Collect** (online bestellen, im Laden abholen) braucht zuverlässige Verfügbarkeitsanzeige.
- **ERP ≠ CRM ≠ PIM:** ERP = Ressourcen/Warenwirtschaft, CRM = Kundenbeziehungen, PIM = Produktinformationen.

## Lernkarten
**F:** Was ist eine Schnittstelle auf technischer Ebene?
**A:** Ein Berührungspunkt im Softwaresystem, über den Informationen übertragen und übersetzt werden; sie wirkt wie ein Dolmetscher zwischen Systemen.

**F:** Wofür steht API und was leistet sie?
**A:** Application Programming Interface; ein Software-Vermittler, der die Kommunikation zwischen zwei Anwendungen ermöglicht.

**F:** Nennen Sie vier Merkmale moderner APIs.
**A:** Basieren auf Standards (HTTP/REST), werden wie Produkte behandelt und versioniert, hohe Sicherheits- und Governance-Anforderungen mit Überwachung, eigener Lebenszyklus (SDLC) mit guter Dokumentation.

**F:** Warum ist die Schnittstelle zwischen ERP und Webshop essenziell?
**A:** Im Shop angelegte Aufträge und Artikel werden ins ERP übertragen und dort weiterverarbeitet (Lager, Rechnung, Versand); je besser sie funktioniert, desto schneller läuft der Kaufprozess.

**F:** Welche Daten braucht ein Logistikdienstleister aus dem ERP?
**A:** Auftrags- und Lieferdaten sowie Stamm- und Metadaten der Artikel wie Maße und Gewicht.

**F:** Nennen Sie drei Besonderheiten von B2B-Shops gegenüber B2C-Shops.
**A:** Kunden müssen einkaufsberechtigt sein, individuelle Preise mit Mengenrabatten, Echtzeitabfrage von Preisen, Bonität und Verfügbarkeit aus dem ERP.

**F:** Welche Daten werden beim Großhändler per API in Echtzeit aus SAP abgerufen?
**A:** Preise, Bonität und Artikelverfügbarkeit.

**F:** Warum ist im B2C laut Material vor allem die Verfügbarkeitsanzeige wichtig?
**A:** Weil viele Händler darauf ihre Click-and-Collect-Lösungen aufbauen; andere Daten sind einheitlich und meist nur tagesaktuell.

**F:** Wann ist Schnittstellenmanagement besonders aufwendig?
**A:** Wenn kein eigenes Lager vorhanden ist, weil zu jedem Dienstleister eine funktionierende, aktuelle Schnittstelle eingerichtet werden muss.

**F:** Ihr Angelshop verkauft im Shop und auf Amazon. Warum brauchen Sie einen Echtzeit-Bestandsabgleich?
**A:** Damit ein Artikel, der auf einem Kanal verkauft wurde, sofort auf dem anderen Kanal nicht mehr verfügbar angezeigt wird; sonst Überverkäufe, Stornos und schlechte Bewertungen.

**F:** Erklären Sie das USB-Beispiel für Schnittstellen.
**A:** Zwei Systeme mit unterschiedlichen Eigenschaften (5 V/1-aktiv/Stecker vs. 3 V/0-aktiv/Buchse) werden über eine Schnittstelle mit festgelegten physikalischen, elektrischen und mechanischen Eigenschaften verbunden, die Signale überträgt und anpasst.

**F:** Was bedeutet Governance im Zusammenhang mit APIs?
**A:** Das verwendete Regelungssystem, also das Einhalten einer festgelegten Struktur bei Sicherheit, Zugriff und Verwaltung der Schnittstelle.

## Bezüge
- LF09_Schnittstellenmanagement-im-B2B-und-B2C_E-Commerce_OSZHandel1: Schnittstellen-Hauptgruppen, Systeme, Logistik
- LF09_Daten-Import-Daten-Export_E-Commerce_OSZHandel1: Datenaustausch, Formate CSV/XML
- LF09_Logistische-Anforderungen_E-Commerce_OSZHandel1: Warenwirtschaftssystem, Datenfluss
- LF09_Kompatibilität-von-neuen-Vertriebswegen_E-Commerce_OSZHandel1: Schnittstelle zur WaWi als Muss-Kriterium
- LF09_Cross-Channel-Situationen_E-Commerce_OSZHandel1: Click and Collect, Kanalverknüpfung
- LF09_Outsourcing_E-Commerce_OSZHandel1: externe Logistikdienstleister anbinden
- LF02_DynamicPricing_E-Commerce_OSZHandel1: Preisänderungen in Echtzeit
- LF09_Testumgebung_E-Commerce_OSZHandel1: Schnittstellen vor Livegang testen
