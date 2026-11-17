# Growth Audit — Open (v2)

**Live:** https://bterzic123.github.io/open-flow-rebuild-v2/

Open's Meta ads promise three different weeks: a nervous-system reset, a grief program and a heartbreak program. Every install meets the same account form and the same "Try Open for free". This audit rebuilds the first launch so each ad's promise is kept, in Open's own design: the black, the spaced-out wordmark, the manifesto, the outlined pill and round arrow, the date wheel, the breathing dots, "Your first week", the lime trial line and the press row. Only the order changes.

The prototype shows three phones side by side, one per Meta ad.

| # | Idea | Potential outcome |
| :-- | :-- | :-- |
| 01 | Let them in before you ask for an account | CR +8% · ARPU +17% |
| 02 | Name the program from the ad on the paywall | CR +15–20% |
| 03 | Ask for notifications and Apple Health after the trial starts | CR +10–15% |
| 04 | Ask what they came for, and read it back while it loads | CR +10–15% |
| 05 | Put Editors' Choice, 4.9 and a member's words next to the plans | CR +10–15% |

"Later →" on the paywall closes straight into the app. There is no second paywall.

Prices ($149.99/yr, $19.99/mo, 14-day trial), program names and the press row come from Open's iOS app. The rating, Editors' Choice and the quoted review come from the US App Store listing. The ads come from the Meta Ad Library (November 2026). Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps, not measured lift for Open.

The first audit is still live at https://bterzic123.github.io/open-flow-rebuild/.

## Run locally

```bash
python3 -m http.server 8921
```

Then open http://localhost:8921. Add `?view=proto` to land on the prototype.
