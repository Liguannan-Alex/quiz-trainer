# quiz-trainer

Single-file, offline-capable quiz trainer.

- One HTML file, no dependencies, no network calls after load
- Question content is AES-GCM encrypted; a passcode-derived key (PBKDF2-SHA256, 150k iterations) unlocks it in the browser
- Progress, wrong-answer book and bookmarks are stored in `localStorage` only — nothing is uploaded
- Mobile-first; supports light/dark, keyboard shortcuts on desktop

Open the page and enter the passcode to use it.
