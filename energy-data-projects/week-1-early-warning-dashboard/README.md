# Week 1: Early Warning Dashboard

**Can energy data help predict electricity supply problems?**

## The problem
Can past months of electricity supply data help flag periods when grid supply is likely to be less reliable, so that businesses can prepare alternative power in advance?

## Approach
Descriptive and exploratory analysis, leading to a warning-rule prototype.

## Who is affected
Small businesses and other grid electricity users who run backup power (such as generators) when the grid fails.

## What "done" looks like
An Excel dashboard that flags:
- Unusual drops in supply
- Recurring low-supply periods
- Widening gaps between demand and available supply

The flags use rules I define. The dashboard will come with a note on its limits and a proposal for how the tool could be tested.

## How success is judged
Whether the warning rules would have flagged past periods of poor supply early enough to be useful for planning backup power.

## Limits
This is a prototype, not a validated forecasting system. With this amount of data, it cannot be verified whether it can accurately predict the future.

## Data
NERC (Nigerian Electricity Regulatory Commission) reports, from 2025 to the end of Q2 2026.

## Tools
Excel

## Progress
- [x] Step 1: Define the problem
- [x] Step 2: Identify who is affected
- [x] Step 3: Get the data
- [ ] Next steps: clean the data, build the dashboard, write up the limits

## Files
- `data/`: NERC reports used in this project
