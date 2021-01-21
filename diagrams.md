# Car-Sharing Availability EDA Diagrams

Generated on 2026-04-26T04:29:37Z from README narrative plus project blueprint requirements.

## Supply vs demand heatmap by zone/hour

```mermaid
flowchart TD
    N1["Step 1\nAligned on business questions with Ops, Supply, Customer Care; defined cancellatio"]
    N2["Step 2\nAudited data from bookings, driver logs, inventory, pricing, support tickets; reco"]
    N1 --> N2
    N3["Step 3\nProfiled data quality; fixed missing/duplicate rides, standardized geo and time zo"]
    N2 --> N3
    N4["Step 4\nExplored patterns by hour, zone, vehicle, promo using cohort/funnel views, seasona"]
    N3 --> N4
    N5["Step 5\nModeled predictors of cancellation (lead time, surge ratio, driver distance) and i"]
    N4 --> N5
```

## Cancellation funnel analysis

```mermaid
flowchart LR
    N1["Inputs\nHistorical support chats and FAQ content"]
    N2["Decision Layer\nCancellation funnel analysis"]
    N1 --> N2
    N3["User Surface\nOperator-facing UI or dashboard surface described in the README"]
    N2 --> N3
    N4["Business Outcome\nOperating cost per workflow"]
    N3 --> N4
```

## Evidence Gap Map

```mermaid
flowchart LR
    N1["Present\nREADME, diagrams.md, local SVG assets"]
    N2["Missing\nSource code, screenshots, raw datasets"]
    N1 --> N2
    N3["Next Task\nReplace inferred notes with checked-in artifacts"]
    N2 --> N3
```
