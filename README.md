# Project Scheduling & Risk Analysis

A project management analysis using PERT, Critical Path Method, and time-cost trade-off modelling to evaluate schedule risk and crashing strategies for a 15-activity conference project.

## Project Overview

This project evaluates whether the ANZ Analytics Innovation Conference could be delivered within a fixed 45-day deadline.

The analysis combines:

- PERT three-point estimation
- Critical path analysis
- Completion probability modelling
- Project crashing
- Time-cost trade-off analysis
- Scenario and sensitivity analysis
- Excel-based decision modelling

The project contains 15 interdependent activities across 5 network paths.

## Key Findings

- Baseline expected project duration: **46 days**
- Deadline: **45 days**
- Baseline probability of on-time completion: **~37.5%**
- Cost-time optimum: **44 days**
- Cost-time optimum completion probability: **~62%**
- 95% confidence schedule: **39 days**
- Crash cost required for 95% confidence: **~$53,000**
- Minimum achievable duration: **36 days**
- Expedited venue booking reduced the cost of reaching 95% confidence by approximately **$20,000**

## Analysis Scenarios

### Scenario 1 — 95% Confidence Target

Project crashing was applied iteratively to reduce the expected project duration from 46 days to 39 days.

The resulting estimated probability of completing within 45 days was approximately 96.8%.

### Scenario 2 — Cost-Time Optimum

Crashing was continued only while the marginal crash cost remained below the indirect cost saved per day.

The minimum-cost schedule occurred at 44 days, with an estimated total project cost of approximately $279,100.

### Scenario 3 — Minimum Achievable Duration

The project could be compressed to a minimum of 36 days using an optimised crashing strategy.

### Scenario 4 — Accelerated Venue Booking

Reducing the duration of the venue booking activity significantly changed the project network.

This reduced the crash cost required to reach 95% confidence from approximately $53,000 to $33,000.

### Scenario 5 — Additional Keynote Crashing Capacity

Additional crashing capacity for keynote confirmation provided value mainly under extreme schedule compression and was better retained as contingency capacity.

## Tools & Methods

- Microsoft Excel
- PERT
- Critical Path Method
- Project Crashing
- Time-Cost Trade-off Analysis
- Probability Analysis
- Scenario Analysis
- Sensitivity Analysis
- Risk Management

## Repository Contents

- `PERT_Crashing_Tool.xlsx` — Excel model containing activity inputs, PERT calculations, critical path analysis, crashing scenarios and cost-time trade-off analysis.
- `project-management-analysis-report.pdf` — Full project report and strategic recommendations.

## Skills Demonstrated

- Project scheduling
- Risk analysis
- Analytical modelling
- Excel modelling
- Cost optimisation
- Scenario evaluation
- Decision support
- Project management
