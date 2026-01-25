# Aufbereitung offener Wetterdaten der Stadt Konstanz

Ein zentrales Ziel offener Verwaltungsdaten ist es, Daten nicht nur bereitzustellen,
sondern sie auffindbar, verständlich und tatsächlich nutzbar zu machen.

Dieses Projekt greift diesen Gedanken exemplarisch auf: Anhand eines konkreten
Datensatzes aus dem Open-Data-Portal der Stadt Konstanz wird gezeigt, wie vorhandene
Datenquellen strukturiert erschlossen, qualitativ eingeordnet und für eine
Weiterverwendung aufbereitet werden können.

Das Repository dient als Arbeitsprobe im Rahmen einer Bewerbung
für eine Trainee-Position bei der Stadt Konstanz.

---

## Motivation

Dieses Projekt demonstriert einen möglichen Workflow zur
Qualitätsverbesserung kommunaler offener Datensätze.

---

## Ausgangslage

Die bereitgestellten Rohdaten enthalten numerische Messwerte, die in der genutzten CSV-Datei nicht direkt als Zahlen, sondern als Zeichenketten mit Formatierungsfehlern vorliegen. Darüber hinaus treten fehlerhafte Größenordnungen auf (z. B. um den Faktor 10 oder 100 abweichende Werte), die eine unmittelbare Weiterverwendung der Daten erschweren.

---

## Ziel der Datenaufbereitung

- Bereinigung und Plausibilitätsprüfung der Rohdaten
- Vereinheitlichung von Struktur und Zeitformaten
- Schaffung einer Grundlage für Visualisierung, Analyse

---

## Inhalt des Repositories

- `wetterdaten_konstanz_aufbereitung.ipynb` 
  Dokumentiertes Jupyter Notebook zur Datenaufbereitung und Datenqualitätssicherung. 
  Die einzelnen Verarbeitungsschritte sind bewusst ausführlich kommentiert.

---

## Technischer Ansatz

- Python (pandas, numpy)
- Jupyter Notebook
- Reproduzierbarer, schrittweiser Workflow
- Fokus auf Nachvollziehbarkeit statt Black-Box-Automatisierung

---

## Datenquelle

- Offenes Datenportal der Stadt Konstanz 
  https://offenedaten-konstanz.de/ 
- Lizenz: Creative Commons Namensnennung 4.0 International (CC BY 4.0)

---

## Credits and License

License

This project is licensed under the GNU General Public License v3.0 or later (GPLv3+). except where otherwise noted.

Parts of the Python code used to retrieve external weather data are based on
example code provided by Open-Meteo. This example code is used in accordance
with the Open-Meteo terms of use and the Creative Commons Attribution 4.0
International License (CC BY 4.0).

External weather reference data retrieved via the Open-Meteo API is licensed
under CC BY 4.0.

This project uses the following third-party Python libraries:
- NumPy (BSD License)
- pandas (BSD License)
- matplotlib (PSF / BSD-style License)
- requests-cache (MIT License)
- retry-requests (GNU General Public License v3 or later, GPLv3+) 
- openmeteo-requests (MIT License)
