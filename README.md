# Car-Sharing Availability Uplift via EDA

> **Domain:** Mobility / Transportation

## Overview

An online car-sharing platform struggled with high booking cancellations and frequent no-cars-available messages during peak demand. Customers faced unreliable wait times, confusing inventory status, and last-minute driver unassignments. Operations teams lacked a clear view of supply vs. demand by hour, area, and vehicle type. Marketing promotions occasionally spiked demand where supply was thin. Left unaddressed, these gaps drive lost revenue, poor app ratings, churn, wasted driver hours, and inflated support costs. The goal: pinpoint root causes using exploratory analysis and turn findings into practical actions improving availability, reducing cancellations, and restoring customer trust.

## Approach

- Aligned on business questions with Ops, Supply, Customer Care; defined cancellation types and service-level thresholds
- Audited data from bookings, driver logs, inventory, pricing, support tickets; reconciled IDs and timestamps
- Profiled data quality; fixed missing/duplicate rides, standardized geo and time zones
- Explored patterns by hour, zone, vehicle, promo using cohort/funnel views, seasonality charts, geospatial heatmaps
- Modeled predictors of cancellation (lead time, surge ratio, driver distance) and identified tipping points for supply rebalancing
- Validated insights with back-tests; packaged actions (dynamic supply shifts, hold buffers, pricing guardrails) and KPI dashboard for weekly review

## Skills & Technologies

- Exploratory Data Analysis
- SQL Data Modeling
- Python (Pandas)
- Time-Series Analysis
- Cohort & Funnel Analysis
- Geospatial Mapping
- Data Cleaning & Validation
- Dashboard Design (Power BI/Tableau)
- Hypothesis Testing
- Stakeholder Workshops
