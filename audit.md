# README Claims Audit

| Claim in README | True? | Evidence |
|---|---|---|
| 5 multiple-choice questions | Yes | `questions` array in `script.js` has 5 entries |
| Progress indicator shown | Yes | `#progress` shows "Question 1 of 5" |
| Each question can only be answered once | Yes | `answered` flag checked at the start of `checkAnswer()` |
| Final score shown at the end | Yes | Tested: all-correct run shows "Your score is 5 out of 5" |
| Play Again restarts the quiz | Yes | Tested: returns to "Question 1 of 5" with score reset |
| Styling lives in a separate CSS file | Yes | No inline `style` attributes in `index.html` |
