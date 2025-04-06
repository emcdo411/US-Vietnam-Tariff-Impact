# USVietnamTariffImpact

**[Summary](#summary) | [Overview](#overview) | [Features](#features) | [Installation](#installation) | [Usage](#usage) | [Economic Insights](#economic-insights) | [Why This Matters](#why-this-matters) | [Conclusion](#conclusion)**

---

## Summary
This repository houses the **US-Vietnam Zero Tariff Impact Analysis**, a Shiny app deployed on shinyapps.io that models the economic fallout of a potential zero-tariff trade deal between the US and Vietnam. Built in R, it quantifies supplier savings, consumer price drops, job creation, and the Vietnamese đồng’s (VND) long-term value—accomplishing a bridge between trade policy and tangible outcomes. From Nike sneakers dropping to $43-$45 to a VND forecast of 16,000-18,000 VND/USD by 2035, it’s a tool for understanding how trade shapes economies.

---

## Overview
As of April 2025, US-Vietnam trade talks hint at slashing tariffs to zero, dodging a 46% US levy set for April 9. This app explores that scenario’s impact on brands like Nike, Samsung, and Zara, their suppliers, and consumers—plus Vietnam’s currency trajectory. Whether you’re an economist crunching trade surpluses or a shopper eyeing cheaper goods, this app offers data-driven clarity.

---

## Features
- **Supplier Savings:** Estimates $7-15B in savings for textile and electronics supply chains.
- **Consumer Savings:** Predicts $5-9B in price reductions (e.g., $50 sneaker → $43-$45).
- **Interactive Map:** Pinpoints Vietnam production hubs (Ho Chi Minh City, Hanoi) with product details.
- **VND Projection:** Slider forecasts VND/USD from 15,000-26,000 by 2035, targeting 16,000-18,000.
- **Tech Stack:** R, Shiny, Leaflet, DT—deployed via rsconnect to shinyapps.io.

---

## Installation
For technical users wanting to run or tweak this locally:
1. **Prerequisites:** Install [R](https://www.r-project.org/) and [RStudio](https://rstudio.com/).
2. **Clone the Repo:**
   ```bash
   git clone https://github.com/[your-username]/USVietnamTariffImpact.git
   cd USVietnamTariffImpact
   ```
3. **Install Dependencies:**
   ```R
   install.packages(c("shiny", "dplyr", "leaflet", "DT", "rsconnect"))
   ```
4. **Run Locally:**
   Open `shiny_app.R` in RStudio and click “Run App.”

---

## Usage
- **Live Version:** Visit [https://mmcdonald411.shinyapps.io/USVietnamTariffAnalysis2025/](https://mmcdonald411.shinyapps.io/USVietnamTariffAnalysis2025/).
- **Navigation:** Use tabs for supplier savings, consumer impacts, Vietnam locations, and VND projections.
- **Non-Tech Users:** Click the link, explore tables, and slide the VND forecast—no coding needed!
- **Tech Users:** Modify `shiny_app.R` data (e.g., add companies) and redeploy with:
   ```R
   rsconnect::deployApp(appDir = "path/to/repo", appName = "YourAppName", account = "your-account")
   ```

---

## Economic Insights
- **Trade Surplus:** A 20% export boost ($28B/year) could widen Vietnam’s $123B US surplus, lifting VND by 30-40% long-term.
- **FDI Flows:** $10B annual FDI could fuel a $1T Vietnamese economy by 2035, a 6-7% CAGR from $433B.
- **Currency Dynamics:** VND might hit 16,000-18,000 VND/USD, though the State Bank may cap it at 20,000 to protect exporters—a classic trade-off in open economy macroeconomics.
- **Elasticities:** Consumer savings reflect a 50-75% tariff pass-through, aligning with empirical trade models.

---

## Why This Matters
Zero tariffs could reshape global supply chains, making Vietnam a linchpin for US imports and a case study in trade-led growth. Economists see a multiplier effect: $1 in exports spurs $1.5-2 in GDP via jobs and investment. For consumers, it’s cheaper goods; for policymakers, it’s a test of reciprocal trade’s limits. This app distills that complexity into actionable insights.

---

## Conclusion
The **USVietnamTariffImpact** app marries data science with economic forecasting, offering a window into a pivotal trade shift. It’s live, interactive, and ready for exploration—whether you’re analyzing VND appreciation or just curious about your next purchase. Feedback welcome!

---
