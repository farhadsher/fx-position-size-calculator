# FX Position Size Calculator

A free, no-signup calculator that helps forex traders size their positions correctly based on account risk, stop loss distance, and currency pair — instead of guessing lot sizes.

**[Live tool →](index.html)** (open in any browser, no build step required)

Built and maintained by [FXMARE](https://fxmare.com) — forex news, market analysis, and free trading tools.

## Why this exists

Most beginner traders blow up their accounts not because their trade idea was wrong, but because their position was too large for their stop loss. This tool makes the math (risk amount → lot size) instant and visual, so risk management becomes a habit instead of an afterthought.

## How it works

1. Enter your account balance and currency.
2. Set how much of your account you're willing to risk on this trade (as a %).
3. Enter your stop loss distance in pips.
4. Pick your currency pair (or enter a custom pip value).
5. Get your position size in standard lots, mini lots, micro lots, and raw units.

The formula:

```
Risk amount   = Account balance × Risk %
Position size = Risk amount / (Stop loss in pips × Pip value per lot)
```

## Usage

This is a single self-contained HTML file — no dependencies, no build tools, no tracking.

- Open `index.html` directly in a browser, or
- Serve it with any static file host, or
- Embed it in a page via `<iframe>`.

## Disclaimer

This tool is for educational purposes only and does not constitute financial advice. Pip values shown are approximations for a USD-denominated account and will vary with live exchange rates — always confirm position sizing with your broker's actual figures before trading.

## License

MIT — see [LICENSE](LICENSE).
