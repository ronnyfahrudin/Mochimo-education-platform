# Mochimo Academy

A free, self-paced learning platform about **Mochimo (MCM)**, the post-quantum resistant blockchain. It takes learners from "what is crypto?" to holding MCM in a wallet they control, with an optional builder track for node runners, miners and developers.

![Certificate sample](assets/certificate-sample.png)

## Curriculum

| Level | Audience | Lessons |
|---|---|---|
| 1. Foundations | Complete beginners | Ledgers and blockchains · Keys and wallets · The quantum threat |
| 2. Inside Mochimo | After Level 1 | Hashes and WOTS+ · Tags and v3 addresses · The network (ChainCollapse, supply, units) |
| 3. Own your MCM | Hands-on | Getting MCM · Wallet setup · Moving MCM into self-custody |
| 4. Builder track | Optional, technical | Running a relay node · GPU mining · Mesh API |

## Features

- 12 lessons with learning objectives and 2 comprehension questions each
- Interactive labs: live SHA-256 hashing, a WOTS+ hash-ladder key-reuse demo, and an MCM ↔ nanoMCM converter
- Searchable glossary of 24 terms, linked back to lessons
- 10-question final exam (pass mark 8/10)
- Shareable certificate rendered as a 2000 × 1414 PNG
- Light and dark themes, responsive down to mobile
- Progress saved locally in the learner's browser (no backend, no tracking)

## Run it

It is a single static file with no build step.

- **Locally:** open `index.html` in a browser.
- **GitHub Pages:** Settings → Pages → Deploy from branch → `main` / root. The site will be live at `https://ronnyfahrudin.github.io/Mochimo-education-platform/`.

## Project structure

```
index.html                  the whole platform (HTML, CSS, JS, inlined logo)
assets/mochimo-logo.jpg     Mochimo logo
assets/certificate-sample.png  example certificate
```

## Notes

- Certificate IDs are unique but not verifiable, because progress is stored only in the learner's browser.
- Exchange listings change, so the course points learners to live market pages instead of naming an exchange.
- Always verify links through [mochimo.org](https://mochimo.org).

Educational material only, not financial advice.
