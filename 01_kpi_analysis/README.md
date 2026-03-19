# E-commerce KPI \& Retention Analysis

## Problem



Analyze user behavior on an e-commerce platform to understand:

&#x09;revenue drivers

&#x09;customer conversion patterns

&#x09;retention behavior over time

The goal is to identify growth opportunities and bottlenecks in the user journey.



## Approach



Queried and analyzed data using SQL (DuckDB)

Performed data manipulation using Pandas

Computed key business metrics:

&#x09;revenue per user

&#x09;conversion rate

&#x09;repeat purchase rate

Built:

&#x09;funnel analysis (view → add to cart → purchase)

&#x09;cohort retention analysis

Visualized results using Matplotlib



## Key Insights



Revenue concentration: A subset of users generates a large portion of revenue

Funnel drop-off: The biggest drop occurs between product view and add-to-cart

High purchase intent: Users who add to cart convert at a very high rate (\~95%)

Retention pattern: Most repeat purchases occur within the first month

Channel differences:

&#x09;Email users show the highest conversion efficiency

&#x09;Organic search drives both scale and strong performance



## Results



View → Add-to-cart conversion: \~67%

Add-to-cart → Purchase conversion: \~95%

Repeat purchase rate: \~46%

Cohort analysis shows strong early retention with rapid decay afterward



## Business Impact



Focus optimization on product page → add-to-cart stage

Invest in email and organic channels for high-quality users

Improve early lifecycle engagement (first 30 days) to boost retention

Use funnel insights to guide UX and pricing improvements



## Tech Stack



SQL (DuckDB)

Python

Pandas

Matplotlib

