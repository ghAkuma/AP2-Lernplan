# Testumgebung: DEV, Staging und Production (LF09, LF09_Testumgebung_E-Commerce_OSZHandel1)
**Prüfungszuordnung:** Teil 2-1 Geschäftsprozesse im E-Commerce > 02 Waren- oder Dienstleistungssortiment mitgestalten und online bewirtschaften > 02 Testmethoden zur laufenden Optimierung des Nutzungsprozesses einsetzen und Ergebnisse auswerten > 01 Testumgebung (übernommen vom inhaltsgleichen Blatt LF02_Testumgebung). Dieses PDF hat selbst keinen Teil/Abschnitt-Kopf; der Seitenkopf nennt nur "Lernfeld 9 – Online-Vertriebskanäle auswählen", Stand 16.03.2022.
**Schwierigkeit:** 1 | **Rechenanteil:** nein | **Lernzeit:** ca. 25 Min

## Kerninhalt

### 1. Allgemeines
- Damit eine Veränderung auch **wirklich eine Verbesserung** ist, bietet jedes gute Shopsystem/Backend eine **Testumgebung**, in der man Versuche durchführen kann.
- Die Testumgebung ist eine **exakte Kopie des Live-Shops**. Dort kann man überarbeiten, **ohne negative Folgen** befürchten zu müssen.
- **Am Anfang** ist eine Testumgebung **nur für den Programmierer sichtbar** = **DEV-Umgebung** (Developer-Umgebung).
- In der DEV-Umgebung arbeiten laut Material die "DevOps" (Begriff dort ungenau verwendet, siehe ⚠️ Hinweis unten): Sie bauen Tools ein, passen Code an, formulieren Texte neu und spielen allgemeine Updates ein.
- In der **DEV-Phase** prüft man z. B., ob der Shop nach den Änderungen **überhaupt noch funktioniert**.
- Sind die Änderungen in DEV abgesegnet, geht es auf die nächste Ebene, das **Staging**. Dort sehen sich **deutlich mehr Personen** die Verbesserungen an, segnen sie ab oder kritisieren sie.
- Ist das Staging abgesegnet, geht die neue Seite in der Regel **live**.
- Manchmal liegen weitere Testumgebungen dazwischen, z. B. eine **automatische Testumgebung**, die per **Scripts** prüft, ob etwa **Links funktionieren** oder **Alt-Tags gesetzt** sind.

### 2. Voraussetzungen (wie in LF02_Testumgebung)
1. Das **Testinstrument** ist korrekt in die Website **implementiert**, die Mitarbeiter **beherrschen** es.
2. Es gibt eine **gute Verbindung zwischen Testing-Tool und Webanalyse-Software**.
3. Das **Testing-Team** steht in engem Kontakt mit **Webdesignern, Programmierern und Textern**.
4. Die **Führungsspitze** ist **offen für Testverfahren**.

### 3. DEV, Staging und Production im Detail
- **DEV (Developer):**
  - umfasst alle Geräte, an denen der Entwickler arbeitet (Dev-Laptop, Dev-PC 1, …)
  - Programmierer bauen hier an einer **Kopie der Live-Seite**, an Software oder Code, ohne Angst, etwas kaputt zu machen
  - **höchstens minimales Testing**, "zu 99 %" wird nur **gebaut und erstellt**
- **Staging:**
  - hat **eigene URLs**, z. B. stag1.amazon.com
  - hier werden **Defekte gefunden** und an die Entwickler **zurückgeschickt**
  - meist gibt es **mehrere Staging-Umgebungen** (stag1, stag2 …), damit **Tester und Entwickler gleichzeitig arbeiten** können
- **Production:**
  - wenn die Staging-Tester das **OK** geben, geht es in diese Phase
  - hier ist **nur Software**, die die **Besucher der Live-Seite** sehen
  - laut Material ist jede Website, die man über Google erreicht, in der Production-Phase (nur Faustregel, siehe Hinweis unten)

**Schaubild aus dem Material (als Struktur):**

| Development Environment | → | Staging Environment | → | Production Environment |
|---|---|---|---|---|
| Developers | | Tester | | Besucher der Website |
| minimales Testen | | aktives Testen | | alles sollte perfekt sein |
| 99 % Software bauen oder Code schreiben | | Defekte finden und Entwicklern melden | | |
| Dev-Laptop | | URL, EXE | | |

Ablauf: **DEV → Staging → Production**. Gefundene Defekte gehen aus dem Staging zurück an DEV.

## Formeln & Rechenwege
Keine Rechenanteile.

## Aufgaben aus dem Material

**Aufgabe 1:** Beschreiben Sie, was man im E-Commerce unter einer Testumgebung versteht.
- **Musterlösung, Schlüsselbegriffe:** Backend-Tool/Backend-Software; mehrere Testumgebungen; Kopie der Live-Seite.
- **Beispielsatz:** Es gibt nicht *die eine* Testumgebung. Eine Testumgebung ist eine **Kopie der Live-Seite**, die im **Backend** angezeigt wird. Dort nimmt man Änderungen vor und testet sie.

**Aufgabe 2:** Erläutern Sie, wann eine Testumgebung genutzt wird.
- **Musterlösung:** Man nutzt sie, um **an der Seite zu arbeiten und zu testen, ohne das Tagesgeschäft zu stören**. Ohne Testumgebung müsste man die Website **jedes Mal offline nehmen**, wenn man etwas ändern will.

**Aufgabe 3:** Auf welcher Umgebung sind Bugs/Defekte üblich?
- **Musterlösung:** Auf der **Staging- und der DEV-Umgebung**.

**Aufgabe 4:** Warum gibt es mehrere Staging-Umgebungen?
- **Musterlösung:** Damit **Entwickler und Tester gleichzeitig arbeiten** können.
- Ergänzende Begründung: So können auch **verschiedene Änderungen oder Projekte parallel** getestet werden, ohne sich gegenseitig zu stören.

## Ergänzungen & Aktualisierungen
- ⚠️ Hinweis (Fehler im Material): **"DevOps"** sind nicht einfach "die Leute in der DEV-Umgebung". DevOps (Development + Operations) bezeichnet eine **Arbeitsweise bzw. Rolle**, die Entwicklung und IT-Betrieb verbindet (z. B. automatisierte Tests und Deployments). In der DEV-Umgebung arbeiten in erster Linie die **Entwickler (Developer)**.
- ⚠️ Hinweis: "Jede Seite, die man über Google erreichen kann, ist Production" stimmt nur als Faustregel. Staging-Seiten sollten **nicht öffentlich auffindbar** sein (Passwortschutz, noindex). Sonst sehen Kunden unfertige Seiten und es entsteht **Duplicate Content** für Suchmaschinen.
- 🔎 Ergänzung (nicht im Original): **Typische Arbeitsschritte bis zum Go-live:** Entwicklung (DEV) → automatisierte Prüfungen (Links, Alt-Tags, Funktionen) → Staging/Abnahme durch Fachabteilung → **Freigabe** → Deployment in Production → **Monitoring der KPIs** nach dem Go-live → bei Problemen Rollback (zur letzten Live-Version zurück).
- 🔎 Ergänzung (nicht im Original): Die Stufen gibt es auch in anderen Abläufen, z. B. **Testshop beim Zahlungsanbieter (Test-/Sandbox-Modus)** oder **Testsystem der Warenwirtschaft**, damit Testbestellungen keine echten Zahlungen oder Lieferungen auslösen.
- 🔎 Ergänzung (nicht im Original): **Alt-Tags** (Alternativtexte für Bilder) sind nicht nur für SEO wichtig, sondern auch für die **Barrierefreiheit** (Screenreader). Seit 28.6.2025 gilt dazu für viele Online-Shops gegenüber Verbrauchern das **Barrierefreiheitsstärkungsgesetz (BFSG)**, siehe LF09_UX-Design-2.

## Prüfungsfallen
- **Reihenfolge merken: DEV → Staging → Production.** Nicht verwechseln: Staging kommt **vor** Live.
- **Wo wird getestet?** In DEV wird **kaum** getestet (99 % bauen). **Aktiv getestet** wird im **Staging**. Bugs/Defekte findet man typischerweise in **DEV und Staging**, nicht in Production (dort soll "alles perfekt" sein).
- **Wer arbeitet wo?** DEV = Entwickler, Staging = Tester (und mehr Personen zur Abnahme), Production = Besucher/Kunden.
- **Mehrere Staging-Umgebungen** gibt es wegen **paralleler Arbeit** von Testern und Entwicklern, nicht wegen mehrerer Shops oder Länder.
- **Testumgebung (DEV/Staging) ≠ A/B-Test:** DEV/Staging laufen **ohne Kunden**, ein A/B-Test läuft im **Live-Betrieb** (siehe LF02_Testumgebung, LF07_Testverfahren).
- Begriff **Sandbox** (LF02-Material) ≈ eine vom Live-Shop getrennte Testkopie. Die LF09-Begriffe sind die feinere Unterteilung.

## Lernkarten

**F:** Was ist eine DEV-Umgebung und wer arbeitet dort?
**A:** Die Developer-Umgebung: alle Geräte bzw. die Kopie der Seite, an der Entwickler Software und Code bauen. Sichtbar ist sie nur für die Programmierer, getestet wird höchstens minimal, zu 99 % wird gebaut.

**F:** Welche Aufgabe hat die Staging-Umgebung?
**A:** Dort testen Tester die Änderungen aktiv, finden Defekte und melden sie an die Entwickler zurück. Außerdem können mehr Personen die Änderungen ansehen, absegnen oder kritisieren, bevor sie live gehen.

**F:** Was gelangt in die Production-Umgebung?
**A:** Nur fertige, im Staging freigegebene Software, die die Besucher der Live-Seite sehen. Dort sollte alles fehlerfrei sein.

**F:** Bringen Sie in die richtige Reihenfolge: Production, DEV, Staging.
**A:** DEV → Staging → Production.

**F:** Auf welchen Umgebungen sind Bugs üblich?
**A:** Auf DEV und Staging.

**F:** Warum betreibt ein Unternehmen mehrere Staging-Umgebungen (stag1, stag2)?
**A:** Damit Entwickler und Tester gleichzeitig arbeiten und mehrere Änderungen parallel getestet werden können.

**F:** Was prüft eine automatische Testumgebung? Nennen Sie zwei Beispiele.
**A:** Per Script werden z. B. funktionierende Links und gesetzte Alt-Tags geprüft.

**F:** Warum sollte ein Online-Shop überhaupt eine Testumgebung nutzen?
**A:** Um Änderungen zu entwickeln und zu testen, ohne das Tagesgeschäft zu stören. Ohne Testumgebung müsste der Shop bei jeder Änderung offline gehen, und Fehler würden direkt bei Kunden landen.

**F:** Fallsituation: Euer Angelshop bekommt einen neuen Größenfilter für Gummiköder. Beschreiben Sie den Weg bis zum Go-live.
**A:** Entwickler bauen den Filter in der DEV-Umgebung. Danach wird er auf Staging von Testern bzw. der Fachabteilung geprüft (filtert er richtig, funktioniert er mobil, sind alle Links in Ordnung?). Gefundene Fehler gehen zurück an DEV. Nach der Freigabe kommt der Filter in die Production-Umgebung (Live-Shop), danach beobachtet man die KPIs.

**F:** Was ist am Satz "In der DEV-Umgebung arbeiten die DevOps" ungenau?
**A:** In DEV arbeiten vor allem Entwickler. DevOps bezeichnet eine Arbeitsweise bzw. Rolle, die Entwicklung und IT-Betrieb verbindet (z. B. automatisiertes Testen und Ausrollen).

**F:** Woran erkennt man laut Material Staging-Seiten?
**A:** An eigenen URLs, z. B. stag1.amazon.com.

## Bezüge
- LF02_Testumgebung_E-Commerce_OSZHandel1: Sandbox, Live-Test, Testdaten, Voraussetzungen
- LF07_Testverfahren_E-Commerce_OSZHandel1: Live-Tests mit A/B- und multivariaten Tests
- LF07_Testgröße_E-Commerce_OSZHandel1: Test-Traffic und Testdauer
- LF10_Qualitätssicherung-von-Prozessen_E-Commerce_OSZHandel1: Qualitätssicherung und KPIs nach dem Go-live
- LF09_Outsourcing_E-Commerce_OSZHandel1: externe Dienstleister für die Shopentwicklung
- LF09_UX-Design-2_E-Commerce_OSZHandel1: Alt-Tags, Barrierefreiheit, Benutzerfreundlichkeit
