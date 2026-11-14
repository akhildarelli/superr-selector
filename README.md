# 🏏 SupeRR Selector – Season 2

### Rajasthan Royals | Performance Analytics & Auction Intelligence

SupeRR Selector is an interactive cricket analytics dashboard designed to evaluate player performances under pressure and support data-driven player selection for the Rajasthan Royals.

The project analyses historical IPL and T20I ball-by-ball data to identify batters and bowlers who perform in high-pressure situations.

## 🚀 Live Dashboard

**[Open SupeRR Selector](https://akhildarelli.github.io/superr-selector/)**

## 📊 Key Features

- **Overview Dashboard** – Key performance indicators and top-ranked players.
- **Batting Analysis** – Pressure strike rate, batting average, runs and dot-ball percentage.
- **Bowling Analysis** – Pressure economy, wickets, dot-ball percentage and bowling performance.
- **Player Comparison** – Compare players using pressure-performance metrics.
- **Player Intelligence** – Player profiles, season trends, strengths and weaknesses.
- **Auction Decision Board** – Categorise players into indicative auction recommendation tiers.
- **Pressure Phase Analysis** – Explore powerplay, middle-over and death-over concepts.
- **RR Squad Builder** – Shortlist players based on roles.
- **Methodology & Data** – Understand the pressure definitions and scoring methodology.
- **Reports & Exports** – Download player summaries in CSV format.
- **Match-by-Match Analysis** – Review available individual pressure records.
- **Role & Position Fit** – Evaluate player suitability by batting position and role.
- **Opposition & Venue Analysis** – Explore performance by opposition and venue.
- **Reliability & Risk Assessment** – Evaluate sample size and consistency.
- **Auction Simulator** – Experiment with purse allocation and squad combinations.
- **Executive Report** – Generate a summary suitable for presentation.
- **Domestic Uncapped Watchlist** – Explore 30 shortlisted domestic prospects.

## 🧮 Pressure Performance Methodology

A delivery is classified as a pressure situation when either condition applies:

1. Second innings with a required run rate of at least 10 runs per over.
2. Final five overs when the batting side has already lost at least four wickets.

### Batting Score

- 35% – Pressure strike-rate percentile
- 25% – Pressure average percentile
- 20% – Inverse dot-ball percentage percentile
- 20% – Improvement in pressure strike rate over overall strike rate

### Bowling Score

- 35% – Inverse pressure economy percentile
- 30% – Wickets per 100 pressure balls percentile
- 20% – Pressure dot-ball percentage percentile
- 15% – Improvement in pressure economy over overall economy

Scores are historical performance indicators, not predictions of future performance.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Data Analytics
- GitHub Pages

## 📁 Project Structure

```text
superr-selector/
│
├── index.html
└── README.md
```

## ⚠️ Data Disclaimer

This dashboard uses the historical dataset supplied for the project. Player scores and rankings depend on the available data and the documented methodology.

Small samples and missing records may affect comparisons. Auction recommendations and player classifications are indicative scouting aids, not guaranteed predictions or official team decisions.

## 👨‍💻 Author

**Akhil Darelli**

GitHub: [@akhildarelli](https://github.com/akhildarelli)

---

*SupeRR Selector – Data-driven cricket intelligence for smarter player selection.*
