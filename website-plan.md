# Focus Flow - Website Plan

## Concept
Minimalistische Produktivitäts-Web-App: Pomodoro-Timer + To-Do-Liste + Statistiken. Alles offline, kein Account, LocalStorage.

## Pages
Single-Page App mit Sektionen:
1. **Header** — App-Name + Tagline + Theme-Toggle (Dark/Light)
2. **Pomodoro Timer** — 25min Arbeit / 5min Pause, Start/Pause/Reset
3. **To-Do Liste** — Aufgaben hinzufügen, abhaken, löschen
4. **Statistiken** — Erledigte Sessions, Aufgaben, Fokus-Zeit gesamt
5. **Settings** — Timer-Dauer, Break-Dauer, Sound an/aus

## Design
- Dark Mode first (Standard), Light Mode umschaltbar
- Modern, clean, aufgeräumt
- Farbverlauf-Akzente (blau → lila)
- Smooth CSS-Animationen
- Mobile-first responsive
- Google Fonts (Inter oder DM Sans)
- Kein Framework, keine Build-Tools

## Tech Stack
- Single HTML-Datei (index.html)
- CSS embedded (style-Tag)
- JS embedded (script-Tag)
- LocalStorage für Persistenz
- Favicon via Emoji (🍅)

## Features
- [x] Timer: Start, Pause, Reset, automatischer Wechsel Arbeit/Pause
- [x] Sound-Benachrichtigung bei Timer-Ende (Web Audio API)
- [x] To-Dos: Hinzufügen, Erledigt-Markieren, Löschen
- [x] Statistiken: Sessions heute/gesamt, Aufgaben, Fokus-Zeit
- [x] Einstellungen: Pomodoro-Dauer, Pausen-Dauer, Sound
- [x] Dark/Light Mode
- [x] Tastaturkürzel: Leertaste = Start/Pause
- [x] Responsive: Handy, Tablet, Desktop
- [x] Alle Daten in LocalStorage
