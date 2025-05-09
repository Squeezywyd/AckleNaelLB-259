## Beschreibung des Datensatzes
Dieser Datensatz enthält historische Bitcoin-Preisdaten von 1. Januar 2021 bis 12. Mai 2021 im 1-Minuten-Intervall. Die Daten wurden mithilfe einer API generiert und zeigen die Preisbewegungen von Bitcoin während dieses Zeitraums.

# Spaltenübersicht:

- open_time – Zeitstempel (Unix), wann die Minute beginnt
- open – Eröffnungspreis von Bitcoin in USD
- high – Höchstpreis von Bitcoin innerhalb dieser Minute
- low – Tiefstpreis von Bitcoin innerhalb dieser Minute
- close – Schlusskurs von Bitcoin in USD
- volume – Gehandeltes Volumen innerhalb dieser Minute
- close_time – Zeitstempel (Unix), wann die Minute endet
- Insgesamt enthält der Datensatz 188'318 Zeilen, da jede Minute zwischen Januar und Mai 2021 erfasst wurde.

## Datenschutz & Lizenz
Dieser Datensatz enthält keine personenbezogenen Daten. Alle enthaltenen Informationen sind öffentlich zugängliche Marktdaten und beinhalten keine privaten oder sensiblen Informationen über einzelne Nutzer oder Transaktionen.

Die Daten wurden durch eine API generiert und enthalten keine spezifischen Identifikatoren. Es sind keine Datenschutzmassnahmen erforderlich, da keine Rückverfolgung auf Einzelpersonen möglich ist.

Lizenz: Frei nutzbar unter der CC0-Lizenz (Public Domain).

## Fazit
Das Projekt zeigt, dass mit einfachen Modellen wie der linearen und logistischen Regression sehr genaue Vorhersagen möglich sind.
Die Regression erreichte einen R²-Wert von 0.99999, die Klassifikation eine Trefferquote von 99.87 %.
Die Auswertung bestätigte eine hohe Aussagekraft des Modells. Für zukünftige Arbeiten wären komplexere Ansätze oder Zeitreihenanalysen interessant.
