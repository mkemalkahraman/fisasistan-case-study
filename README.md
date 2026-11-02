# FişAsistan: a receipt-checking web app (case study)

A web app where employees photograph expense receipts, a vision model reads them, the employee confirms, and a rules engine checks the numbers before the accountant sees them.

![FişAsistan screens: dashboard, receipt list, assistant answer and cash ledger](img/banner.png)

**Read the full case study: https://mkemalkahraman.github.io/fisasistan-case-study/**

## At a glance

- Web app that installs from the browser and runs on a phone home screen
- Next.js 16, React 19, TypeScript (strict), Supabase (Postgres, Storage), a Gemini vision model for reading receipts
- Every accounting rule is a row in a decision table, and every row has a test
- Money is stored as exact decimals; row-level security on every table; the secret key exists only on the server
- 538 automated tests, and the database migrations are tested on a real Postgres engine
- A rule-based assistant (no language model) answers questions from figures the server calculates

## About this repository

- **No source code is published here.** This is a case study only.
- **All screenshots use invented data.** Names, shops and amounts are made up for this page.
- The app's interface is in Turkish because it was built for a Turkish company. The labels are explained next to each screen.

## Credit

Built with Claude as a pair programmer. Product decisions, accounting rules and testing on real phones are mine.
