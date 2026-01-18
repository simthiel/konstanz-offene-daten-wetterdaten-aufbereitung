# Aufbereitung offener Wetterdaten der Stadt Konstanz

Dieses Projekt zeigt exemplarisch, wie offene Wetterdaten der Stadt Konstanz
qualitativ geprüft, bereinigt und für eine Weiterverwendung aufbereitet werden können.

Das Repository dient als Arbeitsprobe im Rahmen einer Bewerbung
für eine Trainee-Position bei der Stadt Konstanz.

---

## Motivation

Dieses Projekt demonstriert einen möglichen Workflow zur
Qualitätsverbesserung kommunaler offener Datensätze.

---

## Ausgangslage

Die bereitgestellten Rohdaten weisen u. a. folgende Herausforderungen auf:

- CSV-Dateien mit inkonsistenten Formaten
- unplausible Messwerte
- uneinheitliche Zeitstempel

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

The source code in this repository is licensed under the MIT License
(see LICENSE file), except where otherwise noted.

Parts of the Python code used to retrieve external weather data are based on
example code provided by Open-Meteo. This example code is used in accordance
with the Open-Meteo terms of use and the Creative Commons Attribution 4.0
International License (CC BY 4.0).

External weather reference data retrieved via the Open-Meteo API is licensed
under CC BY 4.0.
