# JPMorgan-Quantitative-Research-Simulation

## Overview
This repository contains Python solutions for the JPMorgan Chase & Co. 
Quantitative Research Job Simulation completed on Forage (May 2026).

## Tasks

### Task 1 — Natural Gas Price Estimator
- Analyzed monthly natural gas prices (Oct 2020 – Sep 2024)
- Built a seasonal trend model to estimate price at any date
- Extrapolated prices one year into the future

### Task 2 — Commodity Storage Contract Pricing
- Built a prototype pricing model for natural gas storage contracts
- Inputs: injection dates, withdrawal dates, rate, max volume, storage cost
- Output: contract value = revenue - purchase cost - storage cost

### Task 3 — Credit Risk Analysis
- Used Logistic Regression to predict probability of loan default
- Calculated Expected Loss = PD × Loan Amount × LGD (90%)

### Task 4 — FICO Score Bucketing
- Used dynamic programming to find optimal FICO score bucket boundaries
- Maximized log-likelihood to separate defaulters from non-defaulters
- Mapped FICO scores to ratings 1 (best) to 5 (worst)

## Libraries Used
- pandas
- numpy
- scipy
- scikit-learn

## Certificate
Issued by JPMorgan Chase & Co. via Forage — May 2026
