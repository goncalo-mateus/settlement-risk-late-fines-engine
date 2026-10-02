# Settlement Risk & Late Penalties Engine ($T+n$)

## Overview
A financial risk model designed to track settlement cycles ($T+1$, $T+2$), calculate delivery delays, and estimate contractual penalty fees under CSDR guidelines.

## Key Features
* **Dynamic Target Date Logic:** Calculates target delivery dates based on trade dates and settlement cycles.
* **Penalty Calculation Engine:** Applies daily percentage fines ($0.1\%$ per day) based on delayed trade values.
* **Risk Management Dashboard:** Aggregates total delayed volume at risk and total accrued penalty fees.

## Tech Stack & Domain Knowledge
* **Tool:** Microsoft Excel (Web / Desktop)
* **Functions:** `SUMIF`, `COUNTIF`, `DATE`, Date Arithmetic
* **Domain:** Settlement Risk, CSDR Late Settlement Penalties, Post-Trade Operations
