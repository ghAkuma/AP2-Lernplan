# Testumgebung: Sandbox und Live-Test (LF02, LF02_Testumgebung_E-Commerce_OSZHandel1)
**Prüfungszuordnung:** Teil 2-1 Geschäftsprozesse im E-Commerce > 02 Waren- oder Dienstleistungssortiment mitgestalten und online bewirtschaften > 02 Testmethoden zur laufenden Optimierung des Nutzungsprozesses einsetzen und Ergebnisse auswerten > 01 Testumgebung (laut Textebene, Stand 2020-08-30; der sichtbare Seitenkopf nennt dagegen "Lernfeld 10 – Den Online-Vertrieb kennzahlengestützt optimieren", Stand 16.03.2022)
**Schwierigkeit:** 1 | **Rechenanteil:** ja (nur Umrechnung von Conversions auf den Monat) | **Lernzeit:** ca. 30 Min

## Kerninhalt

### 1. Was ist eine Testumgebung?
- **Testumgebung** = ein Ort, an dem man **unabhängig von der Live-Umgebung** Versuche durchführt.
- Laufen **mehrere Tests gleichzeitig**, muss man die Testkennzahlen und -ergebnisse sauber getrennt verwalten. Sonst beeinflussen sich die Tests gegenseitig und die Daten werden verfälscht.

**Sandbox** (im E-Commerce die übliche Testumgebung):
- **exakte Kopie des Live-Shops**
- Änderungen sind möglich, **ohne negative Folgen** für den Live-Shop; im Notfall stellt man die Live-Version wieder her
- gefallen die Änderungen den Zuständigen, werden sie **einfach in den Live-Shop übernommen**
- **Zugriff nur für ausgewählte Mitarbeiter**, die den Shop optimieren; **für Außenstehende nicht einsehbar**
- besteht **dauerhaft** und wird im besten Fall **durchgängig** zur Optimierung genutzt

Im Material steht selbst der Hinweis, dass ein Teil fehlt: der Testbereich, der neue Tools, Updates, Features oder Designs **zunächst ohne Kunden** daraufhin prüft, ob der Shop **noch funktioniert**. Diesen Teil behandelt LF09_Testumgebung (DEV/Staging).

**Live-Test im Live-Shop:**
- Testverfahren gehen auch **direkt im Live-Shop**, z. B. mit **A/B-Testing**: Mehrere Versionen des Shops sind live, jeder Besucher (Visitor) bekommt **zufällig** eine Variante zu sehen.
- An den Ergebnissen (messbar z. B. über **KPIs**) sieht man, wie erfolgreich jede Variante war und welche man übernimmt.

| Merkmal | Sandbox | Live-Test (z. B. A/B-Test) |
|---|---|---|
| Ort | Kopie des Live-Shops | echter Live-Shop |
| Wer sieht es? | nur ausgewählte Mitarbeiter | echte Besucher/Kunden (zufällige Variante) |
| Risiko für das Tagesgeschäft | keins (Live-Version wiederherstellbar) | gering, aber echte Kunden sind beteiligt |
| Zweck | Änderungen gefahrlos bauen und prüfen | Wirkung von Varianten auf das echte Nutzerverhalten messen (KPIs) |

### 2. Voraussetzungen für Testverfahren
1. Das **Testinstrument** ist korrekt in die Website **implementiert** und die Mitarbeiter **beherrschen** es.
2. Es gibt eine **gute Verbindung zwischen Testing-Tool und Webanalyse-Software**.
3. Das **Testing-Team** arbeitet eng mit **Webdesignern, Programmierern und Textern** zusammen.
4. Die **Führungsspitze** ist **offen für Testverfahren**.

### 3. Testgröße und Testdauer
- **Je größer die Testgruppe, desto genauer** sind die Aussagen.
- Faustregel: Der Webshop sollte **mindestens 500 Conversions pro Monat** haben.
- Richtwert für die **Testdauer: durchschnittlich zwei Monate**. Man setzt **strenge Deadlines**. Gibt es nach zwei Monaten noch keine aussagekräftigen, **signifikanten** Ergebnisse, stellt man **Konzeption und Sinn des Tests infrage** und setzt ihn ggf. neu auf.
- Man fragt die relevanten **Kennzahlen und das Konfidenzniveau regelmäßig** ab. So kann man einschätzen, ob der Test im gewünschten Zeitraum ein Ergebnis liefert.

### 4. UX (User Experience)
- Der Kunde soll **nicht merken**, dass er an einem Test teilnimmt, sonst **ändert sich sein Nutzerverhalten** und das Ergebnis wird verfälscht.
- **Ziel:** Nach dem Test ist die User Experience der eigenen Website besser geworden.

### 5. Testdaten
- **Drei Arten:** **Eingabedaten**, **Abrufdaten/Zugriffsdaten**, **erzeugte Daten**.
- Testdaten und **Testfälle** müssen **genau zueinander passen**; unbeabsichtigtes Verändern der Daten vermeiden.
- Testdaten müssen **datenlogisch konsistent** sein (Beispiel: Bestelldaten passen zu den Kunden- und Artikeldaten), und zwar **auch plattformübergreifend**.
- **Testdatenvolumen: so klein wie möglich, so groß wie nötig**, damit Testaufwand und Testkontrollen effizient bleiben.
- Ändert sich die **Datenstruktur**, muss man die Testdaten ggf. strukturell an die **neue Programmversion** anpassen.

### 6. Preise
- Die **Sandbox** ist bei fast jedem Shopsystem **kostenlos dabei**.
- Der Preis für das Shopsystem selbst hängt von Anbieter und Edition ab: von **kostenlosen Versionen** bis zu **Enterprise-Editionen für mehrere Tausend Euro**.

## Formeln & Rechenwege

**Conversions pro Monat** (für die Faustregel "mindestens 500 Conversions/Monat"):
- aus Jahreswerten: Conversions/Monat = Conversions/Jahr ÷ 12
- aus Tageswerten: Conversions/Monat ≈ Conversions/Tag × 30 (genauer: × 365 ÷ 12 = × 30,42)
- Entscheidung: Ergebnis ≥ 500 → Shop ist für einen Live-Test geeignet

Mini-Beispiel: Ein Angelshop hat 7.200 Bestellungen im Jahr → 7.200 ÷ 12 = 600 Conversions/Monat ≥ 500 → geeignet.

**Rückrechnung eines Grundwerts aus einer Prozentsteigerung** (für Ablenker-Angaben):
- Grundwert = aktueller Wert ÷ (1 + Steigerung in Dezimal)
- Beispiel: 200 Conversions sind 16 % über dem Vorjahresdurchschnitt → 200 ÷ 1,16 ≈ 172 Conversions im Vorjahresmonat.

## Aufgaben aus dem Material

**Aufgabe 1:** Beschreiben Sie, was man im E-Commerce unter einer Testumgebung versteht.
- **Musterlösung:** Ein Ort, an dem man **Änderungen am Shop ohne Wissen oder Einsicht Außenstehender** vornehmen kann, z. B. die **Sandbox** oder **A/B-Testing/Multitesting**.
- ⚠️ Hinweis: Die Lösung vermischt zwei Dinge. Bei A/B-Tests sehen echte Kunden die Varianten (sie merken es nur nicht). Bessere Antwort: Eine Testumgebung ist eine **vom Live-Betrieb getrennte Kopie des Shops** (Sandbox), in der man Änderungen gefahrlos testet. **Zusätzlich** gibt es **Live-Tests** wie A/B- oder multivariate Tests im echten Shop mit zufällig verteiltem Traffic.

**Aufgabe 2:** Erläutern Sie, wann eine Testumgebung genutzt wird.
- **Musterlösung:** Um **einzelne Komponenten des Shops zu verbessern**. Im besten Fall wird sie **durchgehend** genutzt, weil ständig Optimierungen nötig sind. Alternative Antwort: wenn die **Conversions erhöht** oder die **Absprungrate gesenkt** werden soll usw.
- Ergänzend aus LF09_Testumgebung: immer dann, wenn man arbeiten und testen will, **ohne das Tagesgeschäft zu stören** (sonst müsste man den Shop offline nehmen).

**Aufgabe 3:** Welche Arten von Testumgebungen gibt es im E-Commerce?
- **Musterlösung:** Sandbox, Live-Shop.
- ⚠️ Hinweis: Der Live-Shop ist eigentlich keine Testumgebung, sondern der Ort für **Live-Tests** (A/B-Tests). Vollständiger nach LF09_Testumgebung: **Development-Umgebung (DEV)**, **Staging-Umgebung** (ggf. mehrere, auch automatisierte Testumgebungen) und **Production** (Live). Für die Prüfung beide Sichtweisen kennen.

**Aufgabe 4:** Kreuzen Sie an, welcher Shop sich für einen Live-Test eignet.
- ☐ Die Hauer AG hat ca. 9.450 Conversions im Jahr.
- ☐ Die Laher GmbH hat über ihren Online-Shop täglich mindestens 17 Neukunden.
- ☐ Mit ca. 200 Conversions ist die Daylo UG 16 % über dem monatlichen Durchschnitt vom letzten Jahr.

**Musterlösung** (selbst nachgerechnet, Maßstab: mindestens 500 Conversions/Monat):

| Shop | Rechnung | Conversions/Monat | Geeignet? |
|---|---|---|---|
| Hauer AG | 9.450 ÷ 12 | 787,5 | ✅ ja |
| Laher GmbH | 17 × 30 (bzw. 17 × 365 ÷ 12) | 510 (≈ 517) | ✅ ja |
| Daylo UG | 200 (Vorjahr: 200 ÷ 1,16 ≈ 172) | 200 | ❌ nein |

- ⚠️ Hinweis zur Laher GmbH: Das Ergebnis ist knapp. Es gilt, weil "mindestens 17" Neukunden **jeweils mindestens eine Conversion** auslösen und die Bestellungen von Bestandskunden **noch dazukommen**. In einem Monat mit 28 Tagen ergäben die Neukunden allein nur 476. Mit den Bestandskunden liegt der Shop aber realistisch über 500.
- Daylo UG: Die "+16 %" sind ein **Ablenker**. Es zählt nur die absolute Zahl von 200 < 500.

**Vorschlag aus dem Material für eine Infodatei:** Vergleichsfotos oder ein Video, wie der Live-Shop bei einem A/B-Test für verschiedene Kunden aussieht.

## Ergänzungen & Aktualisierungen
- 🔎 Ergänzung (nicht im Original): **Umgebungsstufen in der Praxis:** Development (DEV) → Staging → Production (Live). Details stehen in LF09_Testumgebung. Die "Sandbox" aus diesem Blatt entspricht ungefähr der DEV/Staging-Ebene.
- 🔎 Ergänzung (nicht im Original): **Datenschutz bei Testdaten:** Echte Kundendaten sollten nicht unnötig in Testsysteme kopiert werden. Das folgt aus dem Grundsatz der **Datenminimierung (Art. 5 Abs. 1 lit. c DSGVO)** und dem **Datenschutz durch Technikgestaltung (Art. 25 DSGVO)**. Besser sind **anonymisierte/pseudonymisierte oder künstlich erzeugte Testdaten**.
- 🔎 Ergänzung (nicht im Original): **Live-Tests und Cookies:** A/B-Testing-Tools speichern meist Informationen auf dem Endgerät (Cookie/Local Storage, z. B. welche Variante jemand sieht). Dafür braucht man nach **§ 25 Abs. 1 TDDDG** (bis 13.5.2024 hieß das Gesetz TTDSG) eine **Einwilligung** (Cookie-Banner), außer der Zugriff ist für den vom Nutzer gewünschten Dienst unbedingt erforderlich (§ 25 Abs. 2 Nr. 2 TDDDG). Das ist bei Test- und Analysetools in der Regel nicht der Fall. "Der Kunde merkt den Test nicht" heißt also nur: Er weiß nicht, **welche Variante** er sieht. Die Einwilligung zum Tool braucht man trotzdem.
- 🔎 Ergänzung (nicht im Original): **Praxisbeispiel Shopify:** Ein **dupliziertes, unveröffentlichtes Theme** kann man bearbeiten und in der Vorschau prüfen, bevor man es veröffentlicht. Das ist das Sandbox-Prinzip für Design-Änderungen.

## Prüfungsfallen
- **Sandbox ≠ A/B-Test:** In der Sandbox sind **keine echten Kunden** beteiligt. Beim A/B-Test im Live-Shop läuft **echter Traffic**, die Varianten werden zufällig verteilt.
- **500 Conversions pro MONAT:** Jahres- und Tageswerte immer erst auf den Monat umrechnen.
- **Prozentangaben als Ablenker:** "16 % über dem Durchschnitt" sagt nichts über die Eignung, entscheidend ist die absolute Zahl.
- **Conversions ≠ Besucher (Visitors):** Die Faustregel bezieht sich auf **Conversions**, nicht auf Besucher.
- **Testdauer:** Die "zwei Monate" sind ein **Richtwert und eine Deadline**. Nach LF07_Testgröße soll ein Test außerdem in **vollen 7-Tage-Rhythmen** laufen. Kurze Tests mit viel Traffic (z. B. 2 Wochen) widersprechen dem nicht.
- **Drei Testdatenarten** nennen können: Eingabedaten, Abruf-/Zugriffsdaten, erzeugte Daten.
- **"So klein wie möglich, so groß wie nötig"** bezieht sich auf das Testdaten**volumen**, nicht auf die Testgröße (dort gilt: je größer, desto genauer).
- Der Kunde soll den Test **nicht bemerken**, weil sonst das **Nutzerverhalten verfälscht** wird. Das ist kein Freibrief beim Datenschutz.

## Lernkarten

**F:** Was versteht man im E-Commerce unter einer Sandbox?
**A:** Eine dauerhaft bestehende, exakte Kopie des Live-Shops. Darin kann man Änderungen ohne Risiko vornehmen; nur ausgewählte Mitarbeiter haben Zugriff, Außenstehende sehen sie nicht. Gelungene Änderungen werden in den Live-Shop übernommen.

**F:** Wie unterscheidet sich ein Test in der Sandbox von einem A/B-Test im Live-Shop?
**A:** In der Sandbox testet man ohne echte Kunden an einer Kopie. Beim A/B-Test laufen mehrere Varianten live, echte Besucher sehen zufällig eine davon, und KPIs zeigen, welche Variante besser ist.

**F:** Nennen Sie vier Voraussetzungen für erfolgreiche Testverfahren.
**A:** (1) Das Testinstrument ist korrekt implementiert und wird von den Mitarbeitern beherrscht. (2) Testing-Tool und Webanalyse-Software sind gut verbunden. (3) Das Testing-Team arbeitet eng mit Webdesignern, Programmierern und Textern zusammen. (4) Die Führungsspitze ist offen für Testverfahren.

**F:** Ab wie vielen Conversions lohnt sich laut Faustregel ein Live-Test, und wie lange sollte er höchstens dauern?
**A:** Ab mindestens 500 Conversions pro Monat. Richtwert für die Dauer sind etwa zwei Monate als Deadline; fehlen danach signifikante Ergebnisse, wird der Test überdacht oder neu aufgesetzt.

**F:** Ein Angelshop hat 5.400 Bestellungen im Jahr. Eignet er sich für einen Live-Test?
**A:** 5.400 ÷ 12 = 450 Conversions/Monat. Das liegt unter 500, also nach Faustregel nicht geeignet.

**F:** Ein Shop gewinnt täglich mindestens 20 Neukunden. Prüfen Sie die Eignung für einen Live-Test.
**A:** 20 × 30 = 600 Conversions/Monat allein durch Neukunden, dazu kommen Bestandskunden. Das ist mehr als 500, also geeignet.

**F:** Ein Shop hat in diesem Monat ca. 200 Conversions und liegt damit 16 % über dem Monatsdurchschnitt des Vorjahres. Eignet er sich für einen Live-Test?
**A:** Nein. Entscheidend ist die absolute Zahl: 200 < 500 Conversions pro Monat. Die "+16 %" sind ein Ablenker (Vorjahresdurchschnitt nur 200 ÷ 1,16 ≈ 172).

**F:** Warum soll der Kunde nicht bemerken, dass er an einem Test teilnimmt?
**A:** Weil er sich sonst anders verhält als sonst und die Testergebnisse verfälscht werden.

**F:** Welche drei Arten von Testdaten unterscheidet man?
**A:** Eingabedaten, Abrufdaten/Zugriffsdaten und erzeugte Daten.

**F:** Was bedeutet "Testdaten müssen datenlogisch konsistent sein"? Nennen Sie ein Beispiel.
**A:** Die Testdaten müssen inhaltlich zueinander passen, auch über Plattformen hinweg. Beispiel: Eine Testbestellung verweist auf einen existierenden Testkunden und auf existierende Artikel mit passenden Preisen und Varianten.

**F:** Nach welchem Grundsatz bemisst man das Testdatenvolumen?
**A:** So klein wie möglich, so groß wie nötig, damit Testaufwand und Testkontrollen effizient bleiben.

**F:** Was ist zu tun, wenn sich die Datenstruktur des Shops ändert (z. B. neues Variantenfeld "Lauflänge")?
**A:** Die Testdaten müssen strukturell an die neue Programmversion bzw. Datenstruktur angepasst werden.

**F:** Warum muss man bei mehreren parallelen Tests die Kennzahlen sauber trennen?
**A:** Damit sich die Tests nicht gegenseitig beeinflussen und die Daten nicht verfälscht werden.

**F:** Was kostet eine Sandbox typischerweise?
**A:** Sie ist bei fast jedem Shopsystem kostenlos dabei. Die Shopsysteme selbst kosten je nach Anbieter und Edition von 0 € bis zu mehreren Tausend Euro (Enterprise).

## Bezüge
- LF09_Testumgebung_E-Commerce_OSZHandel1: Stufen DEV, Staging und Production
- LF07_Testgröße_E-Commerce_OSZHandel1: Testgröße, Testdauer, statistische Validität
- LF07_Testverfahren_E-Commerce_OSZHandel1: A/B-Tests und multivariate Tests
- LF07_Landingpage_E-Commerce_OSZHandel1: A/B-Tests zur Landingpage-Optimierung
- LF07_Conversion-Funnel_E-Commerce_OSZHandel1: Conversion Rate als Test-KPI
- LF09_Datenschutz_E-Commerce_OSZHandel1: Testdaten, Einwilligung, DSGVO-Grundsätze
- LF09_Auswertung-von-Seitenbesuchen_E-Commerce_OSZHandel1: Webanalyse als Testgrundlage
