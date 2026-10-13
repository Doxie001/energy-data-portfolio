# Project Completion Log: Day 1 (12th October, 2026)

##  PROJECT TOPIC: Can Energy Data Help Predict Electricity Supply Problems?

### STEP 1: DEFINING THE PROBLEM

- Refined question: Can past months of electricity supply data help flag periods when grid supply is likely to be less reliable, so that businesses can prepare alternative power in advance?
- Analysis type: Descriptive and exploratory, leading to a warning-rule prototype.
- Success ("done"): An Excel dashboard that flags unusual drops in supply, recurring low-supply periods and widening gaps between demand and available supply, using rules I define. It will come with a note on its limits and a proposal for how the tool could be tested. This is a prototype, not a validated forecasting system.

### STEP 2: IDENTIFYING WHO IS AFFECTED

- Who is affected: Small businesses and other grid electricity users who run backup power (such as generators) when the grid fails.
- How success is judged: Whether the warning rules would have flagged past periods of poor supply early enough to be useful for planning backup power. Whether it can accurately predict the future cannot be verified with this amount of data.

### STEP 3: GETTING THE DATA

- Source: NERC reports, from 2025 to the end of Q2 2026.
- Source details: [Report titles, link and date retrieved]. An untouched copy of each original file is kept.
- Open check: Whether the reports give monthly values or only quarterly ones. This decides what kind of warning rules are possible. If the data is too thin, I will state that limitation instead of filling gaps.

### STEP 4: UNDERSTANDING THE DATA

- Which tables do I need?
- Which data do I need from those tables?
- How do the tables connect, and how does the data connect?
- What does one row stand for (the grain of each table)?
- What units are used (MW or MWh), and are they consistent?
- Once imported into Excel, do my totals match the totals the report itself states?
