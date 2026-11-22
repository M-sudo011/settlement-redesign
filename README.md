# Tapsi Driver — Settlement Redesign

A mobile-first, Persian (RTL), clickable HTML prototype for redesigning the driver's settlement page.

## Preview

Open [the GitHub Pages prototype](https://m-sudo011.github.io/settlement-redesign/) after GitHub Pages is enabled.

## What to test

- See which banks offer instant settlement *before* adding an account.
- See instant/ACH eligibility beside each registered bank account.
- Manage the maximum of three bank accounts.
- Add an account and simulate IBAN recognition.
- Explore the selection and settlement confirmation states.

**Prototype only:** Bank availability, IBAN identification, account removal/addition, and settlements are simulated. No real backend requests or money transfers occur. The bank list and status are sample data, not live production eligibility.

## Deployment

The root `index.html` is the entire prototype. `.github/workflows/deploy-pages.yml` automatically publishes changes on `main`.

For an empty repository, enable deployment once under **Settings → Pages → Build and deployment → Source: GitHub Actions**, then run the workflow manually from **Actions → Publish settlement redesign → Run workflow** if needed.

The prototype uses the Google Fonts-hosted Vazirmatn web font with local system fallbacks.
