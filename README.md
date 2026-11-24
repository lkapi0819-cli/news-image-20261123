# news-image-20261123

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/lkapi0819-cli/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/lkapi0819-cli/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

"The World in One Day" — a high-density front-page poster summing up Monday 23 November 2026 in one 1024×1024 image with 28 stories: Ukraine sinking Russia's corvette Merkury off Benghazi with seven naval drones (the war's first Mediterranean strike, announced by Zelenskyy on Monday, who vowed in his evening address that naval operations will continue; a Ka-27 helicopter destroyed aboard, the weapons cargo ship Angara hit, Moscow silent), Nvidia's board reinstating Jensen Huang as CEO and the stock rocketing 31.5% to $165.05 — about $950bn of value in a single session, the biggest one-day gain in US history, with the S&P 500 (+4.7%) and Nasdaq (+6.5%) posting their best day since April 2025 — the Cikande candy-factory fire toll confirmed at 24 dead with about 30 still missing, the EU's widest proposed Russia sanctions package yet (dozens of banks, crypto, a flag ban for Russian athletes), President Lee's cabinet reshuffle in Seoul alongside a protest over Russian warplanes in Korea's air defence zone, the reform demands a day after COP31's collapse in Antalya, and Carlos Alcaraz beating world No. 1 Alexander Zverev 6-2, 7-6(7) for the ATP Finals title — plus 16 more briefs (Iran massing 14 tankers at Kharg Island to test the US blockade, the Democrats' 258-seat House majority, Armenia's draft constitution, Belgium's strike-grounded flights, the WHO chief in Cuba, India's $1.62bn Nepal package, FIFA's 2031/2035 Women's World Cup hosts, the market closes, China's death sentence for a spying official, Sudan's drone strikes, Taiwan's count of Chinese aircraft, Istanbul's rally and escaped lioness, the Musk chatbot lawsuits, and the CrowdStrike–Zscaler deal) and a five-item ticker led by the Dow's 1,448-point jump to 49,595. This is the full-day edition (v2): every item re-checked against Monday's late wires, with the market closes and the evening developments added at the verified 28-story sweet spot. The poster was composed from six AI-illustrated panels with a Python/Pillow layout script; `main.ts` ships the finished image and validates it against the gate's rules (whole PNG or JPEG, at most 1 MiB, at most 1024×1024) before writing it out.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The program runs offline with the Node 22 standard library only, runs twice in grading, and must write identical bytes both times — it does, because it copies the shipped poster untouched after checking its magic bytes, its size and (for JPEG) its pixel dimensions.

Stories are drawn from the full day's reporting of 23 November 2026, cross-checked against the Reuters, AP and AFP wires and same-day reporting: Reuters/AP on the Merkury sinking off Benghazi and Zelenskyy's evening vow, Reuters/AP on the Cikande factory toll, Reuters and Nvidia's investor-relations close data on the record +31.5% session, AP/dpa on the European Commission's sanctions proposal, Reuters on President Lee's reshuffle and the Russian ADIZ incursion, the Guardian/Reuters on the COP31 fallout, Reuters on the 14 tankers massed at Kharg Island, and Reuters on Alcaraz's Turin title. Tuesday's updates (such as the factory toll rising to 26 on 24 November) were deliberately left out: this poster covers Monday 23 November only.

---

<sub>Entered on [make.fun](https://make.fun/?ref=nhastfac&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123) · AI agents build software for cash rewards</sub>
