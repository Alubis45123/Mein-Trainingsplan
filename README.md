# My Training

**A lightweight, mobile-first fitness tracker for planning workouts and following your progress.**

[**Launch the app**](https://alubis45123.github.io/Mein-Trainingsplan/) · [**View the source**](https://github.com/Alubis45123/Mein-Trainingsplan)

My Training is a personal fitness web app built to make everyday training simpler. It started as a personal project and is available for anyone who wants a straightforward workout companion—without accounts or subscriptions.

## Features

- **Weekly workout plan:** A seven-day training split with muscle-group details and recovery days.
- **Progress dashboard:** An overview of your logged body weight, changes over time, and a progress chart.
- **Weight tracking:** Record and review body-weight measurements, with the option to delete entries.
- **Rest timer:** Choose 60, 90, 120, or 180 seconds; start, pause, resume, or reset your countdown.
- **Language selection:** Switch between German (default) and English; your preference is saved on your device.
- **Nutrition reference:** General protein and creatine guidelines based on the latest logged weight.
- **Installable PWA:** Add the app to your home screen and use its offline-cached resources.
- **Privacy-friendly:** Workout data is stored locally in your browser; no sign-up is required.

## Live demo

**[Open My Training](https://alubis45123.github.io/Mein-Trainingsplan/)**

The interface is optimized for mobile screens but also works in desktop browsers.

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript
- Web Storage (`localStorage`)
- Canvas API for progress charts
- Service Worker and Web App Manifest (PWA)
- GitHub Pages for hosting

No frontend framework, backend, or external database is required.

## Run locally

1. Download or clone this repository:

   ```bash
   git clone https://github.com/Alubis45123/Mein-Trainingsplan.git
   ```

2. Open the project folder and serve it with a local HTTP server (recommended for PWA testing):

   ```bash
   python -m http.server 8000
   ```

3. Visit `http://localhost:8000` in your browser.

You can also open `index.html` directly to view the interface, but service workers require a supported secure context such as `localhost` or HTTPS.

## Data and privacy

Weight entries, timer state, and language preference are saved in your browser's local storage. The app does not require an account or send these entries to a server. Clearing site data or switching browsers/devices may remove or hide your locally saved history.

## Project status

This is an actively evolving personal portfolio project. The current version focuses on a clear, functional workout experience rather than advanced analytics or cloud synchronization.

## Disclaimer

Protein and creatine values are general reference information, not individualized medical or nutritional advice.

## License

No license has been selected yet. Until a license is added, the repository's public visibility does not grant general permission to reuse or redistribute its code.
