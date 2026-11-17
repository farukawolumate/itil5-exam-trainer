# ITIL 5 Exam Trainer

A practice tool for the **ITIL® Foundation (Version 5)** exam.

It gives you 40-question mock exams that match the real exam:
40 questions, 60 minutes, pass mark 26, same topic split.

## What it does

- **Practice mode** – see if you are right or wrong after every question, with the correct answer and a short explanation.
- **Exam mode** – like the real exam. 60-minute timer. You see your answers at the end.
- **Hints** – a 💡 button gives a small clue without giving the answer away.
- **Easy-read** – clearer font, more space between words and lines, and three text sizes. Built with dyslexia in mind.
- **Read aloud** – hear the question, the options and the explanation.
- **Say it more simply** – rewrites a question in plain English without changing its meaning.
- **Learns from your mistakes** – after each exam it builds a new 40-question exam with extra questions on your weakest topics.
- **Progress tracking** – score history, best score and weak spots.

## How to run it

The trainer is a single file, `index.html`, built to run as a **Claude artifact** on [claude.ai](https://claude.ai).
It uses two features that only exist there:

- a small database (`db`) to save your exams and results, and
- `sample`, which lets the page ask Claude to write new questions, hints and simpler wording.

If you open `index.html` straight in a browser, the layout will show but your exams and results can't load.
To use it, publish `index.html` as an artifact in Claude with the `db` and `sample` capabilities turned on.

## Exam layout used

| Area | Questions |
|---|---|
| Key terms | 12 |
| Four Dimensions | 4 |
| Product and Service Lifecycle | 4 |
| ITIL Value System | 16 |
| Value streams | 2 |
| AI | 1 |
| Other frameworks (DevOps, PRINCE2) | 1 |

## Disclaimer

This is an unofficial study aid. It is not made, checked or endorsed by PeopleCert or AXELOS.
ITIL® and PRINCE2® are registered trademarks of PeopleCert. No official PeopleCert course files are included in this repository.
Practice questions are written by Claude and may contain mistakes, so always check against the official ITIL Foundation (Version 5) materials.
