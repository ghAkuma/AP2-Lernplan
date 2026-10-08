# Schnittstellenmanagement bei B2B und B2C, Systemanbindungen und Logistikschnittstellen (LF09, LF09_Schnittstellenmanagement-im-B2B-und-B2C_E-Commerce_OSZHandel1)
**Prüfungszuordnung:** Teil 2-1 Geschäftsprozesse im E-Commerce > 01 Online-Vertriebskanal auswählen und einsetzen > 05 Technische und organisatorische Voraussetzungen und Rahmenbedingungen für den Einsatz neuer Online-Vertriebskanäle im Zusammenhang mit unterschiedlichen Geschäftsmodellen einschätzen und Maßnahmen ableiten > 01 Schnittstellenmanagement bei B2B, B2C / 02 Kompatibilität von neuen Vertriebswegen / 03 Logistische Anforderungen
**Schwierigkeit:** 2 | **Rechenanteil:** nein | **Lernzeit:** ca. 45 Min

## Kerninhalt

### 1. Schnittstellenmanagement bei B2B, B2C

**Schnittstelle:** durch **Arbeitsteilung** entstandene **Transferpunkte** zwischen Funktionsbereichen, Sparten, Projekten, Personen, Unternehmen usw.

**Programmierschnittstelle (API, Application Programming Interface):** das Stück Software einer Lösung, das anderen Programmen (meist bereits eingesetzten Business-Applikationen) zur Anbindung zur Verfügung gestellt wird. Damit können **Daten zwischen unterschiedlichen Systemen ausgetauscht werden, ohne dass eine manuelle Verarbeitung notwendig ist**.

**Drei grundsätzliche Schnittstellen (Hauptgruppen):**

| Gruppe | Art | Beispiele |
|---|---|---|
| **B2B** | betriebsextern | Wertschöpfungspartnerschaften im Netzwerk, strategische Allianzen, gemeinsame Tochterunternehmen, Zulieferer |
| **B2C** | betriebsextern | Markt- bzw. Kundenorientierung, Kundenintegration |
| **Betriebsintern** | intern | zwischen Mitarbeitern, Abteilungen usw. |

**Ziele des Schnittstellenmanagements:**
- Zielabstimmung
- Vermeidung von **Insellösungen**
- Konfliktmanagement
- "Übersetzeraufgaben" leisten (zwischen Abteilungen/Systemen vermitteln)
- Mitarbeiter motivieren und schulen

### 2. Kompatibilität von neuen Vertriebswegen

**Direkter Vertriebskanal:** direkter Kontakt zwischen Unternehmen und Kunde.

| Vorteile | Nachteile |
|---|---|
| Absatzgeschehen lässt sich besser kontrollieren | höhere Personalkosten |
| persönliche Kommunikation zwischen Verkäufer und Kunde | Massendistribution nur bedingt möglich |
| keine Abhängigkeit von Zwischenhändlern | höherer absatzorganisatorischer Aufwand |

**Indirekter Vertriebskanal:** laut Material Kanäle, die "zunächst nur informativen Charakter haben und die Kunden auf den Shop weiterleiten".

| Vorteile | Nachteile |
|---|---|
| großflächiger Vertrieb | Vertriebspartner vertreiben mehrere Produkte und entscheiden selbst über die Prioritäten |
| Unternehmen wird entlastet, da administrative und logistische Aufgaben an den Absatzmittler abgegeben werden | wenig Einfluss auf Werbemaßnahmen und Verkaufspreise |
| kostengünstiger | schwierige Kundenkommunikation |

⚠️ Hinweis: Die Definition "nur informativer Charakter, Weiterleitung zum Shop" beschreibt eher **Referral-Kanäle** (Preissuchmaschinen, Affiliates). Die klassische Definition des indirekten Vertriebs lautet: Zwischen Hersteller und Endkunde sind **Absatzmittler (Händler)** geschaltet. Die Vor-/Nachteile in der Tabelle passen zu dieser klassischen Definition.

### 3. Systeme, die an den Onlineshop angebunden werden (Schnittstellen)

| System | Zweck der Schnittstelle (laut Material) |
|---|---|
| **Marketing- und Newsletter-Systeme** | Kunden gezielt ansprechen und so den Umsatz erhöhen |
| **(Payment) Service Provider** | Anbindung an einen oder mehrere Zahlungsanbieter erleichtert die Abwicklung von Kundenzahlungen, **essenziell** für jeden Shop; die meisten PSP bieten Plugins für gängige Shopsysteme (z. B. Magento) |
| **ERP-Systeme / Warenwirtschaft** | für die professionelle Abwicklung von Bestellungen **unabdingbar** |
| **CRM-Systeme** | auf einen Blick sehen, was der Kunde gekauft hat, wofür er sich interessiert und womit man ihn bewerben kann; per Schnittstelle Kundendaten austauschen und **personalisierte Inhalte** bereitstellen |
| **PIM-Systeme (Product Information Management)** | Katalog- und Produktdaten an **einem zentralen Ort** verwalten und für verschiedene Systeme bereitstellen; perfekte Ergänzung zum ERP und **Grundlage für eine Multichannel-Strategie** |
| **Marktplätze und Preissuchmaschinen** | "größte Säulen des Onlinehandels" mit beachtlichem Umsatzpotenzial; Schnittstellen sind unabdingbar, damit Produktdaten und Bestellungen reibungslos synchronisiert werden und wenig manueller Aufwand entsteht |
| **Soziale Netzwerke** | Facebook-Timeline, Instagram-Feed oder YouTube-Video in Echtzeit auf der Shop-Plattform ausspielen, ohne doppelte Arbeit bei der Content-Erstellung |
| **Logistiksysteme** | siehe Abschnitt 6 |

Praxisbeispiel einer typischen Systemlandschaft: Shopsystem ↔ WaWi (Bestand, Einkauf, Fulfillment) ↔ Newsletter-/Marketing-Tool ↔ Kundenservice-Software (Helpdesk) ↔ Feed-Tool (Produktfeeds für Marktplätze und Preissuchmaschinen) ↔ Versanddienstleister (Tracking). Jede Verbindung ist eine Schnittstelle; fällt eine aus, entstehen Insellösungen und manueller Aufwand.

### 4. Kanalarten im Online-Marketing (Schaubild, nur im PDF-Bild)
Kreisdiagramm mit vier Kanälen und ihren Vor-/Nachteilen:

| Kanal | Vor- (+) und Nachteile (−) |
|---|---|
| **Referrals** (z. B. Vergleichsportale) | + Vergleichsportale sind wichtig bei Produktrecherchen; + steigern die Reichweite; − unpersönliche Bindung zu Kunden |
| **SEO/SEA** | − hohe Gebühren; + andere Marketingkosten fallen dafür weg; − man ist Regularien und Algorithmen unterworfen |
| **Online-Marktplätze** | − hohe Gebühren; + andere Marketingkosten fallen dafür weg; − man ist Regularien und Algorithmen unterworfen |
| **Social Networks** | + sehr effektiv für Bestandskunden; − setzt Fingerspitzengefühl und Empathie voraus |

⚠️ Hinweis: Bei SEO/SEA ist "hohe Gebühren" nur für **SEA** (bezahlte Anzeigen, Klickpreise) zutreffend. **SEO** (organische Suchmaschinenoptimierung) verursacht keine Gebühren an die Suchmaschine, sondern internen Aufwand bzw. Agenturkosten.

### 5. Multi-Channel- vs. Cross-Channel-Marketing
- **Multi-Channel-Vertrieb:** Nutzung eigener **und** fremder Vertriebskanäle, also eine Mischung aus direktem und indirektem Vertrieb.
- **Multi-Channel-Marketing:** Kanäle werden **unabhängig voneinander** bedient. Schaubild: Jede Kampagne (1, 2, 3) strahlt parallel auf alle Kanäle aus (TV, Print-Anzeigen, Website, E-Mail-Marketing, Social Media), ohne Verbindung zwischen den Kanälen.
- **Cross-Channel-Marketing:** Botschaften werden **über alle Kanäle hinweg aufeinander abgestimmt** → konsistenteres Kundenerlebnis. Schaubild: Die Kanäle sind verkettet und führen den Kunden weiter, z. B.
  - Kampagne 1 → E-Mail-Marketing → Online-Shop
  - Kampagne 2 → SEA → Website ↔ Display-Marketing → Online-Shop
  - Kampagne 3 → TV → Social Media → Website

### 6. Logistische Anforderungen

**Schnittstelle zu Logistiksystemen:** Eine Anbindung des Onlineshops an den Logistikdienstleister (z. B. DHL) optimiert logistische Prozesse und steigert die Kundenzufriedenheit. Neben der **Sendungsverfolgungsnummer** lassen sich weitere USPs bei den Lieferoptionen realisieren: Lieferung an Packstation, zum Wunschtermin, an einen Ablageort usw.

**Anforderungen an die E-Commerce-Logistik:**
- Kommissionier- und Versandleistung speziell auf **schnelle Lieferung** ausgerichtet
- **Flexibilität**, sich auf unterschiedlichste Distributionsformen einzustellen
- **optimale Verpackungsgröße**
- **schnelle Warenannahme**

**Schaubild "Erfolgsfaktoren in der Logistik des Onlinehändlers"** (nur als Bild):

| Ziel | Erfolgsfaktoren |
|---|---|
| **Kosten senken** | Insourcing vs. Outsourcing; Bestandsmanagement; Retourenmanagement |
| **Umsatz steigern** | Kundenzufriedenheit; Unterstützung des Multichannel-Vertriebs; Nachhaltigkeit |

**Hauptziele der Distributionslogistik** (aus Aufgabe 3, laut Lösungsblatt): **Verfügbarkeit**, **Kostenminimierung**, **Einflussnahme**. Das Infoblatt erklärt die drei Ziele nicht.
🔎 Ergänzung (nicht im Original, sinngemäß nach der im Material als Quelle genannten Seite mm-logistik.vogel.de):
- Verfügbarkeit: Kunden steht stets eine ausreichende Produktmenge zeitnah zur Verfügung.
- Kostenminimierung: Transport-, Bestands-, Fehlmengen- und Auftragsabwicklungskosten senken.
- Einflussnahme: möglichst hohes Mitbestimmungsrecht bei der Vermarktung der Produkte (z. B. Platzierung, Präsentation gegenüber der Konkurrenz).

## Formeln & Rechenwege
Keine Rechenanteile.

## Aufgaben aus dem Material

**Aufgabe 1:** Nennen Sie die Vorteile des B2C-Vertriebs über Online-Marktplätze.
**Lösung:** Hoher Bekanntheitsgrad und hohe Reichweite; Kunden haben hohes Vertrauen in bekannte Marktplätze; die Auslagerung von Tätigkeiten wie Lagerung, Versand oder Payment kann vorteilhaft sein.

**Aufgabe 2:** Welche Gefahren drohen einem Unternehmen, das auf allen Marktplätzen gleichermaßen Präsenz zeigt?
**Lösung:** Verzettelung durch das **Gießkannenprinzip**; effektiver ist es zumeist, Schwerpunkte zu setzen.
Ergänzend sinnvoll: hoher Pflege- und Koordinationsaufwand (Produktdaten, Preise, Bestände je Marktplatz), viele Gebühren, Gefahr von Überverkäufen ohne saubere Schnittstellen, Kannibalisierung der eigenen Kanäle.

**Aufgabe 3:** Welche 3 sind die Hauptziele der Distributionslogistik? a. Verfügbarkeit, b. Kostenminimierung, c. Flexibilität, d. vertikale Vernetzung, e. Einflussnahme
**Lösung:** **a, b, e** (Verfügbarkeit, Kostenminimierung, Einflussnahme).

**Aufgabe 4:** Was ist eine Schnittstelle? Nennen Sie außerdem die 3 Hauptgruppen.
**Lösung (Original):** Durch Arbeitsteilung entstandene Transferpunkte zwischen Funktionsbereichen, Sparten, Projekten, Personen, Unternehmen usw. Eine Programmierschnittstelle (API) ist das Stück Software einer Lösung, das anderen Programmen zur Anbindung zur Verfügung gestellt wird.
⚠️ Hinweis: Die Originallösung **vergisst die 3 Hauptgruppen**. Vollständig: **B2B** (betriebsextern, z. B. Zulieferer, strategische Allianzen), **B2C** (betriebsextern, Kundenorientierung/-integration), **betriebsintern** (zwischen Mitarbeitern und Abteilungen).

**Aufgabe 5:** Was ist der Unterschied zwischen Multi-Channel-Marketing und Cross-Channel-Marketing?
**Lösung:** Im Multi-Channel-Marketing werden die Kanäle unabhängig voneinander bedient. Beim Cross-Channel-Marketing werden die Botschaften über alle Kanäle hinweg aufeinander abgestimmt, sodass Kunden ein konsistenteres Erlebnis bekommen.

## Ergänzungen & Aktualisierungen
- 🔎 Ergänzung (nicht im Original): **Magento** heißt in der kommerziellen Version seit 2021 **Adobe Commerce**; weitere verbreitete Shopsysteme sind z. B. Shopify, Shopware, WooCommerce.
- 🔎 Ergänzung (nicht im Original): Seit **13.12.2024** gilt die **EU-Produktsicherheitsverordnung (GPSR)**. Bei Online-Angeboten müssen u. a. Name und Kontaktdaten des Herstellers (bzw. der verantwortlichen Person in der EU), Angaben zur Produktidentifikation sowie Warn- und Sicherheitshinweise angezeigt werden (Art. 19 GPSR). Diese Daten müssen im PIM/Shop gepflegt und über die Schnittstellen an alle Marktplätze übertragen werden.
- 🔎 Ergänzung (nicht im Original): Bei der Anbindung von CRM-, Newsletter- und Logistiksystemen werden personenbezogene Daten übertragen → DSGVO beachten (Rechtsgrundlage, Auftragsverarbeitungsvertrag nach Art. 28 DSGVO). E-Mail-Newsletter grundsätzlich nur mit ausdrücklicher Einwilligung (§ 7 Abs. 2 UWG; Nachweis per Double-Opt-in); Ausnahme: Werbung an Bestandskunden für eigene ähnliche Waren unter den Voraussetzungen des § 7 Abs. 3 UWG (u. a. Widerspruchsmöglichkeit bei jeder Mail).

## Prüfungsfallen
- **Drei Schnittstellen-Gruppen:** B2B und B2C sind **betriebsextern**, die dritte ist **betriebsintern**. Nicht "B2B, B2C, C2C" schreiben.
- **Insellösung** = System ohne Anbindung an andere Systeme (Daten müssen manuell übertragen werden). Ihre Vermeidung ist Ziel des Schnittstellenmanagements.
- **PIM vs. ERP vs. CRM:** PIM = Produktdaten (Texte, Bilder, Attribute); ERP/WaWi = Bestände, Bestellungen, Einkauf, Rechnungen; CRM = Kundendaten und Kundenhistorie.
- **Hauptziele der Distributionslogistik laut Material: Verfügbarkeit, Kostenminimierung, Einflussnahme.** Flexibilität ist laut Infoblatt eine Anforderung an die E-Commerce-Logistik (Abschnitt 6), gehört aber nicht zu den drei Hauptzielen.
- **Multi-Channel = unabhängige Kanäle; Cross-Channel = abgestimmte, verkettete Kanäle.**
- **Direkter Vertrieb: Massendistribution nur bedingt möglich**; indirekter: großflächig, aber wenig Einfluss auf Preise und Werbung.

## Lernkarten
**F:** Definieren Sie den Begriff Schnittstelle.
**A:** Durch Arbeitsteilung entstandene Transferpunkte zwischen Funktionsbereichen, Sparten, Projekten, Personen oder Unternehmen.

**F:** Was ist eine API und welchen Nutzen hat sie?
**A:** Programmierschnittstelle, die eine Software anderen Programmen zur Anbindung bereitstellt; Daten werden automatisch ohne manuelle Verarbeitung zwischen Systemen ausgetauscht.

**F:** Nennen Sie die drei Hauptgruppen von Schnittstellen mit je einem Beispiel.
**A:** B2B, betriebsextern (Zulieferer); B2C, betriebsextern (Kundenintegration); betriebsintern (zwischen Abteilungen).

**F:** Nennen Sie vier Ziele des Schnittstellenmanagements.
**A:** Zielabstimmung, Vermeidung von Insellösungen, Konfliktmanagement, Übersetzeraufgaben, Mitarbeiter motivieren und schulen.

**F:** Welche Aufgabe hat ein PIM-System?
**A:** Zentrale Verwaltung von Katalog- und Produktdaten und deren Bereitstellung für verschiedene Systeme; Grundlage einer Multichannel-Strategie, Ergänzung zum ERP.

**F:** Warum ist eine Schnittstelle zwischen Shop und Marktplätzen unabdingbar?
**A:** Produktdaten, Bestände und Bestellungen müssen reibungslos synchronisiert werden; sonst hoher manueller Aufwand und Gefahr von Überverkäufen.

**F:** Was bringt die Anbindung des Shops an einen Versanddienstleister?
**A:** Optimierte Logistikprozesse, automatische Sendungsverfolgungsnummer, zusätzliche Lieferoptionen (Packstation, Wunschtermin, Ablageort) als USP, höhere Kundenzufriedenheit.

**F:** Nennen Sie vier Anforderungen an die Logistik im E-Commerce.
**A:** Kommissionierung und Versand auf schnelle Lieferung ausgerichtet, Flexibilität bei Distributionsformen, optimale Verpackungsgröße, schnelle Warenannahme.

**F:** Nennen Sie die drei Hauptziele der Distributionslogistik.
**A:** Verfügbarkeit, Kostenminimierung, Einflussnahme.

**F:** Nennen Sie je zwei Vor- und Nachteile des direkten Vertriebskanals.
**A:** Vorteile: bessere Kontrolle des Absatzgeschehens, persönliche Kommunikation, keine Abhängigkeit von Zwischenhändlern. Nachteile: höhere Personalkosten, Massendistribution nur bedingt möglich, höherer absatzorganisatorischer Aufwand.

**F:** Ein Händler stellt sein komplettes Sortiment auf 12 Marktplätzen ein. Welche Gefahr besteht?
**A:** Verzettelung nach dem Gießkannenprinzip: hoher Aufwand, Gebühren, Pflegefehler; besser Schwerpunkte auf die passenden Marktplätze setzen.

**F:** Unterscheiden Sie Multi-Channel- und Cross-Channel-Marketing.
**A:** Multi-Channel: Kanäle werden unabhängig voneinander bespielt. Cross-Channel: Botschaften sind kanalübergreifend abgestimmt und leiten den Kunden von Kanal zu Kanal (z. B. TV → Social Media → Website).

**F:** Welche Logistik-Erfolgsfaktoren senken laut Schaubild Kosten, welche steigern den Umsatz?
**A:** Kosten senken: Insourcing vs. Outsourcing, Bestandsmanagement, Retourenmanagement. Umsatz steigern: Kundenzufriedenheit, Unterstützung Multichannel-Vertrieb, Nachhaltigkeit.

## Bezüge
- LF09_Schnittstellenmanagement-im-B2B-und-B2C-2_E-Commerce_OSZHandel1: Fortsetzung Schnittstellen, Datenaustausch
- LF09_Kompatibilität-von-neuen-Vertriebswegen_E-Commerce_OSZHandel1: WaWi-Integration als K.-o.-Kriterium
- LF09_Logistische-Anforderungen_E-Commerce_OSZHandel1: Warenwirtschaft, Waren- und Datenfluss
- LF09_Cross-Channel-Situationen_E-Commerce_OSZHandel1: Multi-, Cross-, Omni-Channel
- LF09_Daten-Import-Daten-Export_E-Commerce_OSZHandel1: Datenaustausch zwischen Systemen, Formate
- LF09_Outsourcing_E-Commerce_OSZHandel1: Insourcing vs. Outsourcing, Fulfillment
- LF09_Vertriebskanäle_E-Commerce_OSZHandel1: direkter und indirekter Vertrieb
- LF09_Datenschutz_E-Commerce_OSZHandel1: Kundendatenübertragung an CRM/Newsletter
