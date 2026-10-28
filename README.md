# Mein Trainingsplan

**Eine moderne, mobiloptimierte Fitness-App für Trainingsplanung und Fortschrittskontrolle.**

[**App öffnen**](https://alubis45123.github.io/Mein-Trainingsplan/) · [**Quellcode ansehen**](https://github.com/Alubis45123/Mein-Trainingsplan)

(Sie können die App eigenständig auf Ihrem Handy öffnen und brauchen keinen PC, um sie herunterzuladen.)

Mein Trainingsplan ist eine schlanke Fitness-Web-App, mit der ich meinen Trainingsalltag übersichtlich organisieren und meine körperliche Entwicklung verfolgen kann. Das Projekt ist für den Eigengebrauch entstanden, steht aber allen Interessierten kostenlos zur Verfügung – ohne Registrierung oder Abonnement.

## Funktionen

- **Wöchentlicher Trainingsplan:** Übersicht über sieben Tage mit Muskelgruppen, Trainingsschwerpunkten und Regenerationstagen.
- **Fortschritts-Dashboard:** Aktuelles Körpergewicht, Veränderungen und grafischer Gewichtsverlauf auf einen Blick.
- **Gewichtserfassung:** Messwerte eintragen, Verlauf ansehen und Einträge bei Bedarf löschen.
- **Satzpausen-Timer:** Voreinstellungen mit 60, 90, 120 oder 180 Sekunden sowie Start-, Pause-, Fortsetzen- und Zurücksetzen-Funktion.
- **Sprachauswahl:** Jederzeit zwischen Deutsch (Standardsprache) und Englisch wechseln. Die Auswahl wird auf dem Gerät gespeichert.
- **Ernährungsrichtwerte:** Allgemeine Orientierungswerte für Protein und Kreatin auf Grundlage des zuletzt eingetragenen Gewichts.
- **Installierbare Web-App (PWA):** Zum Startbildschirm hinzufügen und zwischengespeicherte Inhalte offline verwenden.
- **Datenschutzfreundlich:** Gewichtsdaten und Einstellungen bleiben lokal im Browser; ein Benutzerkonto ist nicht nötig.

## Live-Demo

**[Mein Trainingsplan ausprobieren](https://alubis45123.github.io/Mein-Trainingsplan/)**

Die Oberfläche ist für Smartphones optimiert und lässt sich auch auf dem Desktop verwenden.

## Verwendete Technologien

- **HTML5** – Aufbau der Benutzeroberfläche
- **CSS3** – Responsives Design und Gestaltung
- **JavaScript (Vanilla JS)** – Interaktionen und App-Funktionen ohne Framework
- **Web Storage (`localStorage`)** – Lokale Speicherung von Gewichtsdaten und Einstellungen
- **Canvas API** – Darstellung der Fortschrittsdiagramme
- **Service Worker und Web-App-Manifest** – PWA-Funktionalität und Offline-Cache
- **GitHub Pages** – Veröffentlichung der Web-App

Das Projekt benötigt weder ein Frontend-Framework noch ein Backend oder eine externe Datenbank.

## Lokal starten

1. Repository herunterladen oder klonen:

   ```bash
   git clone https://github.com/Alubis45123/Mein-Trainingsplan.git
   ```

2. Projektordner öffnen und einen lokalen Webserver starten (für PWA-Tests empfohlen):

   ```bash
   python -m http.server 8000
   ```

3. Im Browser `http://localhost:8000` öffnen.

Die Benutzeroberfläche lässt sich auch direkt über `index.html` anzeigen. Für Service Worker wird jedoch eine unterstützte sichere Umgebung wie `localhost` oder HTTPS benötigt.

## Datenschutz und Datenspeicherung

Gewichtseinträge, Timer-Zustand und Sprachauswahl werden lokal im Browser gespeichert. Die App benötigt keine Anmeldung und sendet diese Daten nicht an einen Server. Beim Löschen der Website-Daten oder beim Wechsel des Browsers beziehungsweise Geräts kann der gespeicherte Verlauf verloren gehen oder nicht mehr verfügbar sein.

## Projektstatus

Dieses Projekt wird als persönliches Entwicklerportfolio weiterentwickelt. Im Mittelpunkt steht zunächst eine übersichtliche, zuverlässige Trainings-App. Erweiterte Analysen und eine geräteübergreifende Synchronisierung sind derzeit nicht enthalten.

## Hinweis

Angaben zu Protein und Kreatin dienen ausschließlich der allgemeinen Orientierung und stellen keine individuelle medizinische oder ernährungswissenschaftliche Beratung dar.

## Lizenz

Für dieses Repository wurde bisher keine Lizenz festgelegt. Die öffentliche Sichtbarkeit bedeutet daher nicht automatisch, dass der Quellcode frei weiterverwendet oder verbreitet werden darf.
