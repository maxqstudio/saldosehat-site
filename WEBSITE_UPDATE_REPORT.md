# SaldoSehat Website Update Report

## Scope

Updated the SaldoSehat static website to English and aligned the public copy with the current SaldoSehat app baseline.

## Updated pages

1. `index.html`
2. `privacy.html`
3. `terms.html`
4. `support.html`
5. `style.css`
6. `README.md`
7. `images/readme.md`

## Key alignment points

- App positioning: local-first personal finance tracker
- Features: income, expenses, wallets, Target, loans, receivables, export, backup, and Ask
- Backup format: `.saldosehat`
- Restore guard: generic `.json` is not supported for restore
- Support email: `saldosehat.support@maxqstudio.dev`
- Ask disclaimer: template/data-based help, not official financial advice
- Privacy: main app data is stored locally on the user's device
- Notification privacy: notification details can be hidden; no money amounts should appear in notification title/body
- Prohibited claims avoided: no bank integration, no cloud sync, no loan/paylater product, no credit scoring, no official financial advisor claim

## Website behavior

- Fixed screenshot carousel image paths to match packaged image files
- Support page includes FAQ show/hide accordion using native HTML `details` and `summary`
- All visible website copy is in English

## Output

Final ZIP: `saldosehat-site-main-english-current.zip`
