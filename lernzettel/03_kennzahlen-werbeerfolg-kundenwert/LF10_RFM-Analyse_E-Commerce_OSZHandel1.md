# RFM-Analyse: Recency, Frequency, Monetary Value (LF10, LF10_RFM-Analyse_E-Commerce_OSZHandel1)
**Prüfungszuordnung:** Teil 2-1 Geschäftsprozesse im E-Commerce > 04 Kaufmännische Steuerung und Kontrolle nutzen > 04 Kundenwertanalysen durchführen und Schlussfolgerungen ableiten > 01 RFM (Recency, Frequency, Monetary Value) (sichtbarer Seitenkopf: Lernfeld 10 – Den Online-Vertrieb kennzahlengestützt optimieren)
**Schwierigkeit:** 2 | **Rechenanteil:** ja | **Lernzeit:** ca. 40 Min

## Kerninhalt

**1. Was ist die RFM-Analyse?**
- Instrument zur **Bestimmung des Kundenwerts** (neben Customer Lifetime Value und ABC-Analyse); interessante KPI für das Marketing; damit lässt sich die **Kundenqualität** berechnen.
- **Voraussetzung:** gut gepflegte **CRM-Datenbank** (Customer Relationship Management) oder Daten aus einer **Webanalyse** mit Informationen über das vergangene Kaufverhalten jedes Kunden.
- Einsatzbereiche: am häufigsten **Direct Marketing**, außerdem E-Mail-Marketing, Kampagnenoptimierung, Performance- und Database-Marketing.
- Nutzen: **Rücklaufquoten von Kampagnen prognostizieren**, **ROI (Return on Investment) erhöhen**.
- Viele Marketingansätze basieren auf **demografischen** Merkmalen; RFM ergänzt sie um eine **verhaltensbasierte Komponente**.

**2. Die drei Kriterien**

| Kriterium | Deutsch | Frage | Annahme |
|---|---|---|---|
| R – Recency | Neuheit/Aktualität | Wie lange liegt der letzte Kauf zurück? | Wer vor kurzem gekauft hat, reagiert eher auf ein neues Angebot. |
| F – Frequency | Häufigkeit | Wie oft kauft der Kunde? | Wer häufig kauft, reagiert eher positiv als Seltenkäufer. |
| M – Monetary Value | monetärer Wert/Umsatzvolumen | Wie viel Geld hat der Kunde insgesamt ausgegeben? | Wer insgesamt mehr ausgibt, reagiert eher auf Angebote als Kunden mit kleinen Beträgen. |

**3. Berechnung des RFM-Werts (Scoring)**
- Für R, F und M wird je eine **Kennzahl (Punktwert)** vergeben, z. B. zwischen **1 und 10**.
- Daten idealerweise aus dem **Backend des Shopsystems** (Kundendaten).
- Jeder Kunde erhält je Parameter einen Wert nach letztem Kaufdatum, Kaufhäufigkeit und Gesamtumsatz.
- Die drei Werte werden **addiert** zum **kumulierten RFM-Wert**.
- In der Praxis oft **automatisiert**; in umfangreichen CRM-Systemen und Business-Intelligence-Software meist schon implementiert.

**4. Praxisbezug und Segmentierung**
- Bei Skala 1–10 liegt der Gesamtwert zwischen **3 (Minimum) und 30 (Maximum)**. Je höher der Score, desto besser der Kunde für das Unternehmen.
- Mögliche Segmente laut Text: **Top-Kunden, aktive Kunden, Kunden mit Potenzial, unsichere Kunden, gefährdete Kunden, Flops**.
- Zielgerichtete Maßnahmen, z. B.:
  - Newsletter nur an Top-Kunden, mit **Dankeschön**,
  - gefährdete Kunden mit speziellen Aktivitäten (z. B. **Rabattgutschein**) binden.
- RFM zeigt, in welchem der drei Bereiche (R, F oder M) Veränderungen nötig sind, und liefert **Potenziale für Cross- und Upselling**.

**5. Abbildung 1: Mögliche Segmentierung in einer RFM-Analyse** (Matrix aus dem Bild)
Zeilen: Recency R5 (sehr hoch) bis R1 (sehr niedrig), jede R-Stufe unterteilt in M5 (sehr hoch) bis M1 (sehr niedrig). Spalten: Frequency F1 (sehr niedrig) bis F5 (sehr hoch). Die farbigen Segmentflächen verlaufen treppenförmig; die senkrechte Trennlinie liegt in der **Mitte der Spalte F2**. Genaue Lage der 7 Segmente:

| Segment (Beschriftung im Bild) | Lage in der Matrix |
|---|---|
| **Top-Kunden** – "häufige & hohe Umsätze" | F4–F5 bei R5 (alle M-Stufen) und R4/M5 |
| **Aktive Kunden** – "regelmäßiger Umsatz" | Mitte F2 bis F3 bei R5 und R4 (M5–M2); F4–F5 bei R4 (M4–M2) |
| **Wachstums-Kunden** – "hohes Potential für Cross- und Upselling" | Mitte F2 bis F5 bei R4/M1 und R3 (M5–M2) |
| **Gelegenheits-Kunden** – "Potential für Cross- und Upselling" | F1 bis Mitte F2 von R5 bis R2/M4; außerdem Mitte F2 bis F5 bei R3/M1 und R2 (M5–M4) |
| **Inaktive Kunden** (ohne Zusatztext) | F1 bis Mitte F2 bei R2 (M3–M1) und R1/M5 |
| **Verlorene Kunden** (ohne Zusatztext) | F1 bis Mitte F2 bei R1 (M4–M1) |
| **Gefährdete Kunden** – "keine regelmäßigen, aber teilweise hohe Umsätze" | Mitte F2 bis F5 bei R2 (M3–M1) und R1 (alle M-Stufen) |

Vereinfachte Merkhilfe (nach R und F):

| Recency | selten (F1–F2) | mittel bis häufig (F3) | häufig (F4–F5) |
|---|---|---|---|
| R5 sehr hoch | Gelegenheits-Kunden | Aktive Kunden | Top-Kunden |
| R4 hoch | Gelegenheits-Kunden | Aktive Kunden | Aktive Kunden (bei M5: Top) |
| R3 mittel | Gelegenheits-Kunden | Wachstums-Kunden | Wachstums-Kunden |
| R2 niedrig | Gelegenheits- (hohes M) bzw. inaktive Kunden (niedriges M) | Gelegenheits- bzw. gefährdete Kunden | Gelegenheits- bzw. gefährdete Kunden |
| R1 sehr niedrig | Verlorene Kunden (bei M5: inaktive) | Gefährdete Kunden | Gefährdete Kunden |

Lesart: Je aktueller (R) und häufiger (F) gekauft wird, desto wertvoller das Segment. Lange zurückliegender Kauf + früher häufige/hohe Umsätze = **gefährdet** (Reaktivierung nötig). Lange zurückliegend + selten = **verloren/inaktiv**.

## Formeln & Rechenwege

**Kumulierter RFM-Wert (additives Scoring)**
RFM-Wert = Punkte R + Punkte F + Punkte M
- R-Punkte: hoch, wenn der letzte Kauf kurz zurückliegt
- F-Punkte: hoch, wenn oft gekauft wurde
- M-Punkte: hoch, wenn insgesamt viel Umsatz gemacht wurde
- Wertebereich bei Skala 1–10: 3 bis 30

**Beispiel aus dem Material:** letzte Bestellung vor 3 Tagen: R = 7; insgesamt 5 Bestellungen: F = 6; immer nur kleinere Beträge: M = 4
RFM-Wert = 7 + 6 + 4 = **17** (Spanne 3–30, also mittelmäßiger bis guter Kunde)

**Eigenes Mini-Beispiel:** Kunde A: R 9, F 8, M 9 = 26 (Top-Kunde). Kunde B: R 2, F 7, M 8 = 17 (gleicher Score wie oben, aber lange nicht gekauft: gefährdet).

## Aufgaben aus dem Material
(Im Original sind die Aufgaben als 5–12 und die Lösungen als 13–20 nummeriert; hier 1–8.)

**Aufgabe 1 (Orig. 5):** Wofür steht die Abkürzung RFM?
**Lösung:** R = Recency (Neuheit/Aktualität), F = Frequency (Häufigkeit), M = Monetary Value (monetärer Wert/Umsatzvolumen).

**Aufgabe 2 (Orig. 6):** Erläutern Sie jeweils die Begriffe aus Aufgabe 1.
**Lösung:**
- Recency: Die Aktualität eines Kaufs identifiziert Kunden, die vor kurzem gekauft haben; sie gehen mit größerer Wahrscheinlichkeit auf ein neues Angebot ein als Kunden, deren Kauf lange zurückliegt.
- Frequency: Kunden, die häufiger kaufen, reagieren mit höherer Wahrscheinlichkeit positiv als Seltenkäufer.
- Monetary Value: Der Geldwert bezieht sich auf alle getätigten Käufe; Kunden, die insgesamt mehr ausgeben, reagieren eher auf ein Angebot als Kunden mit kleineren Beträgen.

**Aufgabe 3 (Orig. 7):** Beschreiben Sie, wofür die Daten einer RFM-Analyse nützlich sein könnten.
**Lösung:** Kundenqualität berechnen; Rücklaufquoten von Kampagnen prognostizieren; ROI erhöhen; Kunden segmentieren, um zielgerichteteres Marketing zu betreiben.

**Aufgabe 4 (Orig. 8):** Nennen Sie mögliche Segmentierungen für Kunden bezogen auf die RFM-Analyse (6 Segmentierungen).
**Lösung:** Top-Kunden, aktive Kunden, Kunden mit Potenzial, unsichere Kunden, gefährdete Kunden, Flops.
(Alternativ nach Abbildung 1: Top-, Aktive, Wachstums-, Gelegenheits-, Inaktive, Gefährdete, Verlorene Kunden.)

**Aufgabe 5 (Orig. 9):** Nennen Sie eine mögliche Marketingmaßnahme für einen gefährdeten Kunden.
**Lösung:** E-Mail mit Rabattgutschein; Erinnerung, dass noch etwas im Warenkorb liegt; E-Mail "Wir vermissen dich ...".

**Aufgabe 6 (Orig. 10):** Wo können Sie Daten über das Kaufverhalten Ihrer Kunden entnehmen? (2 Quellen)
**Lösung:** CRM-System, Webanalyse, Business-Intelligence-Software (auch: Backend des Shopsystems).

**Aufgabe 7 (Orig. 11):** Für welche Kunden ergeben sich Potenziale für Cross- und Upselling?
**Lösung:** Kunden mit Potenzial und unsichere Kunden (in Abbildung 1: Wachstums-Kunden "hohes Potenzial" und Gelegenheits-Kunden "Potenzial").

**Aufgabe 8 (Orig. 12):** Viele Marketingansätze basieren auf demografischen Eigenschaften. Nennen Sie eine weitere Komponente, die durch die RFM-Analyse ergänzt wird.
**Lösung:** Die **verhaltensbasierte** Komponente (tatsächliches Kaufverhalten).

## Ergänzungen & Aktualisierungen

🔎 Ergänzung (nicht im Original): Text und Abbildung verwenden unterschiedliche Skalen und Segmentnamen. Der Text nutzt Punkte 1–10 je Kriterium (Summe 3–30), die Abbildung 5 Stufen (R1–R5, F1–F5, M1–M5). In der Praxis werden oft je Kriterium 1–5 Punkte nach Fünfteln (Quintilen) vergeben und als Kombination (z. B. "555" = Top-Kunde) oder gewichtete Summe ausgewertet. Zuordnung der Begriffe (eigene Interpretation): Kunden mit Potenzial ≈ Wachstums-Kunden, unsichere Kunden ≈ Gelegenheits-Kunden, Flops ≈ inaktive/verlorene Kunden.

🔎 Ergänzung (nicht im Original): **Grenzen der RFM-Analyse:** reine Vergangenheitsbetrachtung, keine Kosten/Deckungsbeiträge (anders als der CLV), Neukunden schneiden bei F und M zwangsläufig schwach ab, gleiche Gesamtpunktzahl kann sehr unterschiedliche Kunden beschreiben (siehe Mini-Beispiel).

🔎 Ergänzung (nicht im Original): **Recht bei Maßnahmen:** Werbe-E-Mails (Gutschein, "Wir vermissen dich", Warenkorb-Erinnerung) brauchen grundsätzlich eine vorherige ausdrückliche Einwilligung (§ 7 Abs. 2 UWG); Ausnahme für Bestandskunden bei eigenen ähnlichen Waren unter den Voraussetzungen des § 7 Abs. 3 UWG. Die Auswertung der Kaufdaten ist eine Verarbeitung personenbezogener Daten und muss die DSGVO beachten.

## Prüfungsfallen
- **Recency: hoher Punktwert = kurz zurückliegender Kauf.** Nicht "viele Tage seit dem letzten Kauf = viele Punkte".
- **Monetary = Gesamtumsatz aller Käufe**, nicht der Wert des letzten Einkaufs.
- **RFM vs. CLV:** RFM bewertet vergangenes Kaufverhalten mit Punkten (verhaltensbasiert); der CLV berechnet einen Geldwert (Deckungsbeitrag über die gesamte Kundenbeziehung, auch zukünftig).
- **RFM vs. ABC-Analyse:** ABC teilt Kunden (oder Artikel) nur nach Umsatzanteil ein (eine Dimension), RFM nutzt drei Dimensionen.
- **Wertebereich:** Bei drei Kriterien mit je 1–10 Punkten liegt der Gesamtwert zwischen 3 und 30, nicht zwischen 0 und 30.
- **Gefährdete Kunden** haben früher teils hohe Umsätze, kaufen aber nicht mehr regelmäßig (niedrige Recency); **verlorene** Kunden haben lange nicht und selten gekauft.
- **Demografisch vs. verhaltensbasiert** sicher zuordnen (RFM = verhaltensbasiert).

## Lernkarten

**F:** Wofür steht RFM?
**A:** Recency (Aktualität des letzten Kaufs), Frequency (Kaufhäufigkeit), Monetary Value (Umsatzvolumen aller Käufe).

**F:** Welche Voraussetzung braucht eine RFM-Analyse?
**A:** Eine gut gepflegte CRM-Datenbank oder Webanalyse-Daten mit dem vergangenen Kaufverhalten jedes einzelnen Kunden.

**F:** Warum ist die Recency so wichtig?
**A:** Kunden, deren letzter Kauf kurz zurückliegt, reagieren mit größerer Wahrscheinlichkeit auf ein neues Angebot als Kunden, deren Kauf lange zurückliegt.

**F:** Ein Kunde erhält R = 7, F = 6, M = 4 (Skala 1–10). Berechnen und bewerten Sie den RFM-Wert.
**A:** 7 + 6 + 4 = 17 bei einer Spanne von 3 bis 30: mittelmäßiger bis guter Kunde.

**F:** Ein Angler hat vor 2 Tagen gekauft (R 9), kauft monatlich (F 9) und hat im Jahr 1.400 € Umsatz (M 10). Welches Segment und welche Maßnahme?
**A:** RFM-Wert 28: Top-Kunde. Maßnahme: Dankeschön, exklusive Vorabinformation zu Neuheiten, VIP-/Treueprogramm statt Rabatt.

**F:** Ein früher sehr umsatzstarker Kunde hat seit 14 Monaten nicht mehr bestellt. Wie stufen Sie ihn ein und was tun Sie?
**A:** Gefährdeter Kunde (niedrige Recency, früher hohe Umsätze). Reaktivierung z. B. per E-Mail "Wir vermissen dich" mit Rabattgutschein (Einwilligung beachten).

**F:** Nennen Sie sechs Kundensegmente der RFM-Analyse laut Material.
**A:** Top-Kunden, aktive Kunden, Kunden mit Potenzial, unsichere Kunden, gefährdete Kunden, Flops.

**F:** Bei welchen Kunden bestehen laut RFM-Analyse Potenziale für Cross- und Upselling?
**A:** Bei Kunden mit Potenzial (Wachstums-Kunden) und unsicheren Kunden (Gelegenheits-Kunden).

**F:** Welche Komponente ergänzt die RFM-Analyse gegenüber demografischen Marketingansätzen?
**A:** Die verhaltensbasierte Komponente (tatsächliches Kaufverhalten).

**F:** Nennen Sie drei Einsatzbereiche der RFM-Analyse.
**A:** Direct Marketing (am häufigsten), E-Mail-Marketing, Kampagnenoptimierung, Performance- und Database-Marketing.

**F:** Wofür können die Ergebnisse einer RFM-Analyse genutzt werden?
**A:** Kundenqualität berechnen, Rücklaufquoten von Kampagnen prognostizieren, ROI erhöhen, Kunden für zielgerichtetes Marketing segmentieren.

**F:** Worin unterscheiden sich RFM-Analyse und Customer Lifetime Value?
**A:** RFM vergibt Punkte für vergangenes Kaufverhalten (Aktualität, Häufigkeit, Umsatz); der CLV berechnet in Euro den Deckungsbeitrag eines Kunden über die gesamte (auch künftige) Kundenbeziehung abzüglich Akquisekosten.

## Bezüge
- LF10_Customer-Lifetime-Value_E-Commerce_OSZHandel1: Kundenwert in Euro berechnen
- LF07_Kundensegmentierung_E-Commerce_OSZHandel1: Segmentierung, ABC-Kundenanalyse als Vergleich
- LF07_Kundentypen-Zielgruppen-Kundensegmentierung_E-Commerce_OSZHandel1: demografische vs. verhaltensbasierte Segmentierung
- LF10_Kennzahlen-zur-Kundenkommunikation-und-Kundenbindung_E-Commerce_OSZHandel1: Kundenbindung messen und steuern
- LF07_Rechtliche-Regelungen-bei-der-Kundenkommunikation_E-Commerce_OSZHandel1: Einwilligung für E-Mail-Werbung
- LF09_Datenschutz_E-Commerce_OSZHandel1: Kaufdaten DSGVO-konform auswerten
- LF10_Analyse-des-Nutzerverhaltens_E-Commerce_OSZHandel1: Kundenverhalten analysieren, ABC-Analyse
