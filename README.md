# Stompers — the Super Stompers paywall, personalized from the onboarding

**Live page: https://plykhvar-glitch.github.io/stompers-paywall-rebuild/**

The Super Stompers paywall that follows onboarding, rebuilt in Stompers' own design and fed by what
the onboarding already asks: the name, the Stomper they picked, and who they want to walk with.
Change them under the phone and the paywall rewrites itself. Flip **Today** to see the screen as it
ships. English and Spanish, light and dark, plus a walkthrough under 30 seconds.

## The five changes

| # | Change | Today | Now | Expected impact |
| :-- | :-- | :-- | :-- | :-- |
| 1 | Their own Stomper on the paywall | A yellow walker and the same words for everyone | Their Stomper, in the colour and top they picked, walks across the desert with their name over it: "Mary, Super Stompers walk 2.5x more" | CR +15–20% |
| 2 | Lead with who they walk with | Seven perks in one fixed order | "All my friends" leads with a free card pack a day, "Close friends & family" with switching items off, "No one" with 24 hr mode | CR +10–15% |
| 3 | Your rating, under the button and up to date | 4.7 from 1.7k reviews, three scrolls below the button | "★ 4.8 · 13K ratings · 1,000,000+ Stompers" under the button | CR +10–15% |
| 4 | Every price says per what | Monthly "9,99 €", Weekly "5,99 €" | 44,99 €/yr · 0,87 €/wk · 9,99 €/mo · 2,31 €/wk · 5,99 €/wk; the button follows the plan | ARPU +8–15% |
| 5 | A month of Super when they close | The X closes it | A Free vs Super sheet with your Monthly plan at 9,99 €, no trial, no discount | CR +3–6% from people who close |

*Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps —
not measured lift for Stompers.*

Prices, plans, perks, the 2.5x line and the review come from the paywall in the Stompers iOS app;
1,000,000+ members from the onboarding; the 4.8 rating from 13K ratings from the US App Store listing
(4.7 on the Spanish listing, used on the Spanish screen); art from stompers.com. Per-week prices are
computed from Stompers' own prices. Dark mode on the phone approximates the Super perk.

## Run locally

```bash
python3 -m http.server 8000
```
