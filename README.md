# Studio — MYP Study Dashboard

A local-first study app for MYP Grade 7 **Math & Science**. Quiz yourself, work through
step-by-step practice problems, and drill the questions you got wrong.

**Live:** https://olyhelpschoreo.github.io/studio

## Features
- **Quiz mode** — multiple choice with instant feedback and explanations
- **Practice mode** — hints and step-by-step worked solutions, honest self-marking
- **Review my mistakes** — every wrong answer is saved; answer it right and it clears
- **Daily streak** — keeps you coming back
- **Saves on your device** — progress persists (localStorage), no login
- **Installable PWA** — add to your home screen, works offline
- **Light & dark mode** — follows your system, or toggle it

## Tech
Single-file `index.html` (vanilla JS, no build step) + a service worker for offline +
web app manifest. That's it. Open `index.html` on any static server:

```
python3 -m http.server 8080
```

then visit http://localhost:8080
