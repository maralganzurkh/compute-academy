# Compute Academy

An interactive, self-paced computer science curriculum inspired by MIT's CS program — theory, in-browser coding assignments, and auto-graded quizzes.

**[Live demo →](#)** *(replace with your GitHub Pages link once enabled)*

## What it does

- **Curriculum map** — a 4-year overview of an MIT-inspired CS degree path.
- **Course 1 — Introduction to Computer Science & Programming** — six modules covering variables, control flow, functions & recursion, data structures, algorithms & complexity, and testing & debugging.
- **Each module includes:**
  - Theory content with explanations and code examples
  - A hands-on coding assignment, auto-graded against test cases
  - A multiple-choice quiz with instant feedback
- **Accounts & progress** — sign up / log in, progress is saved per account in your browser.

## Running it

This is a single self-contained `index.html` file — no build step, no server. Open it directly in any browser, or host it for free with GitHub Pages:

1. Go to **Settings → Pages** in this repo
2. Set source to the `main` branch, root folder
3. Your live link will appear at `https://<your-username>.github.io/<repo-name>/`

## Notes

- Progress and accounts are stored locally in each browser (no backend yet) — the same account won't sync across different devices until a real backend is added.
- Built as a single-page app; all styling and logic are self-contained in `index.html`.
