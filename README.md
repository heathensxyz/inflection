# Inflection

**Career decisions, clearly.**

Inflection is a browser-based tool for modeling the financial and personal trade-offs of a career move. It handles the scenarios that generic salary calculators miss: pre-IPO equity, multi-grant vesting waterfalls, IPO outcome ranges, and the qualitative frameworks that actually drive good decisions.

**[Live demo](https://eclectic-florentine-8251bf.netlify.app/)** — featuring Jordan, a fictional Sr. PM weighing a pre-IPO fintech offer against a public company role.

---

## What it does

- **Year-by-year cash comparison** — segmented bars showing base, bonus, and RSU components side by side
- **IPO scenario explorer** — bear / base / bull / moonshot / no liquidity, with 4-year total comp impact
- **Vesting waterfall** — interactive canvas chart with sliders for stock growth, IPO timing, multiplier, and future refresh grants
- **Decision Lens** — six qualitative frameworks (The Runway Check, The Ladder or the Rope, The Zip Code Test, The Reluctant Yes, The Ghost Test, The Floor Check) with example answers and reflection prompts

## How to run it

No build step. No dependencies. No accounts.

```
open index.html
```

Or just drag the file into any browser.

## Privacy

All data stays in your browser. Nothing is sent to a server. The demo uses entirely fictional data — Jordan, Cloudware, and Meridian are illustrative only.

## Roadmap

- [ ] Phase 2: Input forms + localStorage so users can model their own scenario
- [ ] Sector-based IPO scenario templates (SaaS, fintech, HR-tech, consumer)
- [ ] Optional Claude API integration for company research assistance
- [ ] Staticrypt support for password-protected sharing

## License

MIT — see [LICENSE](LICENSE).
