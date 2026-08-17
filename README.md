# QA Take-Home Exercise — Hotel Search (Bellboy / layla.ai)

This repo is my submission for the QA take-home exercise.

- **[QA Take-Home Exercise.pdf](./QA%20Take-Home%20Exercise.pdf)** — the original problem statement.

## Part 1 — Exploratory Testing

- **[exploratory.md](./exploratory.md)** — overall quality assessment, findings (with severity and repro steps), a prioritized list of what deserves attention first and why, and what I'd investigate next with more time.
- **[screenshots/](./screenshots)** — evidence referenced from the report, numbered in the order they appear in `exploratory.md`.

## Part 2 — Investigation

Customer Support reported that users sometimes repeat the same hotel search and get very different results.

- **[repeat-search-investigation.md](./repeat-search-investigation.md)** — reproduction of the report, what is and isn't known, and recommended next steps.
- **[part2-screenshots/](./part2-screenshots)** — evidence from the two consecutive searches used in the investigation.

## Environment

- Product under test: https://hoteller-theta.vercel.app/ ("Bellboy," natural-language hotel search)
- Test card used for the payment flow: `4242 4242 4242 4242`
