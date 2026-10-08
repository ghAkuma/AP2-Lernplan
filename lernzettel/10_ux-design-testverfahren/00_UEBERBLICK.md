# 10 Usability, UX-Design und Testverfahren

**Prüfungsbereich:** Teil 2 – Geschäftsprozesse im E-Commerce (120 Min, 30 %); dazu Grundwissen fürs Fachgespräch, falls dein Gebiet „Optimieren von Nutzungsprozessen“ ist (§ 13 Abs. 2 Nr. 2) | **Priorität:** B | **Lernzeit Erstdurchgang:** ca. 130 Min (dazu ca. 80 Min für die 3 Fallaufgaben) | **Verordnung:** § 11 Abs. 2 Nr. 1 / A1 (Seitenbesuche auswerten, Prozessabläufe analysieren, anwenderfreundliche Oberfläche, Usability), A2 (Testmethoden: Testumgebung, Testgröße, A/B- und multivariater Test, Ergebnisse auswerten), A7 (Umsetzungsvarianten testen und auswerten), § 11 Abs. 1 Nr. 5 (Barrierefreiheit nach BFSG, Einwilligung für Tracking- und Testing-Tools)

## Worum es geht

Der Block beantwortet drei Fragen in fester Reihenfolge. Erstens: Wie verhalten sich die Besucher im Shop (Seitenbesuche auswerten)? Zweitens: Wie muss die Oberfläche aussehen, damit sie schnell ans Ziel kommen (UX-Design)? Drittens: Ist eine Änderung wirklich besser (Testumgebung und Testverfahren)? Daraus entsteht ein Kreislauf aus Analysieren, Hypothese, Testen, Auswerten und Umsetzen, und danach beginnt er von vorn. In der Prüfung kommt das meist als ungebundene Aufgabe: einen A/B-Test planen, zwischen A/B- und multivariatem Test wählen, mit Traffic und Conversions die Eignung und die Testdauer berechnen oder Gestaltungsfehler einer Seite den UX-Grundsätzen zuordnen. Aus dem Shop-Alltag kennst du das vielleicht: Ein dupliziertes, unveröffentlichtes Shop-Theme ist das Sandbox-Prinzip. Und wer vor der Black Week Produktseiten umbaut, muss vorher wissen, ob das die Conversion-Rate hebt oder senkt. Rechtlich hängen zwei Pflichten daran, die Prüfer gern abfragen: Barrierefreiheit nach dem BFSG und die Einwilligung nach § 25 TDDDG für Test- und Tracking-Tools.

## Lernreihenfolge

| Nr | Lernzettel | Kern/Überfliegen | Minuten | Danach kannst du ... |
|---|---|---|---|---|
| 1 | [Auswertung von Seitenbesuchen](LF09_Auswertung-von-Seitenbesuchen_E-Commerce_OSZHandel1.md) | Überfliegen | 10 | die acht Methoden nennen, schwache und starke Interessenssignale unterscheiden und die Datenschutzgrenzen benennen |
| 2 | [UX-Design und Customer Experience](LF09_UX-Design_E-Commerce_OSZHandel1.md) | Kern | 20 | UX und CX abgrenzen, Konventionen, visuelle Hierarchie und primären/sekundären CTA erklären, CX per NPS messen |
| 3 | [UX-Design: Grundsätze](LF09_UX-Design-2_E-Commerce_OSZHandel1.md) | Kern | 25 | UI und UX abgrenzen, Mängel den Grundsätzen Visibility, Accessibility, Legibility und Language zuordnen, den Nutzen guter UX begründen, die BFSG-Pflicht prüfen |
| 4 | [Testumgebung: Sandbox und Live-Test](LF02_Testumgebung_E-Commerce_OSZHandel1.md) | Kern | 20 | Sandbox und Live-Test unterscheiden, die vier Voraussetzungen nennen, mit der 500-Conversions-Regel die Eignung eines Shops berechnen |
| 5 | [Testumgebung: DEV, Staging, Production](LF09_Testumgebung_E-Commerce_OSZHandel1.md) | Überfliegen | 5 | den Weg einer Änderung von DEV über Staging in die Production beschreiben |
| 6 | [Testverfahren: A/B und multivariat](LF07_Testverfahren_E-Commerce_OSZHandel1.md) | Kern | 30 | den A/B-Test-Ablauf erklären, A/B- und multivariaten Test begründet auswählen, CR, Uplift und Kombinationen berechnen |
| 7 | [Test-Größe beim A/B-Testing](LF07_Testgröße_E-Commerce_OSZHandel1.md) | Kern | 20 | Gesamt-Traffic und Testdauer in vollen Wochen berechnen, die Bedingungen statistischer Validität nennen |
| | **Summe** | | **130** | |

Voraussetzung: Block 08 (Conversion Funnel, Landingpage, above the fold), vor allem [LF07_Landingpage](../08_customer-journey-conversion-funnel/LF07_Landingpage_E-Commerce_OSZHandel1.md) und [LF07_Conversion-Funnel](../08_customer-journey-conversion-funnel/LF07_Conversion-Funnel_E-Commerce_OSZHandel1.md).

## Begriffslandkarte

- **Ziel: Nutzung des Online-Shops optimieren** (mehr Conversions, weniger Absprünge, zufriedenere Kunden)
  - **1. Analysieren: Was tun die Besucher?** → [Auswertung von Seitenbesuchen](LF09_Auswertung-von-Seitenbesuchen_E-Commerce_OSZHandel1.md)
    - 8 Methoden: IP-Adresse, Klickverhalten (Tags), Referrer, wiederkehrende Nutzer, Endgerät, Downloads, Kaufverhalten, Newsletter-Öffnungen
    - schwache Signale (Seitenaufruf, Öffnung) < starke Signale (Download mit Registrierung, Kauf) → kombinieren und über längere Zeit beobachten
    - 🔎 Ergänzung (nicht im Original): Eye-Tracking, Heatmaps, Scroll-Maps, Session-Recordings, Klickpfad- und Formularanalyse
    - Grenze: Datenschutz (IP-Adresse personenbezogen, Einwilligung nach § 25 TDDDG)
  - **2. Gestalten: Wie soll die Oberfläche sein?** → [UX-Design](LF09_UX-Design_E-Commerce_OSZHandel1.md), [UX-Design 2](LF09_UX-Design-2_E-Commerce_OSZHandel1.md)
    - Begriffe von groß nach klein (vereinfachtes Schalenmodell: jeder Begriff umfasst den nächsten):
      - **CX** (Customer Experience): Erlebnis mit der Marke an allen Touchpoints, inklusive Lieferung, Service, Retoure; gemessen u. a. per NPS
        - **UX** (User Experience): Erleben vor, während und nach der Nutzung von Website oder Produkt; gut, wenn Nutzerziel = Unternehmensziel (Garrett)
          - **Usability** (🔎 Ergänzung, nicht im Original): effektiv, effizient, zufriedenstellend nutzbar (DIN EN ISO 9241-11)
            - **UI** (User Interface): sichtbare Oberfläche, Ästhetik
    - 4 Grundsätze: **Visibility** (visuelle Hierarchie, primärer/sekundärer CTA), **Accessibility** (laut Material: Inhalte schnell finden; rechtlich: Barrierefreiheit nach BFSG/WCAG), **Legibility** (Lesbarkeit), **Language** (Sprache der Zielgruppe)
    - Praxisregeln: Konventionen (Suchfeld oben rechts/mittig), einheitliches Corporate Design, Zielgruppe kennen (Tests, Umfragen, [Personas](../11_kundendaten-zielgruppen-segmentierung/LF09_Nutzerprofile_E-Commerce_OSZHandel1.md)), schlicht statt überfrachtet, kurze Ladezeiten („Don't make me think“), Hilfestellungen
  - **3. Testen: Ist die Änderung wirklich besser?**
    - **Wo?** Testumgebungen
      - ohne Kunden: Sandbox ([LF02](LF02_Testumgebung_E-Commerce_OSZHandel1.md)) ≈ Stufen DEV und Staging ([LF09](LF09_Testumgebung_E-Commerce_OSZHandel1.md)): prüft, ob alles funktioniert; nach der Freigabe Go-live in die Production (Live-Shop)
      - mit echten Kunden: Live-Test im Live-Shop: prüft, ob es besser wirkt
    - **Wie?** Testverfahren ([LF07_Testverfahren](LF07_Testverfahren_E-Commerce_OSZHandel1.md))
      - A/B-Test: Kontrollversion A gegen Variante B, Traffic 50 : 50 zufällig (🔎 Sonderformen A/B/n-Test, Split-URL-Test)
      - multivariater Test: mehrere Elemente gleichzeitig, Traffic auf alle Kombinationen (faktorielles Testen)
    - **Wie viel und wie lange?** ([LF07_Testgröße](LF07_Testgröße_E-Commerce_OSZHandel1.md), [LF02](LF02_Testumgebung_E-Commerce_OSZHandel1.md))
      - Eignung des Shops: mindestens 500 Conversions pro Monat
      - Test-Größe = Besucher je Variante → Gesamt-Traffic → Testdauer in vollen Wochen, Deadline ca. 2 Monate
      - Signifikanz/Konfidenzniveau, Teststärke, Fehlervarianz → statistische Validität
    - **Woran gemessen?** KPIs: Conversions/Conversion-Rate, Newsletter-Anmeldungen, Absprungrate, Nutzungs-/Verweildauer, Downloads ([Micro-Conversions](../08_customer-journey-conversion-funnel/LF03_Micro-conversion_E-Commerce_OSZHandel1.md))
  - **4. Umsetzen und wieder analysieren** → Gewinnervariante ausrollen, KPIs nach dem Go-live beobachten ([Qualitätssicherung](../05_rueckabwicklung-retouren-qualitaet-prozesse/LF10_Qualitätssicherung-von-Prozessen_E-Commerce_OSZHandel1.md)), nächster Test

## Geklärte Widersprüche

**1. „Testumgebung“ hat zwei Bedeutungen**
- *Abweichung:* [LF02_Testumgebung](LF02_Testumgebung_E-Commerce_OSZHandel1.md) unterscheidet Sandbox (Kopie ohne Kunden) und Live-Test (A/B mit echten Kunden); die Musterlösung zu Aufgabe 1 zählt A/B-Testing sogar zur Testumgebung „ohne Einsicht Außenstehender“, Aufgabe 3 nennt den „Live-Shop“ als Testumgebung. [LF09_Testumgebung](LF09_Testumgebung_E-Commerce_OSZHandel1.md) beschreibt dagegen die Stufen DEV → Staging → Production und nennt die Leute in DEV „DevOps“. Das LF09-Blatt hat keinen Prüfungskopf.
- *In der Prüfung:* Testumgebung = vom Live-Betrieb getrennte Kopie des Shops (Sandbox, fein unterteilt in DEV und Staging), dort wird ohne Kunden geprüft, ob alles funktioniert. Davon getrennt gibt es den Live-Test (A/B, multivariat) im echten Shop mit echtem Traffic. Wird nach „Arten von Testumgebungen“ gefragt: beide Sichten nennen (Sandbox und Live-Test sowie DEV, Staging, Production).
- *Warum:* Beim A/B-Test sehen echte Kunden die Varianten, sie wissen nur nicht, welche. „DevOps“ ist eine Arbeitsweise bzw. Rolle (Entwicklung + Betrieb), keine Umgebung; in DEV arbeiten Entwickler. Die Zuordnung des LF09-Blatts ist vom inhaltsgleichen LF02-Blatt übernommen.

**2. Faustregeln für Live-Tests: 500 Conversions, volle Wochen, ca. 2 Monate**
- *Abweichung:* [LF02_Testumgebung](LF02_Testumgebung_E-Commerce_OSZHandel1.md) nennt „mindestens 500 Conversions pro Monat“ und „durchschnittlich zwei Monate“; [LF07_Testgröße](LF07_Testgröße_E-Commerce_OSZHandel1.md) rechnet mit „ca. 2 Wochen“ und verlangt den 7-Tage-Rhythmus. Die Laher-GmbH-Aufgabe ist knapp (17 × 30 = 510, im Februar 17 × 28 = 476). Die Beispielzahl 37.363 Besucher je Variante ist ohne Angabe der Teststärke nicht nachrechenbar.
- *In der Prüfung:* (a) Eignung: Conversions auf den Monat umrechnen, ab 500 geeignet. (b) Testdauer: aus Traffic berechnen, immer auf volle Wochen aufrunden, ca. 2 Monate sind Obergrenze bzw. Deadline. Bei Laher: Rechenweg plus Annahme hinschreiben („mindestens 17 Neukunden täglich, dazu Bestandskunden → über 500 → geeignet“). Bei der Test-Größe nur das Rechenschema anwenden: Bestellungen → Ziel-CR → Gesamt-Traffic → Testdauer.
- *Warum:* Zwei Monate sind keine Mindestdauer, sondern die Grenze, nach der man einen Test ohne signifikantes Ergebnis neu aufsetzt. Ein Test mit viel Traffic darf nach 2 Wochen fertig sein. Die Besucherzahl je Variante wird in Prüfungen vorgegeben.

**3. A/B-Test vs. multivariater Test**
- *Abweichung:* Das Infoblatt in [LF07_Testverfahren](LF07_Testverfahren_E-Commerce_OSZHandel1.md) sagt, beim MVT werde der Traffic „wieder auf zwei verschiedene Versionen“ aufgeteilt. Die Lösung zu Aufgabe 4 sagt, beim A/B-Test sehe der Nutzer „zwei völlig unterschiedliche Seiten“, das Infoblatt dagegen, es werde „immer nur ein Element“ verändert. Lösung 5 empfiehlt für den Check-out den MVT.
- *In der Prüfung:* A/B-Test = Kontrollversion A gegen Variante B, idealerweise ein Element geändert, damit die Ursache eindeutig ist. Zwei komplett verschiedene Seiten zu testen heißt 🔎 Split-URL-Test (eine Sonderform des A/B-Tests); dann weiß man nicht, welches Element gewirkt hat. MVT = mehrere Elemente gleichzeitig, Traffic auf **alle Kombinationen** (2 × 2 × 2 = 8). Check-out: MVT **nur, wenn genug Traffic** da ist; diese Bedingung ausdrücklich hinschreiben, sonst Elemente nacheinander per A/B-Test.
- *Warum:* Faktorielles Testen braucht für jede Kombination genug Besucher. Den Check-out erreichen nur Besucher mit Warenkorb, er hat deshalb meist wenig Traffic.

**4. UI, Usability, UX, CX und „Accessibility“**
- *Abweichung:* [LF09_UX-Design](LF09_UX-Design_E-Commerce_OSZHandel1.md) lässt die CX „beim letzten Kontaktpunkt, dem Kauf“ enden und schreibt „ohne gute UX keine gute CX und umgekehrt“. [LF09_UX-Design-2](LF09_UX-Design-2_E-Commerce_OSZHandel1.md) spricht von Touchpoints vor, während und nach der Nutzung und verwendet „Accessibility“ für die Auffindbarkeit von Inhalten.
- *In der Prüfung:* UI ⊂ Usability ⊂ UX ⊂ CX (vereinfachtes Schalenmodell zum Abgrenzen, keine Norm). Die CX umfasst auch die Nachkaufphase (Lieferung, Auspacken, Service, Retoure, Wiederkauf). UX ist Teil der CX: Schlechte UX verdirbt die CX, gute UX allein garantiert aber keine gute CX. Bei „Accessibility“ kurz klarstellen: im Material Auffindbarkeit (Navigation, Suche, Inhaltsverzeichnis), fachlich und rechtlich Barrierefreiheit (Alt-Texte, Kontrast, Tastaturbedienung). CX-Messung per NPS wie in Block 03 ([LF06_Kennzahlen](../03_kennzahlen-werbeerfolg-kundenwert/LF06_Kennzahlen_E-Commerce_OSZHandel1.md)).
- *Warum:* Retouren und Lieferprobleme prägen das Kundenerlebnis stark. „Accessibility“ ist in Gesetz und Norm (BFSG, WCAG) eindeutig als Barrierefreiheit belegt.

**5. Recht und Messgenauigkeit: BFSG, Einwilligung, Öffnungsraten, „Exe-Tracking“**
- *Abweichung:* Das Material erwähnt Datenschutz und Barrierefreiheit gar nicht. [LF02_Testumgebung](LF02_Testumgebung_E-Commerce_OSZHandel1.md) betont, der Kunde solle den Test „nicht mitbekommen“. [LF09_Auswertung](LF09_Auswertung-von-Seitenbesuchen_E-Commerce_OSZHandel1.md) wertet Newsletter-Öffnungen aus und schreibt in der Überschrift „Exe-Tracking“.
- *In der Prüfung:* BFSG gilt seit 28.06.2025 für B2C-Shops (Ausnahme: Kleinstunternehmen bei Dienstleistungen), Maßstab WCAG 2.1 AA. Testing-, Tracking- und Heatmap-Tools brauchen in der Regel eine Einwilligung nach § 25 TDDDG; IP-Adressen sind personenbezogene Daten. „Der Kunde merkt den Test nicht“ heißt nur: Er weiß nicht, welche Variante er sieht. Öffnungsraten sind seit Apple Mail Privacy Protection (2021) verzerrt, Klicks und Käufe sind verlässlicher. „Exe-Tracking“ = Eye-Tracking (Blickverlaufsmessung).
- *Warum:* Das sind gesicherte, aktuelle Rechtsstände (Fundstellen siehe [LF09_UX-Design-2](LF09_UX-Design-2_E-Commerce_OSZHandel1.md) und [LF07_Testverfahren](LF07_Testverfahren_E-Commerce_OSZHandel1.md)); Eye-Tracking erklärt das Material selbst nicht, es ist nur als Ergänzung gelernt.

**6. Uneinheitliche Kopfzeilen und Personas**
- *Abweichung:* Die Seitenköpfe nennen LF10, LF7 oder LF9. Die Textebene nennt bei drei der vier Test-Blätter „02 Waren- oder Dienstleistungssortiment mitgestalten und online bewirtschaften“ (das vierte, LF09_Testumgebung, hat gar keinen Kopf), bei den beiden UX-Blättern und der Seitenbesuchs-Auswertung „01 Online-Vertriebskanal auswählen und einsetzen“. [LF09_UX-Design](LF09_UX-Design_E-Commerce_OSZHandel1.md) hat den falsch kopierten Unterpunkt „01 Online-Vertriebskanäle“.
- *In der Prüfung:* Alle sieben Blätter gehören zum Prüfungsbereich Geschäftsprozesse im E-Commerce, Gebiet 1 „Einsatz eines Online-Vertriebskanals und Optimierung der Nutzung“; Tests von Umsetzungsvarianten kommen auch bei Online-Marketing (A7) vor. Personas wie im Block 11 ([LF09_Nutzerprofile](../11_kundendaten-zielgruppen-segmentierung/LF09_Nutzerprofile_E-Commerce_OSZHandel1.md)).
- *Warum:* Für die Antwort zählt der Inhalt, nicht der Kopf des Arbeitsblatts.

**7. „Signifikanz von 95 %“** (zusätzlich gefunden)
- *Abweichung:* [LF07_Testgröße](LF07_Testgröße_E-Commerce_OSZHandel1.md) schreibt „Signifikanz von 95 %“, [LF02_Testumgebung](LF02_Testumgebung_E-Commerce_OSZHandel1.md) spricht vom „Konfidenzniveau“.
- *In der Prüfung:* Konfidenzniveau 95 % = Signifikanzniveau (Irrtumswahrscheinlichkeit) 5 %. Kurzform: „Der Unterschied ist mit 95 % Sicherheit kein Zufall.“ Nicht: „95 % der Besucher …“.
- *Warum:* Umgangssprachlich wird „Signifikanz 95 %“ benutzt, fachlich ist das Signifikanzniveau die kleine Zahl (5 %). Die Lernkarte im Zettel ist entsprechend präzisiert.

**8. Test-Größe (Besucher) vs. 500-Regel (Conversions)** (zusätzlich gefunden)
- *Abweichung:* [LF07_Testgröße](LF07_Testgröße_E-Commerce_OSZHandel1.md) definiert die Test-Größe als Zahl der Besucher, [LF02_Testumgebung](LF02_Testumgebung_E-Commerce_OSZHandel1.md) misst die Eignung in Conversions.
- *In der Prüfung:* Zwei verschiedene Prüfschritte: erst „Eignet sich der Shop?“ (Conversions pro Monat ≥ 500), dann „Wie lange läuft der Test?“ (Besucher je Variante × Varianten ÷ Besucher pro Tag).
- *Warum:* Wer Besucher mit Conversions verwechselt, rechnet um den Faktor der Conversion-Rate falsch (bei 2 % CR: Faktor 50).

**9. Wer entscheidet, wann der Test fertig ist?** (zusätzlich gefunden)
- *Abweichung:* [LF07_Testgröße](LF07_Testgröße_E-Commerce_OSZHandel1.md), Lösung 4: Die Software bestimmt die Test-Größe selbst. [LF07_Testverfahren](LF07_Testverfahren_E-Commerce_OSZHandel1.md): Die vorher vom Tester hinterlegten Parameter beeinflussen das Ergebnis stark.
- *In der Prüfung:* Beides: Das Team legt **vorher** die Parameter fest (Ziel-KPI, Signifikanzniveau, ggf. Mindestlaufzeit), die Software rechnet damit, wann genug Daten vorliegen, und leitet danach den Traffic auf den Gewinner. Die Schwelle ist je Software unterschiedlich.
- *Warum:* Die Lösung „Software macht das“ ist für eine ungebundene IHK-Aufgabe zu knapp.

## Formeln des Blocks

Ausführlich mit allen Beispielen: [FORMELSAMMLUNG](../../FORMELSAMMLUNG.md).

| Größe | Formel | Variablen / Hinweis | Quelle |
|---|---|---|---|
| Conversions pro Monat | Conversions/Jahr ÷ 12 bzw. Conversions/Tag × 30 | geeignet für Live-Test ab 500 | Material (LF02) |
| Bestellungen | Besucher × Conversion-Rate | 200.000 × 3 % = 6.000 | Material (LF07_Testgröße) |
| Ziel-CR | CR alt × (1 + Verbesserung) | 3 % × 1,15 = 3,45 % | Rechenweg zum Material |
| Gesamt-Traffic | Besucher je Variante × Anzahl Varianten (inkl. Kontrolle) | 37.363 × 2 = 74.726 | Rechenweg zum Material |
| Testdauer | Gesamt-Traffic ÷ (Besucher pro Tag × Anteil im Test), auf volle Wochen aufrunden | 74.726 ÷ 6.667 ≈ 11,2 Tage → 14 Tage | Rechenweg zum Material |
| Conversion-Rate | Conversions ÷ Besucher × 100 | je Variante getrennt | 🔎 Ergänzung |
| Differenz | CR B − CR A | in **Prozentpunkten** | 🔎 Ergänzung |
| Uplift | (CR B − CR A) ÷ CR A × 100 | relative Verbesserung in **%** | 🔎 Ergänzung |
| Mehrumsatz | Besucher × (CR B − CR A) × Ø Bestellwert | CR als Dezimalzahl einsetzen | 🔎 Ergänzung |
| MVT-Kombinationen | Varianten Element 1 × Varianten Element 2 × … | multiplizieren, nicht addieren | 🔎 Ergänzung |
| MVT-Traffic | Kombinationen × Mindestbesucher je Kombination | | 🔎 Ergänzung |
| NPS | % Promotoren (9–10) − % Detraktoren (0–6) | Passive (7–8) zählen nur zur Gesamtzahl | Block 03 |
| Öffnungsrate / Klickrate / CTOR | Öffnungen ÷ zugestellt; Klicks ÷ zugestellt; Klicks ÷ Öffnungen (je × 100) | Öffnungen durch Apple MPP verzerrt | 🔎 Ergänzung |
| Anteil wiederkehrender Besucher | wiederkehrende ÷ alle Besucher × 100 | | 🔎 Ergänzung |

## Top-Prüfungsfallen

1. **Sandbox/DEV/Staging ≠ A/B-Test:** In der Testumgebung sind keine Kunden beteiligt, beim Live-Test echter, zufällig verteilter Traffic.
2. **Reihenfolge DEV → Staging → Production.** Gebaut wird in DEV (kaum getestet), aktiv getestet im Staging; Bugs sind in DEV und Staging üblich. Mehrere Staging-Umgebungen gibt es, damit Entwickler und Tester parallel arbeiten.
3. **500 Conversions pro MONAT:** Jahres- und Tageswerte erst umrechnen; Prozentangaben („16 % über Vorjahr“) sind Ablenker, es zählt die absolute Zahl.
4. **Test-Größe = Besucher je Variante:** Gesamtbedarf = Wert × Anzahl der Varianten (A und B, also × 2; A/B/C × 3).
5. **Testdauer immer auf volle Wochen aufrunden** (Wochenendeffekt): 11,2 Tage → 14 Tage; 28,02 Tage → 35 Tage. Ca. 2 Monate sind Deadline, keine Mindestdauer.
6. **MVT:** Kombinationen multiplizieren (3 × 2 × 2 = 12), Traffic auf alle Kombinationen, nur bei sehr hohem Traffic. Check-out-Frage: MVT nur mit der Bedingung „wenn genug Traffic“.
7. **Erster Schritt beim A/B-Test:** Ziel und Hypothese mit den Abteilungen festlegen, nicht die Software auswählen.
8. **Prozent vs. Prozentpunkte:** CR 2,5 % → 3,0 % = +0,5 Prozentpunkte = +20 % Uplift. +15 % auf 3 % ergibt 3,45 %, nicht 18 %.
9. **Signifikanz 95 % = 5 % Irrtumswahrscheinlichkeit;** Test nicht beim ersten „Sieg“ abbrechen.
10. **UI ⊂ Usability ⊂ UX ⊂ CX:** UI = Ästhetik (kreativ), UX = Anwendbarkeit (analytisch); CX geht über den Kauf hinaus; der NPS misst die Weiterempfehlungsbereitschaft, nicht direkt die Zufriedenheit.
11. **Accessibility:** im Material „Inhalte schnell finden“, rechtlich Barrierefreiheit (BFSG); in der Antwort kurz sagen, welche Bedeutung gemeint ist. Beispiele dem richtigen Grundsatz zuordnen (Kontrast → Legibility, Hierarchie → Visibility, Suche → Accessibility, Fachbegriffe → Language).
12. 🔎 Ergänzung (nicht im Original): **„Kunde merkt den Test nicht“ ≠ keine Einwilligung:** Testing- und Heatmap-Tools brauchen in der Regel eine Einwilligung nach § 25 TDDDG.

## Fachbegriffe Deutsch–Englisch

| Deutsch | Englisch | Kurzbedeutung |
|---|---|---|
| Nutzererlebnis | User Experience (UX) | gesamtes Erleben vor, während und nach der Nutzung |
| Benutzeroberfläche | User Interface (UI) | sichtbare Gestaltung: Farben, Buttons, Schrift, Layout |
| Gebrauchstauglichkeit | Usability | effektiv, effizient, zufriedenstellend nutzbar |
| Kundenerlebnis | Customer Experience (CX) | Erlebnis mit der Marke an allen Touchpoints |
| Kontaktpunkt | Touchpoint | jede Berührung des Kunden mit Marke oder Shop |
| Barrierefreiheit | Accessibility | Nutzbarkeit auch für Menschen mit Behinderungen |
| Sichtbarkeit | Visibility | auf einen Blick erkennen, was man tun kann |
| Lesbarkeit | Legibility | Text leicht lesbar (Kontrast, Schriftart, -größe) |
| Handlungsaufforderung | Call to Action (CTA) | Button/Link zur gewünschten Aktion; primär vs. sekundär |
| sichtbarer Bereich ohne Scrollen | above the fold | sofort sichtbar; below the fold = erst nach Scrollen |
| Absprungrate | Bounce Rate | Anteil der Besuche ohne weitere Interaktion |
| Conversion-Rate | Conversion Rate (CR) | Anteil der Besucher, die das Ziel erreichen |
| Verweildauer | Time on Site / Session Duration | Dauer eines Besuchs |
| Herkunftsseite | Referrer | Quelle, über die ein Besucher kam |
| wiederkehrender Besucher | Returning Visitor/User | war schon einmal im Shop |
| Endgerät | Device | Smartphone, Tablet, Desktop |
| Blickverlaufsmessung | Eye Tracking | misst, wohin Testpersonen schauen |
| Wärmebild | Heatmap | farbige Darstellung von Klicks, Blicken oder Scrolltiefe |
| Testumgebung | Test Environment / Sandbox | vom Live-Shop getrennte Kopie |
| Entwicklungs-, Test-/Abnahme-, Produktivumgebung | Development (DEV), Staging, Production | Stufen bis zum Go-live |
| Fehler | Bug / Defect | Fehlfunktion, gefunden in DEV/Staging |
| Liveschaltung / Zurücksetzen | Go-live, Deployment / Rollback | Änderung veröffentlichen / zur letzten Version zurück |
| A/B-Test | A/B Test, Split Test | Kontrollversion gegen eine Variante |
| multivariater Test | Multivariate Test (MVT) | mehrere Elemente in allen Kombinationen |
| Kontrollgruppe / Variante | Control / Variant (Treatment) | unveränderte vs. geänderte Version |
| Hypothese | Hypothesis | begründete Vermutung „Wenn …, dann …, weil …“ |
| Stichprobengröße | Sample Size | Besucher je Variante (Test-Größe) |
| Signifikanz / Konfidenzniveau | Statistical Significance / Confidence Level | Ergebnis mit z. B. 95 % Sicherheit kein Zufall |
| Teststärke | Statistical Power | Wahrscheinlichkeit, einen echten Effekt zu erkennen |
| relative Steigerung | Uplift / Lift | (CR B − CR A) ÷ CR A |
| Kennzahl | Key Performance Indicator (KPI) | Messgröße für den Erfolg |
| Nutzerprofil | Persona | fiktiver typischer Vertreter der Zielgruppe |
| Einwilligung | Consent | Zustimmung, z. B. im Cookie-Banner |

## Spickzettel

- **Kreislauf:** Analysieren → Ziel + Hypothese (mit Abteilungen, „Wenn …, dann …, weil …“) → Varianten bauen (DEV/Staging) → Live-Test → auswerten → Gewinner ausrollen → nächster Test.
- **Seitenbesuche, 8 Methoden:** IP, Klickverhalten (Tags), Referrer, wiederkehrende Nutzer, Endgerät, Downloads, Kaufverhalten, Newsletter-Öffnungen. Neu = Grundinfos, wiederkehrend = Neuigkeiten; mobil = kompakt, PC = umfassend; Download > Seitenaufruf.
- **Begriffe:** UI (Ästhetik) ⊂ Usability (effektiv, effizient, zufriedenstellend) ⊂ UX (vor/während/nach Nutzung) ⊂ CX (alle Touchpoints inkl. Nachkauf, NPS). Gute UX: Absprungrate ↓, CR ↑, weniger Retouren und Supportanfragen.
- **4 Grundsätze:** Visibility (Hierarchie, primärer CTA auffällig), Accessibility (Material: finden; Recht: barrierefrei), Legibility (Kontrast, keine Schnörkel, keine durchgehenden Großbuchstaben), Language (Zielgruppe, keine unnötigen Fachbegriffe).
- **Testumgebung:** Sandbox = Kopie ohne Kunden; DEV (bauen) → Staging (testen, Bugs zurück an DEV, mehrere parallel) → Production (live). Live-Test = echter Traffic.
- **Voraussetzungen:** Tool richtig implementiert und beherrscht, Verbindung Testing-Tool ↔ Webanalyse, Teamarbeit mit Design/Programmierung/Text, offene Führungsspitze.
- **A/B:** Traffic zufällig 50 : 50, Nutzer nicht informiert, ein Element ändern, laufen bis zur vorher festgelegten Signifikanz, dann Gewinner bekommt den ganzen Traffic. KPIs: Conversions, Newsletter-Anmeldungen, Absprungrate, Verweildauer, Downloads.
- **MVT:** mehrere Elemente, alle Kombinationen (multiplizieren), sehr viel Traffic. Vorteil: wirksamste Elemente finden. Nachteil: Traffic. Check-out → MVT nur bei genug Traffic.
- **Zahlen:** ≥ 500 Conversions/Monat; Testdauer = Besucher je Variante × Varianten ÷ Besucher/Tag → auf volle Wochen aufrunden; Deadline ca. 2 Monate; Signifikanz 95 % = 5 % Irrtum.
- **Validität:** Zuverlässigkeit und Teststärke hoch, Fehlervarianz begrenzt, mathematische Annahmen nicht verletzt.
- 🔎 **Recht** (Ergänzung, nicht im Original): BFSG seit 28.06.2025 (B2C, nicht Kleinstunternehmen < 10 Beschäftigte und ≤ 2 Mio. €), WCAG 2.1 AA, Kontrast 4,5 : 1; § 25 TDDDG Einwilligung für Test-/Tracking-Tools; Testdaten ohne echte Kundendaten (Art. 5, 25 DSGVO).

## Lücken & Ergänzungen

**1. Usability-Tests jenseits von A/B (A1: Usability, anwenderfreundliche Oberfläche)** – Material: nur A/B und MVT, Eye-Tracking nur als Überschrift.
🔎 Ergänzung (nicht im Original):
- **Usability-Test mit Testpersonen:** typische Nutzer lösen Aufgaben („Finde einen Zanderköder unter 10 € und lege ihn in den Warenkorb“), ein Beobachter notiert, wo sie hängen bleiben. Oft mit der **Methode des lauten Denkens** (Thinking Aloud): Die Person spricht aus, was sie denkt.
- **Heuristische Evaluation:** Fachleute prüfen die Seite anhand anerkannter Regeln, z. B. der 10 Usability-Heuristiken von Jakob Nielsen.
- **Card Sorting:** Nutzer sortieren Begriffe in Gruppen; daraus entstehen Kategorien und Navigation.
- **Qualitativ vs. quantitativ:** Usability-Test, Befragung und Session-Recording zeigen, **warum** Nutzer scheitern; Webanalyse und A/B-Test zeigen, **wie viele** und **ob** eine Änderung wirkt. Gute Praxis: erst qualitativ Probleme finden, dann die Lösung quantitativ testen.
- Faustregel nach Nielsen (2000): Mit ca. **5 Testpersonen** findet man im Durchschnitt rund 85 % der Usability-Probleme. Die Regel ist umstritten; besser mehrere kleine Testrunden nacheinander.

**2. Prozessabläufe analysieren und Check-out verbessern (A1)** – Material: nur Grundsätze, keine Prozessanalyse.
🔎 Ergänzung (nicht im Original):
- Schritte des Kaufprozesses als Funnel auswerten (Produktseite → Warenkorb → Check-out-Schritte → Kauf) und den Schritt mit dem größten Abbruch zuerst angehen (siehe [LF07_Conversion-Funnel](../08_customer-journey-conversion-funnel/LF07_Conversion-Funnel_E-Commerce_OSZHandel1.md)); Formularanalyse zeigt, an welchem Feld abgebrochen wird.
- Typische Check-out-Hebel: Gastbestellung, Fortschrittsanzeige, wenige Pflichtfelder, Versandkosten und Lieferzeit früh zeigen, gängige Zahlungsarten, Vertrauenselemente, mobil passende Tastatur und Autofill.
- Rechtliche Grenze beim Umbau: Der Bestellbutton muss weiterhin eindeutig auf die Zahlungspflicht hinweisen, z. B. „zahlungspflichtig bestellen“ (Button-Lösung, § 312j Abs. 3 BGB).
- Ladezeit messbar machen: Googles **Core Web Vitals** – LCP (größtes Element geladen) ≤ 2,5 s, INP (Reaktion auf Eingaben) ≤ 200 ms, CLS (Layoutverschiebung) ≤ 0,1; INP hat am 12.03.2024 den alten Wert FID ersetzt.

**3. Testergebnisse auswerten (A2 „Ergebnisse auswerten“, A7 „Umsetzungsvarianten testen und auswerten“)** – Material: „die Software entscheidet“.
🔎 Ergänzung (nicht im Original): Prüfschema für eine Auswertungsaufgabe:
1. Lief der Test volle Wochen und ist die geplante Test-Größe erreicht?
2. Ist das vorher festgelegte Signifikanzniveau erreicht (z. B. Konfidenz ≥ 95 %)?
3. CR je Variante, Differenz in Prozentpunkten, Uplift in %, hochgerechneter Mehrumsatz bzw. Mehr-Deckungsbeitrag.
4. Nebenkennzahlen prüfen: Ø Bestellwert, Umsatz pro Besucher, Retourenquote (eine höhere CR mit mehr Retouren ist kein Gewinn).
5. Störfaktoren: Black Week, Feiertage, parallele Kampagnen, Saisonstart, technische Fehler. Tests in Aktionszeiträumen liefern nicht übertragbare Ergebnisse.
6. Entscheiden, dokumentieren, nächsten Test ableiten.
- **A/A-Test:** Beide Gruppen sehen dieselbe Version. Zeigt das Tool trotzdem einen „signifikanten“ Unterschied, misst es falsch.

**4. Recht kompakt (§ 11 Abs. 1 Nr. 5)** – Material: kein Rechtsbezug.
🔎 Ergänzung (nicht im Original), Details in [LF09_UX-Design-2](LF09_UX-Design-2_E-Commerce_OSZHandel1.md), [LF07_Testverfahren](LF07_Testverfahren_E-Commerce_OSZHandel1.md), [LF02_Testumgebung](LF02_Testumgebung_E-Commerce_OSZHandel1.md) und Block 02 ([LF09_Datenschutz](../02_recht-online-vertrieb-datenschutz/LF09_Datenschutz_E-Commerce_OSZHandel1.md)):
- **BFSG** seit 28.06.2025: B2C-Shop = Dienstleistung im elektronischen Geschäftsverkehr (§ 2 Nr. 26); Ausnahme nur für Kleinstunternehmen bei Dienstleistungen (§ 3 Abs. 3 i. V. m. § 2 Nr. 17: weniger als 10 Beschäftigte **und** Jahresumsatz oder Bilanzsumme höchstens 2 Mio. €); Informationen zur Barrierefreiheit veröffentlichen (§ 14 Abs. 1 i. V. m. Anlage 3); wer eine Dienstleistung ohne die geforderte Barrierefreiheit anbietet, riskiert ein Bußgeld bis 100.000 € (§ 37 Abs. 2 BFSG).
- **§ 25 TDDDG:** Einwilligung für Testing-, Tracking- und Heatmap-Tools, die Informationen auf dem Endgerät speichern oder auslesen.
- **Personalisierte Preise:** Hinweispflicht seit 28.05.2022 (Art. 246a § 1 Abs. 1 Satz 1 Nr. 6 EGBGB) – Vorsicht bei Preistests.
- **Testdaten:** möglichst anonymisiert oder künstlich (Datenminimierung Art. 5 Abs. 1 lit. c DSGVO, Art. 25 DSGVO).

**5. Englische Fachbegriffe (§ 11 Abs. 1 Nr. 4)** – Material: nur einzelne Kürzel. Siehe Tabelle oben; die Fallaufgabe 3 übt ein englisches Dashboard.

**6. Fachgespräch (§ 13)** – Ist dein Gebiet „Optimieren von Nutzungsprozessen“ oder geht dein Report um eine Shop-Änderung, ist dieser Block dein Fachwissen-Kern. Typische Nachfragen: Warum dieser Test und nicht ein anderer? Wie habt ihr Test-Größe und Dauer festgelegt? Wie habt ihr Störfaktoren ausgeschlossen? Was hättet ihr mit weniger Traffic gemacht? Wie ist die Einwilligung für das Tool geregelt?

## Fallaufgaben im IHK-Stil

**Ausgangssituation (für alle drei Aufgaben):** Du arbeitest im E-Commerce-Team der fiktiven *Raubfisch-Kontor GmbH*, die über einen eigenen Online-Shop Angelzubehör an Verbraucher verkauft (35 Beschäftigte, Jahresumsatz 3 Mio. €). Der Shop läuft auf einem Shopsystem mit Testumgebung; ein Testing-Tool ist eingebunden.

### Fallaufgabe 1: A/B-Test auf den Produktseiten für Gummiköder (25 Punkte, ca. 30 Min)

Die Produktseiten für Gummiköder zeigen bisher Freisteller-Bilder. Das Team möchte testen, ob ein kurzes Unterwasservideo des Köders zu mehr Bestellungen führt. Daten: Der Shop hatte im letzten Jahr 50.000 Bestellungen, davon 21.600 über die Gummiköder-Produktseiten; diese Seiten haben im Schnitt 2.400 Besucher pro Tag; Ø Bestellwert bei Gummiködern 42 €; Deckungsbeitragssatz 35 %.

a) Formulieren Sie eine prüfbare Hypothese für den Test. (3 P, 3 Min)
b) Prüfen Sie rechnerisch, ob sich der Shop und speziell die Gummiköder-Seiten nach der Faustregel für Live-Tests eignen. (3 P, 3 Min)
c) Der Stichprobenrechner des Tools verlangt 18.000 Besucher je Variante. Alle Besucher der Gummiköder-Seiten nehmen am Test teil (vereinfachte Annahme). Berechnen Sie die Testdauer und begründen Sie Ihre Rundung. (5 P, 6 Min)
d) Nach Testende liegen vor: Variante A (Bild) 25.200 Besucher, 630 Bestellungen; Variante B (Video) 25.200 Besucher, 693 Bestellungen. Berechnen Sie die Conversion-Raten, den Unterschied in Prozentpunkten, den Uplift sowie den monatlichen Mehrumsatz und Mehr-Deckungsbeitrag, wenn Variante B für alle Besucher (30 Tage) ausgerollt wird. (8 P, 10 Min)
e) Das Tool meldet für Variante B eine Konfidenz von 96 % (festgelegt waren 95 %). Die Marketingleitung möchte direkt den nächsten Test (neue Produkttitel) in der Black Week starten. Beurteilen Sie das Ergebnis und den Vorschlag. (6 P, 8 Min)

### Fallaufgabe 2: Neue Kategorieseite „Raubfischruten“ (24 Punkte, ca. 28 Min)

Die Kategorieseite „Raubfischruten“ soll überarbeitet werden. Im Usability-Test fiel auf:
- Das Suchfeld steht im Footer.
- Die Produktnamen stehen in hellgrauer, verschnörkelter Schrift, teilweise durchgehend in Großbuchstaben.
- Unter jedem Produkt stehen drei gleich große Buttons in derselben Farbe: „In den Warenkorb“, „Merken“, „Teilen“.
- Die Filter heißen „WG-Klasse“, „Aktion“ und „Taper“ ohne Erklärung, obwohl die Seite vor allem Einsteiger anspricht.

a) Ordnen Sie jeden Mangel einem Grundsatz guter UX zu und schlagen Sie je eine Verbesserung vor. (8 P, 8 Min)
b) Ihr Kollege will die Änderungen direkt im Live-Shop einbauen. Begründen Sie, warum das nicht sinnvoll ist, und beschreiben Sie den Weg bis zum Go-live. (5 P, 6 Min)
c) Für den Check-out möchte das Team zusätzlich 3 Überschriften, 2 Button-Farben und 2 Anordnungen der Zahlungsarten gleichzeitig testen. Je Kombination werden 3.000 Besucher benötigt. Den Check-out erreichen 9.000 Besucher pro Monat. Berechnen Sie den Traffic-Bedarf, beurteilen Sie, ob ein multivariater Test sinnvoll ist, und schlagen Sie eine Alternative mit Testdauer vor (A/B-Test, 3.000 Besucher je Variante). (6 P, 8 Min)
d) Prüfen Sie, ob der Shop barrierefrei sein muss, und nennen Sie drei konkrete Maßnahmen für die Kategorieseite oder den Check-out. (5 P, 6 Min)

### Fallaufgabe 3: Wochenbericht auswerten (21 Punkte, ca. 25 Min)

Die Agentur schickt den Wochenbericht auf Englisch:

| Metric (last 7 days) | Value |
|---|---|
| Users | 48,000 |
| Returning users | 14,400 |
| Bounce rate (product pages) | 58 % |
| Device category: mobile | 72 % |
| Top referrer | a fishing forum |
| Newsletter: delivered | 20,000 |
| Newsletter: unique opens | 9,000 |
| Newsletter: unique clicks | 600 |

Außerdem hat eine Kundenbefragung 800 Antworten auf die Frage „Wie wahrscheinlich ist es, dass Sie uns weiterempfehlen?“ (0–10) ergeben: 400 × 9–10, 240 × 7–8, 160 × 0–6.

a) Erklären Sie die Begriffe „bounce rate“, „returning users“ und „referrer“ auf Deutsch. (3 P, 3 Min)
b) Berechnen Sie den Anteil wiederkehrender Besucher, die Öffnungsrate, die Klickrate und die Click-to-Open-Rate. Beurteilen Sie die Aussagekraft der Öffnungsrate. (6 P, 8 Min)
c) Berechnen Sie den NPS und erläutern Sie, warum er allein nicht reicht, um die Customer Experience zu bewerten. (5 P, 6 Min)
d) Leiten Sie aus dem Bericht zwei Maßnahmen für die Produktseiten ab und beschreiben Sie, wie Sie deren Wirkung prüfen. (4 P, 5 Min)
e) Die Agentur schlägt zusätzlich ein Heatmap- und Session-Recording-Tool vor. Was ist rechtlich zu beachten? (3 P, 3 Min)

### Musterlösungen

**Fallaufgabe 1**

a) Beispiel: „Wenn wir auf den Gummiköder-Produktseiten ein Unterwasservideo statt des Freistellers zeigen, steigt die Conversion-Rate, weil Kunden das Laufverhalten des Köders besser einschätzen können.“
*Bewertung:* je 1 P für Änderung (Wenn), messbare Wirkung mit KPI (dann), Begründung (weil).

b) Shop: 50.000 ÷ 12 ≈ **4.167 Conversions pro Monat**; Gummiköder-Seiten: 21.600 ÷ 12 = **1.800 Conversions pro Monat**. Beides ≥ 500 → geeignet. (Kontrolle mit den Zahlen aus d: 2.400 × 30 × 2,5 % = 1.800, das passt.)
*Bewertung:* je 1 P für die Rechnung Shop und Gummiköder-Seiten, 1 P Entscheidung mit Bezug auf die 500er-Regel.

c) Gesamt-Traffic = 18.000 × 2 = **36.000 Besucher**. Testdauer = 36.000 ÷ 2.400 = **15 Tage** → auf volle Wochen aufrunden: **21 Tage = 3 Wochen**. Grund: Das Kaufverhalten schwankt zwischen Wochentagen und Wochenende; nur volle Wochen gleichen das aus. (Nach 21 Tagen hat jede Variante 2.400 × 21 ÷ 2 = 25.200 Besucher, also mehr als nötig.)
*Bewertung:* 1 P × 2 Varianten, 2 P Tage, 1 P Aufrunden auf 21 Tage, 1 P Begründung. Wer 15 Tage ohne Aufrunden angibt, erhält höchstens 3 P.

d) CR A = 630 ÷ 25.200 × 100 = **2,5 %**; CR B = 693 ÷ 25.200 × 100 = **2,75 %**.
Unterschied = 2,75 − 2,5 = **0,25 Prozentpunkte**; Uplift = 0,25 ÷ 2,5 × 100 = **10 %**.
Besucher pro Monat = 2.400 × 30 = 72.000. Mehrbestellungen = 72.000 × 0,0025 = 180. Mehrumsatz = 180 × 42 € = **7.560 € pro Monat**. Mehr-Deckungsbeitrag = 7.560 € × 0,35 = **2.646 € pro Monat**.
*Bewertung:* je 1 P für CR A und CR B, 1 P Prozentpunkte, 1 P Uplift, 2 P Mehrumsatz (Rechenweg), 2 P Mehr-DB. Folgefehler werden nicht doppelt abgezogen. Die Verwechslung „+0,25 %“ statt „+0,25 Prozentpunkte“ kostet 1 P.

e) Ergebnis: Die Konfidenz von 96 % liegt über den vorher festgelegten 95 %, der Test lief volle Wochen und erreichte die geplante Test-Größe → Variante B übernehmen und den Traffic umstellen; danach die KPIs (auch Ø Bestellwert und Retourenquote) weiter beobachten. Ein Restrisiko bleibt: Die Irrtumswahrscheinlichkeit liegt bei rund 4 % (erlaubt waren höchstens 5 %).
Black Week: nicht sinnvoll. In der Aktionswoche kommen andere Besucher (Schnäppchenjäger, Werbetraffic), Rabatte überlagern die Wirkung der Produkttitel, das erhöht die Fehlervarianz. Ergebnisse wären nicht auf normale Wochen übertragbar. Besser: den Test vor oder nach der Aktion in vollen Wochen fahren. Außerdem: Nur Besucher mit Einwilligung (§ 25 TDDDG) nehmen am Test teil; das gilt auch in der Black Week.
*Bewertung:* 3 P Beurteilung Ergebnis (Signifikanz, Test-Größe/Laufzeit, Entscheidung), 3 P Black Week (mindestens zwei Gründe, Alternative).

**Fallaufgabe 2**

a)
| Mangel | Grundsatz | Verbesserung |
|---|---|---|
| Suchfeld im Footer | Accessibility (im Sinne des Materials: Inhalte schnell finden; Web-Konvention) | Suchfeld oben rechts oder mittig im Header |
| hellgraue, verschnörkelte Schrift, Großbuchstaben | Legibility | schlichte Schrift, normale Groß-/Kleinschreibung, starker Kontrast |
| drei gleiche Buttons | Visibility (keine visuelle Hierarchie) | „In den Warenkorb“ als primären CTA (gefüllt, Signalfarbe), „Merken“/„Teilen“ dezent als sekundäre Elemente |
| unerklärte Fachbegriffe für Einsteiger | Language | verständliche Bezeichnungen („Wurfgewicht“) oder kurze Erklärung per Info-Symbol |

*Bewertung:* je Zeile 1 P Grundsatz, 1 P passende Verbesserung. Wer bei der Suche „Visibility“ angibt und begründet, erhält 1 P für den Grundsatz.

b) Direkt im Live-Shop würden Kunden halbfertige oder fehlerhafte Seiten sehen, das stört das Tagesgeschäft und kann Umsatz kosten. Weg: Entwickler bauen die Seite in der **DEV-Umgebung** (Kopie, nur für Programmierer sichtbar) → im **Staging** prüfen Tester und Fachabteilung aktiv (Filter, mobile Darstellung, Links), Fehler gehen zurück an DEV → nach Freigabe Übernahme in die **Production** (Live-Shop) → KPIs beobachten, bei Problemen Rollback. Ob die neue Seite besser verkauft, prüft anschließend ein A/B-Test im Live-Shop.
*Bewertung:* 2 P Begründung, 3 P Stufen in richtiger Reihenfolge mit Aufgabe.

c) Kombinationen = 3 × 2 × 2 = **12**; Traffic-Bedarf = 12 × 3.000 = **36.000 Besucher**. Bei 9.000 Check-out-Besuchern pro Monat dauert das 36.000 ÷ 9.000 = **4 Monate**. Das liegt deutlich über der Deadline von ca. 2 Monaten, Saisoneffekte würden das Ergebnis verzerren → multivariater Test **nicht sinnvoll**. Alternative: die Elemente nacheinander per A/B-Test prüfen, das wichtigste zuerst (z. B. Anordnung der Zahlungsarten). Je A/B-Test: 2 × 3.000 = 6.000 Besucher; 9.000 ÷ 30 = 300 Besucher pro Tag → 6.000 ÷ 300 = 20 Tage → aufgerundet **21 Tage = 3 Wochen**.
*Bewertung:* 1 P Kombinationen, 1 P Traffic, 1 P Dauer, 1 P Beurteilung mit Deadline/Traffic, 2 P Alternative mit Rechnung und Rundung.

d) Ja. Der Shop verkauft an Verbraucher, ist also eine Dienstleistung im elektronischen Geschäftsverkehr nach dem BFSG (gilt seit 28.06.2025). Die Ausnahme für Kleinstunternehmen greift nicht: 35 Beschäftigte (nicht unter 10) und 3 Mio. € Umsatz (über 2 Mio. €); schon eine der beiden Angaben reicht, weil für die Ausnahme beide Bedingungen erfüllt sein müssten. Maßnahmen (drei davon): Kontrast mindestens 4,5 : 1 (betrifft direkt die hellgraue Schrift), Alternativtexte für Produktbilder, vollständige Tastaturbedienung mit sichtbarem Fokus, beschriftete Formularfelder und verständliche Fehlermeldungen im Check-out, vergrößerbare Schrift. Dazu Informationen zur Barrierefreiheit veröffentlichen.
*Bewertung:* 2 P Prüfung mit Begründung (Verbraucher + Ausnahme greift nicht), 3 P für drei Maßnahmen.

**Fallaufgabe 3**

a) Bounce rate = Absprungrate: Anteil der Besuche, die ohne weitere Interaktion enden (klassisch nach nur einer Seite). Returning users = wiederkehrende Besucher, die schon einmal im Shop waren. Referrer = Herkunftsseite bzw. Quelle, über die der Besucher kam (hier ein Angelforum).
*Bewertung:* je 1 P.

b) Anteil wiederkehrender Besucher = 14.400 ÷ 48.000 × 100 = **30 %**.
Öffnungsrate = 9.000 ÷ 20.000 × 100 = **45 %**. Klickrate = 600 ÷ 20.000 × 100 = **3 %**. CTOR = 600 ÷ 9.000 × 100 ≈ **6,67 %**.
Beurteilung: Die Öffnungsrate ist nur bedingt aussagekräftig. Öffnungen entstehen auch durch eine neugierig machende Betreffzeile oder versehentlich, und Apple Mail Privacy Protection lädt das Zählpixel automatisch, sodass ungelesene Mails als geöffnet zählen. Eine hohe Öffnungsrate bei niedriger CTOR kann ein Hinweis darauf sein. Klicks und Käufe sind die verlässlicheren Signale.
*Bewertung:* je 1 P für die vier Kennzahlen, 2 P Beurteilung (mindestens zwei Gründe).

c) Promotoren = 400 ÷ 800 = 50 %; Detraktoren = 160 ÷ 800 = 20 %; NPS = 50 − 20 = **+30** (Passive 240 = 30 % zählen nicht in die Differenz).
Der NPS misst nur die Weiterempfehlungsbereitschaft. Für die CX gehören auch die Kundenzufriedenheit, die Auswertung von Nutzerverhalten (Suchverlauf, Seitenaufrufe, Verweildauer, Interaktionen) und jedes positive wie negative Kundenfeedback dazu, und zwar an allen Touchpoints bis zu Lieferung, Service und Retoure.
*Bewertung:* 2 P NPS-Rechnung, 3 P Begründung mit mindestens zwei weiteren Messgrößen.

d) Beispiele: (1) 72 % mobile Nutzer → Produktseiten Mobile First gestalten: kompakte Infos, Preis, Verfügbarkeit und „In den Warenkorb“ above the fold, kurze Ladezeit. (2) Absprungrate 58 % und Forum als Top-Referrer → erfahrene Angler suchen Details: technische Daten (Lauftiefe, Gewicht, Hakengröße) und Einsatzvideo gut sichtbar anbieten. Prüfung: jeweils A/B-Test mit vorher festgelegter Hypothese, KPI (Absprungrate, Conversion-Rate oder Add-to-Cart-Rate) und Signifikanzniveau, Laufzeit in vollen Wochen; mobile Besucher ggf. gesondert auswerten.
*Bewertung:* je Maßnahme 1 P (mit Datenbezug), 2 P für die Prüfmethode mit KPI.

e) Heatmap- und Session-Recording-Tools speichern bzw. lesen Informationen auf dem Endgerät und verarbeiten personenbezogene Daten (z. B. IP-Adresse) → vorherige Einwilligung nach § 25 TDDDG bzw. DSGVO (Cookie-Banner); Eingaben in Formularfeldern nicht aufzeichnen; der Tool-Anbieter (und ggf. die Agentur) verarbeitet die Daten im Auftrag des Shops (🔎 Auftragsverarbeitungsvertrag nach Art. 28 DSGVO); Hinweis in der Datenschutzerklärung.
*Bewertung:* 2 P Einwilligung mit Rechtsgrundlage, 1 P weiterer Punkt.
