# Inflection

**Career decisions, clearly.**

Inflection is a browser-based tool for modeling the financial and personal trade-offs of a career move. It handles the scenarios that generic salary calculators miss: pre-IPO equity, multi-grant vesting waterfalls, IPO outcome ranges, and the qualitative frameworks that actually drive good decisions.

**[Live demo](https://heathensxyz.github.io/inflection/)**, featuring Jordan, a fictional Sr. PM weighing a pre-IPO fintech offer against a public company role.

---

## What it does

- **Year-by-year cash comparison** with segmented bars showing base, bonus, and RSU components side by side
- **IPO scenario explorer** covering bear / base / bull / moonshot / no liquidity, with 4-year total comp impact
- **Vesting waterfall** with interactive canvas chart and sliders for stock growth, IPO timing, multiplier, and future refresh grants
- **Decision Lens** with six qualitative frameworks and reflection prompts

## How to run it

No build step. No dependencies. No accounts.

```
open index.html
```

Or drag the file into any browser.

## Using it

The tool opens in **Demo Mode** with a fictional scenario (Jordan choosing between two companies). To model your own decision:

1. Click **"My Analysis"** in the nav bar, or **"Analyze your own decision"** at the top or bottom
2. Walk through the wizard: enter both roles in one form, then review and launch
3. Your data saves automatically in your browser's localStorage
4. Switch between Demo and My Analysis anytime using the nav toggle
5. Use **"Export my data"** to save a backup, **"Clear my data"** to wipe everything

## Privacy

All data stays in your browser. Nothing is sent to any server. Your inputs are saved in localStorage on this device only. Anyone with access to this browser can see the data. No external scripts, images, or resources are loaded.

## Sharing securely

To share with someone:

1. Install StatiCrypt: `npx staticrypt index.html`
2. This produces an encrypted HTML file with a password prompt
3. Send the encrypted file via Signal or email
4. Share the password through a separate channel

## Roadmap

- [x] Phase 1: Demo mode with fictional scenario
- [x] Phase 2: Input wizard + localStorage for personal scenarios
- [x] Phase 2.5: Data export, clear data, print view, validation
- [ ] Sector-based IPO scenario templates (SaaS, fintech, HR-tech, consumer)
- [ ] Optional Claude API integration for company research

## License

MIT. See [LICENSE](LICENSE).
