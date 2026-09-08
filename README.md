# Deriv AI Scanner V2 — iPhone Web App

This is a mobile-friendly, scan-only prototype.

## Use on iPhone
The files need to be hosted at an HTTPS URL. Open the URL in Safari, then:
Share -> Add to Home Screen.

## What it does
- Connects directly from the browser to Deriv's public WebSocket.
- Gets active symbols.
- Gets recent tick history.
- Subscribes to live ticks.
- Calculates Odd/Even and Matches/Differs descriptive frequencies.
- Ranks candidate markets.
- Does not place trades.
- Does not ask for or store a Deriv password/token.

## Important limitation
The current score is a statistical scanner, not a proven profitable prediction model. The next build should add a server-side historical database, walk-forward backtesting, contract-specific proposal/payout lookup, expected-value calculation, and paper-trading statistics before any live execution is enabled.
