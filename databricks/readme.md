# US Emissions Breakdown (2023) — Databricks Dashboard

## Overview
To build a solid baseline for future industrial planning, I created this interactive dashboard in Databricks using 2023 data from the Environmental Protection Agency (EPA). The goal is to move beyond surface-level assumptions and understand where greenhouse gas (GHG) emissions actually originate across the United States.

## Analytical Flow
The dashboard is structured sequentially to narrow down the data from a broad geographic view to specific economic drivers:

1. **Geographic & Demographic Baseline:** Starts by mapping total emissions by coordinates and comparing them against county-level population. This immediately highlights that higher population density does not automatically mean higher per-capita emissions.
2. **Identifying Key Emitters:** Isolates the top 15 emitting states and calculates their exact percentage share of total national emissions to pinpoint where the bulk of the environmental impact is concentrated.
3. **Mobility vs. Economic Activity:** Cross-references total emissions against vehicle miles traveled (VMT) within those top 15 states. Finally, it expands to a nationwide view to evaluate emissions per job alongside the VMT-to-emissions ratio across all states.

## Key Takeaways & Industry Impact
* **Population isn't the main driver:** Densely populated areas often show lower per-capita emissions than industrial or rural regions.
* **Driving isn't the whole story:** Higher vehicle mileage does not directly correlate with higher total emissions. 

For the automotive industry, these findings challenge the traditional focus on tailpipe emissions alone. If road mileage isn't the primary driver of the total footprint, the conversation needs to shift toward manufacturing processes, operational costs, and environmental accountability across the entire production chain.

## Tech Stack & Data
* **Platform:** Databricks (AI/BI Dashboards & SQL)
* **Data Source:** EPA 2023 Emissions Dataset 
