# QFA Life Assurance Practice

A practice quiz for the QFA **Life Assurance** module (Professional Diploma in Financial Advice, Ireland).
It runs entirely in the browser, can be added to a phone's home screen, and works offline once opened.

> Unofficial practice questions for personal study. Not affiliated with or endorsed by the
> Institute of Banking (IOB). The questions were written with AI assistance and may contain errors.
> Always check the current IOB course text — rules, figures and thresholds change.

## What it covers

292 multiple-choice questions across 8 topics:

| Topic | Questions |
|---|---|
| Life protection products | 36 |
| Serious illness and income protection | 36 |
| Underwriting and claims | 38 |
| Legal aspects of life assurance | 36 |
| Life assurance savings and investment policies | 36 |
| Taxation of life assurance | 38 |
| Business protection | 35 |
| Regulation of life assurance | 37 |

Several topics include calculation questions, with the working shown in the explanation.

### Tax figures used

The questions follow Irish figures as of late 2026 and name the date where something changed recently.
Your course text may be based on an earlier tax year.

| Item | Used in the questions |
|---|---|
| Exit tax on life policies | 38% for events in 2026 (previously 41%) |
| Capital Acquisitions Tax | 33%; thresholds €420,000 / €44,000 / €22,000 from 7 October 2026 (previously €400,000 / €40,000 / €20,000) |
| Life assurance levy | 1% |

## Features

- **Practice** one topic or a mix, with the correct answer, an explanation and a reference after each question
- **Mistake review**: wrong answers are remembered; a question is cleared after two correct answers in a row in review mode
- **Mock exam**: timed, no feedback until the end, 60% pass mark, per-topic breakdown
- Star any question to revisit it, light and dark theme, keyboard shortcuts (1–4 or A–D, Enter for next)

## Using it

Open the site's address in a browser. With GitHub Pages the address is
`https://<username>.github.io/<repository-name>/`.

### Add to an iPhone home screen

1. Open the address in **Safari**.
2. Tap **Share**, then **Add to Home Screen**.
3. Open it once from the new icon while online. After that it works without a connection.

### Add to an Android phone

Open the address in Chrome, tap the **⋮** menu, then **Add to Home screen** (or **Install app**).

## Your progress

- Progress is stored **in the browser on each device**. Nothing is sent anywhere.
- A phone and a computer each keep their own progress. Use **Export** and **Import** in the app to move it between them.
- Clearing the browser's site data, or removing the home-screen app, deletes the progress on that device. Export first if you want to keep it.

## Publishing on GitHub Pages

1. Upload all files in this folder to the top level of a public repository.
2. Go to **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
3. Wait a minute or two for the address shown on that page to go live.

## Files

| File | Purpose |
|---|---|
| `index.html`, `app.js`, `styles.css` | The quiz interface |
| `questions.json` | All questions, with answers, explanations and references |
| `static-api.js` | Loads the questions and saves progress in the browser |
| `sw.js` | Offline cache |
| `manifest.webmanifest`, `icon-*.png` | Home-screen name and icon |
