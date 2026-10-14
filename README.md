# Erica's Practice Quiz Generator

A self-serve study tool for Erica (grade 10, Ontario): pick a course, pick a
unit, generate a randomized practice quiz, print it — with the answer key on a
separate printable page so there's no peeking.

**Live site:** https://alexzwu.github.io/erica-quiz-generator/

## What's inside

- `index.html` — the entire app: course/unit navigation, quiz generator
  (random sampling + shuffled options), printable quizzes and answer keys,
  and a Manage page for adding custom courses, units, and questions
  (saved in the browser's localStorage).
- Question banks are embedded in the file, written from the Ontario
  curriculum expectations per unit. 340 questions across 18 units as of
  Oct 2026, covering all of Erica's semester-1 courses
  (Science, Civics, Career Studies, Digital Technology, Core French).

## Updating

Replace `index.html` at the repo root (upload via the GitHub web UI or push).
GitHub Pages rebuilds within a minute or two; the live URL never changes.

## Publishing setup (already done)

Settings → Pages → Deploy from a branch → `main` / `/ (root)`.
