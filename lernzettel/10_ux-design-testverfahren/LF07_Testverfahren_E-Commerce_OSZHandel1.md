# Testverfahren: A/B-Testing und multivariate Tests (LF07, LF07_Testverfahren_E-Commerce_OSZHandel1)
**Prüfungszuordnung:** Teil 2-1 Geschäftsprozesse im E-Commerce > 02 Waren- oder Dienstleistungssortiment mitgestalten und online bewirtschaften > 02 Testmethoden zur laufenden Optimierung des Nutzungsprozesses einsetzen und Ergebnisse auswerten > 03 Testverfahren (Textebene, Stand 2020-08-30; der sichtbare Seitenkopf nennt "Lernfeld 7 – Online-Marketing-Maßnahmen umsetzen und bewerten", Stand 16.03.2022)
**Schwierigkeit:** 2 | **Rechenanteil:** nein (im Material keine Rechnungen; prüfungsübliche Rechnungen unten ergänzt) | **Lernzeit:** ca. 45 Min

## Kerninhalt

### 1. Was sind Testverfahren?
- **Testverfahren** sind Prüfmethoden, mit denen man die Website für den Kunden **noch effizienter** gestaltet.
- **Ziel:** Der Kunde soll **schneller zum Abschluss einer Aktion** kommen bzw. dazu bewegt werden, z. B. zur **Newsletter-Registrierung** oder zum **Kauf**.
- Dazu werden verschiedene Bereiche der Website **analysiert und optimiert**.
- Testverfahren eignen sich für die **Startseite (Main Page)**, **Landingpages**, **Produktdetailseiten** und alle Seiten, die besonders wichtig für **Umsatz** oder **Kundenzufriedenheit** sind.

### 2. A/B-Testing (sehr verbreitete Prüfmethode)
**Ablauf laut Material:**
1. **Ziel definieren:** Mehrere Abteilungen im Unternehmen legen ein Ziel fest. Dann ermittelt man, **welche Seiten** des Webshops zu diesem Ziel beitragen.
2. **Hypothesen aufstellen:** Die Mitarbeiter stellen **begründete Hypothesen** auf, was genau man ändern könnte (z. B. um mehr Conversions zu erzielen).
3. **Traffic aufteilen:** Eine Software teilt den **Live-Traffic per Zufallsprinzip in 2 gleich große Gruppen**. Die Nutzer werden **nicht informiert**, dass sie Teil eines Tests sind.
4. **Varianten ausspielen:** **Gruppe A** und **Gruppe B** sehen **unterschiedliche Versionen**.
5. **Laufen lassen bis zur Signifikanz:** Der Test läuft, bis **genügend Besucher** teilgenommen haben und die Software **statistisch signifikante** Ergebnisse liefern kann. **Wann** ein Ergebnis signifikant ist, legt man **vorher über Parameter** fest. Diese Parameter können das Ergebnis **stark beeinflussen**.
6. **Gewinner ausrollen:** Sind die voreingestellten Werte erreicht, **leitet die Software selbstständig den gesamten Traffic auf die erfolgreichere Variante** um.

**Untersuchte KPIs (Key Performance Indicators):** Downloads, Conversions, Newsletter-Anmeldungen, Absprungrate, Nutzungsdauer.

### 3. Multivariate Tests (MVT)
- Beim A/B-Testing ändert man laut Material **immer nur ein Element zur selben Zeit**. Beim multivariaten Test ändert man **mehrere Elemente gleichzeitig**.
- Man bildet eine **ganze Reihe veränderlicher Variablen** ab und ermittelt, **welche Kombination** aller möglichen Lösungen die **beste Leistung** bringt.
- **Beliebte Variablen:** **Überschriften, Bilder, Buttons**.
- Man misst also die **Effektivität der verschiedenen Element-Kombinationen** für das gesetzte Ziel. Im besten Fall erkennt man sogar, **welche einzelnen Elemente** des erfolgreichsten Designs einen besonders **positiven oder negativen Effekt** auf die Besucher haben.
- **Sinnvoll vor allem** auf Seiten, die von **mehreren Elementen geprägt** sind (Seiten mit **Anmeldeformularen**, **Texte im Header** oder **Fußzeilen**).
- **Nur bei sehr hohem Traffic** sinnvoll bzw. möglich. Grund: Das **faktorielle Testen** verlangt, dass Besucher auf Seiten mit **allen möglichen Kombinationen** umgeleitet werden.
- **Großer Vorteil:** Man findet die Elemente einer Seite, deren Umgestaltung die **größte Wirkung** hat.
- **Größter Nachteil:** der **nötige Traffic**, denn schon wenige änderbare Elemente ergeben schnell **sehr viele Kombinationen**.

### 4. Vergleich A/B-Test und multivariater Test
| Kriterium | A/B-Test | Multivariater Test |
|---|---|---|
| Was wird verändert? | ein Element bzw. eine Version gegen eine andere | mehrere Elemente gleichzeitig, in allen Kombinationen |
| Traffic-Bedarf | geringer | **sehr hoch** (faktorielles Testen) |
| Zeitaufwand | **deutlich geringer** | höher |
| Art der Änderung | auch **radikalere Veränderungen** möglich | Feinoptimierung vieler Einzelelemente |
| Erkenntnis | welche Version besser ist | welche **Kombination** am besten ist und welche Elemente am meisten wirken |
| Typischer Einsatz | einzelne Änderungen; auch bei geringerem Traffic möglich (nur zwei Gruppen müssen genug Besucher bekommen) | Seiten mit vielen Elementen (Formulare, Header, Footer) und sehr viel Traffic |

## Formeln & Rechenwege
🔎 Ergänzung (nicht im Original): Das Material enthält keine Rechnung. Diese Rechnungen kommen in IHK-Aufgaben zu A/B-Tests aber regelmäßig vor.

**1. Conversion-Rate je Variante**
- CR = Conversions ÷ Besucher × 100
- Variablen: Conversions = erreichte Ziele (z. B. Käufe, Newsletter-Anmeldungen); Besucher = Besucher der jeweiligen Variante
- Beispiel: Variante A: 8.000 Besucher, 200 Käufe → 200 ÷ 8.000 × 100 = **2,5 %**. Variante B: 8.000 Besucher, 240 Käufe → **3,0 %**.

**2. Uplift (relative Verbesserung)**
- Uplift = (CR B − CR A) ÷ CR A × 100
- Beispiel: (3,0 − 2,5) ÷ 2,5 × 100 = **20 %** Uplift. Der absolute Unterschied beträgt **0,5 Prozentpunkte**.

**3. Mehrumsatz durch die Gewinnervariante**
- Mehrumsatz = Besucher × (CR B − CR A) × durchschnittlicher Bestellwert
- Beispiel: 30.000 Besucher/Monat × 0,005 × 45 € = **6.750 € Mehrumsatz pro Monat**

**4. Anzahl Kombinationen beim multivariaten Test**
- Kombinationen = Varianten Element 1 × Varianten Element 2 × … (multiplizieren, nicht addieren!)
- Beispiel: 3 Überschriften × 2 Produktbilder × 2 Buttonfarben = **12 Kombinationen**
- Traffic-Bedarf ≈ Kombinationen × Mindestbesucher je Kombination: 12 × 5.000 = **60.000 Besucher**. Ein A/B-Test bräuchte dagegen nur 2 × 5.000 = 10.000.

## Aufgaben aus dem Material
(Das Blatt ist ein kombiniertes Aufgaben-/Lösungsblatt.)

**Aufgabe 1:** Um zu untersuchen, wie effektiv eine beim A/B-Testing getestete Variante ist, analysiert man KPIs. Nennen Sie 3 relevante KPIs.
- **Musterlösung:** Weil es um die Optimierung des Kaufprozesses geht, nimmt man KPIs, an denen man die Zufriedenheit der Kunden erkennt: **Verweildauer**, **Absprungrate**, **Anzahl der Newsletter-Anmeldungen** und **Conversion-Rate** (wie viele Nutzer am Ende kaufen).
- Weitere KPIs aus dem Informationsblatt: **Downloads**, **Nutzungsdauer**.

**Aufgabe 2:** Testverfahren sind zeitaufwändig und teuer. Mit welchem Ziel setzt ein Websitebetreiber sie trotzdem ein?
- **Musterlösung:** Die Tests liefern **eindeutige Ergebnisse** für **fundierte Entscheidungen**. So wird die Website effizienter, und mehr Kunden kaufen. Das investierte Geld soll sich über **bessere Usability** und damit **mehr Umsatz** wieder einspielen.

**Aufgabe 3:** Sie möchten auf Ihrer Website multivariate Tests durchführen. Welche Voraussetzung muss die Website erfüllen?
- **Musterlösung:** Sie braucht **genug (sehr hohen) Traffic**, weil die multivariate Methode mit **faktoriellem Testen** arbeitet (alle Kombinationen müssen genug Besucher bekommen).

**Aufgabe 4:** Was ist der Unterschied zwischen A/B-Testing und multivariaten Testmethoden?
- **Musterlösung:** Beim A/B-Testing sieht der Nutzer **zwei völlig unterschiedliche Seiten**. Beim multivariaten Test wird **eine Seite** aus **vielen Variablen** erstellt, die in **verschiedenen Kombinationen** getestet werden.
- ⚠️ Hinweis: Die Lösung widerspricht dem Informationsblatt ("beim A/B-Testing wird immer nur ein Element zur selben Zeit verändert"). **Prüfungssichere Antwort:** Beim A/B-Test vergleicht man eine **Kontrollversion (A)** mit **einer veränderten Version (B)**. Ändert man nur **ein Element**, kann man den Effekt eindeutig diesem Element zuordnen. Man kann auch **zwei komplett verschiedene Seiten** gegeneinander testen (radikale Veränderung), weiß dann aber nicht, **welches Element** den Unterschied verursacht hat. Beim multivariaten Test verändert man **mehrere Elemente gleichzeitig** und verteilt den Traffic auf **alle Kombinationen**. Man erfährt, welche Kombination am besten ist und wie stark die einzelnen Elemente wirken. Dafür braucht man **deutlich mehr Traffic**.

**Aufgabe 5:** Sie möchten als Webshopbetreiber Ihren Check-out optimieren. Welches Testverfahren ist sinnvoller?
- **Musterlösung:** Bei **genügend Traffic** der **multivariate Test**, weil der Check-out aus **vielen verschiedenen Elementen und Anmeldeformularen** besteht und man so präzisere Ergebnisse bekommt.
- ⚠️ Hinweis: Die Antwort gilt nur **unter der Bedingung "genügend Traffic"**, und diese Bedingung muss man in der Prüfung **ausdrücklich nennen**. Den Check-out erreichen nur Besucher mit gefülltem Warenkorb, er hat also meist **viel weniger Traffic** als Start- oder Kategorieseiten. Reicht der Traffic nicht für alle Kombinationen, testet man besser **einzelne Elemente nacheinander per A/B-Test** (z. B. Gastbestellung ja/nein, Reihenfolge der Zahlungsarten).

**Aufgabe 6:** Sie möchten in Ihrem Unternehmen A/B-Testing durchführen. Was sollten Sie als Erstes tun?
- **Musterlösung:** **Noch bevor** man eine Software sucht, setzt man sich mit **verschiedenen Abteilungen** zusammen und klärt, **was** optimiert werden soll, **wo** getestet wird und **welche Werte** man verändern bzw. erreichen will. Tests sollen immer **gezielt**, auf Basis von **Hypothesen oder Anregungen**, und **nie wahllos** stattfinden.

## Ergänzungen & Aktualisierungen
- ⚠️ Hinweis (Fehler im Material): Beim multivariaten Test wird der Traffic **nicht** "wieder auf zwei Versionen" aufgeteilt, sondern auf **so viele Versionen, wie es Kombinationen gibt** (z. B. 2 × 2 × 2 = 8). Genau deshalb ist der Traffic-Bedarf so hoch.
- 🔎 Ergänzung (nicht im Original): **Weitere Testformen**
  - **A/B/n-Test:** eine Kontrollversion gegen **mehrere** Varianten (A, B, C, …). Mehr Varianten brauchen mehr Traffic (siehe LF07_Testgröße).
  - **Split-URL-Test (Redirect-Test):** Die Besucher werden auf **zwei unterschiedliche URLs** bzw. komplett verschiedene Seiten verteilt. Das ist geeignet für radikale Redesigns.
- 🔎 Ergänzung (nicht im Original): **Gute Hypothese nach dem Muster "Wenn …, dann …, weil …"**. Beispiel: "Wenn wir auf der Produktseite für Hechtwobbler ein Bild des Köders im Wasser statt eines Freistellers zeigen, steigt die Add-to-Cart-Rate, weil Kunden das Laufverhalten besser einschätzen können."
- 🔎 Ergänzung (nicht im Original): **Optimierungskreislauf:** Analyse (Webanalyse, Heatmaps, Kundenfeedback) → Ziel und Hypothese → Varianten erstellen → Test durchführen → statistisch auswerten → Gewinner umsetzen → nächster Test.
- 🔎 Ergänzung (nicht im Original): **Recht:** A/B-Testing-Tools speichern in der Regel Informationen auf dem Endgerät (Cookie/Local Storage). Dafür ist nach **§ 25 TDDDG** (bis 13.5.2024: TTDSG) meist eine **Einwilligung** nötig. Vorsicht bei **Preistests**: Werden Preise auf Grundlage einer **automatisierten Entscheidungsfindung personalisiert**, muss der Händler Verbraucher seit 28.5.2022 darauf **hinweisen** (Art. 246a § 1 Abs. 1 Satz 1 Nr. 6 EGBGB). Bei Preisermäßigungen gilt zusätzlich § 11 PAngV (Angabe des niedrigsten Preises der letzten 30 Tage).

## Prüfungsfallen
- **Erster Schritt** beim A/B-Testing ist **Ziel und Hypothese mit den Abteilungen festlegen**, nicht die Software-Auswahl.
- **A/B = ein Element** (Ursache eindeutig zuordenbar); **MVT = mehrere Elemente gleichzeitig** (Kombinationen). Komplett unterschiedliche Seiten sind ebenfalls ein A/B-Test (radikal), dann ist die Ursache aber unklar.
- **Traffic:** MVT braucht **sehr viel** Traffic. Bei wenig Traffic ist ein A/B-Test die richtige Wahl. A/B ist außerdem **schneller**.
- **Zufallsprinzip und gleich große Gruppen**; die Nutzer werden **nicht informiert**.
- **Signifikanz wird vorher über Parameter festgelegt**, und diese Parameter beeinflussen das Ergebnis stark.
- **Kombinationen multiplizieren** (3 × 2 × 2 = 12), nicht addieren (3 + 2 + 2 = 7).
- **Uplift relativ vs. Prozentpunkte:** Von 2,5 % auf 3,0 % sind **+0,5 Prozentpunkte**, das ist **+20 %**.
- **Check-out-Frage:** Die Antwort MVT immer mit der Bedingung **"wenn genug Traffic vorhanden"** verbinden.
- KPIs für Testverfahren aufzählen können: **Downloads, Conversions, Newsletter-Anmeldungen, Absprungrate, Nutzungsdauer/Verweildauer**.

## Lernkarten

**F:** Was versteht man unter Testverfahren im E-Commerce, und wo setzt man sie ein?
**A:** Prüfmethoden, mit denen man Bereiche der Website analysiert und optimiert, damit Kunden schneller eine Aktion abschließen (Kauf, Newsletter-Anmeldung). Einsatz auf Startseite, Landingpages, Produktdetailseiten und allen umsatz- oder zufriedenheitsrelevanten Seiten.

**F:** Beschreiben Sie den Ablauf eines A/B-Tests in fünf Schritten.
**A:** (1) Ziel mit den Abteilungen festlegen und relevante Seiten bestimmen. (2) Begründete Hypothesen aufstellen. (3) Software teilt den Live-Traffic zufällig in zwei gleich große Gruppen, ohne die Nutzer zu informieren. (4) Gruppe A und B sehen unterschiedliche Versionen, der Test läuft bis zur vorher festgelegten Signifikanz. (5) Die erfolgreichere Variante bekommt den gesamten Traffic.

**F:** Nennen Sie fünf KPIs, an denen man den Erfolg einer Testvariante misst.
**A:** Conversions bzw. Conversion-Rate, Newsletter-Anmeldungen, Absprungrate, Nutzungs-/Verweildauer und Downloads.

**F:** Was ist ein multivariater Test?
**A:** Ein Test, bei dem mehrere Elemente einer Seite (z. B. Überschrift, Bild, Button) gleichzeitig in verschiedenen Ausprägungen verändert werden. Alle Kombinationen werden getestet, um die beste Kombination und die wirksamsten Elemente zu finden.

**F:** Nennen Sie den größten Vorteil und den größten Nachteil multivariater Tests.
**A:** Vorteil: Man erkennt, welche Elemente durch Umgestaltung die größte Wirkung erzielen. Nachteil: Der Traffic-Bedarf ist sehr hoch, weil die Zahl der Kombinationen schnell wächst.

**F:** Welche zwei Vorteile hat A/B-Testing gegenüber multivariaten Tests?
**A:** Es sind radikalere Veränderungen möglich, und der Zeitaufwand ist deutlich geringer (es wird weniger Traffic benötigt).

**F:** Was sollten Sie als Allererstes tun, wenn im Unternehmen A/B-Tests eingeführt werden sollen?
**A:** Mit den Abteilungen klären, was optimiert werden soll, wo getestet wird und welche Werte man erreichen will. Daraus leitet man Hypothesen ab. Erst danach sucht man eine Software. Tests nie wahllos durchführen.

**F:** Euer Angelshop hat wenig Traffic, möchte aber die Produktseite für Ruten optimieren (Überschrift, Bild und Button). Welches Verfahren empfehlen Sie?
**A:** Einen A/B-Test, bei dem die Elemente nacheinander einzeln getestet werden. Für einen multivariaten Test reicht der Traffic nicht, weil sich die Besucher auf alle Kombinationen verteilen müssten.

**F:** Ein MVT testet 2 Überschriften, 3 Bilder und 2 Buttons. Wie viele Kombinationen entstehen? Wie viele Besucher braucht man bei 4.000 Besuchern je Kombination?
**A:** 2 × 3 × 2 = 12 Kombinationen; 12 × 4.000 = 48.000 Besucher.

**F:** Variante A: 12.000 Besucher, 300 Bestellungen. Variante B: 12.000 Besucher, 360 Bestellungen. Berechnen Sie die Conversion-Raten und den Uplift.
**A:** CR A = 300 ÷ 12.000 = 2,5 %; CR B = 360 ÷ 12.000 = 3,0 %. Uplift = (3,0 − 2,5) ÷ 2,5 = 20 % (absolut +0,5 Prozentpunkte). B gewinnt, sofern das Ergebnis signifikant ist.

**F:** Warum sind die vom Tester hinterlegten Parameter beim A/B-Test so wichtig?
**A:** Sie legen fest, ab wann ein Ergebnis als signifikant gilt und die Software den Traffic auf die Gewinnervariante umleitet. Falsche Parameter können zu falschen Entscheidungen führen.

**F:** Warum lohnen sich Testverfahren trotz Zeitaufwand und Kosten?
**A:** Sie liefern eindeutige Daten für fundierte Entscheidungen. Über eine bessere Usability und mehr Käufe holt man die Investition durch Mehrumsatz wieder herein.

**F:** Was ist am Satz "Beim multivariaten Test wird der Traffic auf zwei Versionen aufgeteilt" falsch?
**A:** Der Traffic wird auf alle möglichen Kombinationen verteilt (z. B. 2 × 2 × 2 = 8 Versionen), nicht nur auf zwei.

## Bezüge
- LF07_Testgröße_E-Commerce_OSZHandel1: benötigter Traffic je Variante, Testdauer
- LF02_Testumgebung_E-Commerce_OSZHandel1: Live-Test vs. Sandbox, Voraussetzungen
- LF07_Landingpage_E-Commerce_OSZHandel1: A/B-Tests zur Landingpage-Optimierung
- LF07_Conversion-Funnel_E-Commerce_OSZHandel1: Conversion Rate als Grundlage für A/B-Tests
- LF03_Micro-conversion_E-Commerce_OSZHandel1: Newsletter-Anmeldung als Testziel
- LF09_Nutzerprofile_E-Commerce_OSZHandel1: A/B-Tests für neue Vertriebskanäle
- LF09_UX-Design_E-Commerce_OSZHandel1: Usability und CTA-Gestaltung als Testobjekte
