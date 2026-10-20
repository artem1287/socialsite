# Statline

A "TikTok for statistics" — a scrolling, personalized feed of ~100 statistics drawn from 50 public statistical APIs (BLS, World Bank, FRED, ECB, OECD, DBnomics, BEA, INSEE, NASA POWER, Ember, WHO, UNICEF, OpenAlex, arXiv, and more).

Single-file app: open `index.html` in a browser (or enable GitHub Pages to host it).

## Features
- Line charts (value over time) plus rankings, category bars and composition donuts
- Per-stat country/region tags, units, and a "since" change readout
- Changeable time range per chart (1Y–30Y / All)
- Recommendation engine: dwell-time + engagement signals, interest vector, 3-phase exploration (80% → 45% → 18%), aggressive experimental injection
- Endless feed that loads a freshly-ranked set of 3 at a time

Figures are the latest published values from each source (embedded; the page makes no live cross-origin calls).
