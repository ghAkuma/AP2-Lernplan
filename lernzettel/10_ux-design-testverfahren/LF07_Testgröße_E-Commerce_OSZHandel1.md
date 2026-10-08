# Test-Größe beim A/B-Testing (LF07, LF07_Testgröße_E-Commerce_OSZHandel1)
**Prüfungszuordnung:** Teil 2-1 Geschäftsprozesse im E-Commerce > 02 Waren- oder Dienstleistungssortiment mitgestalten und online bewirtschaften > 02 Testmethoden zur laufenden Optimierung des Nutzungsprozesses einsetzen und Ergebnisse auswerten > 02 Test-Größe (Textebene, Stand 2020-08-30; der sichtbare Seitenkopf nennt "Lernfeld 7 – Online-Marketing-Maßnahmen umsetzen und bewerten", Stand 16.03.2022)
**Schwierigkeit:** 2 | **Rechenanteil:** ja | **Lernzeit:** ca. 40 Min

## Kerninhalt

### 1. Was ist die Test-Größe?
- Die **Test-Größe** ist die **Anzahl an Besuchern (Visitors), die getestet werden müssen**.
- **Je mehr Varianten** ausgespielt werden, **desto mehr Traffic** braucht man, um ein Ergebnis ablesen zu können.
- **Je größer die Test-Größe, desto genauer** sind die Aussagen.
- Die Test-Größe hängt vom **Traffic einer Seite** ab, getestet wird deshalb **nur im Frontend** (dort, wo Besucher die Seite sehen).

### 2. Wovon hängt ab, wie schnell die Test-Größe erreicht ist?
| Einflussfaktor | Wirkung |
|---|---|
| Traffic der Seite | viel Traffic → Test-Größe **schneller** erreicht |
| Position des Elements | **below the fold** (erst nach Scrollen sichtbar) → **später** erreicht als **above the fold** (sofort sichtbar) |
| Beispiel 1 | Banner oben auf der stark besuchten Startseite → Ergebnis nach **einigen Tagen** |
| Beispiel 2 | Element auf der wenig besuchten Karriereseite → kann **mehrere Monate** dauern |
| Laufzeit-Rhythmus | Test im **7-Tage-Rhythmus** laufen lassen, damit sich Abweichungen durch das **Wochenende** ausgleichen |

### 3. Test-Größe im A/B-Testing
- Hier bedeutet Test-Größe den **Zeitpunkt, ab dem genügend Besucher getestet wurden**, damit sich die Software **für eine Version entscheidet**.
- Die **A/B-Software schätzt selbst ein**, wann genug Daten für eine Auswertung vorliegen.
- Diese **Schwelle legt jede Software unterschiedlich** fest.

### 4. Beispielberechnung aus dem Material
- Monatlicher Traffic: **200.000 Besucher**
- Haupt-Conversion-Rate: **3 %** → 200.000 × 0,03 = **6.000 Bestellungen**
- Gewünschte Verbesserung: **15 %** bei einer **Signifikanz von 95 %**
- Benötigter Traffic **je Testvariante** (Kontrollgruppe und Variante): **ca. 37.363 Besucher**
- Laufzeit: **ca. 2 Wochen**, bis der Test **stabil**, also statistisch relevant ist und ausgewertet werden kann

### 5. Statistische Validität
Ein A/B-Test liefert dann **statistisch valide** (gültige) Aussagen, wenn
1. die **Zuverlässigkeit** und die **Teststärke** der A/B-Testing-Software **hoch** sind,
2. die **Fehlervarianz begrenzt** wurde und
3. die **mathematischen Annahmen** der statistischen Methoden **nicht verletzt** wurden.

## Formeln & Rechenwege

**1. Bestellungen (Conversions)**
- Conversions = Besucher × Conversion-Rate
- Variablen: Besucher = Anzahl Visits/Visitors im Zeitraum; Conversion-Rate (CR) = Anteil der Besucher, die das Ziel erreichen (z. B. Kauf)
- Beispiel: 200.000 × 3 % = 6.000 Bestellungen

**2. Ziel-Conversion-Rate bei relativer Verbesserung**
- CR neu = CR alt × (1 + Verbesserung)
- Beispiel: 3 % × 1,15 = **3,45 %** (Unterschied: **0,45 Prozentpunkte**, nicht 15 Prozentpunkte)

**3. Benötigter Gesamt-Traffic**
- Gesamt-Traffic = Besucher je Variante × Anzahl Varianten (inkl. Kontrollvariante)
- Beispiel: 37.363 × 2 = **74.726 Besucher**

**4. Testdauer**
- Besucher pro Tag = Monatstraffic ÷ 30
- Testdauer (Tage) = Gesamt-Traffic ÷ (Besucher pro Tag × Anteil des Traffics im Test)
- Danach **auf volle Wochen aufrunden** (7-Tage-Rhythmus)
- Beispiel: 200.000 ÷ 30 ≈ 6.667 Besucher/Tag → 74.726 ÷ 6.667 ≈ **11,2 Tage** → aufgerundet **14 Tage = 2 Wochen** ✔ (passt zum Material)
- Variante: Sieht nur **50 %** der Besucher das getestete Element (z. B. below the fold), gilt 74.726 ÷ (6.667 × 0,5) = 74.726 ÷ 3.333,5 ≈ 22,4 Tage → aufgerundet **28 Tage = 4 Wochen**.
- Achtung beim Aufrunden: Schon minimal mehr als volle Wochen bedeutet eine Woche mehr. Beispiel 40 %: 74.726 ÷ (6.667 × 0,4) ≈ 28,02 Tage → nicht 4, sondern **5 Wochen (35 Tage)**.

**5. Zusammenhänge (ohne Formel), die man kennen sollte** 🔎 Ergänzung (nicht im Original):
- **kleinerer erwarteter Effekt** → **viel mehr** Besucher nötig (halber Effekt ≈ **vierfache** Stichprobe)
- **niedrigere Basis-Conversion-Rate** → mehr Besucher nötig
- **höheres Konfidenzniveau oder höhere Teststärke** → mehr Besucher nötig
- **mehr Varianten** → mehr Besucher insgesamt

## Aufgaben aus dem Material

**Aufgabe 1:** Was ist eine Test-Größe?
- **Musterlösung:** Die **Menge an zu testenden Visitors** (Besuchern).

**Aufgabe 2:** Wie groß muss die Test-Größe sein?
- **Musterlösung:** Das kann man **nicht pauschal** sagen. Es hängt vom **Testobjekt und seiner Umgebung** ab (**welche Seite** der Website, **wo auf der Seite**).
- Ergänzend: außerdem von der **Basis-Conversion-Rate**, dem **erwarteten Effekt**, dem **Signifikanzniveau** und der **Anzahl der Varianten**.

**Aufgabe 3:** Woran bestimmt man die Test-Größe?
- **Musterlösung:** Daran, **mit wie viel Traffic** beim zu testenden Objekt zu rechnen ist (welche Seite, wo auf der Seite).

**Aufgabe 4:** Was ist beim A/B-Testing zu beachten?
- **Musterlösung:** Die Software ist so programmiert, dass sie die **Test-Größe selbst bestimmt**.
- ⚠️ Hinweis: Diese Antwort ist für eine IHK-Prüfung zu knapp. Ergänzen: Die **Schwelle ist je Software unterschiedlich**, und die vom Tester **hinterlegten Parameter** (z. B. Signifikanzniveau) beeinflussen das Ergebnis (siehe LF07_Testverfahren). Der Test soll in **vollen 7-Tage-Rhythmen** laufen. Traffic und **Position des Elements** (above/below the fold) bestimmen die Laufzeit. Mehr Varianten brauchen mehr Traffic.

**Aufgabe 5:** Welche Aussagen zur statistischen Validität treffen zu?
- a) Die Zuverlässigkeit des Tests ist wichtig.
- b) Damit eine statistische Validität zustande kommt, muss die Fehlervarianz reduziert worden sein.
- c) Die Test-Größe muss hoch sein.
- d) Die mathematischen Regeln sind irrelevant.
- **Musterlösung:** **a, b und c** treffen zu.
- Begründung: a) Zuverlässigkeit ist eine Bedingung. b) Die Fehlervarianz muss begrenzt sein. c) Eine große Test-Größe macht die Aussage genauer und erhöht die im Infoblatt geforderte **Teststärke** (mehr Besucher → ein echter Effekt wird eher erkannt). d) ist **falsch**, denn die mathematischen Annahmen dürfen **nicht verletzt** werden.

**Infodatei-Idee aus dem Material:** Man klebt ein kleines Gewicht auf eine Seite einer Münze und wirft sie erst 5-mal, dann 50-mal, dann 500-mal. Mit mehr Würfen zeigt sich die Verzerrung immer deutlicher. Genauso werden Testergebnisse mit größerer Test-Größe genauer.

## Ergänzungen & Aktualisierungen
- ⚠️ Hinweis zur Beispielzahl 37.363: Die Zahl lässt sich **nicht eindeutig nachrechnen**, weil das Material die **Teststärke** nicht angibt und das Ergebnis vom verwendeten Stichprobenrechner abhängt. Mit der klassischen Formel (Basis 3 %, +15 % relativ, 95 % Konfidenz, zweiseitig) ergeben sich je Variante ca. **24.200** Besucher bei 80 % Teststärke, ca. **32.400** bei 90 % und ca. **40.000** bei 95 %. **Für die Prüfung:** Die benötigte Besucherzahl wird in der Regel **vorgegeben**. Rechnen musst du vor allem **Gesamt-Traffic und Testdauer**.
- 🔎 Ergänzung (nicht im Original): **Begriffe**
  - **Signifikanz / Konfidenzniveau 95 %:** Man nimmt eine **Irrtumswahrscheinlichkeit von höchstens 5 %** in Kauf (Signifikanzniveau α = 5 %): Das Risiko, einen nur **zufälligen** Unterschied fälschlich für einen echten Effekt zu halten, liegt bei höchstens 5 %. Prüfungsübliche Kurzform: "Das Ergebnis ist mit 95 % Sicherheit kein Zufall."
  - **Teststärke (Power):** die Wahrscheinlichkeit, dass ein **tatsächlich vorhandener** Effekt auch **erkannt** wird (üblich: 80 %).
  - **Fehlervarianz:** Streuung der Ergebnisse durch **Störfaktoren** (z. B. Wochentag, Feiertage, parallele Werbekampagnen, Saison wie Start der Raubfischsaison). Man begrenzt sie durch Zufallsverteilung, volle Wochen und möglichst wenige parallele Änderungen.
  - **Above the fold:** der Bereich einer Seite, der **ohne Scrollen** sichtbar ist. **Below the fold:** erst nach Scrollen sichtbar. Auf dem Smartphone ist dieser Bereich deutlich kleiner als am Desktop.
- 🔎 Ergänzung (nicht im Original): **Test nicht zu früh abbrechen.** Wer laufend nachsieht und beim ersten "Sieg" stoppt, bekommt häufig **Zufallsergebnisse**. Erst bei erreichter Test-Größe bzw. Signifikanz auswerten.
- 🔎 Ergänzung (nicht im Original): **Gütekriterien** von Tests und Befragungen: **Objektivität** (unabhängig vom Durchführenden), **Reliabilität** (= Zuverlässigkeit: bei Wiederholung gleiches Ergebnis), **Validität** (= Gültigkeit: misst, was gemessen werden soll).

## Prüfungsfallen
- **Test-Größe = Besucher (Visitors)**, nicht Conversions. In LF02_Testumgebung bezieht sich die Faustregel "500 pro Monat" dagegen auf **Conversions**. Nicht verwechseln!
- **"je Testvariante":** Gesamtbedarf = Wert × Anzahl der Varianten (A **und** B). Beim A/B-Test also mal 2, beim A/B/C-Test mal 3.
- **Relativ vs. absolut:** +15 % auf 3 % CR ergibt **3,45 %**, nicht 18 %.
- **Testdauer immer auf volle Wochen aufrunden** (7-Tage-Rhythmus wegen Wochenende): 11,2 Tage werden 14 Tage, 28,02 Tage werden 35 Tage (nicht 28).
- **Above vs. below the fold:** Elemente unten auf der Seite werden von weniger Besuchern gesehen, die Test-Größe wird **später** erreicht.
- **Signifikanz 95 %** bedeutet **5 %** Irrtumswahrscheinlichkeit, nicht "95 % der Besucher".
- **Aussage d) bei der Validität ist falsch:** Mathematische Annahmen sind sehr wohl relevant.
- **Validität ≠ Zuverlässigkeit (Reliabilität):** Die Zuverlässigkeit ist eine Voraussetzung für Validität, aber nicht dasselbe.

## Lernkarten

**F:** Was versteht man unter der Test-Größe?
**A:** Die Anzahl an Besuchern (Visitors), die getestet werden müssen, damit ein aussagekräftiges Ergebnis entsteht. Beim A/B-Testing ist das der Zeitpunkt, ab dem die Software genug Daten hat, um sich für eine Version zu entscheiden.

**F:** Nennen Sie drei Faktoren, die beeinflussen, wie schnell die Test-Größe erreicht wird.
**A:** Der Traffic der getesteten Seite, die Position des Elements (above oder below the fold) und die Anzahl der Varianten (mehr Varianten brauchen mehr Traffic).

**F:** Warum soll ein A/B-Test im 7-Tage-Rhythmus laufen?
**A:** Damit sich Abweichungen durch das Wochenende bzw. unterschiedliches Verhalten an verschiedenen Wochentagen ausgleichen.

**F:** Ein Banner oben auf der Startseite und ein Element auf der Karriereseite werden getestet. Welcher Test liefert schneller ein Ergebnis und warum?
**A:** Das Startseiten-Banner, weil die Startseite viel mehr Traffic hat und das Banner above the fold liegt. Der Test kann nach einigen Tagen fertig sein, auf der Karriereseite eventuell erst nach Monaten.

**F:** Ein Shop hat 200.000 Besucher pro Monat und eine CR von 3 %. Wie viele Bestellungen sind das, und welche CR wird bei +15 % angestrebt?
**A:** 200.000 × 0,03 = 6.000 Bestellungen. Ziel-CR = 3 % × 1,15 = 3,45 %.

**F:** Je Variante werden 37.363 Besucher benötigt (A/B-Test), der Shop hat 200.000 Besucher pro Monat. Wie lange läuft der Test?
**A:** Gesamt 2 × 37.363 = 74.726. Pro Tag 200.000 ÷ 30 ≈ 6.667. Dauer 74.726 ÷ 6.667 ≈ 11,2 Tage, auf volle Wochen aufgerundet also 2 Wochen.

**F:** Euer Angelshop hat 60.000 Besucher pro Monat. Der Stichprobenrechner verlangt 15.000 Besucher je Variante, getestet werden drei Varianten einer Produktseite für Wobbler, die nur 25 % aller Besucher aufrufen. Wie lange dauert der Test?
**A:** Gesamt 3 × 15.000 = 45.000. Besucher im Test pro Tag: 60.000 ÷ 30 × 0,25 = 500. Dauer 45.000 ÷ 500 = 90 Tage, also rund 13 volle Wochen (91 Tage). Das ist zu lang: Man sollte die Varianten reduzieren oder auf einer Seite mit mehr Traffic testen.

**F:** Unter welchen Bedingungen gilt ein A/B-Test als statistisch valide?
**A:** Wenn Zuverlässigkeit und Teststärke der Software hoch sind, die Fehlervarianz begrenzt ist und die mathematischen Annahmen der statistischen Methoden nicht verletzt wurden.

**F:** Was bedeutet "Signifikanz von 95 %" (so das Material; fachlich korrekt: Konfidenzniveau 95 %, Signifikanzniveau α = 5 %)?
**A:** Die Irrtumswahrscheinlichkeit (das Signifikanzniveau) beträgt höchstens 5 %: Das Risiko, einen nur zufälligen Unterschied zwischen den Varianten fälschlich als echten Effekt zu werten, liegt bei höchstens 5 % (Kurzform: Das Ergebnis ist mit 95 % Sicherheit kein Zufall).

**F:** Was bedeutet "below the fold" und welche Folge hat es für einen Test?
**A:** Das Element ist erst nach dem Scrollen sichtbar. Es sehen also weniger Besucher, und die nötige Test-Größe wird später erreicht.

**F:** Wer legt beim A/B-Testing fest, wann genug Daten vorliegen?
**A:** Die A/B-Testing-Software schätzt das anhand der hinterlegten Parameter selbst ein. Die Schwelle ist bei jeder Software unterschiedlich.

**F:** Warum braucht ein Test mit mehr Varianten mehr Traffic?
**A:** Der Traffic verteilt sich auf mehr Gruppen. Jede Variante braucht für eine sichere Aussage ihre eigene Mindestzahl an Besuchern.

## Bezüge
- LF02_Testumgebung_E-Commerce_OSZHandel1: 500 Conversions, Testdauer zwei Monate
- LF07_Testverfahren_E-Commerce_OSZHandel1: A/B- und multivariate Tests, Traffic-Bedarf
- LF07_Landingpage_E-Commerce_OSZHandel1: above/below the fold, CTA-Tests
- LF07_Conversion-Funnel_E-Commerce_OSZHandel1: Conversion Rate als Testgrundlage
- LF09_Kennzahlen-im-E-Commerce_E-Commerce_OSZHandel1: Traffic- und Conversion-Kennzahlen auswerten
- LF03_Micro-conversion_E-Commerce_OSZHandel1: Micro-Conversions als messbare Testziele
