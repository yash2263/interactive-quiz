# Interactive Quiz Application

A 5-question multiple-choice quiz built with plain **HTML, CSS and JavaScript** (Lecture 10).

## Features
- One question at a time with a progress indicator ("Question 2 of 5")
- Click an option to answer; the quiz moves to the next question automatically
- Each question can only be answered once (an `answered` flag blocks double clicks)
- Final score shown at the end, with a **Play Again** button to restart
- Blue, white and gold colour scheme; responsive on mobile

## How it works
- `questions` in `script.js` is an array of objects: `{ question, options, answer }`.
- `showQuestion()` renders the current question and creates a button for each option.
- `checkAnswer()` compares the clicked option with `answer`, updates `score`, and either shows the next question or the final result.

## Run locally
Open `index.html` in any browser. No install needed.

## Files
| File | Purpose |
|---|---|
| `index.html` | Page structure |
| `style.css` | All styling |
| `script.js` | Quiz data and logic |
