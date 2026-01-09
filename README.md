# Verkaufs-Dashboard – IT-Hardware (Drucker, Monitore, Laptops, Server)  
**Januar 2024 – Dezember 2024**

Ein interaktives Verkaufs-Dashboard zur Analyse des kompletten Jahresumsatzes 2024 eines fiktiven IT-Hardware-Händlers.

![Dashboard Screenshot](dashboard-screenshot.png)  
*(empfohlen: hochauflösenden Screenshot ganz oben rein – am besten im Light- und Dark-Theme)*

## Über das Projekt

Dieses Dashboard ist mein erstes vollständiges Business-Intelligence-Projekt und dient als zentrales Portfolio-Stück, um meine Fähigkeiten in **Datenaufbereitung**, **Visualisierung** und **Storytelling mit Daten** zu zeigen.

Ziel war es, aus einer eher unstrukturierten Verkaufs-Rohdatenbasis (Transaktionen, Produkte, Regionen) ein **klares, übersichtliches und management-taugliches Dashboard** zu entwickeln, das die wichtigsten Fragen eines Geschäftsführers / Vertriebsleiters in wenigen Sekunden beantwortet.

## Wichtigste Erkenntnisfragen, die das Dashboard beantwortet

1. Wie hat sich der Umsatz und die Stückzahlen über das Jahr 2024 entwickelt?
2. Welche Monate waren die stärksten / schwächsten Verkaufsmonate?
3. Welche Produktkategorie bringt den meisten Umsatz und welcher den besten Gewinn/Marge?
4. Wie stark unterscheiden sich die Regionen (Europa, Asien, Nordamerika) in Umsatzanteil und Profitabilität?
5. Wie verhält sich die durchschnittliche Auftragshöhe und der durchschnittliche Stückpreis?
6. Gibt es auffällige Marge-Unterschiede zwischen den Produktkategorien?
7. Welche Kombination aus Kategorie + Region ist besonders lukrativ / problematisch?

## Wichtigste Kennzahlen (KPIs) auf einen Blick

- **Gesamtumsatz 2024**: 22,0 Mio. €
- **Gesamtgewinn**: 6,0 Mio. €
- **Durchschnittliche Marge**: 26,0 %
- **Durchschnittlicher Auftragswert**: 108.150 €
- **Durchschnittlicher Stückpreis**: 1.680 €

## Technologie-Stack

| Bereich               | Technologie/Tools                          | Bemerkung                                  |
|-----------------------|--------------------------------------------|--------------------------------------------|
| Datenaufbereitung     | Python (Pandas), SQL                       | Bereinigung & Transformation               |
| Datenmodell           | Star-Schema (Faktentabelle + Dimensionen)  | sauberes, skalierbares Modell              |
| Visualisierung        | Power BI / Tableau / Looker Studio         | (bitte ergänzen, womit du es gemacht hast) |
| Versionskontrolle     | Git + GitHub                               | Public Repository                          |
| Dokumentation         | Markdown                                   | Diese README + ggf. separate Dokumentation |

## Erkenntnisse & Storytelling-Highlights

- Stärkster Monat: **Januar 2024** mit 4,2 Mio. € Umsatz
- Schwächster Monat: **Mai 2024** mit nur 2,6 Mio. € (starker Rückgang der Verkaufszahlen)
- **Drucker** sind mit Abstand umsatzstärkste Kategorie (27,9 %), aber auch margenstärkste (27 %)
- **Server** bringen zwar hohen Umsatzanteil (23,8 %), aber die niedrigste Marge (24 %)
- **Europa** dominiert klar mit **40 %** des Gesamtumsatzes
- Auffällig: Asien hat trotz geringerem Umsatzanteil (23 %) relativ gute Margen

## Wie man das Dashboard anschaut / benutzt

1. Dashboard-Datei herunterladen (je nach Tool: .pbix / .twbx / .lookml etc.)
2. Entweder:
   - Power BI Desktop öffnen (kostenlos)
   - Tableau Reader nutzen
   - Link zum veröffentlichten Dashboard (falls online gestellt)
3. Optional: Rohdaten + Transformationsskripte im Ordner `/data` und `/transformation`

## Nächste Schritte / geplante Erweiterungen

- Vergleich mit Vorjahr 2023
- Prognose-Funktion für 2025 (einfaches Trend-Modell)
- Detaillierte Kundenanalyse (ABC-Kunden, Wiederholungskäufer)
- Heatmap nach Land/Region
- Warnsystem bei kritischen Marge-Einbrüchen
- Automatische monatliche PDF-Reports per E-Mail

## Feedback sehr willkommen!

Da es mein erstes größeres Dashboard ist, freue ich mich riesig über konstruktives Feedback – egal ob zum Design, zur Story, zu den Kennzahlen oder zur technischen Umsetzung.

Vielen Dank fürs Anschauen! 🙌

---

⭐ Wenn dir das Projekt gefällt – gerne einen Stern dalassen!  
💬 Fragen, Verbesserungsvorschläge, Kritik → gerne in den Issues oder per Kontakt
